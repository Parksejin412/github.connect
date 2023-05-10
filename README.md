# github.connect

## 🚩1. [깃설치](https://git-scm.com/download/win)

🌟 git을 통해서 githubrhk 연결할 수 있다.
        
      ⭐ 1) 깃에 올려야할 폴더에서 Shift + 우클릭 -> PowerShell 창열기 -> git init 엔터
      git init
      
      ⭐ 2).git 폴더가 생성됨
      
------------------------------------------------------------

##  🚩2. 깃 설치 후 Git bash 열기 

🌟 Git bash 열기
      
       ⭐ 오른쪽 마우스 클릭 -> Git bash 창 열기
       
            
🌟 유저이름설정

       ⭐ git config --global user.name "Sejinny"
       
🌟 유저 이메일 설정하기 (반드시 github에 가입했던 이메일 주소와 동일해야함)

       ⭐git config --global user.email "sejin97412@naver.com"

🌟 내 정보 확인하기

       ⭐git config --list

   ↑ 위의 연결은 해당 컴퓨터에서 한번만 실행하면 됨
   
------------------------------------------------------------

#  🚩3. github에 코드 업로드하기
        🌟초기화
          -> git init
          
        🌟추가할 파일(폴더안에 내용을 모두 올림, .은 모든 파일을 의미)
          -> git add . 
          
        🌟히스토리 만들기(-m : 메세지를 의미 / " " : 히스토리 이름 작성)
          ->  git commit -m "first commit" 
          
        🌟Gitub의 repository를 만들고 그 주소와 연결하기
          ->  git remote add origin https://github.com/Parksejin412/css.flex.git (수정할때는 작성X)
         
        🌟연결 확인하기
          -> git remote -v
         
        🌟Github에 올리기
         -> git pull origin master (수정할때 /pull->push)
         -> git push origin master
         
          
