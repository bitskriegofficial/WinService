# WinService
Windows service for monitoring registry changes,process and drive mounting detection. 

# How Does It Work ?
A windows service is an application which runs in the background. In this project, a windows service will be built to monitor key events: registry changes, process monitoring, and drive mounting detection.This can eventually become a program to provide alerts for malicious activity.

# Goal for Current Version 
The first version of the service aims to detect near run-time changes in windows registry for different processes 
Steps:
<ol>
<li>Build the basic outline for the service which performs simple functions (as proof of build)</li>
<li>Add drive mount/unmount detection capability</li>
<li>Add detection for number of children of processes</li>
<li>Add registry key change detection functionality</li>
<li>Add functionality to detect subkey changes as well</li>
</ol>
# Resources
<ul>
<li>
Registry  <a href="https://support.microsoft.com/en-in/help/256986/windows-registry-information-for-advanced-users"> Windows Registry </a>
</li>
<li>
Windows process <a href="https://docs.microsoft.com/en-us/windows/win32/procthread/processes-and-threads#:~:text=A%20process%2C%20in%20the%20simplest,operating%20system%20allocates%20processor%20time.&text=A%20job%20object%20allows%20groups,be%20managed%20as%20a%20unit."> Process </a>
</li>
</ul>

# Disclaimer 
The author(s) and organization do not bear any responsibility for any damage caused by the use of this service. It is being built as a simple logging service inside windows which can detect certain changes. Any modifications which account to malicious use are prohibited, and the author(s) and organization cannot be held liable for use of such modified software.

# Licensing 
To be decided.
