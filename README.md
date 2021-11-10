# GUI文件名批处理软件  
file rename batch GUI   
   
可用正则进行文件名替换，同时可以选择预览需要替换的前三个文件   
you can use re mode to replace the part you want to modify.   
You can also preview the first three files to be replaced.
  
## 正则模式中：   
replace中可以使用“`$+数字`”来保留find中括号内的内容     
re mode:   
you can use `$+num` to get what you want to keep in the "replace" part  
   
如 `(.+?)(\d)`，可以用`$0 $1`分别提取第一个括号内和第二个括号内的内容进行保留  
for example  
`(.+?)(\d)` You can use `$0 $1` to extract the contents of the first and second parentheses respectively   
  
## 快捷键(short cuts)  
Ctrl+Alt+Enter 替换(rename)  
Ctrl+Enter 预览(preview)   
Ctrl+L 清空(clear)
   
## 最后  
欢迎大家在issues中向我提交bug和建议，感谢~  
Welcome to submit bugs and suggestions to me in issues, thanks ~   
   
   
### [Releases+](https://github.com/Dr-WongDJ/file-rename-GUI/releases)
