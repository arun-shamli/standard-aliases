Commands
========

###  Less 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**le, less1** | <code>less --RAW-CONT</code>[**`...`**](../standard_functions#L37-L39) | Display text or file in pager.
**m** | <code>___printOrDispl</code>[**`...`**](../standard_functions#L92-L94) | Print or display text or file in pager.

###  Ls 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**l** | <code>___displayOutpu</code>[**`...`**](../standard_functions#L194-L197) | List or display directory contents in pager using short listing format.
**ll** | <code>___displayOutpu</code>[**`...`**](../standard_functions#L204-L207) | List or display directory contents in pager using long listing format.
**la** | <code>__listOrDisplay</code>[**`...`**](../standard_functions#L209-L212) | List or display all directory contents in pager using short listing format.
**lla** | <code>__listOrDisplay</code>[**`...`**](../standard_functions#L219-L222) | List or display all directory contents in pager using long listing format.
**lt** | <code>__listOrDisplay</code>[**`...`**](../standard_functions#L224-L227) | List or display directory contents in pager ordered by date using short listing format.
**llt** | <code>__listOrDisplay</code>[**`...`**](../standard_functions#L234-L237) | List or display directory contents in pager ordered by date using long listing format.
**dl** | <code>__listOrDisplay</code>[**`...`**](../standard_functions#L239-L242) | List or display matching directories in pager using short listing format.
**dll** | <code>__listOrDisplay</code>[**`...`**](../standard_functions#L249-L252) | List or display matching directories in pager using long listing format.
**l1** | <code>__listOrDisplay</code>[**`...`**](../standard_functions#L254-L257) | List or display in pager one directory item per line using short listing format.
**la1** | <code>__listOrDisplay</code>[**`...`**](../standard_functions#L259-L262) | List or display in pager one directory item per line including hidden files using short listing format.
**first** | <code>ls "$@" &#124; head </code>[**`...`**](../standard_functions#L265-L267) | List first file in directory.
**nf, newest** | <code>ls -pt "$@" &#124; g</code>[**`...`**](../standard_functions#L270-L272) | Print name of newest file in directory.
**rf, randomFile** | <code>ls -pt &#124; grep -</code>[**`...`**](../standard_functions#L275-L277) | Print name of random file in directory.
**findd, directories** | <code>find . -name .g</code>[**`...`**](../standard_functions#L282-L284) | Print all subdirectories.
**extensions** | <code>find . -type f </code>[**`...`**](../standard_functions#L287-L292) | Print all file extensions.

###  Tree 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**t, tree1** | <code>tree -C -I .git</code>[**`...`**](../standard_functions#L304-L306) | Print directory structure.
**tt** | <code>clear</code>[**`...`**](../standard_functions#L308-L311) | Clear screen andprint directory structure.

###  Cd 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**.., cd..** | <code>___goUpNumberOf</code>[**`...`**](../standard_functions#L337-L339) | Go up one directory.
**...** | <code>___goUpNumberOf</code>[**`...`**](../standard_functions#L341-L343) | Go up two directories.
**....** | <code>___goUpNumberOf</code>[**`...`**](../standard_functions#L345-L347) | Go up three directories.
**.....** | <code>___goUpNumberOf</code>[**`...`**](../standard_functions#L349-L351) | Go up four directories.
**......** | <code>___goUpNumberOf</code>[**`...`**](../standard_functions#L353-L355) | Go up five directories.
**.......** | <code>___goUpNumberOf</code>[**`...`**](../standard_functions#L357-L359) | Go up six directories.
**cdiso** | <code>sudo mkdir /med</code>[**`...`**](../standard_functions#L362-L366) | Mount iso and cd into.

###  Files 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**d** | <code>ls -l &#124; grep "^</code>[**`...`**](../standard_functions#L374-L376) | List directories only.
**f** | <code>ls -al &#124;grep "^</code>[**`...`**](../standard_functions#L379-L381) | List files only.
**h** | <code>__listFilesOnly</code>[**`...`**](../standard_functions#L384-L386) | List hidden files only.
**# cp** | <code>cp --interactiv</code>[**`...`**](../standard_functions#L390-L392) | Copy files safely.
**# mv** | <code>mv --interactiv</code>[**`...`**](../standard_functions#L396-L398) | Move files safely.
**# rm** | <code>rm --interactiv</code>[**`...`**](../standard_functions#L403-L405) | Delete files safely.
**cpdir** | <code>cp --interactiv</code>[**`...`**](../standard_functions#L409-L411) | Copy directories safely.
**mvdir** | <code>mv --interactiv</code>[**`...`**](../standard_functions#L415-L417) | Move directories safely.
**rmdir** | <code>rm --interactiv</code>[**`...`**](../standard_functions#L422-L424) | Delete directories safely.
**mk, md, mkdir1** | <code>mkdir --parents</code>[**`...`**](../standard_functions#L428-L431) | Create directory and descend into.
**bk, backup** | <code>sudo cp --prese</code>[**`...`**](../standard_functions#L435-L437) | Backup file.
**switch** | <code>tempFile=$(mkte</code>[**`...`**](../standard_functions#L440-L445) | Switch contents of files.

###  Pwd 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------

###  Echo 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**e** | <code>echo "$@"</code> | Print text.
**ee** | <code>echo -e "$@"</code> | Print text interpreting backslashed characters.
**en** | <code>echo -n "$@"</code> | Print text without trailing newline.

###  Run In Background 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**rb, runInBackground** | <code>nohup "$@" &>/d</code>[**`...`**](../standard_functions#L489-L491) | Run command in background.

###  Basics 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**ef, editFunctions** | <code>"$EDITOR" ~/.st</code>[**`...`**](../standard_functions#L500-L502) | Edit standard aliases.
**er, editUsersRc** | <code>"$EDITOR" ~/.st</code>[**`...`**](../standard_functions#L504-L506) | Edit users standard rc.
**er1, editProjectsRc** | <code>projectLocation</code>[**`...`**](../standard_functions#L508-L511) | Edit projects standard rc.
**ba** | <code>bash "$@"</code> | Start new bash shell.
**ty, type1** | <code># Checks if com</code>[**`...`**](../standard_functions#L550-L570) | Print command type or definition.
**c** | <code>cat "$@"</code> | Print file contents.
**?** | <code>echo $?</code> | Print exit code of last command.
**cl, clr ,cls** | <code>clear</code> | Clear the screen.
**re** | <code>reset "$@"</code> | Reset the screen.
**q** | <code>exit</code> | Exit bash shell.
**o, openFile** | <code>__runCommandInB</code>[**`...`**](../standard_functions#L600-L602) | Open file with default app.
**te, terminal** | <code>x-terminal-emul</code>[**`...`**](../standard_functions#L605-L607) | Open new terminal with same working directory.
**to** | <code>touch  "$@"</code> | Update files timestamp or create new one.
**da** | <code>date  "$@"</code> | Print date and time.
**ma, make1** | <code>make  "$@" 2>&1</code>[**`...`**](../standard_functions#L625-L629) | Run make with pager.
**na, explorer** | <code>__runCommandInB</code>[**`...`**](../standard_functions#L637-L639) | Start file explorer in background in working directory.
**diff1** | <code>colordiff  "$@"</code>[**`...`**](../standard_functions#L643-L645) | Compare files line by line in color.
**me, makeExecutable** | <code>if [[ ! -f "$1"</code>[**`...`**](../standard_functions#L650-L698) | Make file executable or create new bash or python script.

###  History 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**history1** | <code>if [ "$#" -eq 0</code>[**`...`**](../standard_functions#L707-L718) | Search command history for pattern.

###  Text Editors 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**v , vi** | <code>vim -p "$@"</code> | Edit file with vim.
**vv** | <code>view -p "$@"</code> | View file in vim.
**n, nano1** | <code>nano --undo --a</code>[**`...`**](../standard_functions#L747-L749) | Edit file with nano.
**nv** | <code>nano --view --u</code>[**`...`**](../standard_functions#L761-L763) | View file in nano.
**g, gedit1** | <code>__runCommandInB</code>[**`...`**](../standard_functions#L767-L769) | Edit file with gedit.
**sub** | <code>__runCommandInB</code>[**`...`**](../standard_functions#L772-L774) | Edit file with sublime text.

###  Sudo 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**root** | <code>#!/bin/bash</code> | Switch to root.
**s** | <code>sudo "$@"</code> | Execute command as super user.
**sudoCp** | <code>sudo cp --inter</code>[**`...`**](../standard_functions#L799-L801) | Copy files safely as super user.
**smv** | <code>sudo mv --inter</code>[**`...`**](../standard_functions#L805-L807) | Move files safely as super user.
**srm** | <code>sudo rm --inter</code>[**`...`**](../standard_functions#L812-L814) | Delete files safely as super user.
**scpdir** | <code>sudo cp --inter</code>[**`...`**](../standard_functions#L818-L820) | Copy directories safely as super user.
**smvdir** | <code>sudo mv --inter</code>[**`...`**](../standard_functions#L824-L826) | Move directories safely as super user.
**srmdir** | <code>sudo rm --inter</code>[**`...`**](../standard_functions#L831-L833) | Delete directories safely as super user.
**sm, sle** | <code>sudo less --RAW</code>[**`...`**](../standard_functions#L841-L843) | Display text or file in pager as super user.
**sv, se** | <code>sudoedit "$@"</code> | Edit file with vim as super user.
**svv** | <code>sudo view -p "$</code>[**`...`**](../standard_functions#L853-L855) | View file in vim as super user.
**sn** | <code>sudo nano --und</code>[**`...`**](../standard_functions#L867-L869) | Edit file with nano as super user.
**sg** | <code>sudo gedit  "$@</code>[**`...`**](../standard_functions#L873-L875) | Edit file with gedit as super user.

###  Procesess 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**taskManager, ht** | <code>htop  "$@"</code> | Run terminal task manager.
**ps1** | <code>ps  "$@" &#124; __pr</code>[**`...`**](../standard_functions#L962-L964) | Print users processes.
**psa, pse, processes** | <code>ps -e  "$@" &#124; _</code>[**`...`**](../standard_functions#L968-L970) | Print all processes.
**pgrep1** | <code>pgrep --list-na</code>[**`...`**](../standard_functions#L975-L977) | Find processes with part of name.
**kill1** | <code>kill -9 "$@"</code> | Kill process with kill signal.
**st, strace1, trace** | <code>strace -s\ 2000</code>[**`...`**](../standard_functions#L994-L997) | Trace system calls.

###  Text 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**he** | <code>head "$@"</code> | Print first ten lines.
**he1, firstLine** | <code>head -n1 "$@"</code> | Print first line.
**ta** | <code>tail "$@"</code> | Print last ten lines.
**ta1, lastLine** | <code>tail -n1 "$@"</code> | Print last line.
**wcl, countLines** | <code>wc -l "$@"</code> | Count lines.
**wcw, countWords** | <code>wc -w "$@"</code> | Count words.
**trd** | <code>tr --delete "$@</code>[**`...`**](../standard_functions#L1036-L1038) | Delete characters.
**loc, linesOfCode** | <code>rootDir="$PWD"</code>[**`...`**](../standard_functions#L1043-L1059) | Count lines in files with extension in working and subdirectories.

###  Tables 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**table** | <code>column -t -s "$</code>[**`...`**](../standard_functions#L1068-L1070) | Line up columns.
**cut1, keepColumns** | <code>cut --delimiter</code>[**`...`**](../standard_functions#L1076-L1078) | Keep columns.
**sort1** | <code>sort --field-se</code>[**`...`**](../standard_functions#L1084-L1086) | Sort lines by column.

###  Search 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**grep1** | <code>grep --color=au</code>[**`...`**](../standard_functions#L1099-L1101) | Print lines containing pattern.
**gr** | <code>__printLinesCon</code>[**`...`**](../standard_functions#L1105-L1108) | Print or display with pager lines containing pattern.
**grr** | <code>__printLinesCon</code>[**`...`**](../standard_functions#L1112-L1118) | Print or display with pager numbered lines containing pattern in working and subdirectories.
**lo, locate1** | <code>locate  "$1" \</code>[**`...`**](../standard_functions#L1123-L1127) | Locate files on filesystem containing pattern in their names.
**find1** | <code>find . -not -iw</code>[**`...`**](../standard_functions#L1134-L1138) | Locate files containing pattern in their names in working and sub directories.

###  Archives 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**extract** | <code>if [ -z "$1" ];</code>[**`...`**](../standard_functions#L1147-L1180) | Extract archive of any type.

###  Terminal Multiplexer 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**tm, mu** | <code>tmux  "$@"</code> | Run terminal multiplexer.
**tma, mua** | <code>tmux attach "$@</code>[**`...`**](../standard_functions#L1194-L1196) | Run terminal multiplexer and attach to last session.
**tml, mul** | <code>tmux ls</code> | List terminal multiplexers sessions.

###  System Information 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**df1** | <code>df -h &#124; grep "s</code>[**`...`**](../standard_functions#L1209-L1211) | Print available disk space in simplified form.
**du1** | <code>du --summarize </code>[**`...`**](../standard_functions#L1215-L1217) | Print disk space occupied by file or folder.
**fr, free1** | <code>echo "all:  "$(</code>[**`...`**](../standard_functions#L1220-L1227) | Print all and free memory space in megabytes.
**temp, temperature** | <code>acpi -t</code> | Print temperature of cpu.
**batt, battery** | <code>acpi</code> | Print battery status.
**uname1, kernelVersion** | <code>uname --all</code> | Print operating system information.
**pci, lspci1** | <code>lspci -v "$@" &#124;</code>[**`...`**](../standard_functions#L1247-L1249) | Print info about pci devices.

###  Power 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**reboot** | <code>sudo reboot</code> | Restart computer.
**poweroff** | <code>sudo poweroff</code> | Shut down computer.
**hib** | <code>sudo pm-hiberna</code>[**`...`**](../standard_functions#L1267-L1269) | Hibernate computer.
**sus** | <code>sudo pm-suspend</code>[**`...`**](../standard_functions#L1272-L1274) | Suspend computer.

###  Keyboard 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**uskeys** | <code>setxkbmap -layo</code>[**`...`**](../standard_functions#L1282-L1284) | Switch to american keyboard layout.
**keycode** | <code>xev "$@"</code> | Monitor keycodes of pressed keys.
**norepeat** | <code>xset -r</code> | Turn off key repeat.
**repeat** | <code>xset r</code> | Turn on key repeat.

###  Misc 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**blue** | <code>echo -en "\e]PC</code>[**`...`**](../standard_functions#L1308-L1310) | Change hue of color blue in linux terminal.
**path** | <code>echo -e ${PATH/</code>[**`...`**](../standard_functions#L1313-L1315) | List directories contained in path variable.
**libpath** | <code>echo -e  ${LD_L</code>[**`...`**](../standard_functions#L1318-L1320) | List directories contained in libpath variable.
**bc1** | <code>gcalccmd "$@"</code> | Run terminal calculator that supports decimal numbers.
**hd1** | <code>hd  "$@" &#124; __pr</code>[**`...`**](../standard_functions#L1330-L1332) | Print hexadecimal representation of file or stream.
**profile** | <code>source /etc/pro</code>[**`...`**](../standard_functions#L1335-L1337) | Run profile script.
**vimode** | <code>set -o vi</code> | Change bash line editing to vi mode.
**emacsmode** | <code>set -o emacs</code> | Change bash line editing to emacs mode.
**ssd** | <code>sudo fstrim -v </code>[**`...`**](../standard_functions#L1350-L1352) | Trim ssd.
**typingTutor** | <code>gtypist "$@"</code> | Start typing tutor.
**extension** | <code>curl --silent f</code>[**`...`**](../standard_functions#L1360-L1365) | Describe file extension.

###  Package Management 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**ch, canhaz** | <code>if [[ "$__stand</code>[**`...`**](../standard_functions#L1373-L1379) | Install package.
**update** | <code>sudo apt-get up</code>[**`...`**](../standard_functions#L1382-L1384) | Update information about available packages.
**upgrade** | <code>sudo apt-get up</code>[**`...`**](../standard_functions#L1387-L1389) | Upgrade all packages.
**dist-upgrade** | <code>sudo apt-get di</code>[**`...`**](../standard_functions#L1394-L1396) | Upgrade all packages intelligently.
**remove** | <code>sudo apt-get re</code>[**`...`**](../standard_functions#L1400-L1402) | Remove package and all unneeded packages.
**purge** | <code>sudo apt-get pu</code>[**`...`**](../standard_functions#L1407-L1409) | Remove package and all unneeded packages together with configuration files.
**autoremove** | <code>sudo apt-get au</code>[**`...`**](../standard_functions#L1413-L1415) | Remove unneeded packages.
**installed, packages** | <code>cat /var/log/ap</code>[**`...`**](../standard_functions#L1419-L1424) | Print packages that were installed by user.
**allInstalled, allPackages** | <code>dpkg --get-sele</code>[**`...`**](../standard_functions#L1427-L1431) | Print all installed packages.
**depends** | <code>apt-cache show </code>[**`...`**](../standard_functions#L1434-L1440) | Print package dependencies.

###  Package Information 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**pd, describe** | <code>apt-cache show </code>[**`...`**](../standard_functions#L1448-L1450) | Print package description.
**ve, version** | <code># Check if pass</code>[**`...`**](../standard_functions#L1468-L1485) | Print installed and available version of package or command.
**package** | <code>call1=$(sudo wh</code>[**`...`**](../standard_functions#L1515-L1531) | Print package of installed command together with description and location.

###  Package Search 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**findPackage** | <code>apt-cache searc</code>[**`...`**](../standard_functions#L1540-L1543) | Find available packages with part of name or description.
**ap, apropos1, findCommand** | <code>apropos "$@" \</code>[**`...`**](../standard_functions#L1548-L1551) | Find installed commands with part of name or description.
**apt-file1** | <code>apt-file -x sea</code>[**`...`**](../standard_functions#L1554-L1557) | Find available packages that provide command.
**wi, whatis1** | <code># Checks if it </code>[**`...`**](../standard_functions#L1596-L1620) | Describe package or command or find available packages with part of name or command.

###  Git 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**commit** | <code>git commit -am </code>[**`...`**](../standard_functions#L1629-L1631) | Commit changed and deleted files with message.
**commitm** | <code>git commit -a "</code>[**`...`**](../standard_functions#L1635-L1637) | Commit changed and deleted files and edit message in editor.
**init** | <code>git init "$@"</code> | Initialize repository.
**push** | <code>git push "$@"</code> | Push changes to remote repository.
**pull** | <code>git pull "$@"</code> | Pull changes from remote repository.
**merge** | <code>git merge "$@"</code> | Merge specified branch with current one.
**gc, checkout** | <code>git checkout "$</code>[**`...`**](../standard_functions#L1662-L1664) | Checkout branch or file.
**gb, branch** | <code>git branch "$@"</code>[**`...`**](../standard_functions#L1667-L1669) | List branches or create new one.
**gs** | <code>git -c color.st</code>[**`...`**](../standard_functions#L1672-L1675) | Print short repository status.
**gl** | <code>git log --graph</code>[**`...`**](../standard_functions#L1679-L1681) | Display minimal log of commits.
**gll** | <code>git log --graph</code>[**`...`**](../standard_functions#L1685-L1687) | Display medium log of commits.
**glll** | <code>git log --decor</code>[**`...`**](../standard_functions#L1691-L1693) | Display log of commits.
**gu** | <code>git remote upda</code>[**`...`**](../standard_functions#L1697-L1700) | Update information about remote repository and print status.
**gd** | <code>git diff "$@"</code> | Display changes between commits.
**ga** | <code>git add "$@"</code> | Add files to repository.
**gm** | <code>git mv "$@"</code> | Move repositories files.
**gls, lsgit** | <code>git ls-files "$</code>[**`...`**](../standard_functions#L1721-L1723) | List files that are in repository.

###  Github 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**clone** | <code>git clone git@g</code>[**`...`**](../standard_functions#L1732-L1734) | Clone github project.
**origin** | <code>git remote add </code>[**`...`**](../standard_functions#L1738-L1742) | Set github project as remote repository.
**cloneAll** | <code>if [[ -z "$1" ]</code>[**`...`**](../standard_functions#L1745-L1757) | Clone all users github projects.

###  Network 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**ip1** | <code>/sbin/ifconfig </code>[**`...`**](../standard_functions#L1765-L1772) | Print internal ip.
**ip2** | <code>lynx --dump htt</code>[**`...`**](../standard_functions#L1775-L1777) | Print external ip.
**gateway** | <code>route -n \</code>[**`...`**](../standard_functions#L1780-L1785) | Print gateways ip.
**mac** | <code>ifconfig &#124; grep</code>[**`...`**](../standard_functions#L1788-L1790) | Print mac addresses of network devices.
**pa, pingAll** | <code>ping -c 1 -q $(</code>[**`...`**](../standard_functions#L1793-L1797) | Ping gateway and google.
**nmap1** | <code>if [[ $# -eq 0 </code>[**`...`**](../standard_functions#L1801-L1817) | Scan local network.
**ne, network** | <code>localIp=$(ip1)</code>[**`...`**](../standard_functions#L1845-L1876) | Print ssh port status of local devices and ping google.

###  Wireless 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**woff** | <code>sudo rfkill blo</code>[**`...`**](../standard_functions#L1884-L1889) | Block wireless device.
**won** | <code>sudo rfkill unb</code>[**`...`**](../standard_functions#L1892-L1897) | Unblock wireless device.
**wr** | <code>woff</code>[**`...`**](../standard_functions#L1900-L1903) | Reset wireless device.
**up** | <code>sudo ifconfig w</code>[**`...`**](../standard_functions#L1906-L1908) | Activate wireless interface.
**down** | <code>sudo ifconfig w</code>[**`...`**](../standard_functions#L1911-L1913) | Deactivate wireless interface.
**wlan** | <code>sudo iwlist wla</code>[**`...`**](../standard_functions#L1916-L1926) | Print wireless networks in range.

###  Internet 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**i, www, internet** | <code>__runCommandInB</code>[**`...`**](../standard_functions#L1934-L1936) | Start default browser in background.
**fire** | <code>__runCommandInB</code>[**`...`**](../standard_functions#L1939-L1941) | Start firefox in background.
**chrome** | <code>__runCommandInB</code>[**`...`**](../standard_functions#L1946-L1948) | Start chrome in background.
**lynx1** | <code>lynx -accept_al</code>[**`...`**](../standard_functions#L1954-L1956) | Start terminal web browser.

###  Audio 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**mixer** | <code>alsamixer "$@"</code> | Start terminal volume control.
**a** | <code>___setVolumeTo </code>[**`...`**](../standard_functions#L1974-L1976) | Increase volume by six decibels.
**z** | <code>___setVolumeTo </code>[**`...`**](../standard_functions#L1979-L1981) | Decrease volume by six decibels.
**aa** | <code>___setVolumeTo </code>[**`...`**](../standard_functions#L1984-L1986) | Increase volume by two decibels.
**zz** | <code>___setVolumeTo </code>[**`...`**](../standard_functions#L1989-L1991) | Decrease volume by two decibels.

###  Framework 

 _Name_        | _Runs_   | _Description_  
:------------- |:--------:| ----------------
**fu** | <code>"${EDITOR:-nano</code>[**`...`**](../standard_functions#L1999-L2001) | Edit standard functions.
**rc, al** | <code>"${EDITOR:-nano</code>[**`...`**](../standard_functions#L2004-L2006) | Edit standard rc.

