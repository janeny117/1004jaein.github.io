# 블로그 만들기 과정
내용정리

# 1. 깃허브
## 1. 깃허브 계정 생성
블로그를 만들기 위해 가장 먼저 한 일은 깃허브 계정을 만드는 것이었다. 
https://github.com/에 들어가서 계정을 생성했다
<img src="사진 업로드/회원가입.png" width="400">

## 2.repository 생성
Create a new repository를 눌러 깃허브를 만들 공간을 만들었다. 내 repository의 이름은 별명.github.io로 만들었다.
<img src="사진 업로드/create_repository.png" width="400">

## 3.Local-Remote Repository 연동
터미널 창에 git clone <repo_name> <path>를 입력해 러컬 저장소와 원격 저장소를 연동을 시킨 후 push를 통해 원격 저장소에 반영했다. 이 과정에서 푸쉬를 위한 토큰을 발급 받았다. 토큰 발급은 settings에 들어가 developer settings를 선택 후 personal access tokens를 선택하면 된다.  


# 2. 지킬
## 1. 환경 만들기 
지킬을 사용하기 위한 환경을 만들기 위해 ruby 설치가 필요하다. 
터미널창에 sudo apt install ruby-full를 입력해 설치하고 ruby --version를 통해 성공적으로 설치가 되었는지 확인한다.
<img src="사진 업로드/rubyv.png" width="600">
 
그 후 sudo gem install jekyll bundler를 통해 지킬을 설치하고 jekyll -v를 통해 성공적으로 설치되었는지 확인한다.
<img src="사진 업로드/jekyllv.png" width="600">
 
## 2. 지킬 사이트 생성
 블로그 디렉토리로 이동 후 jekyll new . --force를 통해 jekyll관련 파일을 생성해준다. 
 <img src="사진 업로드/ls.png" width="600">
 터미널창에 bundle exec jekyll serve를 실행 후 locahost:4000에 접속하면 지킬 사이트가 생성된 것을 확인할 수 있다. 
 

# 3. 블로그 꾸미기
## 1. 테마 선택
http://jekyllthemes.org/ 사이트에 접속해 마음에 드는 테마를 찾았다. 
<img src="사진 업로드/jtheme.png" width="400">

 minimal mistakes라는 테마를 선택해 홈페이지에 들어가 fork하는 방식을 선택했다.
 
## 2._config.yml 수정
 fork한 파일들 중 _config.yml에 들어가 내가 원하는 정보로 수정을 했다.
 
 <img src="사진 업로드/edit.png" width="400">    
 <img src="사진 업로드/blogimg.png" width="400">    
 
## 3. 포스팅하기
 블로그에 글을 포스팅 하기 위해서는 _post라는 폴더가 필요하다. 내 깃허브와 연결되어있는 디렉토리에 _posts라는 폴더를 생성해준다. 
  <img src="사진 업로드/포스팅1.png" width="400">    
  그 후 마크다운 형식의 파일을 만들어 마크다운 형식에 맞게 블로그에 포스팅할 글을 작성해주었다.  
   <img src="사진 업로드/포스팅2.png" width="400">    
   그 결과 내 블로그 주소에 들어가면   
   <img src="사진 업로드/포스팅3.png" width="400">   
  이와 같은 내용의 글이 업로드가 된 것을 확인할 수 있다.
## 4. 댓글 기능 넣기
 disqus가 아닌 utterances를 이용했다. https://github.com/ansohxxn/comments에 들어가 install을 클릭해 Only Select Repositories를 눌렀다. install을 하고 나면 다음과 같은 페이지가 뜬다. 
 <img src="사진 업로드/댓글1.png" width="400">   
 <img src="사진 업로드/댓글2.png" width="400">   
 repo에 댓글을 넣을 공간을 입력해주고 블로그 포스트 부분을 선택했다.  
 그 후 블로그 코드를 _config.yml에 반영해주었다. 
 <img src="사진 업로드/댓글3.png" width="400">      
 
 <img src="사진 업로드/댓글4.png" width="400">    
 이 과정을 모두 완료하면 
 <img src="사진 업로드/댓글5.png" width="400">     
 포스팅한 글 아래 부분에 댓글 입력창이 뜬다.

## 5. 파비콘 넣기
 https://favicon.io/emoji-favicons/ 사이트에 접속해 마음에 드는 이모티콘을 선택했다.
 그 후 압축을 풀어 내 블로그 최상위 로컬폴더로 옮기고  https://realfavicongenerator.net/에 있는 select your favicon image를 눌러 업로드한다.   
  <img src="사진 업로드/파비콘1.png" width="400">
 그 후 만들어진 코드를 복사해 includes/head/에 있는 custom.html에 붙여 넣으면 된다. 
 <img src="사진 업로드/파비콘2.png" width="400">     
 
 <img src="사진 업로드/파비콘3.png" width="400">   
 
 그러면 
  <img src="사진 업로드/파비콘적용.png" width="400">   
