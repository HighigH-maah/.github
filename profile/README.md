# 💳 Ma:ah 카드 서비스란?

> 보유 카드를 하나로 묶어 사용할 수 있는 슈퍼카드 서비스

## 💳 Ma:ah 카드 서비스 특징

- 카드 실적 분배
  - 슈퍼 카드(**하이카드**)를 통해 결제한 실적을 개별 카드에 분배하는 시스템을 구축, 개별 카드의 혜택을 자유롭게 누린다
- 카드 비교
  - **하이카드**에 등록할 개별 카드(**바이카드**)를 손쉽게 신청할 수 있도록 타 카드사와 마하카드의 카드 비교 서비스를 제공한다

# 💳 조원소개

<table>
  <tbody>
    <tr/>
      <td align="center"><a href="https://github.com/StarrFnl"><img src="https://github.com/HighigH-maah/.github/assets/144782356/5264124f-609c-4e23-be75-dd09fc8d1c0c" width="100px;" alt=""/><br /><sub><b>김현성</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/ksweeni"><img src="https://github.com/HighigH-maah/.github/assets/144782356/4a71f813-08ed-4ca4-bcaf-890aba45a580" width="100px;" alt=""/><br /><sub><b>김수인</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/yu4923"><img src="https://github.com/HighigH-maah/.github/assets/144782356/ff45b588-6563-4978-aedf-6c66c771aae0" width="100px;" alt=""/><br /><sub><b>김태완</b></sub></a><br /></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/wldms819"><img src="https://github.com/HighigH-maah/.github/assets/144782356/54ef0949-4f92-4ac0-aa27-13b16d889ec7" width="100px;" alt=""/><br /><sub><b>박지은</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/mmmmmam"><img src="https://github.com/HighigH-maah/.github/assets/144782356/252f1271-c33d-4a30-879f-b297852d0367" width="100px;" alt=""/><br /><sub><b>한마음</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>

# 💳 ERD 설계

![postgres - public](https://github.com/HighigH-maah/.github/assets/89927567/61dfeaa4-6327-4ec2-8b83-867e8a419b90)

# 💳 페이지 및 기능 구성

### 💱 분배

- 하이카드에 쌓인 포인트를 바이카드에 분배할 수 있는 페이지

  - 하이카드와 바이카드에 들어있는 혜택을 확인
    <img src="https://github.com/HighigH-maah/.github/assets/89927567/f6642d43-2ab5-48c4-a514-a2b12757808e" width="70%">

  - 혜택 요건에 맞춰 바이카드에 포인트를 분배  
    <img src="https://github.com/HighigH-maah/.github/assets/89927567/98a9a43c-b4f0-4533-8c2b-5a7bd11675fe" width="70%">

### 🖧 배포

- 개별 작업을 Github를 통해 관리하고, main branch에 push할 시 GitHub Actions를 통해  
  Azure의 정적 웹페이지(front)와 웹서버(back)에 배포  
  ![Group 1000003347 (1)](https://github.com/HighigH-maah/.github/assets/89927567/80e46bc2-605c-434e-ab55-4c5d17ab241e)

### 🌈 About Us

- Ma:ah 카드 서비스 소개

  - Ma:ah 카드 서비스의 핵심인 CREATE, SHARE, BENEFITS를 소개
    <img src="https://github.com/HighigH-maah/.github/assets/80210564/4e83748d-a192-40c9-a2e3-26652fabdc37" width="70%">

### 🌈 메인

- 서비스 메인 페이지

  - 광고배너/회원정보, 하이카드 종류, 하이카드 신청, 바이카드 신청, 하이카드 특징 으로 구성
    <img src="https://github.com/HighigH-maah/.github/assets/144782356/74ed21c0-19ff-4624-85e4-74ba6d77b3c5" width="70%">

### 👛 카드목록 조회

- 하이카드 및 바이카드, 소유카드 목록 조회 페이지

  - 소유카드를 바이카드로 등록/해제, 카드 상세페이지 이동, 연결계좌 변경
    <img src="https://github.com/HighigH-maah/.github/assets/144782356/bdfd1901-7198-4388-8e6d-b78d1e6d9094" width="70%">

### 👛 카드상세

- 하이카드 및 바이카드 상세 페이지

  - 카드 혜택 확인 및 카드 신청
     
    <img src="https://github.com/HighigH-maah/.github/assets/80210564/f688ce4a-37ad-4a17-9e83-d0760590f451" width="70%">

### 💳 카드 신청

- 하이카드 신청 페이지

  - 하이카드/바이카드 신청 과정 (본인인증, 신분증 인증, 계좌 인증 등으로 구성)
    <img src="https://github.com/HighigH-maah/.github/assets/100287621/b48c55ca-116d-4346-b75f-4775db721ed5" width="70%">


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
