# pdf
如何增加pdf

之后每一次增加文件时，只需要在web文件增加新的pdf文件，然后执行下列命令：

git add * #git添加所有文件，准备上传

git commit -m "xxx" #提交文件

git push -u origin master #上传你提交的文件

回到gitee你创建的仓库中，点击服务-giteepages-更新部署即可。

访问网址http://zhuang_murong.gitee.io/pdf/web/viewer.html?file=PDF文件名称.pdf

例：http://zhuang_murong.gitee.io/pdf/web/viewer.html?file=CY2020-36844.pdf


可以在web文件夹下面设置新文件夹，

则网址改成http://zhuang_murong.gitee.io/pdf/web/viewer.html?file=pdf/shizhan/001-JZ-2021-116/reportqery_getreport.pdf

viewer.html?file=后为web下对应文件的路径


