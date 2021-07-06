# ai_project

### 이전내용 저장
  1. 인코파 url : https://kaist.edwith.org/python4ai/joinLectures/47074
  2. Anaconda Navigator : env 추가
  
    1) conda list : List all libraries installed in an environment.
    2) conda create –n 'name' python=3.7 : Creating a new virtual environment, 'name'. Not specifying python version? Newest one!
    3) conda env list : List all existing virtual environments.
    4) conda env remove –n 'name' : Remove the environment and all packages in it.
    5) conda activate 'name' : Entering into the virtual environment, 'name'.
    6) conda deactivate : Closing 'name' and getting out of it.
    7) conda --version : Checking anaconda version that you are using.
    8) python --version : Checking Python version that you are using.
    9) exit : Closing Anaconda prompt window
    
  3. env Library추가 :

    1) pip install jupyterlab
    2) conda install tensorflow numpy pandas matplotlib seaborn scikit-learn keras
    3) jupyter extenction : jupyter labextension install my-extension my-other-extension
                          jupyter / jupyter labextension list / jupyter labextension install git

  4. jupyterlab extensions : https://jupyterlab.readthedocs.io/en/stable/user/extensions.html
  5. 머신러닝 알고리즘 선택 가이드 : https://www.sas.com/ko_kr/solutions/ai-mic/blog/machine-learning-algorithm-cheat-sheet.html

### 6/8 회의
  1. 일주일에 한번 진행상황 점검
  2. 소스관리 Github 사용
  
    1) git 및 github 사용방법
        https://reddb.tistory.com/145?category=948284
        - git 설치
        - git 기본 사용법
        - git 작업 되돌리기
        - 브랜치 만들기
        - 브랜치 병합
        - 깃허브 가입 및 원격저장소 사용
        - 깃허브를 이용한 협업
    2) md문서 작성 방법
        https://ko.wikipedia.org/wiki/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4

  3. 개발환경 구축
  4. Linear regression으로 간단한 프로젝트 각자 진행 (기한 2주)
  5. 프로젝트 문서화(Github 최대한 활용)

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
 
    1) 나현 - jupyterlab - github 연동하여 push / pull 진행
      - ai_project내 master branch
      - https://github.com/rinato/ai_project/tree/master
      - py3.7 새로운 가상환경 설치 > Jupyterlab > Extension설치 > Node.js설치 > Git Extension > 기존 ai_project repositories에 git연동
    2) 이지윤 - Linear regression을 이용한 서울 자전거 대여 예측 프로젝트 완료 및 발표
      - 독립변수 24개 > 10개 모델링으로 결과예측
      
  2. 차주 진행사항
  
    1) 나현 - 셋업한 환경에서 Linear Regression 프로젝트 진행
      - opentutorials Tensorflow 101 강의 수강 및 참고
      - https://opentutorials.org/module/4966
    2) 이지윤 - 인프런 파이썬 강의 수강을 통해 파이썬 역량 강화
