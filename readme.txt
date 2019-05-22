gradle 学习

com.android.tools.build:gradle:0.5.0 和 com.android.tools.build:gradle:0.5+
固定版本和某版本以上都可以



x utils3 在library module下无法引入必须放在app目录下（什么原因？怀疑资源冲突）

xutils3是aar文件 采用两种方式引入：
1、使用android studio 导入 aar 的方式引用
2、将aar文件复制到libs目录下，再通过配置build.gradle文件引入
compile(name: 'xxx', ext: 'aar')


遍历集合的方法
groovy
http://blog.csdn.net/escaflone/article/details/5508291
any findAll collect等等方法
gradle 遍历方法
all


推荐文章
http://blog.csdn.net/innost/article/details/48228651


Groovy的API文档
http://www.groovy-lang.org/api.html

Gradle的官网文档
https://docs.gradle.org/current/release-notes

https://docs.gradle.org/current/dsl/  <==这个文档很重要

Android定义的DSL参考文档
https://developer.android.com/tools/building/plugin-for-gradle.html下载
已经迁移到github上
https://github.com/google/android-gradle-dsl