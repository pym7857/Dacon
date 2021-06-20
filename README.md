# Dacon

🙋‍♂️[구내식당 식수 인원 예측 AI 경진대회](https://dacon.io/competitions/official/235743/overview/description) <br>
🙋‍♀️[토론은 issue탭에서~](https://github.com/pym7857/Dacon/issues) <br>
🧛‍♂️반드시 각자 branch에 코드 작성 후, Pull request 요청 ⚠이때, 리뷰어는 멤버 모두 지정 <br>
💥[깃 commit 컨벤션](https://doublesprogramming.tistory.com/256) 지킵시다. 제발 <br>

<br>

✔ 시각화 라이브러리는 대화형 라이브러리 `Plotly` 권장!! <br>
👉👉~~씹 틀딱 matplotlib, seaborn 사용 ㄴㄴ~~ <br>
✔ `Plotly` 사용 위해서는 `nbformat` 설치 필요

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
