安装
npm install -g less
命令行用法
lessc styles.less
这将输出编译之后的 CSS 代码到 stdout，你可以将输出重定向到一个文件：

$ lessc styles.less > styles.css
若要输出压缩过的 CSS，只需添加 -x 选项。如果希望获得更好的压缩效果，还可以通过 --clean-css 选项启用 Clean CSS 进行压缩。

执行 lessc 且不带任何参数，就会在命令行上输出所有可用选项的列表。