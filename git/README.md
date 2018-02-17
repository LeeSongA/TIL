# Git 사용법 (18.02.13 ~ )  
> Git을 사용하면서 정리한 기본적인 Git 사용법입니다.  

### 1. GitHub로부터 저장소 내려 받기  
```
사용법 : git clone 주소
예시 : git clone https://github.com/LeeSongA/TIL
```
- GitHub(깃 저장소)로 부터 저장소를 내려 받음  
---

### 2. 수정한 파일 서버로 업로드
```
git add 파일명
git commit -m "내용"
git push origin master
```
- `add` : 인덱스에 파일 내용을 추가
- `commit` : 저장소에 변경사항을 기록
- `push` : 변경 내용을 서버로 올림

