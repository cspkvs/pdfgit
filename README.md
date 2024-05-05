如何增加PDF

1、到github新建一个仓库，把相关资料上传进去

2、下载github desktop，网站：https://desktop.github.com
            github desktop汉化补丁，网站：https://github.com/robotze/GithubDesktopZhTool/tree/3.3.14

3、连接在线仓库，在本地文件夹进行更新，备注摘要后commit到仓库，点击同步

4、注册cloudflare，网站：https://dash.cloudflare.com/，同步在线仓库

5、点击page进行部署

6、在线查看：

https://pdfgit.pages.dev/web/viewer?file=pdf/CS2022-00062/document.pdf

https://9fb2bb05.pdfgit.pages.dev/web/viewer?file=pdf/shizhan/1BL2020-00064/reportqery_getreport.pdf

https://1f088abf.pdfgit.pages.dev/web/viewer?file=pdf/CS2022-00062/Document.pdf

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


