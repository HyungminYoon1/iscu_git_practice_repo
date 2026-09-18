# 깃 명령어

>최신화: 2026-09-18

## 새로운 깃 저장소 만들기
git init

## 저장소 복사하기
git clone

## 변경사항 모두 추가
git add .

## 변경사항 커밋
git commit -m "<커밋 메시지 작성>"

## 깃 상태 확인
git status

## 원격 저장소 약칭을 `origin` 으로 등록
git remote add origin <원격 레포 주소>

## 현재 로컬 브랜치의 이름을 main으로 강제 변경하는 명령어
git branch -M main

## 원격 저장소에 `main` 브랜치 만들기
git branch -M main

## 원격 저장소(약칭 origin)의 main 브랜치에 현재 로컬 브랜치 작업 내용 올리기
git push origin main

git push -u origin main

(참고) 최초로 push할 때 -u (또는 --set-upstream) 옵션을 붙여서 실행하면, 그다음부터는 브랜치명을 생략하고 git push나 git pull만 입력해도 자동으로 origin main과 연동

## 원격 저장소의 main 브랜치에서 가져오기
git pull origin main
