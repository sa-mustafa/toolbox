# Windows Developer's Toolbox

## Description

This is a collection of Windows tools I frequently use as a developer and pack them as a *developer's diagnostic toolbox* on my flash disk or store them on disk for reference. You should have heard the saying: a developer is as good as his tools. Here are the tools I have come to know from years of experience as a developer. I hope to get your comments and suggestions on this list. This list should be updated every once in a year or two, since the technology comes and goes, and the tools get old.

## File Tools

### [7-zip](https://www.7-zip.org)

To create compressed archives you may use this free open-source tool. 7-zip is capable of creating archives smaller than the commercial tools like [WinRAR](https://www.rarlab.com) or [WinZip](https://www.winzip.com).

## [ChaosMD5](http://www.elgorithms.com/downloads/chaosmd5.php)

Use this tool to compute MD5 hash of files to check if the contents of two files are identical or not. Another easy way is to use [7-zip](https://www.7-zip.org) File \ CRC menu to compute CRC or SHA hashes. Another way is to use PowerShell's Get-FileHash command.

### [FreeCommander](https://freecommander.com)

The free file manager on Windows that can be used instead of the TotalCommander or Unreal Commander. The utility allows you to compare or synchronize folders, rename multiple files, search files or folders based on contents or naming patterns and much more. It reminds me of the old days of Norton Commander on DOS.

### [WinMerge](http://winmerge.org)

This utility allows comparing and merging files and folders on Windows. The only paid version which I find superior to this tool with regard to comparison quality is [CompareIt](https://www.grigsoft.com).

## Executable Files

### [Dependency Walker](http://www.dependencywalker.com)

This handy tools shows the list of an EXE (executable) file modules and DLL's (Dynamic Link Library). By clicking on each module you may see what functions of the module is internally used by the EXE file. This tool, however, does not usually show useful information for .Net applications.

### [Dependency Walker .Net](https://github.com/isindicic/DependencyWalker.Net) or [Net Depends](https://www.workshell.co.uk/products/netdepends)

This tool does the job of Dependency Walker for .Net applications. 

### [Explorer Suite](https://ntcore.com/?page_id=388)

This great tool from NT Core shows the internals of EXE files for both native and .Net applications. This tool comes in handy when application lacks a dependent file on a system or when you want to inspect an EXE file. It also allows you to view or edit Portable Executable (PE) file flags, disassemble and patch (binary edit) the file. The older tool in this category was ExeScope.

### [Resource Hacker](http://www.angusj.com/resourcehacker)

This tool is a resource editor for native Windows applications. It allows both resource compiling and decompiling.

## Debuggers & Disassemblers

There are many debuggers and disassemblers on the Internet. Many tools just come and go like fashion designs. And that may be due in part to the fact that technology behind these tools are very obscure and dependent on deep internals of the systems that change from time to time. I used to be a fan of SoftICE for its ability to debug Windows kernel live, but, the technology was handed from NuMega to Compuware and is now defunct! 

Currently, I know and use these tools.

### [OllyDbg](http://www.ollydbg.de)

This debugger along with W32DASM are becoming golden oldies and do not get updated anymore.

### [Hopper Disassembler](https://www.hopperapp.com)

This tool lets you disassemble, decompile and debug your applications. There used to be a Windows version which allowed 30 minutes of free session.

### [IDA](https://www.hex-rays.com/products/ida)

IDA is the definitive disassembler tool  allowing one to decompile binary files from DOS, Linux, Mac, Android, iOS, XBOX, Motorola, Nintendo, Sony PlayStattion, QNX and more. It supports AMD, ARM, Intel, ATMEL, Hitachi, JVM, .Net, NEC, Motorola, etc instruction sets. The owner company gives away a free personal version.

### [JustDecompile](https://www.telerik.com/products/decompiler.aspx)

This tool allows you to decompile .Net source files from un-obfuscated .Net EXE files. There are other alternative tools including [JetBrains dotTrace](https://www.jetbrains.com/profiler) and [RedGate Reflector](https://www.red-gate.com/products/dotnet-development/reflector/index). Another great open source tool is [dnSpy](https://github.com/0xd4d/dnSpy).

### [x64dbg](https://x64dbg.com)

This tool is an open-source x64/x86 debugger for Windows and has an interface similar to IDA.

## System Specs

### [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html)

Use CPU-Z to see processor model, count of cores, manufacturing technology, core frequency, instructions set, cache sizes, memory size/frequency/latencies and more.

### [GPU-Z](https://www.techpowerup.com/download/gpu-z/)

GPU-Z is used to see graphics card's GPU specs such as GPU model, manufacturing technology, GPU memory size and bandwidth, and many more.

### [HWiNFO](http://www.hwinfo.com)

This small utility shows an in-depth view of your system and can monitor hardware components in real-time.

### [Speccy](https://www.ccleaner.com/speccy)

Speccy gives a quick spec of your system including CPU, motherboard, memory, hard disk and more. One nice feature is its ability to save and load system specs.

## [SysInternals Suite](https://docs.microsoft.com/en-us/sysinternals)

The whole set of tools in this suite are precious and worth learning. The suite was originally written by Mark Russinovich and Bryce Cogswell and is currently owned by Microsoft. The suite allows you to monitor disks (DiskMon), monitor files (FileMon), monitor ports (PortMon), monitor processes (ProcMon), explore processes (ProcExp), list all loaded DLL's (ListDll), list all handles (handle), view debug outputs (DbgView), view system objects (WinObj), view disk id (VolumeID), view auto run applications (AutoRuns), view load order of system drivers (LoadOrd), run EXE files remotely (PsExec) and many more.

## System Tuning

### [CCleaner](https://www.ccleaner.com)

This tool easily cleans up you system for privacy or tuning purposes.

### [Glary Utilities](https://www.glarysoft.com)

This one contains a bunch of utility tools to clean, fix, or tune your Windows freely!

