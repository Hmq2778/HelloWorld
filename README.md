# HelloWorld Android项目
软件系统开发实验作业

## 一、实验目的
1. 掌握Android Studio开发环境的基本使用，创建Android HelloWorld项目。
2. 理解Android项目目录结构，认识app模块、Gradle配置文件作用。
3. 学习使用Git进行版本控制，掌握代码提交、推送至GitHub远程仓库的操作。

## 二、实验环境
- 操作系统：Windows
- 开发工具：Android Studio
- 版本管理工具：Git
- 远程代码仓库：GitHub

## 三、项目功能
基础Android HelloWorld程序，运行后在手机/模拟器屏幕上展示文字“Hello World!”。

## 四、项目目录说明
HelloWorld3
├── app                 # 应用主模块，存放源代码、布局、资源文件
│   └── src             # java 代码与 xml 布局资源
├── gradle              # Gradle 包装器，管理构建工具版本
├── build.gradle        # 项目根构建配置
├── settings.gradle     # 项目模块设置
├── gradle.properties   # Gradle 全局属性
└── .gitignore          # Git 忽略文件，不提交缓存、本地配置文件

## 五、Git操作步骤
1. 在Android Studio项目目录初始化Git仓库
2. 将项目代码添加到暂存区：`git add .`
3. 本地提交代码：`git commit -m "第一次提交：HelloWorld安卓实验代码"`
4. 绑定GitHub远程仓库：`git remote add origin https://github.com/Hmq2778/HelloWorld.git`
5. 拉取远程仓库文件，处理.gitignore合并冲突
6. 再次提交冲突修改，推送代码到GitHub：`git push -u origin main`

## 六、实验总结
本次实验完成Android基础项目搭建，熟悉Android项目结构。使用Git完成本地代码版本管理，解决网络与文件合并冲突问题，成功将项目源码推送到GitHub远程仓库，掌握代码托管基本流程。
