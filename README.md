# JustWeDoIt 

- 프로젝트 사이트 -> **Nike**
- 나이키는 운동선수들을 위한 스포츠 의류 기업으로 세계적인 스포츠웨어 e-commerce 사이트이다. 
- 직관적인 UI와 다양한 상품 필터링으로 구성되어있어, 사용자에게 편리한 UX를 제공한다.

## 개발 기간
- 2022/10/17 ~ 2022/10/28


## 참여 개발자
### Front-end Developers
- [최현](https://github.com/choigus98)
- [김민경](https://github.com/KMK99cone)
- [정현석](https://github.com/Sn-bow)
- [강은지](https://github.com/imchloedev)

### Back-end Developers
- [신인혁](https://github.com/ShinInHuck)
- [이현태](https://github.com/iflov)
- [박은송](https://github.com/Eunsong-Park)
- [Back-end Repository](https://github.com/wecode-bootcamp-korea/38-1st-JustWeDoIt-backend)



### 프로젝트 선정 이유
- 다양한 레이아웃과 여러가지 기능을 구현하면서 학습하기에 적합한 사이트라고 생각되어 선정하게 되었습니다.

### Demo Video
- https://drive.google.com/file/d/1x0dBhn2STadj-iYMPrWgG7CDr7_ViGWC/view
- https://drive.google.com/file/d/19HN7vaGPeEn3buyPKMLY9M1j57C_rYrA/view

---

### 적용 기술

- Front-End : <img src="https://img.shields.io/badge/Javscript-F7DF1E?style=flat&logo=javascript&logoColor=white"/> <img src="https://img.shields.io/badge/React.js-61DAFB?style=flat&logo=React&logoColor=white"/> <img src="https://img.shields.io/badge/sass-CC6699?style=flat&logo=sass&logoColor=white"/> <img src="https://img.shields.io/badge/React Router-CA4245?style=flat&logo=ReactRouter&logoColor=white"/> <img src="https://img.shields.io/badge/Create React App-09D3AC?style=flat&logo=CreateReactApp&logoColor=white"/>
- Back-End : <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=Node.js&logoColor=white"/> <img src="https://img.shields.io/badge/Express-000000?style=flat&logo=Express&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white"/> <img src="https://img.shields.io/badge/EC2-FF9900?style=flat&logo=AmazonEC2&logoColor=white"/> <img src="https://img.shields.io/badge/RDS-527FFF?style=flat&logo=AmazonRDS&logoColor=white"/> <img src="https://img.shields.io/badge/PostMan-FF6C37?style=flat&logo=PostMan&logoColor=white"/>
- common : <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=Git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/> <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=AmazonAWS&logoColor=white"/> <img src="https://img.shields.io/badge/ESLint-4B32C3?style=flat&logo=AmazonAWS&logoColor=white"/> <img src="https://img.shields.io/badge/Prettier-F7B93E?style=flat&logo=prettier&logoColor=white"/>
- 협업툴 : <img src="https://img.shields.io/badge/Notion-000000?style=flat&logo=Notion&logoColor=white"/> <img src="https://img.shields.io/badge/Slack-4A154B?style=flat&logo=Slack&logoColor=white"/> <img src="https://img.shields.io/badge/Trello-0052CC?style=flat&logo=Trello&logoColor=white"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=Figma&logoColor=white"/>


### 구현 기능
1. Main

<div align="center">
  
![mainpage](https://user-images.githubusercontent.com/70960594/198539167-043192e3-dc44-49b9-87a4-bd5f5c49ddb5.gif)
  
</div>

---


2. Sign Up
<div align="center">
  
  ![SignUp](https://user-images.githubusercontent.com/70960594/198539664-7788560a-4eef-4df0-98b6-5df3d357ba99.gif)
  
</div>

---

3. Sign In

<div align="center">
  
![SignIn](https://user-images.githubusercontent.com/70960594/198539736-6da97d5a-3bb9-40b2-9c94-ae52c4cbaa9a.gif)

</div>

---

4. Infinite Scroll

<div align="center">
  
![InfiniteScroll](https://user-images.githubusercontent.com/70960594/198539779-65de330b-b90f-42fc-b0e6-333ef86a5fd5.gif)

</div>

---

5. Filter

<div align="center">
  
![Filter](https://user-images.githubusercontent.com/70960594/198539823-21395c60-fb52-4765-8ca8-2913ff975a14.gif)

</div>

---

6. Categories

<div align="center">
  
![Categories](https://user-images.githubusercontent.com/70960594/198539860-22a12854-4702-4fa1-a426-36a3fa79d73a.gif)

</div>

---

7. Product Detail

<div align="center">
  
![productdetail](https://user-images.githubusercontent.com/70960594/198539907-4378365d-caa1-478f-8583-5dec44a6d492.gif)

</div>

---

8. Cart

<div align="center">
  
![Cart](https://user-images.githubusercontent.com/70960594/198539958-2ad4bf52-e89e-4c8b-91fa-d9726a47d78a.gif)

</div>

---

9. Search

<div align="center">
  
![Search](https://user-images.githubusercontent.com/70960594/198539983-01ee0550-00eb-4a9f-ab5b-fd2c4a6c6ed6.gif)
  
</div>


---
### 기능 구현 사항 (정현석)

## 무함 스크롤
1. useState를 사용해서 스크롤시 생성되는 페이지의 초기값을 생성 & 생성되는 페이지의 내용을 채우기 위해 초깃값으로 빈 배열 을 생성
2. useRef를 사용하여 페이지의 중복 생성 방지를 위해 생성 & 옵저버의 역할을 하기위해 생성
3. obsHandle 함수를 만들고 실행 내용으로는 조건값을 만족했을때 페이지가 생성되는 내용
4. 이후 new IntersectionObserver을 통해서 관찰하는 대상을 초기화 하고 observer() 메소드를 통해서 관찰자를 등록
5. 포인트로는 useEffect를 사용하여 return에 observer를 disconnect() 메소드를 통해서 관찰을 중지 시켜주는것이 중요
6. 이후 JSX문법으로 옵저버의 위치를 속성 ref를 통해 지정
7. fetch를 이용하여 쿼리스트링으로 페이지가 생성 될때마다 데이터를 새롭게 받아옴
8. 또한 받아온 데이터는 처음 만들었던 useState의 빈 배열 안에 담기게 됨

## 드롭다운
1. DropDown 컴포넌트 생성
2. 부모 컴포넌트에서 chirdren을 이용하여 DropDown컴포넌트에 들어갈 코드 작성
3. 버튼 태그 생성
4. 생성한 버튼 클릭시 Dropdown 컴포넌트의 값이 true로 전환되면서 UI에 출력
5. 다시 클릭시 UI에서 OUT

## 아코디언 기능
1. ProductAside 컴포넌트를 만든다
2. useState를 생성하여 아코디언 메뉴를 눌렀을때의 값을 넣어주기 위해 초기값을 null로 생성
3. 아코디언 메뉴 클릭시 className이 변경되며 숨겨져있는 세부내용이 UI에 나타남
4. 또 다른 아코디언 메뉴 클릭시 처음 생성했던 useState의 값이 초기값인 null로 변하면서 해당 창은 닫히고 클릭한 아코디언 메뉴의 세부내용이 표시됨
5. 상수 데이터를 생성하고 해당 데이터로 map() 함수를 통해 아코디언 메뉴 구성

## 필터링 기능
1. 백 엔드 팀원과의 소통을 통해서 쿼리 스트링의 값을 조건식을 통해서 변경
2. 버튼을 클릭시에 해당 조건값으로 쿼리 스트링의 값이 변경되면서 해당 조건을 가진 데이터가 출력됨












