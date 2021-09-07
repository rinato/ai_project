# ai_project

### 이전내용 저장
  1. 인코파 수강완료 4~5월 진행. 
  2. 개발환경 설정 Anaconda Navigator : jupyterlab
  
    - env 추가 :
    1) conda list : List all libraries installed in an environment.
    2) conda create –n 'name' python=3.7 : Creating a new virtual environment, 'name'. Not specifying python version? Newest one!
    3) conda env list : List all existing virtual environments.
    4) conda env remove –n 'name' : Remove the environment and all packages in it.
    5) conda activate 'name' : Entering into the virtual environment, 'name'.
    6) conda deactivate : Closing 'name' and getting out of it.
    7) conda --version : Checking anaconda version that you are using.
    8) python --version : Checking Python version that you are using.
    9) exit : Closing Anaconda prompt window
    
    - env Library추가 :
    1) pip install jupyterlab
    2) conda install tensorflow numpy pandas matplotlib seaborn scikit-learn keras
    3) jupyter extenction : jupyter labextension install my-extension my-other-extension
                          jupyter / jupyter labextension list / jupyter labextension install git
    4) jupyterlab extensions : https://jupyterlab.readthedocs.io/en/stable/user/extensions.html
  
  - 머신러닝 알고리즘 선택 가이드 : https://www.sas.com/ko_kr/solutions/ai-mic/blog/machine-learning-algorithm-cheat-sheet.html

  - 인코파 : https://kaist.edwith.org/python4ai/joinLectures/47074

### 6/8 회의
  1. 일주일에 한번 진행상황 점검
  2. 소스관리 Github 사용
  
    1) git 및 github 사용방법
        - git 설치
        - git 기본 사용법
        - git 작업 되돌리기
        - 브랜치 만들기
        - 브랜치 병합
        - 깃허브 가입 및 원격저장소 사용
        - 깃허브를 이용한 협업       
        
  3. 개발환경 구축
  4. Linear regression으로 간단한 프로젝트 각자 진행 (기한 2주)
  5. 프로젝트 문서화(Github 최대한 활용)

  - git 사용법 : https://reddb.tistory.com/145?category=948284
  - github md문서 작성방법 : https://ko.wikipedia.org/wiki/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4

### 6/15 회의
  1. 함께 할 수 있는 프로젝트
 
    1) Tensorflow 자격증(v)
        - 기출문제에 관련된 프로젝트 진행, 프로젝트 끝난 후 기출문제 풀기(기본 2주)
    2) 공모전
        - 공모전을 목표
    3) 프로젝트
        - 기획부터 개발까지 한가지 프로젝트를 목표로 진행
  2. Linear regression 간단 프로젝트 개인별 완료 후 Github에 업로드 및 공유

### 6/29 회의

  1. 진행사항 공유

    1) 현
      - jupyterlab - github 연동하여 push / pull 진행
      - ai_project내 master branch
      - https://github.com/rinato/ai_project/tree/master
      - py3.7 새로운 가상환경 설치 > Jupyterlab > Extension설치 > Node.js설치 > Git Extension > 기존 ai_project repositories에 git연동
      
    2) 화이팅
      - Linear regression을 이용한 서울 자전거 대여 예측 프로젝트 완료 및 발표
      - 독립변수 24개 > 10개 모델링으로 결과예측
      
  2. 차주 진행사항
  
    1) 현
      - 셋업한 환경에서 Linear Regression 프로젝트 진행
      - opentutorials Tensorflow 101 강의 수강 및 참고

    2) 화이팅
      - 인프런 파이썬 강의 수강을 통해 파이썬 역량 강화

  - tensowflow101 : https://opentutorials.org/module/4966

### 7/6 회의

  1. 진행사항 공유

    1) 현
      - 집 <-> 사무실간 git 사용에 익숙해짐
      - tensorflow101 7강까지 진행
    
    2) 화이팅
      - 모위딥 10강까지 진행, 파이썬 8강 진행.
      - 파이썬, 모위딥 병행하려 했으나 모위딥 선행으로
    
    3) jupyterlab보다, 클라우드 GPU지원을 받을 수 있는 구글 colab 사용하는 방향
    
  2. 차주 진행사항
    
    1) 현
      - tensorflow101 22강까지 진행, 수강완료
      - 이후 셋업한 환경에서 Linear Regression 프로젝트 진행
    
    2) 화이팅
      - 모위딥 50강까지 진행, 수강완료
     
  - 모위딥 url : https://hunkim.github.io/ml/

### 7/13 회의

  공통 목표 - 인프런강의 파이썬 머신러닝 완벽 가이드 들으면서 캐글 프로젝트 실습예제 진행
  
  1. 진행사항 공유

    1) 현
      - tensorflow101 17강까지 수강 / 실습 예제 깃허브 업로드

    2) 화이팅
      - 모위딥 50강까지 수강 완료

    3) 다다
      - 머신러닝 야학 / 인프런 파이썬 머신러닝 완벽 가이드 섹션1
      - 캐글 대회 목표
      
  2. 차주 진행사항

    1) 현
      - tensorflow101 22강까지 수강 / 프로젝트 진행 ...
      - 인프런강의 - 파이썬 머신러닝 완벽 가이드 - 섹션1 '넘파이 ndarray의 정렬과 선형대수 연산' 까지

    2) 화이팅
      - 인프런 강의 - 파이썬 머신러닝 완벽 가이드 섹션1 완료
      
    3) 다다
      - 인프런 강의 - 파이썬 머신러닝 완벽 가이드 섹션2 완료

  - tensowflow101 : https://opentutorials.org/module/4966
  - 인프런 파이썬 머신러닝 완벽 가이드 : https://www.inflearn.com/course/%ED%8C%8C%EC%9D%B4%EC%8D%AC-%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D-%EC%99%84%EB%B2%BD%EA%B0%80%EC%9D%B4%EB%93%9C

### 7/20 회의

  공통 목표 - 인프런강의 파이썬 머신러닝 완벽 가이드 들으면서 캐글 프로젝트 실습예제 진행
  
  1. 진행사항 공유
    
    1) 현
      - tensorflow101 22강까지 수강완료
      - 인프런강의 - 파이썬 머신러닝 완벽 가이드 - 섹션1 주피터 노트북 사용법과 넘파이/판다스 필요성 까지 수강
      - 캐글 내용 확인

    2) 화이팅
      - 파이썬 머신러닝 완벽 가이드 - 섹션 1 미완
    
    3) 다다
      - 선형대수학개론 - 섹션1 완강
      - 파이썬 머신러닝 완벽 가이드 - 섹션 2 미완
      
  2. 차주 진행 사항

    1) 현
      - 인프런강의 - 파이썬 머신러닝 완벽 가이드 - 섹션1 완강
    
    2) 화이팅
      - 파이썬 머신러닝 완벽가이드 -섹션 1 완강
      - 딥러닝 cnn 완벽가이드 - 섹션0, 섹션 1 완강
    
    3) 다다
      - 선형대수학개론 - 섹션 2
      - 파이썬 머신러닝 완벽 가이드 - 섹션2

  - Kaggle : https://www.kaggle.com/

### 7/27 회의

  공통 목표 - 인프런강의 파이썬 머신러닝 완벽 가이드 들으면서 캐글 프로젝트 실습예제 진행
  
  1. 진행사항 공유
    
    1) 현
      - 인프런강의 - 파이썬 머신러닝 완벽 가이드 - 섹션1 판다스 개요와 기본 API-01 까지 수강  12/123
      
    2) 화이팅
      - 파이썬 머신러닝 완벽가이드 - 섹션 1 완강
      - 딥러닝 cnn 완벽가이드 - 섹션 0, 1 완강
      
    3) 다다
      - 선형대수학개론 섹션2 완강
      - 파이썬 완벽 가이드 섹션2 미완(2강 정도 남았어요!)
      
  2. 차주 진행 사항 <<< 여름휴가 ㅎㅎ >>>

    1) 현
      - 인프런강의 - 파이썬 머신러닝 완벽 가이드 - 섹션1 완강.. 20/123
    
    2) 화이팅
      - 딥러닝 cnn 완벽가이드 - 섹션 2 완강
    
    3) 다다
      - 선형대수학개론 - 섹션 3
      - 파이썬 머신러닝 완벽가이드 섹션3

### 8/3 회의

  공통 목표 - 인프런강의 파이썬 머신러닝 완벽 가이드 들으면서 캐글 프로젝트 실습예제 진행
  
  1. 진행사항 공유 <<< 여름휴가 ㅎㅎ >>>
    
    1) 현
      - 파이썬 머신러닝 완벽 가이드 - 섹션1 판다스 개요와 기본 API-01 까지 수강  12/123
      
    2) 화이팅
      - 딥러닝 cnn 완벽가이드 - 섹션 2 - 5강까지 수강
      
    3) 다다
      - 선형대수학개론 - 섹션 3 완강
      - TensorFlow 2.0으로 배우는 딥러닝 섹션3 3강 

  2. 차주 진행 사항
    
    1) 현
      - 파이썬 머신러닝 완벽 가이드 - 섹션1 완강.. 20/123
      
    2) 화이팅
      - 딥러닝 cnn 완벽가이드 - 섹션 4 - 5강까지 수강
    
    3) 다다
      - 선형대수 섹션 4
      - 머신러닝 섹션 3

### 8/10 회의

  공통 목표 - 인프런강의 파이썬 머신러닝 완벽 가이드 들으면서 캐글 프로젝트 실습예제 진행
  
  1. 진행사항 공유

    1) 현
      - 파이썬 머신러닝 완벽 가이드 - 섹션1(넘파이, 판다스) 완강.. 20/123
      
    2) 화이팅
      - 딥러닝 cnn 완벽가이드 - 섹션3, 5강

    3) 다다
      - 선형대수학개론 섹션 4
      - 머신러닝 섹션 3

  2. 차주 진행 사항

    1) 현
      - 파이썬 머신러닝 완벽 가이드 - 섹션2(사이킷런) 25/123
      
    2) 화이팅
      - 딥러닝 cnn 완벽가이드 - 섹션3 완강
      
    3) 다다
      - 선형대수학 개론 완강(섹션6)
      - 머신러닝 섹션 3


### 8/17 회의

  공통 목표 - 인프런강의 / 캐글 프로젝트 실습예제 진행
  
  1. 진행사항 공유

    1) 현
      - 파이썬 머신러닝 완벽 가이드 - 섹션2(사이킷런) 완강 25/123
      
    2) 화이팅
      - 딥러닝 cnn 완벽가이드 - 섹션4 절반

    3) 다다
      - 선행 대수학 (4강 외)
      - 머신러닝 섹션 3

  2. 차주 진행 사항

    1) 현
      - 파이썬 머신러닝 완벽 가이드 - 섹션2 완강, 타이타닉 생존자 예측 각종 실습(사이킷런) 28/123
      
    2) 화이팅
      - 딥러닝 cnn 완벽가이드 - 섹션5 완강
      
    3) 다다
      - 파이썬 머신러닝 완벽가이드 섹션 4  
      - 선형대수학 남은 4강 마무리
      

### 8/24 회의

  공통 목표 - 인프런강의 / 캐글 프로젝트 실습예제 진행
  
  1. 진행사항 공유

    1) 현
      - (진행)파이썬 머신러닝 완벽 가이드 - 섹션2(사이킷런) 완강 28/123
      - (목표)섹션3-1,2,3,4,5 진행 33/123
      
    2) 화이팅
      - (진행)딥러닝 cnn 완벽가이드 - 섹션5-8강 완료
      - (목표)딥러닝 cnn 완벽가이드 - 섹션6 완강
    3) 다다
      - (진행)선행 대수학 완강
      - (진행)파이썬 머신러닝 완벽 가이드 4강 완강
      - (목표)파이썬 머신러닝 완벽 가이드 4강 완강

### 8/31 회의

### 9/07 회의

  공통 목표 - 결과물을 낼 수 있는 프로젝트 고민
  (kaggle 대회와 같이 머신러닝 알고리즘을 사용해 데이터에서 유의미한 패턴을 뽑아내는 프로젝트)
  
  1. 진행사항 공유

    1) 현
      - (진행)파이썬 머신러닝 완벽 가이드 - 섹션3-2 완료 30/123
      - (목표)파이썬 머신러닝 완벽 가이드 - 섹션3 완강 36/123
      
    2) 화이팅
      - (진행)딥러닝 cnn 완벽가이드 - 
      - (목표)딥러닝 cnn 완벽가이드 - 
      
    3) 다다
      - (진행)파이썬 머신러닝 완벽 가이드 - 
      - (목표)파이썬 머신러닝 완벽 가이드 - 
