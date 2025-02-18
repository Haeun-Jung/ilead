# 아이리드(ILead)🖼

### "아이가 리드하는 동화"

> 아이가 직접 동화 속을 경험하는 동화 체험 서비스
<br>

## 1. 서비스 개요

### 😮 기획 배경

- 12세 이하의 아이를 키우는 부모님 약 50명을 대상으로 진행한 설문조사 결과
  ![기획배경](https://user-images.githubusercontent.com/81166378/172042757-03a83d67-1444-4b4f-bd2b-c1faad135eb1.png)
- 아이를 키우는 부모님들의 공통적인 어려움! 바로 아이에게 동화를 소리내서 반복적으로 읽어주어야 한다는 것입니다. 때문에 동화를 읽어주는 유튜브 음원 등을 많이 이용하고 있습니다.
  - **동화를 단순히 읽고 보고 듣는 것을 넘어서 `등장 인물과 대화하면서 동화를 이끌어갈 수 있다면` 어떨까요?**

### 🎯 대상

    ✔ 동화를 책으로 읽는 것이 지겨운 아이들
    ✔ 동화속 등장인물들과 대화하고 싶은 아이들
    ✔ 아이에게 매번 동화를 읽어주는 것이 부담스러운 부모님

### ⭐ 목적

    - 아이들이 직접 동화 속 등장인물들과 상호작용하면서 동화를 이끌어가도록 하자.
    - 동화책을 매번 읽어주는 부모님들의 부담을 줄여주자.

<br>

## 2. 프로젝트 개요

### 1) 기간

    2022. 4. 11. ~ 2022. 5. 20.(기획 2주, 설계 1주, 개발 3주)

### 2) 인원

    6명

### 3) 주요 기능

|구분|기능|설명|비고|
|:---|:---|:---|:---|
|1|캐릭터 선택|16가지의 캐릭터 중 원하는 캐릭터를 선택할 수 있다.||
|2|튜토리얼|게임이 어려운 아이는 동화를 플레이할 수 있는 조작 방법을 익힐 수 있다.||
|3|동화 선택|동화 선택 맵에서 직접 움직여 플레이하고 싶은 동화를 선택할 수 있다.||
|4|동화 플레이|동화를 진행하는 데 필요한 일러스트, 자막 및 더빙을 제공한다.<br>간단한 단어를 직접 말하면서 말하기 연습을 할 수 있다.<br>모바일에서는 모바일용 조이스틱을 통해 조작할 수 있다.<br>동화 속 주인공을 도와주는 다양한 미션을 수행할 수 있다.||
|5|기념 촬영|등장인물과의 기념 촬영을 통해 몰입감을 더할 수 있다.||


### 4) 기술스택

- **Game**: **Unity**, blender
- **Frontend: React, TypeScript, Material UI**

![Architecture](https://user-images.githubusercontent.com/37528765/169279252-c14e0e0c-7cab-47ac-854e-9e6629b64076.png)

### 5) 역할 `Frontend` `Unity`

#### Landing 페이지 구현

- 아이리드를 간단히 소개하는 Landing 페이지를 구현하였습니다.
- 애니메이션 동작을 추가하여 생동감을 더하였습니다.

#### WebGL 빌드

- 웹에서 Unity가 열릴 수 있도록 WebGL로 빌드하였습니다.

#### 동화 맵 구현

- 아기 돼지 삼형제의 맵 일부를 구현하였습니다.

<br>

## 3. 기능 소개

### 1) Landing 페이지

- 아이리드의 장점과 컨텐츠에 대한 소개

<img src="https://user-images.githubusercontent.com/81166378/172043731-8e7d5f31-f5c3-46de-bcdc-5d285cffc652.gif" width="500">

---

### 2) 캐릭터 선택

- 동화 속 주인공을 도와줄 나의 캐릭터 선택
- 동화 속 주인공들에게 알려줄 나의 이름 입력

<img src="https://user-images.githubusercontent.com/81166378/172043818-f7f27a97-ca64-4546-898b-9a41eee047e0.gif" width="500">

---

### 3) 튜토리얼

- 키 조작법을 배우기 위한 튜토리얼

<img src="https://user-images.githubusercontent.com/81166378/172043842-49af00a7-d8e5-4273-b924-e87c31ad61b3.gif" width="500">

<img src="https://user-images.githubusercontent.com/81166378/172043940-23418ed3-5688-4a55-b69f-eadd1cadb230.gif" width="500">

---

### 4) 동화 선택

- 플레이하고 싶은 동화를 선택하여 이동

<img src="https://user-images.githubusercontent.com/37528765/169278422-1ff2149d-8a35-45e7-8472-1e07774f4ca4.JPG" width="500">

<img src="https://user-images.githubusercontent.com/81166378/172044019-1e23b82c-7541-4c6a-b55c-85d849d5f153.gif" width="500">

---

### 5) 동화 플레이

▶ 동화 전개를 위한 일러스트, 자막, 더빙

<img src="https://user-images.githubusercontent.com/81166378/172044062-6509a561-d990-4c92-85fb-06aa76812896.gif" width="500">

<img src="https://user-images.githubusercontent.com/81166378/172044067-8f90fc38-216d-46f7-9fce-507fb0ea36ac.gif" width="500">

<br>

🐷 아기 돼지 삼형제

▶ 아기 돼지와 함께 재료를 모아 집짓기

<img src="https://user-images.githubusercontent.com/81166378/172044166-9e68ce69-8123-4d83-b09e-af389e1d6534.gif" width="500">

<img src="https://user-images.githubusercontent.com/81166378/172044168-2c0ce1c2-cd6f-4134-a874-52432f4c361a.gif" width="500">

▶ 늑대가 나타났다고 알려주기

<img src="https://user-images.githubusercontent.com/81166378/172044210-da6e3556-2bb0-4696-bc06-179dbded269f.gif" width="500">

▶ 벽난로에 불 피워 늑대 쫒아내기

<img src="https://user-images.githubusercontent.com/81166378/172044242-d3931cc2-af61-4bbc-8a2f-ca9c2dcf9690.gif" width="500">

<br>

🍩 헨젤과 그레텔

▶ 헨젤과 그레텔에게 길 알려주기

<img src="https://user-images.githubusercontent.com/81166378/172044322-452e188f-f682-4c0c-aa5c-313c1af145b2.gif" width="500">

▶ 헨젤, 그레텔과 함께 과자 먹기

<img src="https://user-images.githubusercontent.com/81166378/172044346-19444a09-0427-4ff6-971c-be68d816afa8.gif" width="500">

▶ 솥에 불을 피워 마녀를 물리치자

<img src="https://user-images.githubusercontent.com/81166378/172044390-bdfd4953-d087-461e-bfe6-b167035a898a.gif" width="500">

<img src="https://user-images.githubusercontent.com/81166378/172044392-91da0b3e-a3a5-4e05-adb0-6a0d0d8bf28e.gif" width="500">

---

### 6) 기념촬영

- 동화속 등장인물과 기념촬영 할 수 있습니다.

<img src="https://user-images.githubusercontent.com/81166378/172044433-a6e9108e-be34-4651-8bf7-a0314687bb12.png" width="500">

<br>

## 4. Team

<br>

| <img src="https://user-images.githubusercontent.com/53832553/154294418-3be4d2dd-81f5-4376-84a7-89c037ed73f2.png"  width="150" height="150"/> | <img src="https://user-images.githubusercontent.com/53832553/154294666-905e7da1-b8fd-463d-aba8-84b243a71acc.png"  width="150" height="150"/> | <img src="https://user-images.githubusercontent.com/53832553/154294596-5cfd74c8-0b0d-4d12-b965-6395d2949c09.png"  width="150" height="150"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------: |
|                                                                  👑곽현준👑                                                                  |                                                                    권오범                                                                    |                                                                    박민주                                                                    |

| <img src="https://user-images.githubusercontent.com/53832553/154294716-d449a9af-8419-4cef-906e-a802320217fb.png"  width="150" height="150"/> | <img src="https://user-images.githubusercontent.com/37528765/161694976-0c06cf4f-28a9-4eab-8293-6c4de05bde3d.jpg"  width="150" height="150"/> | <img src="https://user-images.githubusercontent.com/53832553/154294097-01760928-93ac-479e-b9f9-160ba9d5c1b1.png"  width="150" height="150"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------: |
|                                                                    박혜준                                                                    |                                                                    신미래                                                                    |                                                                    정하은                                                                    |

<br>

## 5. 프로젝트 진행

### 1) Plastic SCM

- Unity의 버전 및 소스 관리 툴인 Plastic SCM을 이용하여 프로젝트를 진행했습니다.
- 각자 맡은 기능에 맞게 브랜치를 생성하고, 완료된 기능은 `main` 에 merge하여 테스트를 수행했습니다.

![plastic scm](https://user-images.githubusercontent.com/81166378/172044711-7325c214-e616-4431-8239-b11dea9ed3fe.gif)

<br>

### 2) Jira

- 매주 월요일 오전, 이전 주에 진행된 내용을 공유하고 일주일 동안 진행되어야 할 이슈를 백로그에 등록했습니다.
- 에픽은 `기획`, `프로젝트`, `라이브 방송`, `발표` 등으로 구성했습니다.
- 스토리는 `모바일 조이스틱`, `헨젤과 그레텔 퀘스트` 등 세부 기능 단위로 작성하였으며, 스토리를 완료하기 위한 작은 업무 단위(`모바일 조이스틱 줍기 추가`, `퀘스트 - 아이템 드롭` 등)를 추가하여 구성했습니다.

<br>

### 3) 협업 툴

- Notion
- Figma
- Jira
- Webex
- Mattermost
- Discord
- GitLab
- Postman

<br>

## 6. 개선할 점

    ✔ 다중접속을 통해 다른 사람들과 협동하여 진행
    ✔ 자동진행

## 7. 수상 내역

    🏆 삼성 청년 SW 아카데미(SSAFY) 자율 프로젝트 우수상 수상

<img src="https://user-images.githubusercontent.com/81166378/174917148-3db84c6f-401b-4550-94bf-62fed153d948.jpg" width="50%">
