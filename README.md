# myqnabook
명령어나 기타등등 모음

TightVNC

# 찾던거 모아두기
 
# Table of contents
 
 - [WINDOWS관련 명령어](#WINDOWS관련-명령어)
   - [네트워크](#네트워크)
     - [포트 점유중인 task 알아내기](#포트-점유중인-task-알아내기)
     - [포트 점유중인 task 죽이기](#포트-점유중인-task-죽이기)
 - [프로젝트 관련](#프로젝트-관련)
   - [book](#book)

# WINDOWS관련 명령어
## 네트워크
### 포트 점유중인 task 알아내기
netstat -ano | findstr "8082"
### 포트 점유중인 task 죽이기
taskkill /pid 19972 /f

# 프로젝트 관련
## book
### 책등록 
#### books 바로 호출
http POST http://localhost:8082/books title=testbook stock=100
bookId 관련...참고사이트
https://lion-king.tistory.com/entry/JPA-JPA-Id-GenerationTypeAUTO-IDENTITY
#### gateway 호출
http POST http://localhost:8088/books title=testbook stock=100



# 링크
https://noonnu.cc/
폰트 
https://youtu.be/NGPnW1VMP2Y
ppt 팁
