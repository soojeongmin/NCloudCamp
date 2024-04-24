# Day 1
## Git과 GitHub
1. 버전 관리
1.1. 특정한 시점(version)을 저장해 돌아가거나 관리할 수 있도록 함
1.2. 버전 관리 시스템: 버전 관리를 도와주는 프로그램/웹 사이트
2. Git
2.1. 소스코드의 버전을 관리해주는 시스템(Git, SVN 등)
3. GitHub: Git으로 관리된 프로젝트 올리는 호스팅사이트(GitLab, BitBucket 등)
3.1. 시공간 제약 X, 자유로운 협업 가능

## 로컬 저장소
1. commit: Git에서 생성되는 모든 버전 
2. 버전관리 
`git add .`
`git commit -m "message"`
`git log`
`git checkout "ID 7자리"`

## 원격 저장소
1. GitHub상 Repository 생성
2. Remote Repository에 연결된 Local Repository 생성
3. 메인 브랜치명 master -> main
4. 원격 및 로컬 저장소 연결 `remote add origin "원격저장소 주소"`
5. commit 원격 저장소 업로드 `git push origin main`
