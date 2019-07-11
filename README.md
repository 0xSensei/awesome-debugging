# awesome-debugging

### Introduction - 简介
* 调试（Debugging），是一门学问，一门技术，一不小心掉进深渊无法生还。
* 话说盘古开天之时，调试界有三种人，他们在.....
  * 推崇者：呵呵，9012年还不会调试，...你先这样...然后那样...Breakpoint/CallStacks/Step/Trace...此处省略一万字...
  * 鄙视者：楼上的，TM一来就调试，不从问题本身、架构设计去思考，缺少思维实验，手速快思想狭隘。
  * 吃瓜者：神仙打架，不明觉厉...
* Why/When/How Debugging?
  * 整个项目会围绕这三个点进行。
  * 项目也会沉积一些有用的工具、书、网站、历史、文章、以及分享各位Contributor的经历和思考。
  * 若是Contributor的原创，会以标注:gem:

<details1>
<summary> 🔧 Debuggers - 调试器</summary>

* [Windbg](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugger-download-tools)
  * Windows官方调试器，牛逼不接受反驳。
  * 《Dive Into Windbg》
    * :gem: [1-Wireshark卡死与崩溃](windbg/dive-into-windbg/1-Wireshark卡死与崩溃/1-Wireshark卡死与崩溃.md)
    * :gem: [2-AudioSrv音频服务故障](windbg/dive-into-windbg/2-AudioSrv音频服务故障/2-AudioSrv音频服务故障.md)
    * :gem: [3-Explorer无法启动排查](windbg/dive-into-windbg/3-Explorer无法启动排查/3-Explorer无法启动排查.md)
    * :gem: [4-Windbg脚本与插件](windbg/dive-into-windbg/4-Windbg脚本与插件/4-Windbg脚本与插件.md)

* [x64dbg](https://github.com/x64dbg/x64dbg)/[Ollydbg](http://www.ollydbg.de/)
  * Ollydbg，人称OD，驰骋江湖多年，OD之所以能流行很大程度上依赖于它的插件生态圈，当然可操作性也是没话说。x64dbg，在开源世界里疯狂生长。只能说长江后浪推前浪，一浪更比一浪强。
  * [TODO]

* [gdb](https://www.gnu.org/software/gdb/)
  * GNU Debugger，*nix系列调试器，当然也可调试PE，不过Windows系统下还是用标准的吧。
  * [TODO]

* [lldb](https://lldb.llvm.org/)
  * LLVM项目调试器，Android/iOS/MacOS开发逆向必备，常用于调试Mach-O。
  * [TODO] 

* [Go](https://golang.org/)
  * [dlv](https://github.com/go-delve/delve) 全名delve，是为Go语言量身打造的一款调试器。
  * [TODO]

* [Python](https://www.python.org/)

* [Javascript / Node](https://nodejs.org/en/)
  * [v8-debugger](https://v8.dev/docs/inspector)
    * Node调试 --inspect 参数
    * [TODO]

* [PHP](https://php.net/) 
  * [xdebug Github](https://github.com/xdebug/xdebug)
  * [xdebug php断点调试配置](https://jpsoft.com/all-downloads/downloads.html)

* [cmd]()
  * [CMDebug](https://jpsoft.com/all-downloads/downloads.html) - 批处理调试器，收费版

</details>

### 📚 Books - 书籍
* 《Windows高级调试 Advanced Windows Debugging》
* 《Inside Windows Debugging》
* 《软件调试》
* [delve Internal Architecture](dlv/delve_Internal_Architecture.pdf)

### 🌐 Webs - 网站
* [TODO]

### Contributions
* Welcome to PR - 欢迎提交