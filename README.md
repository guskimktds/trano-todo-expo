# trano-todo-expo

  00. 제목 : 티라노 투두앱
  01. 목적 : 해야할일 기록관리하는 앱 
  02. 기반기술 : React Native 0.57, Expo, 추가라이브러리 : package.json dependency 참고
  03. 참고 : academy.nomadcoders.co/courses 에서 투두앱 강좌 참고

	1. TodoAppExpo 프로젝트 생성
		a. expo inti TodoAppExpo


	2. Expo client 단말에 설치 후 실제 단말에서 QR코드를 읽어서 접속하면
		a. Open up App.js to start working on your app! 이라고 표시된 첫 화면이 표시된다.

	3. App.js 를 편집해서 실제 TodoApp Expo 버전을 개발해본다.

		a. 요구사항 정리
			i. 해야 할일(Todo)을 저장하는 앱을 만든다.
			ii. 할일을 등록, 수정, 삭제한다.
				1) 나중에 등록한 todo 가 젤 상위로 표시된다.
			iii. 할일을 선택하여 완료/미완료를 체크한다.
				1) 완료 시 취소선을 넣는다.
				2) 완료 시 미완료 ToDo 와 색상으로 분별되도록 처리한다.
			iv. 화면스타일은 메모장과 같은 느낌이 나도록 표시한다. 상단 메모를 모서리를 둥글게 표시
