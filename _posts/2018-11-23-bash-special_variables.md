---
layout: post
title: Bash Special Variables
---
|Variable   |Description   |
|---|---|
| $0  |The filename of the current script   |
| $!  | The process ID of the last background command  |
| $_  | The last argument of the previous command  |
| $?  |  The exit status of the last command executed |  
| $#  | Number of command-line arguments
| $@  | All arguments on command line($1 $2...) one by one, starting from the first argument
| $*  | All arguments on command line as one string ("$1 $2...")
