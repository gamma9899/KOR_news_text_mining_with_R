# KOR_news_text_mining_with_R
1. 개요 :

R언어를 활용한 한국어 뉴스 텍스트 마이닝 프로젝트입니다.

2. 사전 필요 작업 :
(OS 환경을 Windows 기준으로 설명합니다. mac, linux, WSL 등은 자력으로 환경을 갖추시기 바랍니다.) 
2-1.  Java 언어 개발 패키지인 JDK를 R에서 활용할 수 있게 해주는 rJava, 웹 개발 도구 셀레니움을 R에서 활용할 수 있게 해주는 RSelenium, 그외 Konlp 등의 기타 라이브러리들을 사용했습니다. 각각의 라이브러리 설치 방법은 기본적으로(install.packages('') 명령어 사용) 주석에 기술해 놓았으나, rJava, Konlp 등의 일부 라이브러리들은 고유한 설치 방법을 갖습니다.

2-2.  상기의 r_selenium 폴더를 c:\ 경로에 넣으세요. 이후 c:\r_selenium 폴더의 셀레니움 구동방법.txt 파일을 보면 windows 명령어 프롬프트(cmd)를 실행해 셀레니움을 구동하는 명령어를 입력하는 방법이 명시되어 있습니다. 이를 따라해, 셀레니움을 구동하고 있는 상태에서 Rselenium 관련 라이브러리 및 코드를 실행해야 정상적으로 실행됩니다. 

3. 프로젝트 코드 설명 : 

본 프로젝트는 총 2개의 기능과 이를 구현하기위한 각 코드 파일들(Project 1, Project 2)로 나뉘어져 있습니다. 

Project 1 은 네이버 랭킹뉴스 페이지를 대상으로 뉴스 및 댓글 크롤링 작업과 이를 대상으로한 전처리, TF-IDF, 잠재적 디리클레 할당 토픽모델링(LDA), 감성분석을,

Project 2 는 빅카인즈 뉴스 빅데이터 대상 전처리, 구조적 토픽모델링(STM) 및 의미연결망(중심성, 군집분석)분석, 그리고 QAP 상관/회귀분석 분석을 실시하였습니다.

본 프로젝트는 MIT 라이선스를 따릅니다. 

This project follows the MIT License

제작 : 강대한

Made by Kang Dae Han

E-mail : gamma9899@gmail.com

