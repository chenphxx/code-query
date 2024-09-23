## 开发文档

--- 

本项目是一款基于QT和MySQL开发的数据库查询软件, 包含了作者在开发和日常学习当中可能会用到的各种技术栈知识点 

在搜索框中输入, 查询结果会在下方展示 

**联系作者** 

如果在使用过程中遇到任何问题, 欢迎联系开发者`chenphxx`进行反馈 

```
E-Main: john201950@outlook.com
VX: XieG0110
```

--- 

2024.9.18 

1. C++已经能够正常读写MySQL数据库 

2. QT初步的UI已经设计完成 

3. MySQL数据库初步搭建完成, 有了一些简单的测试用数据 

--- 

V2024.9.19 

第一个可以正常使用的版本开发完成, 可以通过搜索中文以及英文索引来查找信息 

--- 

V2024.9.20 

1. 采用了参数化查询, 防止SQL注入风险 
2. 在选择了新的目标语言并且送出查询后, 将会将上一次的查询结果清空 
3. 新增了保存功能, 点击保存按钮后, 可以将修改后的数据保存至表中 
4. 在输入框输入之后, 按下`Enter`键即可触发搜索 

--- 

V2024.9.23 

1. 修改了当查询结果有多条时只显示最后一条的问题, 在结果中添加了一条水平线以分隔开不同的结果 

2. 增加了对查询失败或没有查询到结果的提示 

3. 增加了当查询结果有多条时点击保存按钮的提示 

4. 更新了软件的字体为`Cascadia Code` 

5. 新增了为数据库添加新的数据的功能, 点击按钮`另存为`来添加新的数据 

--- 


