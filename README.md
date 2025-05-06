1. Github Desktop설치 (윈도우용)  
- github 회원가입 필수   
- 레포지토리 ([https://github.com/ParkJiSu28/i-onecar](https://github.com/ParkJiSu28/i-onecar))


2. 기본 브랜치 구성  
- root : main  
  \-  develop   
  \-  feature, design, plan 

3. 브랜치 설명  
- main :  배포 소스코드  
- develop : 다음 배포를 위한 개발서버 소스코드

4. 배포 예시  
- 개발자 : feature/기능명: 개발자 기능 구현 (예: feature/user-auth)  
- 디자이너 : design/디자인명: 디자이너 UI 작업 (예: design/main-page)  
- 기획자 : plan/기획명: 기획자 문서 작업 (예: plan/api-spec)

5. 배포 방법  
1) GitHub Desktop에서 develop 브랜치 체크아웃  
2) Branch → New branch로 feature/login 생성(예시)  
3) 로컬에서 코드 수정 후 변경사항 커밋  
4) Push origin으로 원격 저장소에 업로드  
5) Branch → Create Pull Request 클릭  
6) GitHub 웹에서 base: develop ← compare: feature/login 확인  
7) 리뷰어 지정 후 풀리퀘스트 생성

     