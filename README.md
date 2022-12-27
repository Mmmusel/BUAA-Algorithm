## step1

安装`texlive`

## step2

1. 写好tex文件后，打开`tlaunch.exe`，例如我的路径在：

   `D:\SOFTWARE\texlive\2021\bin\win32\tlaunch.exe`

2. 正确打开打开`tlaunch.exe`后，可以在页面打开`TeX Live Command Prompt`。

   tex命令行的默认路径是c盘的文档。

3. 如果tex在c盘文档，直接使用以下命令编译即可，或者cd到tex所在目录进行如下命令编译：

   `xelatex -shell-escape -8bit   filename.tex`

4. 每次编译之前，记得把生成的pdf关闭