```bash
##按照时间排序取文件夹内第一个文件
ll -t |head -n 2
ll -t |head -n 2|awk '{print $9}'
ll -t |head -n 2|awk '{print $9}'|tail -1





```
