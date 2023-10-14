# minigrep
一个简单的命令行构建，由rust构建，用于在文件的指定行中搜索字符串，仅用于学习目的

不区分大小写搜索需加上环境变量:CASE_INSENSITIVE=1

CASE_INSENSITIVE=1 cargo run 要搜索的字符串 文件名.txt > 输出结果.txt
