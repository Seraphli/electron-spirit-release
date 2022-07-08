# Electron Spirit

## Introduction

Electron Spirit is a desktop app that can place any webpage on top of the screen.

It's similar to `Picture-in-Picture(PiP)` in Chrome that allows you to watch videos in a floating window (always on top of other windows) so you can keep an eye on what you’re watching while interacting with other sites, or applications.

ES provides users with more functionalities. You can disable interaction of the on-top window, to prevent losing focus of your current application. It's especially useful when playing a video game while watching a video on some website. 

ES can show Danmu while watching a video and interact with the webpage when you want to. It is a browser window, but frameless and on top. ES also supports changing the opacity of windows on Windows and macOS.

ES provides plugin APIs, allowing you to place any HTML content on the top of the screen and control its behavior. ES provides a plugin API demonstration in Python.

ES works on Windows, macOS, and Linux.

## 介绍

Electron Spirit (电子精灵) 是一个桌面程序，可以允许用户将任意网页置顶在桌面上。

ES类似于Chrome中的画中画功能，可以在一个置顶悬浮的窗口中看视频或者网页，所以用户可以边看视频边干其他事情。

不过ES比画中画有更多的功能。用户可以禁止置顶窗口的交互，这样在使用其他软件的时候就不会由于不小心点到置顶窗口而丢失焦点。这个功能特别是在用鼠标和键盘玩游戏的时候很有用。

ES还可以显示弹幕，特别是在B站上看直播和视频的时候有用。也正是因为画中画无法显示弹幕，所以我才自学写了这个软件。ES创建的窗口本质上就是一个浏览器窗口，只不过是无边框而且置顶的。在Windows和macOS上，窗口还可以调节透明度。

为了方便自定义功能，ES还提供了插件接口，可以很方便的使用自己熟悉的语言接上，实现在桌面上覆盖HTML元素和控制窗口的行为。ES提供了Python写的插件示例。

ES可以运行在Windows，macOS和Linux上。

## Usage (使用说明)

[English](docs/en/USAGE.md)

[中文](docs/zh/USAGE.md)

## About Open Source (关于开源)

Like Obsian, ES provides plugin APIs to control its behavior and do some customization. I think it is enough for someone want to add their own stuff. I also have no intention to open source ES in the future.

就像Obsidian一样，ES也提供了插件API来处理自定义的问题。插件API应该足够一些人添加自己的内容。而且我未来没有将ES开源的打算。