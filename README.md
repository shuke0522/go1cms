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

## 部署步骤中环境准备以及中文翻译由许治贤撰写
## (I) Deployment Steps
### (II) Installation of Frappe and Go1 CMS

* Create User and Directory: For security and standardization, create a dedicated user to run Frappe and Go1 CMS. Enter `sudo useradd -m frappe` in the terminal to create the user, then switch to that user using `sudo su - frappe`. Next, create a project directory, such as `mkdir frappe-bench && cd frappe-bench`.

* Install Bench: Bench is a command-line tool for managing Frappe applications. Install it using `pip3 install bench`. After installation, initialize Bench by executing `bench init --frappe-branch version-14` (this example uses Frappe version 14; you may adjust according to your actual needs).

* Install Go1 CMS: After entering the bench directory, execute `bench get-app go1_cms https://github.com/xzx719/go1cms.git` (replace with the actual repository address) to download the Go1 CMS application, then install the application by executing `bench install-app go1_cms`.


## (一)部署步骤
### （二）安装 Frappe 和 Go1 CMS​
* 创建用户和目录：为了安全和规范，创建一个专门的用户用于运行 Frappe 和 Go1 CMS。在终端输入 sudo useradd -m frappe 创建用户，然后切换到该用户 sudo su - frappe。接着创建项目目录，如 mkdir frappe-bench && cd frappe-bench。​
* 安装 Bench：Bench 是用于管理 Frappe 应用的命令行工具。使用 pip3 install bench 进行安装，安装完成后，初始化 Bench，执行 bench init --frappe-branch version-14（这里以 Frappe 14 版本为例，可根据实际需求调整）。​
* 安装 Go1 CMS：进入 bench 目录后，执行 bench get-app go1_cms https://github.com/[Go1 CMS 仓库地址]（需替换为实际仓库地址）下载 Go1 CMS 应用，然后执行 bench install-app go1_cms 安装应用。​