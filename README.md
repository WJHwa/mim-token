## MIM-Token 강의자료

### 메타마스크 설치
>
>웹 브라우저에서 메타매스크 사이트 (https://metamask.io) 열기
>
>Download 버튼 클릭 후 Download Now 버튼 클릭.
>
>Install MetaMask for Chrome 을 선택
>
>'MetaMask 을(를) 추가하시겠습니까?' 라는 alert창이 뜨면 확장 프로그램 추가 버튼을 클릭
>
>설치후 시작하기 버튼 클릭.
>
>지갑이 있으면 지갑가져오기 지갑이 없으면 지갑생성 클릭.
>
>MetaMask 개선에 참여 전 괜찮습니다"를 클릭.
>
>비밀번호를 만들고 이용 약관 동의후 생성 버튼 클릭
>
>다음 버튼 클릭 후 나오는 비밀 복구 구문 (Pass Phrase)을 파일에 저장해 두기
>
>※중요※ 메타매스크 비밀번호를 잊어버릴 경우 이 비밀 복구구문 조합을 가지고 있어야 복구 가능
>
>이 비밀 복구 구문을 잊어버리면 매타매스크에 있는 모든 토큰은 접근 불가
>
>비밀 백업 구문 확인에 방금 적어 둔 비밀 복구 구문을 복사하여 붙여넣기
>지갑이 생성되면 상단의 이더리움 메인넷 부분을 클릭하여 Ropsten 테스트 네트워크 선택
>##
>
### 토큰 만들어보기
>
>웹 브라우저에서 Remix IDE 사이트 (https://remix.ethereum.org) 열기
>
>좌측에 Workspace 옆에 + 버튼을 눌러서 Workspace 새로 만들기 
>
>contracts폴더를 클릭하고 스마트 컨트랙트 파일 (Sample Token.sol) 만들기
>
>MimToken.sol 파일 내용을 전부 복사하여 Sample Token.sol 파일에 붙여넣기
>
>ctrl + s 를 눌러서 저장하기
>
>좌측 <img width="20" alt="스크린샷 2022-09-02 오후 12 01 17" src="https://user-images.githubusercontent.com/89440736/188050278-a97228c8-64a3-47ec-a5d4-b4ecef37fc94.png"> 아이콘을 클릭하여 컴파일 환경 설정
>
>(Cmpliler+ 메뉴 아래의 선택창에서 0.4.24버전로 변경)
>
>푸른색 버튼( Compile My Token.sol) 을 클릭하여 실행파일 만들기
>
>좌측 <img width="20" alt="스크린샷 2022-09-02 오후 12 03 00" src="https://user-images.githubusercontent.com/89440736/188050510-be99fce6-5535-45f3-a27b-2450b4733486.png"> 아이콘을 클릭하고 Depoly 아이콘을 클릭하여 스마트 컨트랙트 배포 환경 설정
>
>(Evironment를 Injected Web3 로 선택(Metamask와 연동할 때 사용) 하고 Ropsten 테스트넷으로 설정)
>
>Contract  해당 솔리디티 파일(지금 만든 My Token.sol)로 선택)
>
>CONTRACT 부분에 INVENToken-My Token.sol 를 선택)
>
>Depoly 아이콘을 클릭하여 배포하기
>
>Deployed Contracts 부분이 생기면 >화살표 를 클릭하여 기능들을 살펴보며 사용하기
>
## 직접 만들어서 서로 한테 주고받기
