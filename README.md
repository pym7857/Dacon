# Dacon

<img src="https://dacon.s3.ap-northeast-2.amazonaws.com/competition/235697/logo1.jpeg">

<br>

## private 레포에 git pull/push 하는법 😀
1. Personal Access Token 생성하기 [생성하는 법👈](https://calvinjmkim.tistory.com/19)
2. Token value 복사
3. 
```bash
$> git remote add origin https://[YOUR_LOGIN_NAME]:[TOKEN_VALUE]@github.com/pym7857/Dacon
```
### pull
git pull origin main 

### push
git push --set-upstream origin master
