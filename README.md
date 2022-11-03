# git
git clone 방법

## MAC

0. git을 처음 설치할 경우
  - git config --global user.name "gitHub 사용자 이름"
  - git config --global user.email " gitHub 이메일"
  
1. 폴더 생성
  - mkdir gitHub
  - cd gitHub
  
2. git 초기화
  - git init  
    - README.md 파일이 있을 경우
      - git add README.md
      - git commit -m "first commit"
  - git branch -M master
  - git remote add origin https://github.com/~~~.git

3. gitHub 자료 가져요기
  - git pull origin master

4. gitHub로 자료 보내기
  - git push -u origin master
