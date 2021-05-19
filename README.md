# myqnabook
명령어나 기타등등 모음

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
taskill /pid 19972 /f

# 프로젝트 관련
## book
### 책등록 
http POST http://localhost:8082/books bookId=1 title=testbook stock=100
