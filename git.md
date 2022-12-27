# git 정리

## 1. 작업을 하고
## 2. 변경된 파일을 모아
### (add)
## 3. 버전으로 남긴다.
### (commit)
---
## git은 파일을 modified, staged, committed로 관리
- modified
  - 파일이 수정된 상태
  - add 명령어를 통하여 staging area로

- staged
  - 수정한 파일을 곧 커밋할 것이라고 표시한 상태
- committed
  - 커밋이 된 상태
---
## Working Directory
- 파일의 변경사항

## Staging Area
- 버전으로 기록하기 위한 파일 변경사항의 목록

## Repository
- 커밋(버전)들이 기록되는 곳
---
## 기본 명령어
1. git add <file> (add)
  - working directory상의 변경내용을 staging area에 추가하기 위해 사용
2. git commit -m '<커밋메시지>'
  - staged 상태의 파일들을 커밋을 통해 버전으로 기록

