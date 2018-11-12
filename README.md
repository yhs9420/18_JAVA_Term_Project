18_JAVA_Term_Project

팀 구성 
  
  *  Han Sang Banetta Kim - https://github.com/Banetta 
  *  HS Yu https://github.com/yhs9420

주제는 다음의 범주에서 정의

   *   다자간 메신저 (참고: 카카오, LINE, Whats App 등)
   *   기본 개발 언어는 자바
   *   인터넷 or 전화망 or 블루투스 활용
   *   사용자 사용 환경은 Windows PC GUI
   *   Open source로 기 개발된 메신저 사용 불허


일정

   *   10/30 (화)  팀구성
   *   11/06 (화)  개발 시스템 아이디어 정의 문서 제출 (A4 2~3쪽) (10%) - 교수 평가
   *   11/13 (화)  개발 시스템 아키텍처 정의 문서 제출 (A4 2~3쪽) (10%) - 교수 평가
   *   12/04 (화)  개발 시스템 1차 데모 평가 (20%) - 동료 상호 평가
   *   12/11 (화)  개발 시스템 2차 데모 평가(최종) (60%) - 동로 상호 평가


개발 시스템 아이디어 정의

   *   메신저의 기본
      
      -   Java를 기반으로 구동되는 다자간 메신저이며, 메신저 간의 네트워크 연결은 인터넷 IPv4 주소로 통신한다. Windows PC에서 아이디와 비밀번호를 입력하고 회원가입 및 로그인을 할 수 있도록 한다. 현재 상용화된 메신저 중 카카오, LINE, Telegram 등을 참고하여 기능들을 포함시키도록 한다. 

   *   메신저의 주요 기능
      
      -   로그인을 하면 친구 목록이 뜨고 다른 사용자를 추가하여 친구 목록을 관리 할 수 있으며 대화를 진행할 수 있도록 한다.
      
      -   가장 기본적인 사용자 : 사용자 간의 대화를 주고 받을 수 있는 1:1 대화 를 추가시킨다. 1:1 대화에서는 메시지를 주고 받는것과, 사용자 간에 파일(사진, 음악 압축파일 등)을 주고받을 수 있도록 한다. 모든 대화는 이를 기본으로 한다.
      
      -   그룹 대화에서는 초대를 2명 이상 또는 1:1 대화방에서 1명 이상 초대 했을 때 그룹 대화를 진행할 수 있다.
      
      -   비밀 1:1 대화에서는 사용자 : 사용자 간의 대화 내용을 서버에서 접근 권한을 강화하여 관리자가 채팅 내용을 확인 할 수 없도록 한다. 또한 채팅방이 삭제 되면 채팅 로그의 암호화도 자동으로 삭제되도록 한다.
      
      -   비밀 그룹대화는 비밀 1:1대화와 동일하되 사용자가 한명이라도 나갈 경우 채팅방을 삭제한다
      
      -   메신저에 나만 이용할 수 있는 나만의 저장소를 추가하여 사용자가 메모 또는 파일 등을 기록하거나 보관하고 싶을 때 사용할 수 있도록 한다.
      
      -   #태그 기능은 웹 검색엔진의 검색 결과를 상대방 혹은 그룹 구성원들에게 보내줄 수 있는 기능으로, 다른 웹 브라우저를 사용하지 않아도 채팅방 내에서 원하는 검색결과를 보여줄 수 있는 기능이다.
      
      -   메신저 투명화 기능은 다른 작업을 같이 할 때 창이 겹쳐서 보이지 않을 경우를 대비하여, 메신저 창에서 투명화를 조절할 수 있는 기능을 사용할 수 있도록 한다.
      
      -   최근 인기 메시지(자주 사용한 단어)는 Elastic Stack(구 ELK)에서 Elastic Search의 기능중 분석 기능을 이용하여 채팅 로그를 형태소 단위로 분석하여 자주 사용되는 단어를 그래프 이미지로 확인할 수 있는 기능이다.
      
      -   관리자 페이지는 위에 최근 인기 메시지 기능을 포함하여 어떤 단어가 많이 사용되는지 어떤 파일이 제일 많이 오고가는지 등의 정보를 Elastic Stack의 kibana를 이용해 대쉬보드로 확인할 수 있도록 한다. 이 페이지는 관리자만 접근 가능하도록 한다.

