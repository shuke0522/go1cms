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

## 部署步骤中环境准备以及中文翻译部分由唐宇撰写
##  Deployment steps
###  Environmental preparation
* Operating system: Go1 CMS is built on Frappe, Linux system (such as Ubuntu 20.04 and above) is recommended, Windows system may have compatibility issues, and it is not recommended to use it as a production environment.
* Dependent installation
* Python: Make sure you have Python 3.7 or later installed on your system. You can check the version number by typing python3 --version in the terminal. If it is not installed, you can use the command sudo apt-get install python3 python3-pip on Ubuntu to install it.
* Node.js: Install Node.js 14 and above. On Ubuntu systems, you can add and install the Node.js official source with the following command:
​
* curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -​
* sudo apt-get install -y nodejs​
​
* MariaDB: The Go1 CMS uses MariaDB as the database and installs MariaDB 10.3 and above. On the Ubuntu system, run the sudo apt-get install mariadb-server installation, and after the installation is complete, use the sudo mysql_secure_installation to configure the security and set the password of the root user.
* Redis: Install Redis for caching, in Ubuntu system, run sudo apt-get install redis-server to install, and make sure that the Redis service has been started, you can check the service status through sudo systemctl status redis-server.

## 一、部署步骤​
### （一）环境准备​
* 操作系统：Go1 CMS 基于 Frappe 构建，建议使用 Linux 系统（如 Ubuntu 20.04 及以上版本），Windows 系统可能存在兼容性问题，不推荐作为生产环境使用。​
* 依赖安装​
* Python：确保系统中安装了 Python 3.7 及以上版本。可以通过在终端输入 python3 --version 查看版本号。若未安装，在 Ubuntu 系统中可使用命令 sudo apt-get install python3 python3-pip 进行安装。​
* Node.js：安装 Node.js 14 及以上版本。在 Ubuntu 系统中，可通过以下命令添加 Node.js 官方源并安装：​
​
* curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -​
* sudo apt-get install -y nodejs​
​
* MariaDB：Go1 CMS 使用 MariaDB 作为数据库，安装 MariaDB 10.3 及以上版本。在 Ubuntu 系统中，执sudo apt-get install mariadb-server 安装，安装完成后，通过 sudo mysql_secure_installation 进行安全配置，设置 root 用户密码等。​
* Redis：安装 Redis 用于缓存，在 Ubuntu 系统中，运行 sudo apt-get install redis-server 进行安装，并确保 Redis 服务已启动，可通过 sudo systemctl status redis-server 查看服务状态。



