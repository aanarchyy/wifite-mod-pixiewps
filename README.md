#Added flags
    -pto <sec>        # configurable timeout for pixiewps attack
    -ponly            # uses only pixiewps and reaver up until M3
    -pnopsk           # do not run retrieved pin through reaver
    -paddto <sec>     # add n seconds to timeout on each hash retrevial
    -update           # now updates to this fork instead of original wifite
#Required tools

    You must install Pixiewps by Wiire (https://github.com/wiire/pixiewps)
      and 
    You must install reaver-wps-fork-t6x by t6x (https://github.com/t6x/reaver-wps-fork-t6x)

#ToDo
    Add option to dynamically spoof connected client
    Add option to loop through forever instead of exiting out when any selected networks fail, not recracking

#May do    
    
    Add mdk3 support
    Add default pin calculations and options

