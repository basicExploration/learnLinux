# shell环境变量等相关环境问题。
[目录](./summary.md)
## 本课程主要是有几下知识点：
- printenv 列表出环境变量。
- set 设置shell选项
- export 导出环境变量
- alias 设置命令的别名。
## set printenv

- set 可以显示环境变量和shell变量
- printenv只能显示环境变量。
- printenv 还可以显示具体的命令
~~~bash
printenv USER

thomashuke
~~~
- set显示很多东西例如环境变量，shell变量，shell定义的函数，并且set默认显示的内容按照首字母的顺序进行排序。
- 也可以使用`echo $USER`这意义就不一样了，因为echo是输出流，使用$+具体的环境变量就不属于查询，算是直接输出了，之所以使用$是因为$代表了变量，也就是归于函数变量这个部分了
