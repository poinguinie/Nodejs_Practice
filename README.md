# Nodejs_Practice
### 교재 : Node.js 프로그래밍
### 저자 : 정재곤
### 출판사 : 이지스퍼블리싱

![image](https://user-images.githubusercontent.com/64086893/128055806-274b5a1f-fd9d-45ba-855b-488eed8ac584.png)

## Language : Node.js

### 목차
0. 노드로 만들 수 있는 대표적인 서버와 용도
1. 노드에 대해 알아보고 개발 도구 설치하기
2. 노드 간단하게 살펴보기
3. 노드의 자바스크립트와 친해지기
4. 노드의 기본 기능 알아보기
5. 웹 서버 만들기
6. 데이터베이스 사용하기
7. 익스프레스 프로젝트를 모듈화하기
8. 뷰 템플릿 적용하기
9. 패스포트로 사용자 인증하기
10. 채팅 서버 만들기
11. JSON-PRC 서버 만들기
12. 위치 기반 서비스 만들기
13. 모바일 서버 만들기
14. 게시판 만들기
15. 클라우드에 올리기

### 후기
개정판이 2018년에 나온 책이라 그런지 현재 NodeJS에서 활용이 불가능한 부분도 꽤나 있습니다.
그래도 NodeJS를 접하고 익히는 데에는 유용한 책이라고 생각합니다.

### 특이사항
#### 1
static 사용 중 public 폴더를 정적으로 사용하기 위해

''' javascript
app.use('/public', static(path.join(__dirname, 'public')));
'''

으로 표현되는데 
이것이 잘 되지 않아

''' javascript
app.use(express.static(__dirname + '/public'));
'''

로 사용하였습니다.

#### 2
semantic-ui가 Node버전 6.x.x버전 까지만 호환되는 것 같아 현재 14.x.x를 사용중이기에 사용 불가했습니다.

