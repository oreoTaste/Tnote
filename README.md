# T-Note


운영 도메인: http://t-note.kro.kr/



=== 2024/09/10 회의 내용 ===
1) 환경구성
  - github (하는게 좋을듯 ~9/24) 건수
  - lib들 설치 (이건 진행하면서)
  - db mysql (UI상 필요하다면?) (~9/24) 나
  + 필요하다면 테이블도...( 화면에서 이전요약들 볼수 있게하는정도의 역할?) (~9/24) 나 
추가의견 : 기존의 요약정보만 db에 들어가니까 현재 화면에 보여지는 여러 정보는 바로 문서로 저장하는 정도? 

1) UI
  - 구성 (메인페이지 + 서브페이지 구성을 어떻게 가져갈 것인지 대략적인 안) (~9/24) 다같이 하는데, 초안을 내가 올릴테니 계속 의견수렴해서 수정, 카카오 오븐)
  - 구현 (실제 화면 구현인데 streamlit 은 기능이랑 묶어서 됨)
  - 추가의견 : 요약하는 전 과정을 순서에따라 화면에 출력해주는 기능을 넣으면 멋있지 않을까?
  - 로딩화면에 전 과정 텍스트를 보여줄 수 있다면?

2) 핵심기술
 - STT - (naver stt 파이썬으로 만들기 ~ 9/24) 건수 승연
 - 데이터클라우드 
 - 형태소분석 : 그냥 형태소분석만하고 끝나는게 아니라 UI까지
 - bow : 이것도 UI까지
 - TF-IDF : 이것도 UI까지
 - LDA : 이것도 UI까지 : 주제선정관련
 - K-means : 이것도 UI까지

3) 메인페이지 
 - 요약 : 핵심기능
 - 주제 : 키워드 or 한줄요약 
 - 화자별 : 요약 / 키워드(가장중요한 단어) / 부정긍정
 - 기능1 : 업로드 (~9/24) 건수 승연
 - 기능2 : 다운로드 (회의록 완성본을 pdf 등의 문서로 : 화면에 있는내용은 나중에 정하고 우선 PDF로 뽑는 기능) (~9/24) 찬명 
 - 기능3 : 회의록 요약 리스트 

4) LKUE 및 회의요약 등 교육마무리 후 알아오기 (~9/24) 찬명, 승연, 건수 
 - 요약/주제/머신러닝?/모델? 등 관련된거 전부 확실하게