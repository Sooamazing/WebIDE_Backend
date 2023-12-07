# WebIDE_Backend

## 🪄 프로젝트 개요
- idemainserver: 주요 요청을 처리하는 서버. 로그인, 회원가입 등 메인 서비스들은 해당 서버 코드에서 진행됩니다.
- runserver: 요청이 들어온 소스코드를 실행하는 서버입니다.

### 📅 개발 기간:
- 2023/12/10 ~ 2023/12/22

### ⚙️ 개발 환경
- `Java 17`
- **FrameWork**: Spring Boot 3.x
- **DataBase**: Mysql version미정
- **ORM**: JPA

### 담당 기능
- **이건**: 소스코드 파이프라인 및 소스코드 실행 요청 처리
- **이재은**: 실시간 채팅 기능
- **홍예지**: 로그인 및 회원가입 기능
- **황한나**: 소스코드 실행 서버

## 🛑 커밋 전 체크 리스트 🛑

### 커밋 메세지
- 커밋 메세지 형식은 다음과 같습니다.
> type(타입) : title(제목)
> 
> body(본문, 생략 가능)
> 
> Resolves : #issueNo, ...(해결한 이슈 , 생략 가능)
> 
> See also : #issueNo, ...(참고 이슈, 생략 가능)

여기서 타입은 다음과 같습니다.

- feat : 새로운 기능을 추가하거나, 기존 기능을 요구사항 변경으로 인해 변경한 경우
- fix : 버그를 수정한 경우
- docs : 문서(주석) 추가/수정의 경우, 직접적인 코드의 변화 없이 문서만 추가 수정 했을 때
- style : UI를 추가/수정하거나, 스타일 관련 작업의 경우
- refactor : 기능의 변경 없이, 코드를 리팩토링 한 경우
- test : 테스트 코드를 추가/수정한 경우
- chore : 기능/테스트, 문서, 스타일, 리팩토링 외에 배포, 빌드와 같이 프로젝트의 기타 작업들에 대해 추가/수정한 경우

### 브랜치
- 해당 프로젝트는 Github Flow 전략을 사용합니다.
- main 브랜치에 직접 push하는 것을 금지합니다.
- pull request를 통해 코드 리뷰 후 merge 합니다.
- 또한 작업하는 브랜치가 main 브랜치가 아닌 개발 브랜치인지 확인합니다.
- 브랜치 명은 feature/기능명 입니다. 예시) feature/login
- 버그 fix를 위한 브랜치 분기의 경우 bug/버그명 입니다.

### 테스트 체크
- 반드시 테스트를 모두 통과하는지 확인합니다.
- 통합 테스트가 필요한 경우 로컬에서 확인 후 pull request 합니다.

### !!중요!! 중요 리소스 정보 노출
- AWS 키페어 같은 중요한 정보가 노출되지 않도록 확인합니다.
- 만약 새로운 키가 추가될 경우 환경 변수를 사용할 수 있도록 합니다.
- 중요 리소스가 노출되었고 그것을 인지했다면 최대한 빠른 시간 내에 팀에 연락합니다.

### conflict 방지
- conflict가 날 우려가 있는 파일 수정 시 수정 전에 팀원에게 알립니다.
- 우려가 있는 파일은 보통 build.gradle 파일이나 자신이 맡은 기능 외의 파일 입니다.
- 애매하면 무조건 코드 수정 전에 먼저 연락을 취하길 바랍니다.

update: 2023/12/07 🕥
