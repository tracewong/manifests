# manifests
使用repo跟踪感兴趣的开源库，方便下载各种开源的仓库

#下载repo
## 1.1.从github上下载repo
$ curl https://raw.githubusercontent.com/tinalinux/repo/stable/repo > ~/bin/repo
## 1.2.将repo添加到环境变量
$ chmod +x ~/bin/repo
$ export PATH=~/bin:$PATH

# Auzre-rtos threadx 下载方法
$ repo init -u https://github.com/tracewong/manifests -b master -m azure-rtos.xml
$ repo sync
$ repo start master --all
