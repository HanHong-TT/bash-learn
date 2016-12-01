[Totorial Website](http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html#toc5)

# Redirect Output

* testscript.sh > log.log # Clear log file and redirect output to the log file

* testscript.sh >> log.log # Append new output to the log file

* 2>&1 # redirect stderr to stdout

* ls > mydirlist 2>&1 # directs both stdout and stderr to the file mydirlist

* ls 2>&1 > mydirlist # directs only stdout, and not stderr, to file mydirlist, because stderr was made a copy of stdout before stdout was redirected to mydirlist.

NOTE: It's the way that the shell works scanning from left to right. So read the second one as saying "copy stderr onto stdout" before it says "send stdout to mydirlist". Then read the first one as saying "send stdout to the file mydirlist" before it says "duplicate stderr onto that stdout I've set up". I know. It's totally not intuitive!