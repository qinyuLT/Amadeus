##上传本地项目
  1. 在本机需要上传的项目名右键点击 [Git Bash Here]()
  2. 将XXX改成自己的文件夹或项目名称，整体复制执行，快
```
  git remote rm origin; 
  git init;
  git add ./XXX;
  git commit -m 'XXX';
  git remote add origin git@github.com:qinyuLT/XXX.git;
  git pull --rebase origin master;
  git push -u origin master;
```

##克隆远程项目
```
  $ git clone <版本库的网址>
  $ git clone <版本库的网址> <本地目录名>
```
```
  git clone git@github.com:qinyuLT/XXX.git;
```

##具体命令介绍
- [Git教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/00137628548491051ccfaef0ccb470894c858999603fedf000)
- [Git远程操作详解](http://www.ruanyifeng.com/blog/2014/06/git_remote.html)
