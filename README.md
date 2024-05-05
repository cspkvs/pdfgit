如何增加PDF

https://9fb2bb05.pdfgit.pages.dev/web/viewer?file=pdf/shizhan/1BL2020-00064/reportqery_getreport.pdf

https://9fb2bb05.pdfgit.pages.dev/web/viewer?file=pdf/CS2022-00062/document.pdf





# pdf
如何增加pdf

之后每一次增加文件时，只需要在web文件下的PDF文件夹新建想要文件夹，增加新的pdf文件，然后执行下列命令：

git add * #git添加所有文件，准备上传

git commit -m "xxx" #提交文件

git push -u origin master #上传你提交的文件

但上传出错时执行一次 git pull --rebase origin master 命令即可

回到gitee你创建的仓库中，点击服务-giteepages-更新部署即可。

访问网址例如：

https://zjj_szgcjc.gitee.io/pdfpreview/web/viewer.html?file=pdf/gangjia/GG2020-01147/reportqery_getreport.pdf

viewer.html?file=后为web下对应文件的路径


