# do

* IPC   inter-process communication 
* LPE		local Privilege escalation


# IPC
* 2021 Feb 21 - [Offensive Windows IPC Internals 2: RPC](https://csandker.io/2021/02/21/Offensive-Windows-IPC-2-RPC.html) | [:closed_book:](../../blob/master/paper/csandker.io-Offensive_Windows_IPC_Internals_2_RPC.pdf)
* 2021 Jan 10 - [Offensive Windows IPC Internals 1: Named Pipes](https://csandker.io/2021/01/10/Offensive-Windows-IPC-1-NamedPipes.html) | [:closed_book:](../../blob/master/paper/csandker.io-Offensive_Windows_IPC_Internals_1_Named_Pipes.pdf)



# Article
* [1] https://medium.com/tenable-techblog/psexec-local-privilege-escalation-2e8069adc9c8
* [2] https://book.hacktricks.xyz/windows/windows-local-privilege-escalation/named-pipe-client-impersonation
* [3] https://halove23.blogspot.com/2021/01/another-privilege-escalation-in-windows.html
* [4] PrintSpoofer - Abusing Impersonation Privileges on Windows 10 and Server 2019  https://itm4n.github.io/printspoofer-abusing-impersonate-privileges/
* [5] https://versprite.com/blog/security-research/vulnerable-named-pipe-application/
* [6] 2021 Feb 10 CVE-2021-1732 https://ti.dbappsecurity.com.cn/blog/index.php/2021/02/10/windows-kernel-zero-day-exploit-is-used-by-bitter-apt-in-targeted-attack/
* [7] 2019 https://versprite.com/blog/security-research/vulnerable-named-pipe-application/
* [8] 2021 Feb 10.CVE-2021-24092: 12 Years in Hiding – A Privilege Escalation Vulnerability in Windows Defender  https://labs.sentinelone.com/cve-2021-24092-12-years-in-hiding-a-privilege-escalation-vulnerability-in-windows-defender/
* [9] 2020 Nov https://itm4n.github.io/windows-registry-rpceptmapper-eop/
* [10] 2020 Feb 19 https://blog.vonahi.io/srclient-dll-hijacking/  | [:closed_book:](../../blob/master/paper/blog.vonahi.io-SrClient-DLL-Hijacking-a-Windows-Server-2012-0-day-that-wont-be-patched.pdf)
* [11] 2021 May  https://www.blackhat.com/asia-21/briefings/schedule/index.html#the-rise-of-potatoes-privilege-escalations-in-windows-services-22373
* [12] 2019 Aug 01 https://blog.xpnsec.com/analysing-rpc-with-ghidra-neo4j/
* [13] 2021 Feb 28 https://www.hackingarticles.in/window-privilege-escalation-automated-script/  | [:closed_book:](../../blob/master/paper/hackingarticles.in-Window_Privilege_Escalation_Automated_Script.pdf)
* [14]  leverages the Outlook Application Interface (COM Interface) to execute shellcode on a system based on a specific trigger subject line https://github.com/S4R1N/BadOutlook
* [15] Windows & Active Directory Exploitation Cheat Sheet and Command Reference https://casvancooten.com/posts/2020/11/windows-active-directory-exploitation-cheat-sheet-and-command-reference/ | [:closed_book:](../../blob/master/paper/Windows_Active_Directory_Exploitation_Cheat_Sheet.pdf)
* [16] Windows File Confusion: Masquerading Unsigned Binaries as Signed Ones http://www.exploit-monday.com/2013/02/WindowsFileConfusion.html?m=1  | [:closed_book:](../../blob/master/paper/Windows_File_Confusion.pdf)


# Twitter tips
* [1] EOP in Foxit PDF Reader - yeah, their updater runs as SYSTEM   https://twitter.com/LloydLabs/status/1355701446117912576



# POC/Tools
* [1] https://github.com/tenable/poc/tree/master/Microsoft/Sysinternals/PsExecEscalate.cpp
* [2] https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite
* [3] https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Windows%20-%20Privilege%20Escalation.md
* [4] UAC_bypass_windows_store https://github.com/sailay1996/UAC_bypass_windows_store
* [5] Windows 10 Privilege Escalation (magnify.exe) via Dll Search Order Hijacking https://github.com/sailay1996/magnifier0day
* [6] leverage the Windows Performance Counters https://github.com/itm4n/Perfusion
* [7] https://www.offensive-security.com/metasploit-unleashed/privilege-escalation/
* [8] https://github.com/quentinhardy/pytmipe
* [9] https://github.com/ZecOps/CVE-2020-0796-LPE-POC 
* [10] https://github.com/BeichenDream/BadPotato
* [11] https://github.com/antonioCoco/RogueWinRM
* [12] Windows IPC open source code https://github.com/microsoft/IPC

# Story
* [1] https://www.zdnet.com/article/privilege-escalation-vulnerability-patched-in-docker-desktop-for-windows/

# Webcasts
* [1] Pen Testing with PowerShell: Local Privilege Escalation Technique https://www.sans.org/webcasts/pen-testing-powershell-local-privilege-escalation-technique-108745

# Reference
* [1] https://github.com/sailay1996/awesome_windows_logical_bugs

# Old info
* [1] 2019 Another Local Privilege Escalation (LPE) Vulnerability Using Process Creation Impersonation https://www.fortinet.com/blog/threat-research/another-local-privilege-escalation-lpe-vulnerability
* [2] 2019 More Than a Penetration Test (Microsoft Windows CVE-2019–1082) https://medium.com/@bazyli.michal/more-than-a-penetration-test-cve-2019-1082-647ba2e59034
* [3] https://awesomeopensource.com/project/m0nad/awesome-privilege-escalation
* [4] https://awesomeopensource.com/project/marcosValle/awesome-windows-red-team#privilege-escalation
* [5] Microsoft https://docs.microsoft.com/en-us/windows/win32/ipc/interprocess-communications


