# Day 1
## Git과 GitHub
1. 버전 관리
- 특정한 시점을 저장해 돌아가거나 관리할 수 있도록 함
2. Git
- 소스코드의 버전을 관리해주는 시스템(Git, SVN 등)
3. Git의 호스팅사이트(GitLab, BitBucket 등)

## 로컬 저장소
1. 생성되는 모든 버전 commit
2. 파일 추가 
- git add .
- git commit -m "message"
- git log
- git checkout "ID 7자리"

## 원격 저장소
1. Repository 생성
2. Remote Repository에 연결된 Local Repository 생성
3. 메인 브랜치명 main
4. 원격 및 로컬 저장소 연결
- remote add origin "원격저장소 주소"
5. commit 원격 저장소 업로드
- git push origin main
