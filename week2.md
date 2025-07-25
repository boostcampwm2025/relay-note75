## 주제
**부스트캠프 커뮤니티 또는 개발자로서 학습과 성장을 위해 AI 활용하기**

---

## week1 팀원들이 고민한 문제

> 개발자로서 지속적인 학습과 회고는 중요한데, 이를 어떻게 AI와 함께 루틴화할 수 있을까?

AI를 단순 보조 도구가 아닌, **성장을 위한 동료**로 활용해보고자 다음과 같은 고민을 했습니다.

- 회고나 학습 내용을 정리해도 피드백 받기가 어렵다.
- 내가 무엇을 배우고 있는지 정리할 시간이 부족하다.
- 감정적 상태나 집중력이 학습에 영향을 주는데, 이걸 어떻게 인지할 수 있을까?
- 다양한 AI 도구가 있는데도 실제로 어떻게 써야 할지 막막하다.

---


## 우리가 만든 퀘스트 (WEEK2)
### 1. 학습정리 기반 노래 생성하기

- 목적 : 학습정리한 내용을 가지고 AI를 활용해서 가사를 만들고 이를 AI를 활용해서 노래를 만들어서 복습하기

- 실행 방법 :
  1. AI를 활용해서 학습정리한 내용을 가사로 만들어 달라고 요청하기
      ```txt
          첨부한 학습정리.md 파일을 토대로 요약정리해서 인디밴드 스타일의 가사로 만들어줘
      ``
  2. 만들어진 가사를 토대로 AI를 활용해서 노래로 만들기
    
      <img width="678" height="722" alt="Image" src="https://github.com/user-attachments/assets/4c8c18fb-cfe6-4cab-ab4e-5d073456c410" />
      
      - 노래로 만들어주는 링크 예시 : https://www.aisongmaker.io/ko
      
      - 가사에 AI가 만든 가사 첨부 후에 제목하고 노래 스타일을 지정해서 노래로 만들기

   
   - 달성기준 : 만든 노래를 가지고 링크 공유하기 


   - 예시 노래 링크 : 
        - https://storage.aisongmaker.io/audio/04a70643-acbb-4f1e-94b2-73360130cd39.mp3
        - https://storage.aisongmaker.io/audio/325b4516-d5be-4c38-9a3d-7c45d69aacc4.mp3

### 2. 에러 메시지를 예술 작품으로 만들기
- 목적:
   
   - 에러 경험을 재해석해 창작물로 바꾸는 재미 느끼기
   
   - 개발자만 알 수 있는 에러의 밈을 웃음으로 풀어내고 힐링하기

- 실행 방법:
   
   - 미션 수행 중 마주치는 여러 에러 메시지를 이용하여 추상적인 이미지 생성
      ```txt
      // 프롬포트 예시 1
      "Segmentation Fault", broken labyrinth, glitch art style, 
      neon colors, high resolution, digital painting
      ```
      ```txt
      // 프롬포트 예시 2
      "Blue Screen of Death", a sleepy cat laying on a crashed computer, 
      cute cozy vibe, warm lighting, kawaii illustration style
      ```  

- 달성 기준
   
   - 이미지 생성 후 공유하기 좋은 이미지는 Slack에 공유
   
   
   - 팀원들에게 생성한 이미지를 공유하며 웃음 나누기
- 추천 모델
   
   
   - Mage.space - 무료
- 예시 이미지
   
   ![Image](https://github.com/user-attachments/assets/2181b87c-aa24-4f0e-964f-6bc8cb36c6fe)
   
   ![Image](https://github.com/user-attachments/assets/3a4624af-dd6f-4d12-976c-2c7415f92ee6)

### 3. gist 홍보 포스터 만들기
    
- 목적 : 본인이 작성한 gist에 다른 캠퍼들의 방문을 유도하여 피드백 받기

- 실행방법 :
    1. AI(DALL·E 3 등)에 학습 정리를 복사하고 홍보 포스터 만들어 달라고 하기
        ```txt
        ...(학습 정리 내용)
        위의 내용을 바탕으로 홍보 포스터 이미지 만들어줘.
        ```
    2. 만들어진 이미지를 매일마다 슬랙에 공유하여 피드백 받기

- 예시 이미지
  
  <img width="412" height="613" alt="Image" src="https://github.com/user-attachments/assets/de60200d-5479-46ee-85a0-bfa57694df73" />

### 4. 오늘 회고, AI가 대신 질문
- 목적:
  
  - 이번 주 학습한 내용을 바탕으로 AI가 질문자 역할을 수행한다.
  
  - AI가 나에게 회고를 이끌어주는 인터뷰어가 된다.

- **퀘스트 수행방법**
  
  1. 이번주 학습한 내용을 정리해서 입력한다.
  
  2. AI에게 아래와 같이 요청한다:
     ```txt
     이게 내가 오늘 학습한 내용이야:
     - 멀티스레딩
     - 비동기 프로그래밍  
     - 동시성 프로그래밍
     이 내용을 바탕으로, 내가 더 깊게 회고할 수 있도록  
     질문 5~7개를 인터뷰 형식으로 던져줘.  
     기계적 요약이 아니라, 생각을 이끌고 확장하는 질문이면 좋겠어.
     ```
  3. AI가 던진 질문에 대답하며 회고 작성 후에 슬랙에 회고를 공유한다.

## 우리가 기대하는 효과
- 더 인상적인 방법으로 학습내용 점검 및 복습하기
- GIST 홍보포스터를 만들어서 어떤 것에 관한 내용인지 시각적으로 쉽게 파악하기 
- 다양한 AI 도구들을 목적에 맞게 활용하는 경험 쌓기
- 에러메시지에 대한 이미지를 생성하면 해당 에러메시지의 상황을 다시 한번 돌아보기
- AI에게 질문을 받는 형식으로 학습 내용에 대해서 회고하기

## 과제 수행 내역

<details>
  
  <summary>S035</summary>

  #### 퀘스트: 학습정리 기반 노래 생성하기
  
  
</details>

<details>
  
  <summary>J217</summary>

  #### 퀘스트: 에러 메시지를 예술 작품으로 만들기
  
  
</details>

<details>
  
  <summary>J247</summary>

  #### 퀘스트: 에러 메시지를 예술 작품으로 만들기
  
  
</details>

<details>
  
  <summary>J273</summary>

  #### 퀘스트: gist 홍보 포스터 만들기
  
  
</details>
