# Markdown이란

Markdown은 텍스트 기반의 마크업언어로 2004년 존그루버에 의해 만들어졌으며 쉽게 쓰고 읽을 수 있으며 HTML로 변환이 가능하다. 특수기호와 문자를 이용한 매우 간단한 구조의 문법을 사용하여 웹에서도 보다 빠르게 컨텐츠를 작성하고 보다 직관적으로 인식할 수 있다. 마크다운이 최근 각광받기 시작한 이유는 깃헙(https://github.com) 덕분이다. 깃헙의 저장소Repository에 관한 정보를 기록하는 README.md는 깃헙을 사용하는 사람이라면 누구나 가장 먼저 접하게 되는 마크다운 문서였다. 마크다운을 통해서 설치방법, 소스코드 설명, 이슈 등을 간단하게 기록하고 가독성을 높일 수 있다는 강점이 부각되면서 점점 여러 곳으로 퍼져가게 된다.

## 1.2. 마크다운의 장-단점

### 1.2.1. 장점
1. 간결하다.**
2. 별도의 도구없이 작성가능하다.
3. 다양한 형태로 변환이 가능하다.
3. 텍스트(Text)로 저장되기 때문에 용량이 적어 보관이 용이하다.
4. 텍스트파일이기 때문에 버전관리시스템을 이용하여 변경이력을 관리할 수 있다
5. 지원하는 프로그램과 플랫폼이 다양하다.

# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6

##2.2. BlockQuote

>This is a first blockqute.


>>This is a second blockqute.


>>>This is a third blockqute.

*Bold*
**Bold**
~~Italic~~
__Italic__
_Cancel_

# git 명령어

## git 명령어

### 전역 설정 정보 조회


> git config - -global - -list

### 전역 설정 정보 삭제시키기


> git config --global --unset-all user.email


>git config --global --unset-all user.name

## 새로운 저장소 초기화하기


> git init

## 저장소 복제하기


> git clone <저장소 url>

## 새로운 원격 저장소 추가하기


> git remote add <원격 저장소> <저장소 url>

## 새로운 파일 git에 등록시키기(staging)


> git add <파일>

## 현재까지 작업한 내용 저장하기


> git commit -m “<메시지>”

## 원격 저장소에서 합치지 않고 지역 브랜치로 변경 사항 가져오기


> git fetch <원격 저장소>

## 원격 저장소에서 변경 사항을 가져와 현재 브랜치에 합치기


> git pull <원격 저장소>

## 새로운 로컬 브랜치를 원격 저장소에 푸싱하기


> git push <원격 저장소> <지역 브랜치>
