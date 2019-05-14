```bash
##按照时间排序取文件夹内第一个文件
ll -t |head -n 2
ll -t |head -n 2|awk '{print $9}'
ll -t |head -n 2|awk '{print $9}'|tail -1
#tail -f输出最新日志
ll -t |head -n 2|awk '{print $9}'|xargs tail -f




```
