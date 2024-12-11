# Git_Use
협업을 위한 git 사용법 정리

## How to use
1. clone으로 flow git 가져오기
```
git clone 우리 flow git주소
```
2. clone 폴더 연 pycharm에서 terminal 실행
```
git branch
git branch feature/SPRING2024_SE //branch 생성
git branch //현재 있는 branch 확인/로컬
git checkout feature/SPRING2024_SE //branch 전환
git branch //현재 branch 확인
```
* feature인 이유? </br>
버전 충돌 방지하기 위함 </br>
따로 제작 후 추가하는 방식

-Local branch 삭제 시
```
git checkout master
git branch -d <name>
```
3. push로 원격 저장소에 기본 branch 설정
```
git push --set-upstream origin feature/SPRING2024_SE
```

4. 파일 넣기

5. 파일 올리기
```
git add . 
git commit -m "Upload~~"

git push origin feature/SPRING2024_SE //branch에 올림
git push //이때 파일 올라감
```

6. master에 올리기
```
git checkout master //branch 변경
git merge feature/SPRING2024_SE
git push //master에 올라감
```
