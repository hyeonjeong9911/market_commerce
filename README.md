## MarketSNOW

### 마트형 커머스 

마트 물건들을 온라인으로 구매할 수 있는 서비스입니다.

### ERD
![image](https://github.com/hyeonjeong9911/MarketSNOW/assets/127717572/fcc99aec-a029-4acb-87ad-3389113b273f)

### 사용 기술 스택
* SpringBoot
* Java
* MYSQL
* JPA
  
### 프로젝트 기능
* 회원가입 기능
  * 일반적으로 모든 사용자는 회원가입시 USER 권한을 가진다.
  * 고유한 id와 비밀번호로 로그인
  * 회원가입 시 입력해야할 정보
    ( id / 이름 / 연락처 / 생년월일 / 이메일 / 비밀번호 )
  
* 로그인 기능
  * 관리자의 경우 관리자번호를 추가적으로 입력 후 로그인
  * 로그인 시 관리자 코드를 입력하여 로그인 하는 경우 관리자 권한으로 로그인된다.
 
* 상품 리스트
  * 등록된 상품들을 보여주는 기능
  * 상품의 재고 상태도 나타낸다.

* 상품 상세페이지
  * 상품에 대한 설명을 보여준다.
 
* 장바구니 기능
  * 장바구니에 물건을 추가 / 삭제할 수 있다.

* 주문
  * 물건, 수량을 선택하고 배송지 주소와 배송 요청 사항을 입력 후 주문한다.
 

#### 추가 기능
* 상품 등록 / 삭제 기능
  * 관리자 권한으로 가능하다.
  * 상품명 / 가격 / 등록 일자 / 재고 수량을 입력 받아 상품을 등록한다.
  * 상품의 재고 상태를 수정한다.
