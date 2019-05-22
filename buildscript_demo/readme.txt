buildscript代码块的作用：
只在当前的脚本中生效
只能使用classpath 加载包的依赖(依赖本地maven库中的包，如果没有会报错)
注意：buildscript区分大小写（错误的拼写：buildScript）