# NGA21
넷마블 게임아카데미 5기 - 유니티 특강

[프로젝트 리소스](https://github.com/IndieGameMaker/UnityBook)

### 프로젝트 오픈시 Layout 관련 오류 발생시 대처법

1. 윈도우 탐색기에서 다음 경로로 이동
	AppData\Roaming\Unity\Editor-5.x\Preferences\Layouts\default

2. Default.wlt 파일 복사
3. 유니티 프로젝트 생성한 폴더 하위에 있는 Library 폴더로 이동
4. 기존에 있는 CurrentLayout-default.dwlt 파일 삭제
5. 복사한 Default.wlt 파일을 붙여 넣기
6. Default.wlt 파일 이름을 CurrentLayout-default.dwlt 로 변경
7. 유니티 재 실행
