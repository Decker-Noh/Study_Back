\# ssh 접속

$ ssh -p 1345(포트번호) falsy(사용자계정)@100.100.100.100(ip주소 또는 도메인)

 

\# 계정 목록 확인

$ cat /etc/passwd (cat - 해당 내용을 수정하지 않고 보여주기만함)

 

\# 계정 추가

$ useradd cheolguso;

 

\# 계정에 비밀번호 부여

$ passwd cheolguso

 

\# 현재 위치의 절대 경로 보기

$ pwd

 

\# 디렉토리 생성

$ mkdir ./names

 

\# 파일/디렉토리 소유권 수정

$ chown name:name /home/name/www

 

\# 파일/디렉토리 권한 수정

$ chmod 744 ./name.php

 

\# 파일 정보 확인

$ ls

 

\# 퍼미션까지 확인

$ ls -al

 

\# 파일 내용? 검색하기

$ grep "검색할 내용" /home/name/www (검색할 대상 디렉토리 경로)

$ grep -r "검색할 내용" /home/name/www (r - 대상의 모든 하위 디랙토리 포함)

 

\# 심볼링크 생성

$ ln -s /etc/nginx/sites-available/cheolguso /etc/nginx/sites-enabled

 

\# 파일 삭제

$ rm ./cheolguso.txt

 

\# 디렉토리 삭제

$ rm -r ./cheolguso

 

\# 한번더 묻지 않고 디렉토리까지 삭제

$ rm -rf ./cheolguso

 

\# 파일과 디렉토리의 권한에 대한 의미 차이

\# 출처 : http://blog.naver.com/lbs8482/220962014710

\# 1. 파일에 대한 권한

r : 파일을 읽을 수 있는 권한

w : 파일을 수정할 수 있는 권한

x : 파일을 실행할 수 있는 권한

 

\# 2. 디렉토리에 대한 권한

r : 디렉토리 안에 ls CMD 수행할 수 있는 권한

w : 디렉토리 안의 파일을 삭제 또는 생성할 수 있는 권한

x : 디렉토리 안에 cd CMD 수행할 수 있는 권한