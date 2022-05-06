<h3>0. Home</h3>
   내 손 안에서 언제든 버거를 만들고, 수정하고, 보고, 지울 수 있다면 얼마나 좋을까요 ?  
'내손안의 버거킹' 서비스,   **BURGER PROJECT!**

<h2>📝 목차 📝</h2>
<h5>0. Home</h5>
<h5>1. 소개</h5>
<h5>2. 함수 기능</h5>
<h5>3. 협업</h5>


<h2>1. 소개</h2>
버거를 만들고, 수정하고, 관리하는 서비스입니다! <br>
버거를 생성하여 재료를 마음대로 추가하고, 관리해 보세요! <br>
<h2>2. 함수 기능</h2>
1) createBurger()[김민상 구현]   <br>
: 새로운 버거를 새로 생성한다. 이름, 가격을 새로 설정하고, 빵의 종류, 패티 종류, 소스 종류를 정한다.  <br>  
2) readBurger() [김민상 구현]      <br>
: 버거 1개의 정보를 읽어들인다. 또한 readBurger를 실행하면,      <br>
이름, 가격      <br>
-------------<br>
 버거{  <br>
빵  <br>
마요네즈  <br>
양상추  <br>
토마토  <br>
양파  <br>
소스  <br>
패티    <br>
기타재료  <br>
빵  <br>
}<br>  
-------------<br>
위의 글처럼 직관적으로 버거에 포함된 메뉴를 알 수 있다. <br>
3) updateBurger() [이산하 구현]  <br>
: 버거의 가격,이름, 빵, 소스, 패티를 수정할 수 있다.  <br>
4) deleteBurger() [이산하 구현] <br>
: 버거 1개의 정보를 삭제한다. <br> 
5) saveData() <br>
: 현재 저장된 버거들의 정보를 burger.txt 파일에 저장한다.  <br>
6) loadData()  <br>
: burger.txt 파일에 저장된 버거들의 정보를 읽어들인다. <br> 
7) selectMenu() [이산하 구현] <br>
: crud,save,load,search 등 여러가지 명령을 실행할 수 있다. <br> 
8) listBurger() [김민상 구현] <br>
: 모든 버거들의 정보를 출력한다.  <br>
9) searchName()  <br>
: 버거의 이름을 검색한다. 검색한 문자열이 포함된 버거를 모두 검색한다. <br>   
10) searchPrice()  <br>
사용자가 입력한 2개의 가격 사이에 있는 모든 버거를 모두 검색한다. <br>  
11) searchBurger()     <br>
 : 버거에 포함된 빵의 종류, 패티의 종류, 소스의 종류로 버거를 검색한다.  <br>

<h2>3. 협업</h2>  
<br> 
1) 개발일지 <br> <br>   
[9주차] <br>
(1) teamproject를 위한 organization 생성 <br>
(2) teamproject를 위한 burgerproject repo 생성 <br>
(3) 함수 정의, 구조체 및 header file 선언, README.md 파일 작성, wiki page 개설 <br><br>
2) 개발 일정 및 계획 <br><br>
[9주차] <br>
(1) 주제 선정 및 기획 <br>
(2) 함수 정의<br><br>
[10주차] <br>
(1) 데이터 정의
(2) createBurger(), readBurger(), updateBurger(), deleteBurger(), listBurger(), selectMenu() 함수 구현<br>
(3) README.md 파일 작성<br>
(4) Wiki page 작성<br> 
<br>
[11주차]<br>
(1) savaData(), loadData(), searchName(), searchPrice(), searchBurger() 함수 구현 <br>
(2) 더 세부적인 searchBurger()함수 기능 추가 <br>
(3) 전반적인 project 마무리 <br><br>
3) commit convention <br>
+ feat: 새로운 기능 추가 <br>  
+ fix: 버그 픽스   <br>
+ docs: 문서 수정  <br>
+ style: 포맷,  세미콜론 수정, Optimize import, Code clean up 등 코드가 아닌 스타일에 관련된 수정  <br> 
+ refactor: 코드 리펙토링  <br>
+ test: 테스트 코드 추가  <br>
+ chore: 빌드 관련 업무 수정<br>
<br>

3. 프로젝트 참여자 <br>
* **이산하**  
역할: wiki page 관리  
github ID : sanha33 
* **김민상**  
역할: README.md page 관리  
github ID : 21900094
<br>
: 모든 팀원이 프로젝트 기획 및 코드를 관리하고 수정