# shell_caozuo
shell_caozuo

shell去掉第五个逗号前的内容
$ awk -F',' '{for(i=6;i<=NF;i++) printf "%s%s", $i, (i==NF?ORS:",")}' file.txt
