# pdf
如何增加pdf

之后每一次增加文件时，只需要在web文件下的PDF文件夹新建想要文件夹，增加新的pdf文件，然后执行下列命令：

git add * #git添加所有文件，准备上传

git commit -m "xxx" #提交文件

git push -u origin master #上传你提交的文件

但上传出错时执行一次 git pull --rebase origin master 命令即可

回到gitee你创建的仓库中，点击服务-giteepages-更新部署即可。

访问网址例如：

http://zjj_szgcjc.gitee.io/pdf/web/viewer.html?file=pdf/shizhan/001-JZ-2021-116/reportqery_getreport.pdf

viewer.html?file=后为web下对应文件的路径


