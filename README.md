<p>
<h4 class="utilsubject">Description</h4>
PingInfoView is a small utility that allows you to easily ping multiple host names and IP addresses, and 
watch the result in one table.
It automatically ping to all hosts every number of seconds that you specify, and displays the number of succeed and failed pings, as well
as the average ping time.
You can also save the ping result into text/html/xml file, or copy it to the clipboard.


<p>
<img src="https://www.nirsoft.net/utils/pinginfoview.gif">
<p>


<p>
<h4 class="utilsubject">System Requirements</h4>
This utility works under Windows 2000, Windows XP, Windows Server 2003, Windows Server 2008, Windows Vista, Windows 7, Windows 8, and Windows 10.
Older versions of Windows are not supported.




<p>
<h4 class="utilsubject">Versions History</h4>
<ul>


<li>Version 1.80
<ul>
<li>Added new option: Beep On Succeeded Pings (After Failure).
<li>Fixed bug: When the lower pane option was turned off, PingInfoView didn't add the pings to the log file.
</ul>


<li>Version 1.75
<ul>
<li>Added 'Resolve host name to IP address on every ping' option. If the IP address of the host you ping may change, you should turn on this option , so when
the IP address is changed, PingInfoView will ping the new IP address.
<li>Added new option in 'Advanced Options' window: 'Limit the total number of accumulated pings' (Default is 50000). 
If you run PingInfoView for long period of time, you should use this option.
Otherwise, the accumuated ping result will consume a lot of memory, and eventually PingInfoView will respond very slowly or crash.

<li>Added 'Window Title' field. The text you type here will appear in the title of the main window. 
</ul>


<li>Version 1.70
<ul>
<li>Automatic export feature: You can now choose to generate a new filename on every session (When you close the program and then run it again) or on every save. You can also generate a filename with date/time (e.g: ping20170925112130.csv) instead of numeric counter. 
</ul>


<li>Version 1.65
<ul>
<li>The 'Consecutive Failed Count' column now keeps the last value when pings are ok again.
<li>Added 'Max Consecutive Failed Count' column which displays the maximum number of consecutive failed pings and 'Max Consecutive Failed Time' which displays the date/time that
the maximum number of consecutive failed pings was detected.
<li>Added 'Add only failed pings' option to the 'Lower Pane Mode' in 'Advanced Options' window.
</ul>


<li>Version 1.60
<ul>
<li>Added option to automatically export the current pings status to a file (csv/tab-delimited/html/xml) every xx seconds (In 'Advanced Options' window). 
<li>Added option to execute a command on ping failure. 
<li>Added option to specify the number of consecutive failed pings to trigger the sound/beep alert and the failed command executaion.
<li>Added 'Consecutive Failed Count' column.
</ul>


<li>Version 1.55
<ul>
<li>Added option to choose the type of beep/sound to use when a ping fails (In 'Advanced Options' window).
<li>Added option to add all ping results or only the failed pings into a comma-delimited or tab-delimited log file (In 'Advanced Options' window).
<li>Added option to stop adding the ping results into the lower pane (In 'Advanced Options' window). 
It's recommended to use this option if you have large amount of pings, because the accumulation of ping results consumes a lot of memory and 
eventually causes PingInfoView to crash.

<li>When 'Use IP-Host Description format' option is turned on, PingInfoView now adds the IP address even if it doesn't have a description.
</ul>





<li>Version 1.51
<ul>
<li>On IP-Host format, if you put '#' in the beginning of the line, PingInfoView will consider it as a remark line and ignore it.
</ul>

<li>Version 1.50
<ul>
<li>Added option to specify the ping size (The default is 32 bytes).
<li>Added 'Order' column, which specifies the original order of hosts, as you typed in the 'Ping Options' window.
</ul>


<li>Version 1.45
<ul>
<li>Added option to control the maximum number of concurrent pings (In 'Advanced Options' window - F9). The default value is 500.
<li>Fixed bug: PingInfoView failed to remember the last size/position of the main window if it was not located in the primary monitor. 
</ul>


<li>Version 1.43
<ul>
<li>Fixed bug: When using PingInfoView from command-line, /IPHostDescFormat and some other command-line options failed to work properly.
</ul>

<li>Version 1.42
<ul>
<li>Fixed issue: When editing PingInfoView_hosts.txt with external editor that adds Byte order mark to the file, PingInfoView failed to
handle the first host name.
</ul>


<li>Version 1.41
<ul>
<li>Added 'Sort On Every Update' option.
</ul>


<li>Version 1.40
<ul>
<li>Added 'Auto Scroll Lower Pane' option.
<li>Fixed bug: In some circumstances, when using 'Copy Selected Items' on the lower pane, PingInfoView copied the wrong items or crashed.
<li>Improved the ability of PingInfoView to handle hundreds or thousants of IP addresses in the same time.
</ul>
<li>Version 1.36
<ul>
<li>Added 'Auto Size Columns+Headers' option, which allows you to automatically resize the columns according to the row values and column headers. 
<li>Fixed issue: The properties and the options windows opened in the wrong monitor, on multi-monitors system. 
</ul>

<li>Version 1.35
<ul>
<li>Added a lower pane that lists the result of all pings for the selected IP address in the upper pane.
(You can disable this feature by unchecking the 'Show Lower Pane' option under the Options menu)
</ul>

<li>Version 1.30
<ul>
<li>PingInfoView now resolves the IP addresses and displays the result under the 'Host Name' column.
<li>Added 'Minimum Ping Time' and 'Maximum Ping Time' columns.
</ul>


<li>Version 1.28
<ul>
<li>Fixed the sorting problem of 'IP Address' and 'Reply IP Address' column.
</ul>

<li>Version 1.27
<ul>
<li>Made another workaround that hopefully will solve the mysterious problem that people report where PingInfoView stop pinging after hours of continuous work.
PingInfoView now check the pinging status, and if the pings stoped from some reason, PingInfoView should start them again.
</ul>

<li>Version 1.26
<ul>
<li>Added command-line options to make a single ping test and save it to html/text/xml/csv file.
<li>Fixed some problems with the xml file.
</ul>

<li>Version 1.25
<ul>
<li>New column: Last Succeed On.
<li>New column: Last Failed On.
<li>The % Failed value now shows the value in accuracy of 0.01% instead of interger values in previous versions.
</ul>

<li>Version 1.20
<ul>
<li>New column: % Failed.
<li>New option: Beep On Failed Pings.
<li>New option: Put Icon On Tray.
</ul>

<li>Version 1.18
<ul>
<li>Fixed bug: The size of addresses list text-box was limited to 32 KB.
</ul>

<li>Version 1.17
<ul>
<li>Added new option: Start pinging immediately without displaying this dialog-box.
</ul>

<li>Version 1.16
<ul>
<li>Added more accelerator keys.
</ul>

<li>Version 1.15
<ul>
<li>Added support for IP Range (For example: 192.168.0.10-192.168.0.20)
<li>Added support for IP-Host Description format. (See below)
<li>Fixed bug: PingInfoView continued to ping even when 'Ping every...' option is unchecked.
</ul>

<li>Version 1.10
<ul>
<li>Added command-line support.
<li>Added 'Always On Top' option.
<li>Added Drag & Drop support - You can drag a text file containing IP addresses into the main window of PingInfoView.
<li>Added 'Start Pinging' option. (Start again after you previously used the Stop option)
<li>Added 'Reset' option.
<li>Added 'Load Addresses From File' option.
</ul>

<li>Version 1.06
<ul>
<li>Fixed sorting problems in some columns.
</ul>

<li>Version 1.05
<ul>
<li>Automatically save the hosts list and load it in the next time that you use PingInfoView utility.
<li>Fixed the IP address sorting.
<li>The 'Ping Options' dialog-box is now resizable.
</ul>
 
<li>Version 1.01 - Fixed bug: The main window lost the focus when the user switched to another application and then returned back to PingInfoView.
<li>Version 1.00 - First release.
</ul>



<p>
<h4 class="utilsubject">Using PingInfoView</h4>
PingInfoView doesn't require any installation process or additional dll files.
In order to start using it, simply run the executable file (PingInfoView.exe), type the host names and IP addresses that
you want to ping, and click the 'Ok' button to start pinging.

<p>
<h4 class="utilsubject">Known Issues</h4>
<ul>

<li>If you ping to a lot of hosts concurrently, PingInfoView may return a failed result to some of the hosts, even if the hosts are ok. In order to solve this issue, go to the 'Advanced Options' and 
decrease the maximum number of concurrent pings.
</ul>


<p>
<h4 class="utilsubject">Use IP-Host Description format</h4>
When this option is selected, you should specify the IP addresses list in the following format:
<pre class="srcbg">
192.168.1.10 Main Server
192.168.1.11 Host 01
192.168.1.12 Host 02
#192.168.1.14 Host 03
</pre>
The description of each IP address is automatically added to the description column.
If you add '#' character in the beginning of the line, PingInfoView will ignore it.

<p>
<h4 class="utilsubject">Command-Line Options</h4>


<table border="1" cellpadding="5" bordercolor="#000000">

<tr><td nowrap>
/stext &lt;Filename&gt;
<td>Make a single ping test and save the result into a simple text file.

<tr><td nowrap>
/stab &lt;Filename&gt;
<td>Make a single ping test and save the result into a tab-delimited text file.

<tr><td nowrap>
/scomma &lt;Filename&gt;
<td>Make a single ping test and save the result into a comma-delimited text file (csv).


<tr><td nowrap>
/stabular &lt;Filename&gt;
<td>Make a single ping test and save the result into a tabular text file.

<tr><td nowrap>
/shtml &lt;Filename&gt;
<td>Make a single ping test and save the result into HTML file (Horizontal).

<tr><td nowrap>
/sverhtml &lt;Filename&gt;
<td>Make a single ping test and save the result into HTML file (Vertical).

<tr><td nowrap>
/sxml &lt;Filename&gt;
<td>Make a single ping test and save the result into XML file.



<tr><td nowrap>
/loadfile &lt;filename&gt;
<td>
Load the specified filename that contains host names and/or IP addresses.
You can use this command-line option in conjunction with the above save commands (/scomm, /stab, and so on)

<tr><td nowrap>
/PingTimeout &lt;value&gt;
<td>
Specifies the ping timeout value, in ms.

<tr><td nowrap>
/PingEvery &lt;0 | 1&gt;
<td>
Specifies whether to ping every xx seconds (0 - No, 1 - Yes)

<tr><td nowrap>
/PingEverySeconds &lt;value&gt;
<td>
Specifies the number of seconds to wait between the pings.

<tr><td nowrap>
/IPHostDescFormat &lt;0 | 1&gt;
<td>
Specifies whether to use the IP-Host Description mode (0 - No, 1 - Yes)

</table>




<p>
<h4 class="utilsubject">Translating PingInfoView to other languages</h4>
In order to translate PingInfoView to other language, follow the instructions below:
<ol>
<li>Run PingInfoView with /savelangfile parameter:
<br>
PingInfoView.exe /savelangfile
<br>
A file named PingInfoView_lng.ini will be created in the folder of PingInfoView utility.
<li>Open the created language file in Notepad or in any other text editor. 
<li>Translate all string entries to the desired language.
Optionally, you can also add your name and/or a link to your Web site. 
(TranslatorName and TranslatorURL values) If you add this information, it'll be 
used in the 'About' window. 
 
<li>After you finish the translation, Run PingInfoView, and all translated 
strings will be loaded from the language file.
<br>If you want to run PingInfoView without the translation, simply rename the language file, or move 
it to another folder. 

</ol>




<p>
<h4 class="utilsubject">License</h4>
This utility is released as freeware. 
You are allowed to freely distribute this utility via floppy disk, CD-ROM, 
Internet, or in any other way, as long as you don't charge anything for this.  
If you distribute this utility, you must include all files in
the distribution package, without any modification !

<p>
<h4 class="utilsubject">Disclaimer</h4>
The software is provided &quot;AS IS&quot; without any warranty, either expressed or implied,
including, but not limited to, the implied warranties of merchantability and fitness
for a particular purpose. The author will not be liable for any special, incidental,
consequential or indirect damages due to loss of data or any other reason. 

<p>
<h4 class="utilsubject">Feedback</h4>
If you have any problem, suggestion, comment, or you found a bug in my utility, 
you can send a message to <a href="mailto:nirsofer@yahoo.com">nirsofer@yahoo.com</a>
