gradle 构建语言

基于groovy语言

项目API

标准项目属性：
Name    Type    Default Value
project    Project    Project 实例对象
name    String    项目目录的名称
path    String    项目的绝对路径
description    String    项目描述
projectDir    File    包含构建脚本的目录
build    File    projectDir/build
group    Object    未具体说明
version    Object    未具体说明
ant    AntBuilder    Ant实例对象

脚本API

声明变量
局部变量（local）和扩展属性(extra)
ls

gradle init:自动创建build.gradle 文件(如果有build.gradle 文件就不会进行任何处理)