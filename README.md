# Spring Project : HTA_mall
스프링을 이용한 쇼핑몰 사이트 입니다.
<br/><br/>

## :hourglass: 개발 기간
23.02.01 ~ 23.02.16

<br/><br/>

## :hammer_and_wrench: 사용 기술
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black)
![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)
<br/><br/>

## :runner: 참여 인원
- Joo young Kim
- Han byeol Kim
- Won woo Seo
- Jun soo Lee
- Sung hwan Cho
- Seong min Cho
- Won jun Jung
<br/><br/>

## :compass: ERD

<img src="https://user-images.githubusercontent.com/116073413/225074668-5070ac43-843c-427e-81f7-0801b80ba6dd.jpg" width="100%" height="100%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>


<br/><br/>

## :open_book: 프로젝트 요약
 * 회원가입시 중복된 아이디는 사용할수 없습니다. 회원가입 전 '중복체크' 기능을 사용하여 미리 중복 여부를 확인할수 있습니다. 
 * 로그인이 성공적으로 진행되면 로그인 정보를 세션에 저장/유지 시키고, 로그아웃으로 세션을 해제합니다.
 * 전체 카테고리와 검색, 슬라이드쇼를 통해 상품목록으로 이동합니다.
 * 추천상품, 상품목록의 이름으로 상품 상세 페이지로 이동합니다.
 * 상세 페이지에서 수량, 바로 구매와 장바구니로 결제 방식을 선택 할 수 있습니다.
 * 장바구니에서 담은 상품을 선택적으로 구매 가능합니다.
 * 주문/결제 시 자동으로 로그인된 고객의 정보가 들어가며 수정 가능합니다.
<br/><br/>

## :gear: 주요 기능 
> ### :slightly_smiling_face: 회원가입/로그인
>
> <br/>
> 우측 상단의 재생버튼을 클릭하세요.
<img src="https://user-images.githubusercontent.com/116073413/224787676-1aac5486-2fb0-4b7b-a978-c5fc0dec84a1.gif" width="100%" height="100%" title="px(픽셀) 크기 설정" alt="RubberDuck">

<br/>

> * 회원가입과 로그인은 하나의 창에서 토글로 구분하고 있습니다.<br/>
> * 회원가입시 중복된 아이디를 미리 확인할 수 있습니다. 중복 확인을 하기 전까지는 '회원가입' 버튼은 비활성화 상태로 유지됩니다. <br/>
> * 로그인시 틀린 아이디/ 틀린 비밀번호/ 정상 로그인 의 경우의 수를 잡고 있습니다. 

<br/><br/><br/>

> ### :mag: 검색 기능
> 
> <br/>
> 우측 상단의 재생버튼을 클릭하세요.
<img src="https://user-images.githubusercontent.com/116073413/224794990-3a52c50f-ce2b-4fb9-b8cf-8ec32f758730.gif" width="100%" height="100%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>

<br/>

> * 사용자가 '검색창' 을 사용해 검색을 할 시 검색한 키워드를 SQL에서 like 연산자를 사용해 검색된 단어가 일치한 관련된 상품이 나오게끔 로직을 구현했습니다. <br>
> * 존재하지 않는 상품이나 잘못된 입력을 통해서 검색을 할 시 사용자에게 "검색하신 상품이 없습니다"라고 응답을 보냅니다.
> * 상품 분류를 클릭하여 원하는 카테고리의 상품을 조회할 수 있습니다. 

<br/><br/><br/>

> ### :shopping_cart: 장바구니
> 
> <br/>
> 우측 상단의 재생버튼을 클릭하세요.
<img src="https://user-images.githubusercontent.com/116073413/224799315-0043f934-4821-4980-a565-267d9346ff05.gif" width="100%" height="100%"/>

<br/>

> * 사용자가 장바구니에 추가한 품목의 이미지, 수량, 이름, 총 가격을 출력합니다.
> * 장바구니에 있는 항목을 삭제할 경우 비동기로 처리되어 즉시 최신화 된 목록을 보여줍니다. 
> * 장바구니에 추가된 상품이 없거나, 장바구니에서 체크박스로 선택한 상품이 없을 경우, '결제하기' 버튼은 비활성화 됩니다. 


<br/><br/><br/>

> ### :shopping_cart: 상품 구매
> 
> <br/>
> 우측 상단의 재생버튼을 클릭하세요.
<img src="https://user-images.githubusercontent.com/116073413/225075032-10da839e-ef84-459d-815d-20a2c6f7e5ae.gif" width="100%" height="100%"/>

<br/>

> * 사용자가 선택한 상품, 수량 정보를 받아 결제 페이지를 출력합니다. 
> * '약관동의' 체크박스를 체크하지 않으면 '결제하기' 버튼이 작동하지 않습니다. 

<br/><br/>
	
## :face_with_head_bandage: Trouble Shooting
> 
> :heavy_check_mark: 회원가입시 데이터가 추가된 시간을 입력하려고 했으나 원하는 Date 형식으로 저장되지 않음.
> * @Temporal 어노테이션을 사용하여 db 에 맞는 Date 형식을 저장. -> 혹은 LocalDateTime 타입으로 저장하는 방법도 있었음.
>
> :heavy_check_mark: 깃허브를 사용하여 조원간 파일을 공유할때 필요없는 파일까지 같이 공유가 됨.
> * gitignore 파일을 사용하여 공유될 필요가 없는 파일은 제외시킴.
>
> :heavy_check_mark: 로그인 성공시 그 정보를 서버 어디에 저장시켜 로그인 상태를 유지시킬지 고민.
> * Model api 를 사용하여 로그인 정보를 저장하여 session 관리.
>
> :heavy_check_mark: form 태그 내에 있는 정보를 바로 controller 로 보내지 않고 jsp 내에서 가공을 한 후 보낼 필요가 있었음.
> * onClick 함수를 사용하거나 EventHandler 를 사용.
>

<br/><br/>

## :bulb: 느낀점

> :heavy_check_mark: 회원 가입시 회원 정보를 저장하는 알고리즘이 보안에 매우 취약하다고 생각. 모종의 방법으로 암호화를 시켜 보안성을 늘려야 한다는 생각.
>
> :heavy_check_mark: 로그인 상태 유지를 단순하게 하나의 세션에 저장하여 관리 하였는데, 동일하게 보안성에 문제가 있다고 생각. 
>
> :heavy_check_mark: 데이터 베이스 설계시 '정규화' 라는 개념을 사용하여 일관성/무결성을 올려야 겠다고 생각. 