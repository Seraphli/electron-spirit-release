# Change Log
## v22.7.3-1190
### New Features
- #### api
  - return whole content to support multiple input hooks. (ceb0734)
    BREAKING CHANGE: the return of processContent need to be updated
- #### frame
  - frame now has same size of subwin. (483c0f9)
    let user to move window to the edge of the screen
- #### subwin
  - add transparent control. (886a1a5)
- use timer to control show and hide. (f197f69)


### Bug Fixes
- #### frame
  - fix subwin focus on macos. (2747eec)
    use a different way to focus subwin, in order to prevent the whole frame remain unclickable
- #### hotkey
  - focus subwin when interact unlock. (d969d72)
- #### input
  - remove control char. (57bb975)
- update boundary of input and render win when display change. (4e27dff)
- fix backgroud render. (642e12e)
- fix on top when remove item. (97b98fe)
- minor fix. (07fc6ab)
- reset skip taskbar when changing focusable. (4ff0e1f)
- use animation. (3fcd16b)


### Performance improvements
- #### subwin
  - optimize focus. (5eb4e7e)
- clean up unused code. (eb21f9a)


### Refactors
- add allowSyntheticDefaultImports in tsconfig. (21671ab)


### Build System
- fix build on macos. (535c478)
  https://github.com/electron-userland/electron-builder/issues/6606
- upgrade electron to 18.3.0. (cc4eade)
- upgrade electron to 18.3.5. (7132947)


### Chores
- add scope. (a2b4875, 2fb8122)
- add new scope. (853fc9e, ba8b9aa)