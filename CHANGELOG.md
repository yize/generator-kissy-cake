## v0.3.5
- 升级界面

## v0.3.4
- 升级界面

## v0.3.3
- 统一和优化了log输出
- 添加了help命令
- 修改SASS初始化文件中的注释为英文，避免因为中文出现编译出错的问题
- 简化widget的初始化文件
- 添加对于新建page或者widget用户输入中包含空格的处理
- 针对迁移脚本添加文件编码转化功能
- 添加.npmignore，避免test被打包
- 更新gruntfile-helper到0.0.9，修复自动更新的功能

## v0.3.2

更新UI，支持最新的目录结构和Gruntfile

## v0.3.1

更新abc-gruntfile-helper到0.0.8，修正自动检查更新的问题。

## v0.3.0

1、去掉了pages目录中的原码版本目录
2、修正了对应的migrate
3、强制设定abc-gruntfile-helper的版本
4、优化了package-config.js文件

## v0.2.0

1、优化css_combo的配置
2、优化common目录，打包层级为任意
3、去掉了uglify的输出banner，压缩目标为任意层级
4、修改cssmin压缩层级为任意层级
5、更新grunt-css-combo依赖到0.2.2
6、更新abc-gruntfile-helper依赖到0.0.4
7、修正less的paths设置
8、暂时先去掉对于页面版本的版本号格式限制
9、添加持续集成
10、添加common的watch功能
