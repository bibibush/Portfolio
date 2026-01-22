# 김진형 Portfolio

## 소개
>프로그램을 개발할 때, '지금은 많은 사람들이 이 코드를 당연하게 사용하지만, 처음 이 코드를 작성한 사람은 무슨 생각으로 작성했을까? '
> 라는 질문을 저 자신에게 많이 합니다.
> 
> 쉬운 코딩은 그만큼 효율성이 높은 코드라는 생각을 갖고 효율적인 코드를 만들기 위해 끊임없이 탐구하는 개발자입니다.

<br />

## 프로젝트

### (Next.js) 프로젝트 관리 웹사이트

> 웹사이트 : https://projecttodo.store
>
> 
> 기간 : 2025년 02월
>
> 상세 설명 : https://github.com/bibibush/project-todo
>
> 사용 기술: Typescript, Next.js:15.1, React-Hook-Form, Tanstack Query:v5, Shadcn Ui, Tailwindcss, Auth.js, Postgresql, Prisma,
> Docker, Nginx, Aws EC2, vercel

<br />

- auth.js를 사용한 JWT 인증 구현
  
- next.js의 병렬 라우팅을 통해 인증 상태에 따라 ui 구분 구현
  
- revalidatePath를 통해 캐시 설정 무효화 구현
  
- server action, react query의 프리패치를 사용해 더 빠른 성능의 react query 구현
  
- next.js의 server components, server action 그리고 prisma를 사용해 백엔드 로직 구현
  
- React.memo, useMemo, useCallback을 사용해 렌더링 최적화 구현
  
- nginx와 certbot을 사용해 리버스 프록시 구현 및 스태틱 파일 서빙, ssl인증 설정

- docker(Dockerfile, docker-compose.yml)을 사용해 EC2에 배포

- 기존 EC2배포에서 프리티어 만료로 vercel로 이전

---
<br />

### (webpack) 인터넷 속도 계기판

> 기간: 2025년 11월
>
> 상세 설명: https://github.com/bibibush/internet_speed
>
> 사용 기술: typescript, scss, express.js, webpack

<br />

- webpack기반 ssg방식 렌더링 구현
- webpack 기반 프론트엔드 + 백엔드 동시 서빙 구현
- 클라이언트와 서버의 요청 RTT 측정을 통한 ping, download, upload 속도 측정 로직 구현 완료

---
<br />

### (Django, React)증권 대시보드 웹사이트

> 웹사이트 : https://foxstocks.site (aws 프리티어 만료로 인해 당분간 사이트 다운)
> 
> 
> 기간 : 2024년 12월
> 
> 프론트엔드 상세 설명 : https://github.com/bibibush/react-vite-frontend
> 
> 백엔드 상세 설명 : https://github.com/bibibush/Foxstocks_Django_backend
> 
> 사용 기술: Typescript, React:18.3, React-Hook-Form, Tanstack Query:v5, Shadcn UI, Zustand, Postgresql, Django:5.1,
> Django Rest Framework, beautifulSoup4, pandas, Docker, Nginx, Aws EC2

<br />

- react-cookie, zustand, djangorestframework-simplejwt를 이용한 JWT인증방식 구현

- 네이버 증권을 크롤링 하여 차트 및 데이터 테이블 구현

- react-hook-form을 사용한 클라이언트에서 폼 유효성 검사 실행

- tanstack-query를 이용한 서버상태(server state) 관리

- zustand를 이용한 전역 클라이언트 상태 관리

- URL객체를 이용한 이미지 미리보기 구현

- Django의 media_url을 이용한 미디어 파일들 서빙

- Django의 메타모델을 사용해 유일성 제한 구현

- aws s3를 사용해 프론트엔드 정적파일들 배포

- nginx와 certbot을 사용해 리버스 프록시 구현 및 스태틱 파일 서빙, ssl인증 설정

- docker(Dockerfile, docker-compose.yml)을 사용해 EC2에 배포

- github-action과 ssh-action을 사용해 CI/CD 구현

---
<br />

### Salaisons de la Brèche 웹사이트

> 기간 : 2023년 1월 - 2023년 11월
>
> 
> 프로젝트 상세 설명 : https://github.com/bibibush/salaisons-de-la-breche
> 
>
> 사용 기술: React, Django:4.2, Python:3.11, sqlite3

<br />

- 고품질 재료와 전통적인 방법을 사용한 제품생산이라는 사실을 강조하는 웹사이트 개발


- 프론트엔드에서 React를 사용해 제품소개 및 문의하기 페이지에 고객들이
쉽게 도달할 수 있도록 설계


- 백엔드 서버에서는 문의하기, login, 달력으로 주문 관리, 첨부파일
다운로드와 전송 등의 기능 구현


- 달력으로 주문 관리 및 첨부파일 다운로드와 전송, 주문 정보 보내기 기능은
2024년 12월 서비스될 예정

---
<br />

### 생산 계획서 자동화 프로그램 개발

> 기간 : 2023년 8월 - 2023년 10월
>
> 
> 프로젝트 상세 설명 : https://github.com/bibibush/Automatisation
>
>
> 사용 기술 : Python:3.11, Xlwings, tkinter, pyautogui

<br />

- 엑셀로 된 재고서를 자동 실행한 뒤 데이터를 가져와 파이썬 코드로 된 계산식을 실행하는
프로그램 개발


- tkinter GUI를 사용해 버튼만 누르면 동작하는 실행 파일로 사용할 수 있도록 개발

---
<br />

### 라벨 제작 자동화 프로그램 개발

> 기간 : 2023년 10월 - 2023년 12월
>
> 
> 프로젝트 상세 설명 : https://github.com/bibibush/Etiquettes
>
>
> 사용 기술 : Python:3.11, Xlwings, tkinter, pyautogui

<br />

- 포장 박스 크기에 맞게 제품들의 개수를 담은 라벨 작성 자동화 개발


- 엑셀로 된 주문서를 자동 계산하여 데이터 표 자동 작성

---
