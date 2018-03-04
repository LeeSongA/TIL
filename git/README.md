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
---

### 3. 풀리퀘스트
```
풀리퀘스트하고 싶은 사이트에서 fork 버튼을 누른다.
git clone [포크해온 내 주소]
cd [포크해온 폴더]
git remote add upstream [원본 주소]
git fetch upstream		// 원본 주소에서 자료 가져오기
git merge upstream/master	
```
- 수정한 후에, 수정한 파일 서버로 업로드 과정과 동일
```
git add .			
git commit -m "내용"
git push origin master
```

```
[포크해온 내 주소]로 들어간다.
New pull request 버튼 클릭
Create pull request 버튼 클릭
```
---

### 4. Git에서 ignore 파일 설정
- 이클립스 이용하기
	- 무시할 [폴더/파일] 오른쪽 클릭 > Team > ignore
	- 무시할 [폴더/파일] 삭제한 후 git에 업데이트
- 직접하기
	- git을 받은 폴더로 이동
	- .git이 있는 폴더 내에 .gitignore 파일 생성
	- .gitignore 파일에 무시할 [폴더/파일] 작성
	- git에 업로드
- .gitignore 설정 후 적용되지 않았을 때, 문제 해결
	- git rm -r --cached .
	- 파일 생성, 내용 작성
	- git에 업로드

