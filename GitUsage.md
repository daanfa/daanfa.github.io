git config --global credential.helper cache  
git config credential.helper 'cache --timeout=300'  
git config --global credential.helper store  
git config --global credential.helper wincred  
git config --list  
git config --global --list  
//저장소 생성 및 연결  
$ git init  
$ git remote add origin [원격저장소 주소]  
$ git branch -m master main  
//파일 업로드  
$ git pull (또는 git pull origin [브랜치 이름])  
$ git add .  
$ git commit -m "commit message"  
$ git push (또는 git push origin [브랜치 이름])  
//추가적인 명령어  
$ git remote -v  
$ git remote rm origin  
$ git branch  
$ git config --global init.defaultBranch [브랜치 이름]  

$ git status  
$ git rm --cached -r .  
