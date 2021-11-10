# file-rename-GUI
GUI文件名批处理软件

file rename batch GUI

可用正则进行文件名替换，同时可以选择预览需要替换的前三个文件

you can use re mode to replace the part you want to modify


正则模式中：

re mode:

replace中可以使用“$+数字”来保留find中括号内的内容

you can use $+num to get what you want to keep in the "replace" part

如 (.+?)(\d)，可以用$0,$1分别提取第一个括号内和第二个括号内的内容进行保留


for example 

(.+?)(\d) You can use $0 $1 to extract the contents of the first and second parentheses respectively
