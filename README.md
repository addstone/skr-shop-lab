# skr-shop-lab
参考 skr-shop 的电商设计手册(manuals)项目进行具体实现的电商项目。

### 简介



本项目是根据 [电商设计手册 | SkrShop](https://github.com/skr-shop/manuals) 内容，进行代码实现。

目前规划为后台管理系统，前台电商系统以及后端代码。

### 技术架构

#### 技术选型

​	后台 

​		java

​			Jdk 1.8

​			spring boot 2.3

​		数据

​			mysql 8.0(兼容5.7)

​	前端

​			vue

### 项目及目录

​	docs	存放项目文档  

​		mysql	存放mysql 相关sql代码  

​	shop-lab 存放 Java后端相关代码  

​		spring-cloud 	spring 微服务相关  

​		shop-lab	电商业务相关  

​	shop-lab-admin-vue 后代系统代码  

​	shop-lab-vue 电商界面代码  



### 功能模块

[功能模块详见](docs/shop-lab/module/FunctionalModule.md)

​		

### 版本规划

​	目前版本以基本功能实现为主。目前阶段可能出现文件路径改变或者功能进行重大更变。



### 代码提交规范

### GIT提交规范

feat：新增功能
fix：bug 修复
docs：文档更新
style：不影响程序逻辑的代码修改(修改空白字符，格式缩进，补全缺失的分号等，没有改变代码逻辑)
refactor：重构代码(既没有新增功能，也没有修复 bug)
perf：性能, 体验优化
test：新增测试用例或是更新现有测试
build：主要目的是修改项目构建系统(例如 glup，webpack，rollup 的配置等)的提交
ci：主要目的是修改项目继续集成流程(例如 Travis，Jenkins，GitLab CI，Circle等)的提交
chore：不属于以上类型的其他类，比如构建流程, 依赖管理
revert：回滚某个更早之前的提交