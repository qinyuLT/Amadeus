#上传本地项目

  git remote rm origin; 
  git init;
  git add ./XXX;
  git commit -m 'XXX';
  git remote add origin git@github.com:qinyuLT/XXX.git;
  git pull --rebase origin master;
  git push -u origin master;
