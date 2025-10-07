L4D2 Launcher Unlock & Autocomplete
===================================

概述
-
加载时遍历所有控制台指令，找到带有 `FCVAR_LAUNCHER` 标志的命令，移除其 `hidden/cheat/developmentonly` 限制，使之：

- 直接在控制台输入即可执行（无需 `sm_` 命令）
- 出现在控制台的自动补全/下拉建议中
- 所有flag为LAUNCHER的控制台指令也和其他普通指令一样直接在控制台中输入执行

安装
-
1. 将 `.smx` 放入游戏目录 `left4dead2/addons/sourcemod/plugins/`
2. 重启服务器或更换地图以加载插件

参考
-
- L4D2 控制台命令与变量（LAUNCHER 标志命令列表）：https://developer.valvesoftware.com/wiki/List_of_Left_4_Dead_2_console_commands_and_variables

注意
-
-进入游戏后先用map命令建图，以加载插件，之后你便可以直接在控制台输入执行https://developer.valvesoftware.com/wiki/List_of_Left_4_Dead_2_console_commands_and_variables 中的所有命令-进入游戏后先用map命令建图，以加载插件，之后你便可以直接在控制台输入执行https://developer.valvesoftware.com/wiki/List_of_Left_4_Dead_2_console_commands_and_variables 中的所有命令

Overview
-
On plugin load, it scans all console commands and finds those with the `FCVAR_LAUNCHER` flag, then removes `hidden/cheat/developmentonly` restrictions so that:

- You can execute them directly in the console (no `sm_` admin commands required)
- They appear in the console's autocomplete/suggestion dropdown
- All commands flagged as LAUNCHER behave like normal commands and can be typed and executed directly

Install
-
1. Put the compiled `.smx` into `left4dead2/addons/sourcemod/plugins/`
2. Restart the server or change the map to load the plugin

Reference
-
- L4D2 console commands and variables (LAUNCHER list): https://developer.valvesoftware.com/wiki/List_of_Left_4_Dead_2_console_commands_and_variables

Notes
-
- After launching the game, use the `map` command first to start a map so the plugin loads. Then you can type and execute any command listed on the page above directly in the console.
