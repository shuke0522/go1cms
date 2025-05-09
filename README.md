## Go1 CMS 

Go1 CMS - Its a Advanced Content Management System built on top of Frappe with Advanced Page builder. Lead your business towards the future of website development and content-editing without any developer support.

This advanced open source app encourages both editors and designers to create websites with zero creative limitations and zero coding knowledge.

#### CREATING WEBSITES INTO GROWTH ENGINES
* Get a quick blueprint of Go1 CMS page builder: Experience our interactive design tool

* Powerful code-free website builder built using Frappe, Ionic, and Angular technologies.

* Advanced, customizable Page Builder Interface with existing CMS Market standards.

* Pre-defined, multiple beautiful Templates to build or re-use section and component slices.

* Easy drag-and-drop like positioning of UI block elements forming unique page layouts.

* Form, blog, content segmentation and header footer with heaps of detailed doc types.

* Follow the latest trends to sparkle creativity with flexible font styles and color elements.

* Create and assemble compelling contents for engaging pages.

* Easy-to-manage and well-optimized SEO parameters.

* Custom plugin options and other marketing integrations available.

Go1 CMS is proudly part of the Frappe family, born to support many Frappe Community members, developers, Enterprises with our highly versatile builder platform, giving creative wings to fly globally online.

#### GO1 CMS Screens
![image](https://user-images.githubusercontent.com/54178464/191701378-7285350b-dece-4634-ac42-d0cb772eed1b.png)

* Page Builder

* Page Template

* Section Templates

* Page Sections

* Header Templates

* Footer Templates

master

## 以下介绍补全以及介绍翻译由莫汶颖撰写
## Introduce completions Masters Content Sections Header & Footer Section Design Settings
#### Masters 
* Section Groups

* Section Templates

* Menus

* Fonts

* FAQ Category

* Color Palette

* Background Gradient

* Background Pattern

* Background Mask

#### Content
* Sliders

* Services / Solutions

* Blogs

* Career

* Contact Enquiries

* Testimonials

* FAQs

* Gallery

#### Sections
* Section Template

* Section Template Group

* Section Template Layout

* Section Component

* Section Component Group

* Section Dividers

* Page Section

#### Header & Footer Section
* Header Layout

* Header Component

* Footer Layout

* Footer Component

#### Design
* Background Gradient

* Background Mask

* Background Pattern

* Color Palette

* Detail Page Layout

* Web Page Builder

#### Settings
* CMS Settings

* Web Theme

* Custom Query

## 中文翻译
## Go1 CMS 
* Go1 内容管理系统（CMS）—— 它是一款基于 Frappe 搭建的先进内容管理系统，配备先进的页面构建器。无需开发人员的支持，就能引领您的企业迈向网站开发与内容编辑的未来。

* 这款先进的开源应用程序鼓励编辑人员和设计师在毫无创意限制且无需编码知识的情况下创建网站。
## 将网站打造成增长引擎
* 快速了解 Go1 内容管理系统的页面构建器：体验我们的交互式设计工具。

* 功能强大的无代码网站构建器，采用 Frappe、Ionic 和 Angular 技术构建。

* 先进的、可定制的页面构建器界面，符合现有内容管理系统（CMS）市场的标准。

* 预定义的多个精美模板，可用于构建或重复使用页面部分和组件片段。

* 轻松进行类似拖放的操作，定位用户界面（UI）块元素，形成独特的页面布局。

* 拥有表单、博客、内容分割功能，以及页眉和页脚，还有大量详细的文档类型。

* 紧跟最新潮流，利用灵活的字体样式和色彩元素激发创造力。

* 创建并组合引人入胜的内容，打造吸引人的页面。

* 易于管理且经过良好优化的搜索引擎优化（SEO）参数。

* 提供自定义插件选项以及其他营销集成功能。

* Go1 内容管理系统（CMS）很荣幸成为 Frappe 家族的一员，旨在通过我们功能高度多样的构建平台，为众多 Frappe 社区成员、开发人员和企业提供支持，助力在全球网络上尽情发挥创意。

## Go1 内容管理系统（CMS）界面展示，图片链接
![image](https://user-images.githubusercontent.com/54178464/191701378-7285350b-dece-4634-ac42-d0cb772eed1b.png)
* 页面构建器

* 页面模板

* 部分模板

* 页面分区

* 页眉模板

* 页脚模板

## 主人
* 分区组

* 部分模板

* 菜单

* 字体

* FAQ 类别

* 调色板

* 背景渐变

* 背景图案

* 背景蒙版

## 内容
* 滑 块

* 服务 / 解决方案

* 博客

* 生涯

* 联系查询

* 推荐

* 常见问题

* 画廊

## 部分
* 部分模板

* 部分模板组

* 部分模板布局

* Section Component

* Section Component 组

* 分区分隔线

* 页面部分

## 页眉和页脚部分
* 标题布局

* 标头组件

* 页脚布局

* 页脚组件

## 设计
* 背景渐变

* 背景蒙版

* 背景图案

* 调色板

* 详情页面布局

* 网页生成器

## 设置
* CMS 设置

* 网页主题

* 自定义查询 

 master
 
## 部署步骤中环境准备以及中文翻译部分由唐宇撰写
##  Deployment steps
###  Environmental preparation
* Operating system: Go1 CMS is built on Frappe, Linux system (such as Ubuntu 20.04 and above) is recommended, Windows system may have compatibility issues, and it is not recommended to use it as a production environment.
* Dependent installation
* Python: Make sure you have Python 3.7 or later installed on your system. You can check the version number by typing python3 --version in the terminal. If it is not installed, you can use the command sudo apt-get install python3 python3-pip on Ubuntu to install it.
* Node.js: Install Node.js 14 and above. On Ubuntu systems, you can add and install the Node.js official source with the following command:

* curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
* sudo apt-get install -y nodejs

* MariaDB: The Go1 CMS uses MariaDB as the database and installs MariaDB 10.3 and above. On the Ubuntu system, run the sudo apt-get install mariadb-server installation, and after the installation is complete, use the sudo mysql_secure_installation to configure the security and set the password of the root user.
* Redis: Install Redis for caching, in Ubuntu system, run sudo apt-get install redis-server to install, and make sure that the Redis service has been started, you can check the service status through sudo systemctl status redis-server.

## 中文翻译
## 一、部署步骤
### （一）环境准备
* 操作系统：Go1 CMS 基于 Frappe 构建，建议使用 Linux 系统（如 Ubuntu 20.04 及以上版本），Windows 系统可能存在兼容性问题，不推荐作为生产环境使用。​
* 依赖安装
* Python：确保系统中安装了 Python 3.7 及以上版本。可以通过在终端输入 python3 --version 查看版本号。若未安装，在 Ubuntu 系统中可使用命令 sudo apt-get install python3 python3-pip 进行安装。
* Node.js：安装 Node.js 14 及以上版本。在 Ubuntu 系统中，可通过以下命令添加 Node.js 官方源并安装：

* curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
* sudo apt-get install -y nodejs

* MariaDB：Go1 CMS 使用 MariaDB 作为数据库，安装 MariaDB 10.3 及以上版本。在 Ubuntu 系统中，执sudo apt-get install mariadb-server 安装，安装完成后，通过 sudo mysql_secure_installation 进行安全配置，设置 root 用户密码等。
* Redis：安装 Redis 用于缓存，在 Ubuntu 系统中，运行 sudo apt-get install redis-server 进行安装，并确保 Redis 服务已启动，可通过 sudo systemctl status redis-server 查看服务状态。

 master

## 部署步骤中环境准备以及中文翻译由许治贤撰写
## (I) Deployment Steps
### (II) Installation of Frappe and Go1 CMS

* Create User and Directory: For security and standardization, create a dedicated user to run Frappe and Go1 CMS. Enter `sudo useradd -m frappe` in the terminal to create the user, then switch to that user using `sudo su - frappe`. Next, create a project directory, such as `mkdir frappe-bench && cd frappe-bench`.

* Install Bench: Bench is a command-line tool for managing Frappe applications. Install it using `pip3 install bench`. After installation, initialize Bench by executing `bench init --frappe-branch version-14` (this example uses Frappe version 14; you may adjust according to your actual needs).

* Install Go1 CMS: After entering the bench directory, execute `bench get-app go1_cms https://github.com/xzx719/go1cms.git` (replace with the actual repository address) to download the Go1 CMS application, then install the application by executing `bench install-app go1_cms`.

## (一)部署步骤
### （二）安装 Frappe 和 Go1 CMS
* 创建用户和目录：为了安全和规范，创建一个专门的用户用于运行 Frappe 和 Go1 CMS。在终端输入 sudo useradd -m frappe 创建用户，然后切换到该用户 sudo su - frappe。接着创建项目目录，如 mkdir frappe-bench && cd frappe-bench。
* 安装 Bench：Bench 是用于管理 Frappe 应用的命令行工具。使用 pip3 install bench 进行安装，安装完成后，初始化 Bench，执行 bench init --frappe-branch version-14（这里以 Frappe 14 版本为例，可根据实际需求调整）。
* 安装 Go1 CMS：进入 bench 目录后，执行 bench get-app go1_cms https://github.com/[Go1 CMS 仓库地址]（需替换为实际仓库地址）下载 Go1 CMS 应用，然后执行 bench install-app go1_cms 安装应用。

master

## 一、部署步骤 （三）配置和启动由韩民丰撰写
### Deployment Steps
### Configuration and Startup
* Configure the site: Execute "bench new-site [site name]" to create a new site, such as "bench new-site mysite". After the creation is completed, edit the site configuration file sites/mysite/site_config.json to configure information such as database connections and mail servers. 
* start the service: Under the bench directory, execute bench start to start the Frappe and Go1 CMS services. After the service is started, you can enter the Go1 CMS login page by using a browser to access the server IP address http://[:8000 (default port 8000, use the corresponding port if you have changed). 

## 中文版
### 一、部署步骤
### （三）配置和启动
* 配置站点：执行 bench new-site [站点名称] 创建新站点，例如 bench new-site mysite。创建完成后，编辑站点配置文件 sites/mysite/site_config.json，配置数据库连接、邮件服务器等信息。
* 启动服务：在 bench 目录下，执行 bench start 启动 Frappe 和 Go1 CMS 服务。服务启动后，可通过浏览器访问 http://[服务器 IP 地址]:8000（默认端口为 8000，若有修改则使用对应端口）进入 Go1 CMS 登录页面。

master

# 使用页面构建器的英文版由魏毅杰编写 
##  User Guide
### Using the Page Builder

* Creating a Page

* Navigate to the Page Builder in the left-hand menu of the admin panel.

* Click New Page.

* Enter a page name, select a page template (choose a predefined template if applicable, or select a blank template for custom design), then click Create.

* Adding and Editing Elements

* Drag-and-Drop Elements:

* On the Page Builder interface, the left panel displays an Element Library containing various UI block elements (e.g., text boxes, images, buttons, forms).

* Drag elements from the library to the editing canvas to add them to your page.

* Editing Elements:

* Select any element on the canvas to open its Property Panel on the right.

* Configure:

* Styling: Font styles, colors, sizes, margins, etc.

* Content: Text, image URLs, etc.

* Interactions: Link settings (e.g., button redirects).

* Adjusting Page Layout:

* Reposition elements by dragging them on the canvas.

* Use Grid Layout Tools for precise alignment.

* Add Rows and Columns to divide sections and build complex layouts.

master


