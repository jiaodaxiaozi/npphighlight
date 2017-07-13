## Brief Introduction

**Version**: 17.0

**Tools**
- [`LINGO`](http://www.lindo.com/): a powerful optimization tool with many exciting features
- [`Notepad++`]( http://notepad-plus-plus.org/ ): a free and powerful text editor on Windows platform

**Files**
- userDefineLang.xml: `Syntax Highlight` for `lng/ltf` scripts
- LINGO.xml: `Auto Completion` and `Call Tips` for `lng/ltf` scripts


## Install Guide
1 Suggestions on installing `Notepad++`
 - When installing `Notepad++`, be sure to enable the option: `"Allow plugins to be loaded from %APPDATA%\notepad++\plugins"`, if you already installed one, please check if `"plugins\APIs"` folder exists in your `Notepad++` install directory, or you should update to a full version of `Notepad++` that includes the plugins feature.
 - You can also install `"XBrackets Lite"` plugin for auto-completion of various brackets, it may be helpful sometimes, just follow the steps: `"Plugins->Plugin Manager->Show plugin manager"`, in `"Available"` menu of `"Show plugin manager"`, find `"XBrackets Lite"` and install it. By default, symbol `'` is not recognized as bracket, you should enable it following the steps: `"Plugins->XBrackets Lite->settings"`, check the box before `"Treat '' as brackets"`, also, you can check other boxes if you like. Make sure that `"Autocomplete brackets"` is checked.
 - Another useful plugin of `Notepad++` is `"NppExec"`. To use it, follow the steps below:
 	- First, make sure that you have enabled it by checking `"plugins"` folder in your `Notepad++` install directory, a dynamic link library named `"NppExec.dll"` should be there, if not, check if it's in `"disabled"` sub-folder, if so, move it to `"plugins"` folder.
 	- Second, open `Notepad++`, in `"Plugins->NppExec"`, check `"Show Console Dialog"` and `"Follow $(CURRENT_DIRECTORY)"`, then drag the console dialog to any position you would like, for details of usages, refer to `Doc` and `Manual` of it.
 	- Unicode version of `"NppExec.dll"` is recommended, check it by typing `ver` command in console dialog.
	
2 Copy `"userDefineLang.xml"` to `"%APPDATA%\Notepad++"`
 - Here `"APPDATA"` is an environmental variable, you can check it in command prompt with `"echo %APPDATA%"`
 - If you already have an `"userDefineLang.xml"`, just copy contents in between `"<UserLang ...</UserLang>"` to the existed one.

3 Copy `"LINGO.xml"` to `"plugins\APIs"` folder of `Notepad++` install directory.

4 Restart `Notepad++` (if not opened, just run it).

5 Open `".lng"` or `".ltf"` file with `Notepad++`.


## Other Information
1 These `".xml"` files are designed for `"default style theme"`, you may modify them to suit your needs. To choose another theme, try `"Settings->Style Configurator->Select theme"`.

2 Tested with `Notepad++ 7.4.2`, `Windows 7 SP1 Ultimate 32-bit`.

3 I am Chinese, sorry for my poor English, and I am not an expert of `Notepad++`, so **better ideas are welcome!**

4 Email address
 - `wujianjack2@163.com`      (personal)
 - `wujianw@stu.xjtu.edu.cn`  (educational)

 **Wu Jian**
 
 `July 13th, 2017`