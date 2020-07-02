# Specification

东莞理工学院城市学院校易班学生工作站
技术部部门规范

## [写在前头](#写在前头)

**部门不应永远遵循此规范里要求的开发要求和技术要求等，应当循序渐进，按照部门和技术的发展，不断进行修改完善，**


## [开发规范](#开发规范)

1. 部门项目源码仓库，可建立于个人账户或部门账户
- 建立于个人账户须给予部门账户参与者权限
- 建立于部门账户可Fork到个人仓库进行开发（符合公司开发方式，较为推荐）
2. 项目Java代码变量命名按照阿里代码规范
- 类名使用 UpperCamelCase 风格
- 方法名、参数名、成员变量、局部变量都统一使用 lowerCamelCase 风格
- 常量命名全部大写，单词间用下划线隔开，不要缩写
3. 项目Python代码按照Google开源项目规范
- 类名采用 CamelCase 风格
- 方法名、参数、变量都使用单词小写命名，采用snake case风格，利用下划线分隔单词，特殊方法变量以下划线为前缀
- 模块名和包名小写，不使用下划线
- 常量命名全部大写，单词间用下划线隔开，不要缩写
4. 前端代码ID和class总是使用可以反应元素目的和用途的名称，或其他通用的名称
5. 前端项目开发工具推荐采用VSCode，后端开发工具推荐采用JetBrains产品

## [技术要求](#技术要求)

### 前端开发人员

- 大一上学期结束时，应当掌握HTML5和CSS3
- 大一下学期结束时，应当掌握JavaScript、ES6规范和Vue.js或其它前端框架
- 大二应当掌握Vue-CLI或其它开发快速SPA的技术，可使用UI库和开源的前端解决方案项目进行开发

### Java开发人员

- 大一上学期结束时，应当完成C语言的学习
- 大一下学期结束时，应当掌握Java开发和MySQL
- 大二需要学会使用SpringBoot搭建后端服务，掌握Redis

### Python开发人员

- 大一上学期结束时，应当完成C语言的学习
- 大一下学期结束时，应当掌握Python基础、Python数据处理包以及其它数据处理工具
- 大二需要学会使用Flask搭建后端服务，提供数据处理接口

## [项目文档](#项目文档)

1. 每个项目都必须有README.md文件进行文档说明
2. 项目文档开头必须要有以下内容：
- 仓库创建者
- 项目创建时间
- 主要开发者
- 参与开发者
- 技术选型
