# Electron Spirit Usage

## What Can ES Do
- Display a webpage on top, or Play a video with Danmu support.
- Display any HTML element on top.
- Interact with on-top windows can be disabled.
- Provide plugin API for manipulating ES.

## Quick Start

*Assume hotkey registration works fine*

1. Press `Ctrl|Command + Alt + P` to open the input window, input `https://www.bilibili.com/` as its content, and Press `Enter`.
2. Press `Ctrl|Command + Alt + L` to unlock interaction, Press `Ctrl|Command + Alt + M` to unlock window movement. Moving your mouse over on-top windows will display the frame window. Drag the title bar to move the on-top window and resize the window by dragging around it.
3. Press `Ctrl|Command + Alt + L` again to lock interaction and Press `Ctrl|Command + Alt + M` again to lock window movement.

## Hotkey

1. Press `Ctrl|Command + Alt + X` to show/hide all windows. The default behavior is showing all windows.
2. Press `Ctrl|Command + Alt + P` or click `New element` in the tray menu to display the input window. You can input URL, HTML, or plain text, ES will automatically recognize the content type. Input content can also trigger the specified plugin functionality.
3. Press `Ctrl|Command + Alt + L` or click `Toggle Interaction` to unlock/lock the interaction with windows. The default behavior is lock interaction.
4. Press `Ctrl|Command + Alt + M` or click `Toggle Window Movement` to unlock/lock windows movement. With movement enable, moving the mouse to one window will display the frame window with a title bar. Dragging on the title bar will move the window and dragging around the window will resize the window. When moving the mouse aside, the frame window will automatically hide.

## Bar on Frame

The title bar on the frame also contains buttons for convenience.

All descriptions about buttons from left to right:
- `T`: hide/show title bar. **Note** title bar only go transparent, it doesn't disappear. You can still move the window by dragging the invisible title bar.
- `B`: toggle the transparent/white background color of the webpage. This is useful when some web pages' background color is transparent.
- `100`: display opacity of the window. You can adjust the opacity by placing the mouse on the button and scrolling the mouse wheel.
- `↻`: reload button.
- `X`: close button.


## Auto Update

ES supports auto-update, although it only works on Windows.

## Example Plugin

https://github.com/Seraphli/es_plugin_example_py


## Plugin List

https://github.com/Seraphli/esp_list

## Note

- ES will use a system proxy.
- All settings will take effect after restart.
- Hotkey registration may fail. The hotkey can be set in the setting.
- If you are stuck when `loading Adblock`, you need to download `adblock.bin` from the `data` folder and place it in the setting folder. You can open the setting folder using the tray menu `Debug -> Open Settings Folder`. Then you should restart ES.
- If the webpage can not be loaded, it might result in a completely transparent window. You need to unlock window movement and close it using the close button on the frame title bar.
- Do not right-click on the frame window and close it. It will result in a bug.
- If the new window doesn't show, try to enable window movement and drag around.
