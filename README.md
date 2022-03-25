- git init : git 시작 (.git 파일 생성됨)
주의: .git 파일이 위치한 디렉토리와 그 하위 디렉토리에서 변경되는 모든 것들이 기록된다. 실수로 최상위 디렉토리에 .git 파일을 생성하면 내 컴퓨터의 모든 파일이 업로드 될 수 있다.
- git status : git 상태 확인
git add (file_name) : 파일 수정 이력 기록 준비 (쇼핑몰 장바구니 같은 역할), file_name 자리에 . 를 입력하면 모든 파일 지정됨
- git commit : 파일 수정 이력 기록 (쇼핑몰 결제와 같은 역할)
- git commit -m "(commit message)" : (commit message)와 함께 commit하기
주의: commit message는 Guideline에 따라서 작성한다.
- git log : commit 이력 보기
- git remote add origin "(github-url)" : git을 github과 연결
통상적으로 origin을 repository 이름으로 사용, 필요에 따라 origin 대신 다른 이름으로 대체 가능
- git remote : 연결된 repository 확인
- git push origin master : origin repository의 master branch로 올리기
- git reset --hard "" : 그때시점으로 롤백, 그 사이 수정본은 다 지워진다.
- git reset --soft "" : 시점을 옮기긴 하지만 그 사이 진행된 수정본은 지워지지 않는다.

