# Day 2
## Clone
1. `git clone https://github.com/soojeongmin/Ex02_RemoteRepository.git .` 
2. '.'을 추가해서 폴더 제외 파일만 클론 가능
3. 버전 정보, 소스코드 포함한 로컬 저장소가 생성됨
4. 'remote origin' 하지 않아도 원격 저장소 위치가 연결되어있음

## Source Tree
1. GUI 형태의 Git

## 깃 명령어
1. `git init` 로컬 저장소 생성
2. `git add` 새로운 버전에 추가할 파일 지정
3. `git commit` 새로운 버전 생성(현재 상태 저장)
4. `git remote add origin` 원격 저장소와 로컬 저장소 연결
5. `git push` 원격 저장소에 코드와 버전 정보 업로드
6. `git clone` 원격 저장소에 있는 내용 다운
7. `git pull` 원격 저장소에 업데이트된 내용 다운

## commit 이해하기
1. commit은 기존파일+변경파일 포함 프로젝트 전체 저장
2. SVN commit은 차이점(Delta)만 저장하지만 Git은 전체 저장(SnapShot)
3. 100번 변경되면 100번 비교하는 SVN보다 Git의 연산이 빠르고 용량이 적음
4. 복잡한 명령어 빠른 처리 가능

## 파일 상태 종류
1. untracked(추적 없음) </br>
2. tracked</br>
2.1. unmodified(수정 없음)</br>
2.2. modified(수정함)</br>
2.3. staged(스테이지됨)</br>

## branch
1. 1인 1 branch 1 commit
2. branch를 생성 규칙 지정(branch 명명규칙, commit 방식)

## checkout
1. HEAD 포인터를 다른 branch나 이전 commit으로 옮기는 명령어

## merge
1. merge commit 병합커밋
2. Fast-forward 빨리감기
3. conflict 충돌

## pull request
1. 예의바른 merge
2. 
