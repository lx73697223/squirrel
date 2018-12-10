# Introduction

GitBook使用方式参考: https://blog.csdn.net/lu_embedded/article/details/81100704



1. 安装 Node.js、Git、Typora
2. 安装 GitBook: ` $ npm install -g gitbook-cli `
3. 新建目录: ` $ mkdir mybook `
4. 进入目录: ` $ cd mybook `
5. 初始化: ` $ gitbook init `
6. 编辑 `SUMMARY.md`, 定义目录文件结构
7. 再次执行 ` $ gitbook init `. (GitBook 会查找 SUMMARY.md 文件中描述的目录和文件，如果没有则会将其创建)
8. 预览: ` $ gitbook serve (默认端口 4000, 指定端口: $ gitbook serve --port 2333) `
9. 构建: ` $ gitbook build (默认将生成的静态网站输出到 _book 目录, 指定路径: $ gitbook build [书籍路径][输出路径]) `
10. 生成 PDF 格式的电子书: ` $ gitbook pdf ./ ./mybook.pdf `
11. 生成 epub 格式的电子书: ` $ gitbook epub ./ ./mybook.epub `
12. 生成 mobi 格式的电子书: ` $ gitbook mobi ./ ./mybook.mobi `
13. 使用 Git 做版本管理: 在Git账号下创建仓库. 按照 Git 的步骤, 在目录下执行 git 相关命令