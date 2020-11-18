Manifest
========

* 매니페스트 파일 정의 - (위키백과, 우리 모두의 백과사전) [링크] : https://ko.wikipedia.org/wiki/%EB%A7%A4%EB%8B%88%ED%8E%98%EC%8A%A4%ED%8A%B8_%ED%8C%8C%EC%9D%BC

    매니페스트 파일(manifest file)은 컴퓨팅에서 집합의 일부 또는 논리정연한 단위인 파일들의 그룹을 위한 메타데이터를 포함하는 파일이다. 
    
    예를 들어, 컴퓨터 프로그램의 파일들은 이름, 버전 번호, 라이선스, 프로그램의 구성 파일들을 가질 수 있다.
    
    이 용어는 화물 목록(ship manifest)이 선원 및 화물을 나열하는 화물 수송 절차로부터 가져온 것이다.

* 역할 
    1. 패키지 네임 지정 - 앱의 리소스 접근, 상대경로 적용(build.gradle에 의해 재정의 됨)
    
    2. 사용 구성요소(Component - Activity, Service, BroadCastReceiver, ContentProvider) 선언
    
    3. 권한(Permission) 설정
    
    4. 앱의 필요로 하는 H/W, S/W 특징 명시 - <uses-feature>, <uses-sdk> => uses-sdk 는 build.gradle 에서 minSdkVersion 로 재정의 됨

intent-filter : 해당 Component 가 어떤 암시적 Intent 를 처리할 수 있는지 정의
 
     action : 어떤 작업을 처리할 수 있는지 정의
     
     category : component 의 유형이 무엇인지 정의
