## Database > RDS for MySQL > 릴리스 노트

### 2018.10.16

#### 기능 추가

* 인스턴스 Storage 확장 기능 추가

### 2018.08.28

#### 기능 추가

* Binary Log 파일 삭제을 통한 인스턴스 용량 확보 기능 추가

### 2018.07.24

#### 기능 추가

* MySQL 5.7.15 버전을 추가 지원

### 버그 수정

* MySQL 5.7.19 버전 인스턴스 생성 시, floating ip 를 붙이지 않으면 생성하지 못하는 현상 수정
* 특정 상황에서 자동 백업의 시간이 평소의 2배 소요되는 현상 수정 

### 2018.05.29

#### 기능 추가

* MySQL 5.7 버전 신규 지원

### 2018.04.24

#### 기능 개선

* master의 port 변경 시, read only slave의 master 접속 정보 자동 변경
* 백업 후, 불필요하게 남는 로그 삭제

#### 버그 수정

* 검색결과 페이지 > 인스턴스 생성 후 페이지 이동 시도 시, 검색 결과 페이지로 이동되는 현상 수정
* 비밀번호 확인란을 공백으로 인스턴스 생성 시도 시 경고문구가 뜨지 않는 현상 수정

### 2018.03.22

#### 버그 수정

* 백업 보관 기관 '없음'으로 변경 시, 일정 시간동안 리스트에서 보이는 현상 수정
* 인스턴스 설정 수정을 하지 않았음에도 인스턴스의 상태가 변경 중으로 보이는 버그 수정
* 인스턴스 재시작 시, QPS 가 음수로 보이는 현상 수정
* Monitoring 화면에서 기간 설정 버튼 클릭 시, 화면의 날짜 및 시각의 갱신 없이 데이터만 갱신 되는 버그 수정

### 2018.02.22

#### 신규 상품 출시

* TOAST Cloud Relational Database Service (RDS) 는 Relational Database 를 클라우드 환경에서 제공하는 상품입니다.
* 복잡한 설정 없이 Relational Database 사용할 수 있습니다.
* MySQL 5.6.33 버전을 제공합니다.