## 에디터 부가 기능 사용
1. Extensions -> git graph 검색 후 설치
2. 완전히 껏다가 켜기
3. 왼쪽 git 메뉴 클릭-> view git graph 활성화 확인

## 복습
1. ch03 -> git init
1. readme.md 파일생성(##main에서 init)
1. add -> commit
1. branch 생성/변경 후 readme.md 파일 수정(###새로운 branch에서 수정)
1. main branch 변경 후 readme.md 파일 수정(###main에서 수정)
1. merge 후 git graph로 확인

## github와 연결
> 토큰생성: 깃허브 → 우측상단 내 아이콘 클릭 → settings → 좌측 하단 developer settings → personal access tokens → tokens(classic) → generate token(classic) → repo 체크 후 생성 
* `git config --global user.name "이름"`
* `git config --global user.email "이메일"`
* `git config --list`
1. git hub 레파지토리에서 'enviroment' 생성(리드미 추가X)
1. 다시 로컬로 돌아와서
1. `git branch -M main`
1. `git remote add origin URL주소복붙`
1. `git push -u origin main`

## 파이썬 파일 형상관리
1. `touch main.py`
```
print("hello python world")
```
2. add->commit->push

## 협업을 위한 방법
> clone은 단순 구경용임!
1. 다른 사람 프로젝트에 기여할 때
  * 레파지토리 fork -> clone -> branch 생성후 개발 -> push -> PR
2. 같은 팀원 프로젝트에 기여할 때
  * 팀장이 팀원들에게 collaborator 권한 부여 -> (팀원) clone -> branch 생성후 개발 -> push -> PR 
