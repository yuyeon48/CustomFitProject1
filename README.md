# 멋사 대학 12TH HACKATHON 
동덕여대 12기 1팀 맞춤




# 1. 서비스 소개
![맞춤 서비스](https://github.com/user-attachments/assets/a8c5818b-ef3c-4ed9-991a-bee728f84245)

맞춤형 영양 정보 비교 분석 서비스 '맞춤'은 이용자가 키워드를 선택하여 계정을 생성하면, 이용자마다 개별적인 추천 기준을 생성하여 이용자의 건강지표에 가장 알맞은 식품을 추천하는 서비스입니다. 

이용자가 계정 생성 과정에서 키워드화되어있는 신체 정보(연령, 키, 몸무게) 및 관리가 필요한 영역(근 손실, 당뇨, 비만 등)을 선택하면 서비스 내에서 해당 선택에 근거한 기준이 생성됩니다.

추후 이용자가 서비스를 이용하는 과정에서 비교가 필요한 식품을 '맞춤 건강 카트’ 기능을 통해 선택하면 키워드 기반 생성 기준에 맞춰 가장 알맞은 제품을 추천받을 수 있습니다.

즉, '맞춤'은 건강한 삶 유지에 있어 중요한 부분인 섭취와 관련하여 여러 선택지 중 가장 최선의 선택을 제공하여 이용자의 웰빙을 돕는 서비스입니다. 




# 2. 기술 스택
- 기획/디자인 : 피그마
- 프론트 : 리액트
- 백 : 파이썬, 장고
- 협업툴 : 피그마, 노션, 깃허브




# 3. 팀원 소개
|정예원|선지오|조민영|최유연|이가연|
|------|-----|------|------|------|
|기획&디자인|프론트엔드|프론트엔드|백엔드|백엔드|
|기획<br/>디자인<br/>발표|페이지<br/>백엔드 연동|페이지<br/>백엔드 연동|회원관리,추천 기준<br/>알림|맞춤 추천 기능<br/>리뷰|




# 4. 폴더 구조
all_project<br/>
└─ CustomFitProject<br/>
├─ CustomFitProject<br/>
│  ├─ settings.py<br/>
│  └─ urls.py<br/>
├─ accounts/<br/>
│  ├─ admin.py<br/>
│  ├─ apps.py<br/>
│  ├─ serializers.py<br/>
│  ├─ urls.py<br/>
│  └─ views.py<br/>
├─ customFit/<br/>
│  ├─ db.uploader.py<br/>
│  ├─ ProductDB.csv<br/>
│  ├─ admin.py<br/>
│  ├─ apps.py<br/>
│  ├─ signals.py<br/>
│  ├─ serializers.py<br/>
│  ├─ urls.py<br/>
│  └─ views.py<br/>
├─ myPage/<br/>
│  ├─ admin.py<br/>
│  ├─ apps.py<br/>
│  ├─ serializers.py<br/>
│  ├─ urls.py<br/>
│  └─ views.py<br/>
├─ frontend/<br/>
│  ├─ build/<br/>
│  └─ views.py<br/>
├─ db.sqlite3/<br/>
├─ requirements.txt/<br/>
└─ manage.py<br/>
└─ CustomFitProject<br/>

├─ customfront<br/>
├─ build/<br/>
├─ node_modukes/<br/>
├─ public/<br/>
├─ src/<br/>
│  ├─ page/<br/>
│  └─ style<br/>





# 5. 플로우 차트
![플로우차트](https://github.com/user-attachments/assets/73685e10-82a7-478e-91c0-9f17ea3aad09)

# 6. ERD
<img width="609" alt="erd" src="https://github.com/user-attachments/assets/72df50c0-2edd-4185-96a8-a770bebc46cd">

