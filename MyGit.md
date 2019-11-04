https://www.cnblogs.com/cxq0017/p/9636083.html


cd /d/MyGit/    //文件路径

 git config --global user.name "YOKE3"

git config --global user.email "7422159..@qq.com"
。。。
。。。
。。
。。。。

如果报错  rm -rf .git //删除.git   

git init

git add 文件名 // 文件名 将要 上传 的 文件 （如果要整个文件夹上传: git add .）

git commit -m "just atest"

git remote add origin git@github.com:YOKE3/要保存的文件名.git

如果有错误： git remote rm origin

git remote add origin git@github.com:YOKE3/要保存的文件名.git

git push origin master //开始上传