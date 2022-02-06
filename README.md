# ESLint Config

## Let's Learn A VS Code Setting

The setting I chose to research was the `"editor.minimap.enabled": "false"` setting. This setting allows you to enable or disable the minimap that appears on the right side of your vs code window, right next to the scroll bar. This minimap gives you a "code outline" of what code is visible on the screen and the surrounding code without in being on the screen. While you can't really read anything in there, you can get a general idea of what code is where and you can quickly jump to other sections of code by clicking or dragging the shaded area on the minimap around.
Info from [Visual Studio Docs](https://code.visualstudio.com/docs/getstarted/userinterface#_minimap)

## Let's Learn an ESLint Rule

The ESLint rule `"no-trailing-spaces": "error"` is important because when you are editing files you may end up with whitespaces at the end of lines and they can be picked up by source control system (like git & github) and get flagged as diffs. So even though they don't cause any functional issues, many coding guidelines require them to be removed.

Info from [ESLint Docs](https://eslint.org/docs/rules/no-trailing-spaces)
