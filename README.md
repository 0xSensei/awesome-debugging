## Introduction - 简介
* Why/When/How Debugging?
  * 整个项目会围绕这三个点进行。
  * 项目也会精选一些工具、书、网站、文章、历史文献，以及各位Contributor的经历和思考。
  * 若是Contributor的原创，会标注:balloon:

## TOC - 目录

<details>
<summary> :wrench:Debuggers - 调试器</summary>

* [Windbg](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugger-download-tools)
  * Windows官方调试器，牛逼不接受反驳。
  * 《Dive Into Windbg》:balloon:
    * [1-Wireshark卡死与崩溃](windbg/dive-into-windbg/1-Wireshark卡死与崩溃/1-Wireshark卡死与崩溃.md)
    * [2-AudioSrv音频服务故障](windbg/dive-into-windbg/2-AudioSrv音频服务故障/2-AudioSrv音频服务故障.md)
    * [3-Explorer无法启动排查](windbg/dive-into-windbg/3-Explorer无法启动排查/3-Explorer无法启动排查.md)
    * [4-Windbg脚本与插件](windbg/dive-into-windbg/4-Windbg脚本与插件/4-Windbg脚本与插件.md)
    * [5-Dump分析和内核调试](windbg/dive-into-windbg/5-Dump分析和内核调试/5-Dump分析和内核调试.md)
  * [x86/x64异常处理流程图](windbg/exception-handling-flow.png):balloon:
  * [VirtualKD](http://sysprogs.com/legacy/virtualkd/) 
    * 用VMware/VirtualBox双机调试加速，创建快照+SSD，速度快。
  * [LiveKD](https://docs.microsoft.com/en-us/sysinternals/downloads/livekd)
    * 几乎完全替代了Windbg的本地内核调试，无需设置BCD的Debug参数，即开即用。
  * Extensions - 插件
    * [CMKD](https://www.codemachine.com/cmkd.html) 查看x86/x64栈参数、内存PTE等
    * [blwdbgue](http://kdext.com/extensions/uienh_asmhl.html) 语法高亮插件，可以高亮相同单词，在反汇编跟踪寄存器时是很有用


* [x64dbg](https://github.com/x64dbg/x64dbg)/[Ollydbg](http://www.ollydbg.de/)
  * Ollydbg，人称OD，驰骋江湖多年，OD之所以能流行很大程度上依赖于它的插件生态圈，当然可操作性也是没话说。x64dbg，在开源世界里疯狂生长。只能说长江后浪推前浪，一浪更比一浪强。
  * [TODO]

* [gdb](https://www.gnu.org/software/gdb/)
  * GNU Debugger，*nix系列调试器，也可以调试PE程序。
  * [TODO]

* [lldb](https://lldb.llvm.org/)
  * LLVM项目调试器，Android/iOS/MacOS开发逆向必备，常用于调试Mach-O。
  * [lldb和gdb命令对照表](https://lldb.llvm.org/use/map.html) 

* [Go](https://golang.org/)
  * [dlv](https://github.com/go-delve/delve) 全名delve，是为Go语言量身打造的一款调试器。
  * [gdlv](https://github.com/aarzilli/gdlv) dlv GUI版本，支持Windows/MacOS/Linux

* [Python](https://www.python.org/)

* [Javascript / Node](https://nodejs.org/en/)
  * [v8-debugger](https://v8.dev/docs/inspector)
    * Node调试 --inspect 参数
    * [TODO]

* [PHP](https://php.net/) 
  * [xdebug Github](https://github.com/xdebug/xdebug)
  * [xdebug php断点调试配置](https://jpsoft.com/all-downloads/downloads.html)

* [cmd]()
  * [CMDebug](https://jpsoft.com/all-downloads/downloads.html) - 批处理调试器，商业版。

</details>

<details>
<summary> :ledger:Books - 书籍</summary>

* 《Windows高级调试 Advanced Windows Debugging》
* 《Inside Windows Debugging》
* 《软件调试》
* [delve Internal Architecture](dlv/delve_Internal_Architecture.pdf)
</details>

<details>
<summary> :globe_with_meridians: Webs - 网站</summary>

* [TODO]

</details>

## Contributors - 贡献者
* [BlackINT3](BlackINT3)
* Welcome to PR - 欢迎提交