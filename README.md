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
>
>지갑이 생성되면 상단의 <img width="177" alt="스크린샷 2022-09-02 오후 12 19 46" src="https://user-images.githubusercontent.com/89440736/188052318-2e9ac67e-ae3f-49f6-b5e8-f5e1168678a1.png"> 이 부분을 클릭하여 Ropsten 테스트 네트워크 선택
>
>(없을시 손들고 말하기)
>
> 새 크롬창 열고 무료 테스트토큰 지급 사이트 (https://faucet.dimensions.network) 열기
>
>Metamask 창에서 Account1을 클릭하여 자신의 지갑주소를 복사
>
>Enter Your Ropsten Address 아래 검색창에 복사한 지갑주소를 붙여넣기.
>
>Send Ropsten ETH를 선택
>
> 메타마스크 창에서 무료 이더를 확인
>
>(안될 시 https://faucet.metamask.io/ 열고 User 부분에 1ether 아이콘 클릭하여 받기)
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
>좌측 <img width="20" alt="스크린샷 2022-09-02 오후 12 03 00" src="https://user-images.githubusercontent.com/89440736/188050510-be99fce6-5535-45f3-a27b-2450b4733486.png"> 아이콘을 클릭하고 <img width="200" alt="스크린샷 2022-09-02 오후 12 07 52" src="https://user-images.githubusercontent.com/89440736/188051066-a763f849-9e15-4daa-b7ec-923b8217805d.png"> 이 부분을 INVENToken 으로 변경
>
><img width="150" alt="스크린샷 2022-09-02 오후 12 10 42" src="https://user-images.githubusercontent.com/89440736/188051376-e0bf9d6e-8ff7-4580-a05c-adbeebc1e9a3.png">이부분을 Injected Provider 로 변경 (MetaMask에서 연결 알림 뜨면 연결하기 버튼 클릭)
>
>Depoly 아이콘을 클릭하여 스마트 컨트랙트 배포 환경 설정
>
><img width="200"  height="30" alt="스크린샷 2022-09-02 오후 12 15 08" src="https://user-images.githubusercontent.com/89440736/188051779-f0377616-dd5f-4355-a564-5333cd2ce18f.png"> Deployed Contracts 부분이 생기면 > 화살표 를 클릭하여 기능들을 살펴보며 사용하기
>
><img width="400"  height="20" alt="스크린샷 2022-09-02 오후 12 16 11" src="https://user-images.githubusercontent.com/89440736/188051900-3e9b8959-8dbf-45d6-bebb-de7bb62aca6a.png"> 오른쪽에 ∨ 화살표 클릭 후 transaction hash 옆에 값을 복사하기
>
>새로 웹 브라우저에 https://ropsten.etherscan.io/ 에 들어가기
>
><img width="400"  height="30" alt="스크린샷 2022-09-02 오후 12 24 43" src="https://user-images.githubusercontent.com/89440736/188053160-2adef79a-315b-4ea6-8290-a03c6451fa77.png">이 부분에 복사한 값 넣고 검색하기
>
>왼쪽 상단에 Contract 부분에 값을 복사.
>
>MetaMask를 키고 맨 아래 부분에 토큰 가져오기 클릭.
>
>토큰 계약 주소에 복사한 값을 붙여넣고 맞춤형 토큰 추가버튼 클릭.
>
>옆사람과 주소를 받고 토큰을 보내기.
>
>##



