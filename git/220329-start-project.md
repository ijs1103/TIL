## repositories 클론하기
```javascript
git clone '레포지터리 주소' 
git add '변경된 파일'
git commit -m "message"
// branch 이름 main으로 변경
git branch -M main 
git push origin main 
git remote -v
```
## local에서 repositories 연결하기
```javascript
git init
git remote add origin https://github.com/{username}/{reponame}.git
touch README.md
git add README.md
git commit -m "docs: Create README.md"
git push -u origin main
```
## 커밋 메시지 

5개의 prefix가 존재한다.

| docs: | feat: | conf: | fix: |  refactor: |
| :---         |     :---      |          :--- | :--- | :--- |
| 문서작업   | 특징     | 환경설정    | 버그픽스 | 리팩토링 |

> ex) `docs: update README.md`
