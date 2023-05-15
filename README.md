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

##  🚩3. github에 코드 업로드하기
        🌟초기화
          -> git init
          
        🌟추가할 파일(폴더안에 내용을 모두 올림, .은 모든 파일을 의미)
          -> git add . 
          
        🌟히스토리 만들기(-m : 메세지를 의미 / " " : 히스토리 이름 작성)
          ->  git commit -m "first commit" 
          
        🌟Gitub의 repository를 만들고 그 주소와 연결하기
          ->  git remote add origin https://github.com/Parksejin412/css.flex.git (수정할때는 작성X) / 새로생성된 주소 입력하기
         
        🌟연결 확인하기
          -> git remote -v
         
        🌟Github에 올리기
         -> git pull origin master (수정할때 /pull->push)
         -> git push origin master
         
 ------------------------------------------------------------

# Github 협업하는 방법 (사원입장)
 ## 🚩1. 소스코드 다운로드
        🌟협업하기위해 콜라보 초대 코드 공유 or 수락
   
        🌟new터미널 

        🌟git clone 입력
   
        🌟git clone 코드주소  / 원하는 github 폴더 -> 코드 -> http 주소 복사
   
           ->git clone https://github.com/Parksejin412/hanacard.git
     
  ------------------------------------------------------------   
   
 ## 🚩2. 브랜치 만들기 
           🌟git checkout -b 브랜치이름 / 가지생성(name) / ""입력X

             ->git checkout -b park 

           🌟 git add .

           🌟 git commit -m "name"

              -> git commit -m "신입 박세진" 

           🌟 git push origin 브랜치이름  / master 아니고 가지이름 입력

              -> git push origin park

           🌟 다음 이미지와 같이 되면 완료!
           ![image](https://github.com/Parksejin412/github.connect/assets/129017065/0ddd771f-631c-4572-94e9-2a1f3457549c)

   
   
