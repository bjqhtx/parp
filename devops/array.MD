http://www.jb51.net/article/52382.htm



loglist=(`cat /usr/local/mis/etc/catalog.conf |grep ^log |awk '{print $3}'`) ; echo ${loglist[0]}

#SHELL
declare -a   index : 0-
declare -A   
