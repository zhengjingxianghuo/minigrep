# minigrep🦀
*一个简单的命令行程序，由rust构建，用于在文件中搜索字符串，并把结果存放在任意指定的输出文件中(不加任何参数，则把错误信息输出到输出文件里，格式推荐使用txt，或任意纯文本格式)，仅用于学习目的*   

*不区分大小写搜索需加上环境变量:**CASE_INSENSITIVE=1** ，

## 用法  
***CASE_INSENSITIVE=1 cargo run 要搜索的字符串 文件名.txt > 输出结果.txt***   

默认结构目录如下:
minigrep/  
├── Cargo.lock  
├── Cargo.toml  
├── src\n  
│   ├── lib.rs  
│   └── main.rs  
└── test.txt  
