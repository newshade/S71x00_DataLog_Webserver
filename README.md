# S7-1x00_DataLog_Download
A bunch of scripts for automating of DataLogs download via SIMATIC S7-1200/1500 Webserver. As of FW V4.2 the way of accessing DataLogs and other files on webserver has been changed, due to security issues. Now direct access is not permitted, all files can only be downloaded using the referer, which makes webserver actions "automation" a bit more difficult.
<br /><br />
Currently tested on:
<ul>
 <li>S7-1200 FW V4.4</li>
</ul>
Setting up:
<ul>
 <li>Set the protocol before IP address in the script based on your S7-1x00 webserver setting (HTTP or HTTPS)</li>
 <li>Set the IP address</li>
 <li>Upload all files from the repo's subdirectory to your webserver (with all sub-scripts and libraries)</li>
 <li>Do not insert .js extension to the section "files with synamic content" in your webserver settings</li>
 <li>Change the main page from "index.htm" to "index.html" in your webserver settings</li>
 <li>The scripts do not take user authentication into consideration thus it is necessary to set files permission to "Everyone" in your webserver settings</li>
</ul>
