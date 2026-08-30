# Awesome Apple Security List with stars

> Curated list of tools, techniques and resources related to Apple Security (macOS, iOS, iPadOS, tvOS, watchOS) aimed to help people with an interest in Apple related cyber security topics to gain a foothold in this field.

## Contents

* [Awesome Apple Security List ](#awesome-apple-security-list-)
  * [Contents](#contents)
  * [Forensics](#forensics)
    * [Acquisition and Evidence Collection](#acquisition-and-evidence-collection)
  * [Apple Guidance](#apple-guidance)
  * [Attack Vectors and Adversary Techniques](#attack-vectors-and-adversary-techniques)
  * [Blogs](#blogs)
  * [Articles](#articles)
  * [Books and Magazines](#books-and-magazines)
  * [People](#people)
  * [Software Collections](#software-collections)
  * [Malware](#malware)
  * [Hardware Information](#hardware-information)
  * [Log Analysis](#log-analysis)
  * [Processes](#processes)
  * [Persistence](#persistence)
  * [Tools](#tools)
    * [Process Viewer](#process-viewer)
    * [File System](#file-system)
    * [Offensive Tools](#offensive-tools)
    * [Reverse Engineering Tools](#reverse-engineering-tools)
    * [Dynamic Analysis Tools](#dynamic-analysis-tools)
    * [Static Analysis Tools](#static-analysis-tools)
    * [Frida](#frida)
  * [Conferences](#conferences)
  * [Trainings](#trainings)
  * [Videos](#videos)
  * [Contributing](#contributing)

***

## Forensics

### Acquisition and Evidence Collection

* [Auditor](https://github.com/jipegit/OSXAuditor) ⭐ 3,135 | 🐛 8 | 🌐 JavaScript | 📅 2020-07-27 - Deprecated macOS DFIR tool for older systems.
* [Collector](https://github.com/yelp/osxcollector) ⚠️ Archived - macOS offshoot for live response.
* [mac\_apt](https://github.com/ydkhatri/mac_apt) ⭐ 1,079 | 🐛 8 | 🌐 Python | 📅 2026-08-21 - Plugin based forensics framework for quick mac triage that works on live machines, disk images or individual artifact files.
* [Cellebrite Digital Collector (Former Macquisition)](https://cellebrite.com/en/digital-collector/) - Commercial Tooling for Acquisition of macOS Forensic Images.
* [The ESF Playground](https://themittenmac.com/the-esf-playground/) - A tool to view the events in Apple Endpoint Security Framework (ESF) in real time.

## Apple Guidance

* [Developers Documentation](https://developer.apple.com/documentation/foundation?preferredLanguage=oc) - Developer Documentation for reference.
* [Security Documentation](https://support.apple.com/en-gb/guide/security/welcome/we) - Security Documentation of Apple Products.
* [Report Vulnerabilities](https://support.apple.com/en-gb/HT20122) - In case you want to submit a vulnerability to Apple.
* [Apple Security Bounty](https://developer.apple.com/security-bounty) - Apple's Bug Bounty Program information.
* [Apple Platform Security](https://manuals.info.apple.com/MANUALS/1000/MA1902/en_GB/apple-platform-security-guide-b.pd) - Apple Information on Platform Security.
* [Apple File System](https://developer.apple.com/documentation/foundation/file_system/about_apple_file_system) - Documentation on the filesystem.

## Attack Vectors and Adversary Techniques

* [MITRE ATT\&CK - macOS Matrix](https://attack.mitre.org/matrices/enterprise/macos/) - Tools, Techniques and Attack Vectors used by adversaries to target macOS devices.
* [Sandbox Evasion Macros](https://www.mdsec.co.uk/2018/08/escaping-the-sandbox-microsoft-office-on-macos/) - How to evade the sandbox with MS Office Macros.

## Blogs

* [Mac Security Blog](https://www.intego.com/mac-security-blog/) - Generic Blog on macOS Security.
* [Wojciech Regula's Blog](https://wojciechregula.blog/post/) - Wojciech's macOS Related blog.
* [Cedric Owens Medium Blog](https://cedowens.medium.com) - Cedric Owens Blog on macOS Security.
* [Objective-See by Patrick Wardle](https://objective-see.com/) - Patrick Wardle's Website.
* [Mac4n6](https://www.mac4n6.com/) - Mac Forensics.
* [Mandiant](https://www.mandiant.com/search?search=macos) - Mandiant macOS Articles.
* [Scripting OSX!](https://scriptingosx.com/) - macOS Admin related Blog.

## Articles

* [RE Cocoa Applications](https://www.mandiant.com/resources/blog/introduction-to-reve) -
* [Office365 Sanbox Escape](https://desi-jarvis.medium.com/office365-macos-sandbox-escape-fcce4fa4123c) - Sandbox Escape macOS for Office365.

## Books and Magazines

* [The Art of Mac Malware](https://taomm.org/) - Primer on malware on macOS by Patrick Wardle.
* [macOS Incident Response](https://www.amazon.com/OS-Incident-Response-Scripting-Analysis-ebook/dp/B01FHOHHVS) - macOS Incident Response primer (2017).
* [Kernel Book](http://newosxbook.com/index.php) - Book in three parts about the macOS Kernel.
* [macOS Internals](https://www.amazon.com/Mac-OS-Internals-Systems-Approach-ebook/dp/B004Y4UTLI/) - Internals of macOS (2007).
* [Kernel Programming](https://www.amazon.com/OS-X-iOS-Kernel-Programming/dp/1430235365/) - Kernel Programming reference for macOS / iOS.
* [eForensics Magazine](https://eforensicsmag.com/product/macos-forensics/) - Magazine for (macOS) Forensics.
* [iOS Forensics for Investigators](https://www.amazon.com/iOS-Forensics-Investigators-forensics-extracting-ebook-dp-B09V19ZBKK/dp/B09V19ZBKK/ref=mt_other?_encoding=UTF8\&me=\&qid=) - iOS Forensics Book.
* [iOS Hacking Guide](https://web.securityinnovation.com/hacking-ios-applications) - By Security Innovation.
* [iOS Application Security: The Definitive Guide for Hackers and Developers](https://nostarch.com/iossecurity) - By David Thiel.
* [iOS Penetration Testing: A Definitive Guide to iOS Security](https://link.springer.com/book/10.1007/978-1-4842-2355-0) - By Kunal Relan.
* [Learning iOS Penetration Testing](https://www.packtpub.com/product/learning-ios-penetration-testing/9781785883255) - By Swaroop Yermalkar.
* [Hacking and Securing iOS Applications](https://www.oreilly.com/library/view/hacking-and-securing/9781449325213/) - By Jonathan Zdziarski.
* [iOS Hacker's Handbook](https://www.amazon.com/iOS-Hackers-Handbook-Charlie-Miller/dp/1118204123) - By Charlie Miller.

## People

* [Cedric Owens](https://twitter.com/cedowens) - X - macOS Security Researcher and Purple Teamer.
* [Csaba Fitzl](https://twitter.com/theevilbit) - X - Hungarian Researcher specialized on macOS Security.
* [Patrick Wardle](https://twitter.com/patrickwardle) - X - Founder of Objective-see, and Security Researcher.
* [Sarah Edwards](https://twitter.com/iamevltwin) - X - Security Researcher and Trainer of SANS 518 Course.
* [Cody Thomas](https://github.com/its-a-feature) - GitHub - Developer of Mythic C2.
* [Regula Wojciech](https://x.com/_r3ggi) - X - macOS Security Researcher.
* [Alexis Brignoni](https://infosec.exchange/@abrignoni) - X - DFIR Researcher, iLEAPP Developer.
* [M4shl3](https://hackmd.io/@M4shl3) - hackmd.io - Digital Forensics Investigator.

## Software Collections

* [Macintosh Repository](https://www.macintoshrepository.org/) - Repository of old macOS Software.
* [IPSW Repository](https://ipsw.me/) - Repository of IPSW Restore files.
* [Mr Macintosh](https://mrmacintosh.com/) - Collection of macOS Firmware and so much more.

## Malware

* [VX-Underground Malware Source Code](https://github.com/vxunderground/MalwareSourceCode) ⭐ 18,689 | 🐛 14 | 🌐 Assembly | 📅 2026-05-30 - Malware Sourcecode collection (various OS).
* [Objective-See Malware](https://github.com/objective-see/Malware) ⭐ 765 | 🐛 0 | 📅 2026-08-20 - Malware Collection by Patrick Wardle.
* [The Safe Mac](https://www.thesafemac.com/mmg-catalog/) - Older macOS Malware Catalogue.
* [VX-Underground](https://www.vx-underground.org/archive/VxHeaven/vl.php.html) - Malware Collection (various OS).

## Hardware Information

* [Hardware Database](https://everymac.com/) - Lookup hardware specifications of every mac model.
* [M1 Chip Safe Mode](https://eclecticlight.co/2022/01/17/what-does-safe-mode-do-to-an-m1-mac/) - Blogpost on M1 Chipset Safe Mode.

## Log Analysis

* [Unified Log](https://eclecticlight.co/2018/03/20/macos-unified-log-2-content-and-extraction/) - A primer on macOS Unified Log.
* [Unified Log in Incident Response](https://www.crowdstrike.com/blog/how-to-leverage-apple-unified-log-for-incident-response/) - Using the Unified Log for Incident Response.

## Processes

* [True Tree](https://themittenmac.com/the-truetree-concept/) - Improved process tree.
* [Process and File Monitor](https://objective-see.com/products/utilities.html) - Command Line Utilit(ies) to monitor processes and files.

## Persistence

* [Persistence Samples](https://theevilbit.github.io/categories/persistence/) - Collection of persistence methods and samples used.
* [Knockknock](https://objective-see.com/products/knockknock.html) - Displays persistence items in macOS.
* [PersistentJXA](https://github.com/D00MFist/PersistentJXA) ⭐ 291 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-26 - Collection of macOS persistence methods in JXA.
* [Apple Persistence Mechanisms](https://gist.github.com/jipegit/04d1c577f20922adcd2cfd90698c151b) - Persistence Mechanisms.

## Tools

### Process Viewer

* [Process Tree](https://github.com/ydkhatri/mac_apt/tree/729630c8bbe7a73cce3ca330305d3301a919cb07) ⭐ 1,079 | 🐛 8 | 🌐 Python | 📅 2026-08-21 - Process tree Repository.

### File System

* [iOS FS Event Parser](https://github.com/dlcowen/FSEventsParser) ⭐ 283 | 🐛 2 | 🌐 Python | 📅 2024-12-04 - Parsing filesystem events.
* [macOS FS Events Parser](https://github.com/mac4n6/FSEventsParser) ⭐ 46 | 🐛 1 | 🌐 Python | 📅 2024-05-06 - FS Events Parser.
* [FS Monitor](https://fsmonitor.com/) - FS Monitor to view live file system changes.

### Offensive Tools

* [SwiftSpy](https://github.com/slyd0g/SwiftSpy) ⭐ 93 | 🐛 0 | 🌐 Swift | 📅 2021-09-01 - macOS Keyloger written in Swift.
* [VOODOO](https://github.com/breakpointHQ/VOODOO) ⭐ 50 | 🐛 0 | 🌐 Ruby | 📅 2024-12-24 - Browser Attack Framework for macOS.
* [Mythic C2](https://docs.mythic-c2.net/) - Mythic C2 Framework Documentation.

### Reverse Engineering Tools

* [Ghidra](https://github.com/NationalSecurityAgency/ghidra) ⭐ 73,770 | 🐛 1,922 | 🌐 Java | 📅 2026-08-28 - A software reverse engineering (SRE) framework created and maintained by the National Security Agency Research Directorate.
* [Radare2](https://github.com/radareorg/radare2) ⭐ 24,681 | 🐛 821 | 🌐 C | 📅 2026-08-30 - UNIX-like reverse engineering framework and command-line toolset.
* [Cutter](https://github.com/rizinorg/cutter) ⭐ 19,635 | 🐛 494 | 🌐 C++ | 📅 2026-08-22 - Free and Open Source Reverse Engineering Platform powered by rizin.
* [iOS App Signer](https://github.com/DanTheMan827/ios-app-signer) ⭐ 6,313 | 🐛 123 | 🌐 Objective-C | 📅 2025-09-01 - An app for macOS that can (re)sign apps and bundle them into ipa files that are ready to be installed on an iOS device.
* [frida-ios-dump](https://github.com/AloneMonkey/frida-ios-dump) ⭐ 3,922 | 🐛 107 | 🌐 JavaScript | 📅 2023-05-03 - A tool to pull a decrypted IPA from a jailbroken device.
* [Clutch](https://github.com/KJCracks/Clutch) ⭐ 3,824 | 🐛 43 | 🌐 Objective-C | 📅 2024-11-15 - A high-speed iOS decryption tool.
* [class-dump](https://github.com/nygard/class-dump) ⭐ 3,586 | 🐛 41 | 🌐 Objective-C | 📅 2022-04-06 - A command-line utility for examining the Objective-C segment of Mach-O files.
* [bagbak](https://github.com/ChiChou/bagbak) ⭐ 1,497 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-24 - Yet another frida based App decryptor. Requires jailbroken iOS device and frida.re.
* [dsdump](https://github.com/DerekSelander/dsdump) ⚠️ Archived - An improved nm + objc/swift class-dump tool.
* [flexdecrypt](https://github.com/JohnCoates/flexdecrypt) ⭐ 738 | 🐛 8 | 🌐 Swift | 📅 2023-06-24 - An iOS App & Mach-O binary decryptor.
* [bfinject](https://github.com/BishopFox/bfinject) ⭐ 642 | 🐛 34 | 🌐 Objective-C++ | 📅 2022-03-17 - Easy dylib injection for jailbroken 64-bit iOS 11.0 - 11.1.2. Compatible with Electra and LiberiOS jailbreaks.
* [bfdecrypt](https://github.com/BishopFox/bfdecrypt) ⭐ 491 | 🐛 10 | 🌐 C | 📅 2020-05-24 - Utility to decrypt App Store apps on jailbroken iOS 11.x.
* [SwiftDump](https://github.com/neil-wu/SwiftDump/) ⭐ 442 | 🐛 6 | 🌐 Swift | 📅 2023-08-18 - A command-line tool for retriving the Swift Object info from Mach-O file.
* [r2flutch](https://github.com/as0ler/r2flutch) ⭐ 185 | 🐛 0 | 🌐 Python | 📅 2026-04-16 - Yet another tool to decrypt iOS apps using r2frida.
* [Hopper](https://www.hopperapp.com/) - A reverse engineering tool that will assist you in your static analysis of executable files.
* [jtool](http://www.newosxbook.com/tools/jtool.html) - An app inspector, disassembler, and signing utility for the macOS, iOS.
* [Sideloadly](https://sideloadly.io/) - An app to sideload your favorite games and apps to Jailbroken & Non-Jailbroken iOS devices.
* [Cydia Impactor](http://www.cydiaimpactor.com/) - A GUI tool for sideloading iOS application.
* [AltStore](https://altstore.io/) - Allows to sideload other apps (.ipa files) onto iOS device.

### Dynamic Analysis Tools

* [Frida](https://github.com/frida/frida) ⭐ 21,794 | 🐛 1,960 | 🌐 Meson | 📅 2026-08-27 - Dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers.
* [objection](https://github.com/sensepost/objection) ⭐ 9,352 | 🐛 55 | 🌐 Python | 📅 2026-07-23 - A runtime mobile exploration toolkit, powered by Frida, built to help you assess the security posture of your mobile applications, without needing a jailbreak.
* [Qiling](https://github.com/qilingframework/qiling) ⭐ 6,079 | 🐛 122 | 🌐 Python | 📅 2026-07-22 - An advanced binary emulation framework.
* [fishhook](https://github.com/facebook/fishhook) ⭐ 5,427 | 🐛 39 | 🌐 C | 📅 2024-08-01 - A library that enables dynamically rebinding symbols in Mach-O binaries running on iOS.
* [unidbg](https://github.com/zhkl0228/unidbg) ⭐ 5,175 | 🐛 419 | 🌐 Java | 📅 2026-08-30 - Allows you to emulate an Android ARM32 and/or ARM64 native library, and an experimental iOS emulation.
* [ios-deploy](https://github.com/ios-control/ios-deploy) ⭐ 3,637 | 🐛 45 | 🌐 Objective-C | 📅 2024-06-24 - Install and debug iOS apps from the command line. Designed to work on un-jailbroken devices.
* [Runtime Mobile Security (RMS)](https://github.com/m0bilesecurity/RMS-Runtime-Mobile-Security) ⭐ 3,076 | 🐛 8 | 🌐 JavaScript | 📅 2026-08-03 - Runtime Mobile Security (RMS), powered by FRIDA, is a powerful web interface that helps you to manipulate Android and iOS Apps at Runtime.
* [Passionfruit](https://github.com/chaitin/passionfruit) ⚠️ Archived - Simple iOS app blackbox assessment tool, powered by frida 12.x and vuejs.
* [r2frida](https://github.com/nowsecure/r2frida) ⭐ 1,435 | 🐛 44 | 🌐 TypeScript | 📅 2026-08-30 - Radare2 and Frida better together.
* [Grapefruit](https://github.com/ChiChou/grapefruit) ⭐ 1,379 | 🐛 12 | 🌐 TypeScript | 📅 2026-08-11 - Runtime Application Instruments for iOS.
* [Dwarf](https://github.com/iGio90/Dwarf) ⭐ 1,318 | 🐛 5 | 🌐 Python | 📅 2024-05-16 - Full featured multi arch/os debugger built on top of PyQt5 and frida.
* [frida-gum](https://github.com/frida/frida-gum) ⭐ 1,011 | 🐛 208 | 🌐 C | 📅 2026-08-27 - Cross-platform instrumentation and introspection library written in C.
* [iproxy](https://github.com/libimobiledevice/libusbmuxd) ⭐ 687 | 🐛 31 | 🌐 C | 📅 2025-09-07 - A utility allows binding local TCP ports so that a connection to one (or more) of the local ports will be forwarded to the specified port (or ports) on a usbmux device.
* [r2ghidra](https://github.com/radareorg/r2ghidra) ⭐ 543 | 🐛 5 | 🌐 C++ | 📅 2026-08-23 - An integration of the Ghidra decompiler for radare2.
* [Fridax](https://github.com/NorthwaveSecurity/fridax) ⭐ 180 | 🐛 9 | 🌐 JavaScript | 📅 2023-04-04 - Fridax enables you to read variables and intercept/hook functions in Xamarin/Mono JIT and AOT compiled iOS/Android applications.
* [aah](https://github.com/zydeco/aah) ⭐ 180 | 🐛 1 | 🌐 Objective-C | 📅 2020-08-15 - Run iOS arm64 binaries on x86\_64 macOS, with varying degrees of success.
* [FridaHookSwiftAlamofire](https://github.com/neil-wu/FridaHookSwiftAlamofire) ⭐ 113 | 🐛 11 | 🌐 TypeScript | 📅 2023-01-06 - A frida tool that capture GET/POST HTTP requests of iOS Swift library 'Alamofire' and disable SSL Pinning.
* [Corellium](https://www.corellium.com/) - The only platform offering ARM-based mobile device virtualization using a custom-built hypervisor for real-world accuracy and high performance.
* [itunnel](https://code.google.com/archive/p/iphonetunnel-usbmuxconnectbyport/downloads) - Use to forward SSH via USB.
* [membuddy](https://zygosec.com/membuddy.html) - Dynamic memory analysis & visualisation tool for security researchers.
* [LLDB](https://lldb.llvm.org/) - A next generation, high-performance debugger.
* [mitmproxy](https://mitmproxy.org/) - A free and open source interactive HTTPS proxy.
* [Burp Suite](https://portswigger.net/burp) - An advanced HTTPS proxy software.

### Static Analysis Tools

* [Keychain Dumper](https://github.com/ptoomey3/Keychain-Dumper) ⭐ 1,419 | 🐛 19 | 🌐 Objective-C | 📅 2024-08-15 - A tool to check which keychain items are available to an attacker once an iOS device has been jailbroken.
* [iLEAPP](https://github.com/abrignoni/iLEAPP) ⭐ 1,178 | 🐛 60 | 🌐 Python | 📅 2026-08-30 - An iOS Logs, Events, And Plist Parser.
* [XMachOViewer](https://github.com/horsicq/XMachOViewer) ⭐ 961 | 🐛 4 | 🌐 C++ | 📅 2026-08-29 - A Mach-O viewer for Windows, Linux and macOS.
* [MachO-Explorer](https://github.com/DeVaukz/MachO-Explorer) ⭐ 678 | 🐛 5 | 🌐 Swift | 📅 2020-09-05 - A graphical Mach-O viewer for macOS. Powered by Mach-O Kit.
* [BinaryCookieReader](https://github.com/as0ler/BinaryCookieReader) ⭐ 106 | 🐛 1 | 🌐 Python | 📅 2024-09-28 - A tool to read the binarycookie format of Cookies on iOS applications.
* [PList Viewer](https://github.com/TingPing/plist-viewer) ⭐ 20 | 🐛 0 | 🌐 C | 📅 2015-05-28 - Gtk application to view property list files.
* [iFunbox](https://www.i-funbox.com/en/index.html) - A general file management software for iPhone and other Apple products.
* [3uTools](http://www.3u.com/) - An All-in-One management software for iOS devices.
* [iTools](https://www.thinkskysoft.com/itools/) - An All-in-One solution for iOS devices management.

### TCC & Permissions Tools

* [MacOS-Full-Disk-Access-Tunnel](https://github.com/civillizard/MacOS-Full-Disk-Access-Tunnel) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-04-17 - Grant Full Disk Access to interpreter binaries (Python, Node, Ruby) so launchd and cron scripts can read TCC-protected data like Safari history, cookies, and Photos metadata.

### Frida

* [FridaSwiftDump](https://github.com/neil-wu/FridaSwiftDump/) ⭐ 93 | 🐛 9 | 🌐 TypeScript | 📅 2023-03-05 - A Frida script for retriving the Swift Object info from an running app.
* [iOS 13 SSL Bypass](https://codeshare.frida.re/@federicodotta/ios13-pinning-bypass/) - SSL Pinning Bypass for iOS 13.
* [iOS 12 SSL Bypass](https://codeshare.frida.re/@machoreverser/ios12-ssl-bypass/) - SSL Pinning Bypass for iOS 12.
* [iOS Jailbreak Detection Bypass](https://codeshare.frida.re/@liangxiaoyi1024/ios-jailbreak-detection-bypass/) - A Frida script used for bypass iOS jailbreak detection by hooking some methods and functions.
* [iOS App Static Analysis](https://codeshare.frida.re/@interference-security/ios-app-static-analysis/) - Script for iOS app's static analysis.
* [Touch ID Bypass](https://highaltitudehacks.com/2018/07/26/ios-application-security-part-50-touch-id-bypass-with-frida/) - A Frida script for iOS Touch/Face ID Bypass.

## Conferences

* [MacDevOps YVR](https://mdoyvr.com)
* [OBTS](https://objectivebythesea.org)

## Trainings

* [OffSec EXP-312](https://www.offsec.com/courses/exp-312/) - Advanced macOS Control Bypass Trainin by OffSec's @theevilbit.
* [Sumuri](https://sumuri.com/mac-training/) - Forensics Training in two parts for macOS, to gain Certified Forensic Mac Examiner Certification.
* [SANS 518](https://www.sans.org/cyber-security-courses/mac-and-ios-forensic-analysis-and-incident-response/) - Course at SANS for macOS and iOS Forensics.
* [Objective-by-the-sea](https://objectivebythesea.org/v5/index.html) - Security Conference (macOS) organized by Patrick Wardle.
* [SpecterOPS](https://specterops.io/training/mac-tradecraft/) - SPECTEROPS macOS Adversary Tactics.
* [Pentesting iOS Applications](https://www.pentesteracademy.com/course?id=2) - By PentesterAcademy.
* [iOS Pentesting](https://www.youtube.com/playlist?list=PL5Fxd3nu70eyqiqrVlD9QMoaOARr082TA) - By Mantis.
* [iOS Application Pentesting Series](https://www.youtube.com/playlist?list=PLm_U3e1sSTMvgj1sbZ2Ng6VbxMWw8Wyk9) - By Sateesh Verma.
* [IOS: Penetration Testing](https://www.youtube.com/playlist?list=PLanZMaPa4zzyGJ7IiW2zQNC40pWf2-7uE) - By Noisy Hacker.
* [JAMF 100 Course](https://www.youtube.com/watch?v=DsaWL0xzs6o\&list=PLWs1qukS_mcb1wwKeSnT80kvTKow_eJXJ) - JAMF 100 Youtube Playlist.

## Videos

* [Curated YouTube Playlist](https://www.youtube.com/playlist?list=PL-zBXVr8oElPpEuhuTON7qE4k6iVh0zMv) - Curated YouTube playlist with macOS/iOS Security Topics.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-30._
