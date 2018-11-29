# OpenSource A-Team  
# 20154300 임대인  - DB, 소켓통신, GUI 구현 및 연동  
# 20154295 강성민  - 디자인, DB 데이터 관리
# 20154219 조휘훈  - 발표, DB 데이터 관리, 서버 GUI 구현  

2018-11-10 GUI 구현 및 서버와 GUI 연동    
2018-11-11 GUI와 실시간 유저 정보 연동  
(운영자 창에만 실시간 업데이트 가능, 추후 유저도 실시간 업데이트 추가 예정)  

2018-11-11 퀴즈 방 입장, 퇴장시 서버로 실시간 전송  
2018-11-12 입장, 퇴장시 실시간 접속 유저 정보를 관리자 포함 모든 유저에게 전송    
2018-11-17 유저가 푼 문제 채점하는 기능 추가, 채점후 모든 사용자에게 정답 유무 전송    
2018-11-19 퀴즈목록들 DB에서 읽어와 유저에게 전송 기능 추가  
2018-11-20 GUI Close버튼 이벤트 추가하여 강제 종료해도 정상적으로 종료처리 되도록 구현  
2018-11-21 퀴즈와 타이머 연동하여 퀴즈 풀게 알고리즘 변경, 아직 채점 기능은 덜 만듦    
2018-11-22 각 유저 문제 채점 기능 구현, 전 유저에게 각 유저 점수 알려주는 기능 만드는 중  
2018-11-23 전공 퀴즈 10문제 SQL 문서 업로드  
2018-11-24 전공 퀴즈 5개 업로드  
2018-11-25 전공 퀴즈 5개 업로드  
2018-11-27 상식 퀴즈 14개 업로드  
2018-11-28 상식 퀴즈 7개 추가 업로드, 채점 로직 수정, GUI 불투명 하게 변경  
2018-11-28 exe 파일로 만들어 업로드 예정  -> 원인 불명 오류로 인하여 exe 파일 만들기 불가능, 프로젝트 채 실행 해야함. . . . .


  
# 프로젝트 설명
 - 개요  
  * 명령어 기반으로 작동  
  * 퀴즈 목록 창에 있는 이름을 전송하여 해당 분야의 퀴즈를 푼다  
 - 목적  
  * c, c++, java 공부간 배운 모든 라이브러리, 함수들을 활용하여 실무 능력   
  * 팀원간의 협업을 통하여 개별 개발 후 연동을 하여 프로그램을 만드는 실무 체험  
  * 이제껏 사용해보지 못한 DB, 서버, GUI를 연동하여 하나의 프로그램을 만들기  
    
# 프로그램 설명  
    
사용 전 환경 구축법 (필 수)  
1. 첨부된 SQL파일을 이용하여 MySQL 혹은 MariaDB를  test라는 데이터베이스를 만든 후 쿼리를 등록한다.   
2. 반드시 JDK 10버전 이하를 이용해야 한다.
  
유저   
$ 전공 -> 전공 분야의 퀴즈를 푼다.  
$ 답:x -> x번으로 답을 기록한다.  
  
서버 운영자  
$ 접속한 인원의 IP 등의 정보를 볼 수 있다.  
$ 모든 정보들의 입출력을 담당  
  
# 사용처  
$ 친구와의 퀴즈 대결  
$ 교수의 강의 퀴즈 평가시 활용 가능  
$ 약간의 소스 수정을 통하여 끝말잇기, 스무고개 등의 게임으로 변형 가능  

