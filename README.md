# JDBCPro3
상태정보유지기술
(1) ServletContext, HttpSession, HttpServletRequest, Cookie 중에서 다음 질문에 답해주세요.
   - 서버 사이드 저장 기술은 어느것들인가?
			답 : ServletContext, HttpSession, HttpServletRequest
   - ServletContext와 HttpSession의 차이?
			답 : ServletContex은 웹 어플리케이션 내의 모든 서블릿 간 정보 공유가 가능
				HttpSession은 클라이언트마다 독립적인 session이 존재 (클라이언트가 달라지면 다른 session으로 관리됨)
   - HttpSession 키는 어디에 저장되어 있는지?
		  답 : Cookie
   - Cookie의 옵션 중 Path와 MaxAge 기능 설명
			답 : Path - 해당 URL로만 cooki를 보내도록 설정
				MaxAge - 브라우저에 설정된 경로에 외부파일로 Cookie가 저장됨
   - 서버 사이드 저장 기술 대비 클라이언트 사이드 저장 기술의 장점?
		  답 : 서버 관리자의 입장에서, 서버의 처리 부담을 줄여서 결과적으로 서버 비용을 줄일 수 있다. 처리하는 데이터가 보안에 민감한 경우, 클라이언트 내에서 처리가 가능한 부분에 대해서는 통신에 대비하여 암호화할 필요가 없으므로 암호화 소요가 줄어든다.



실행화면

3. servlet 시작 4. 출력응답 ![3](https://user-images.githubusercontent.com/63589323/84457838-a1f1a580-ac9e-11ea-95a7-1cc38891693d.png)

5.Request 데이터 처리 ![4](https://user-images.githubusercontent.com/63589323/84457949-d9f8e880-ac9e-11ea-8597-ad1e4f20dfd8.png)

8.상태 정보 유지 기술 ![8](https://user-images.githubusercontent.com/63589323/84457973-e41ae700-ac9e-11ea-8e56-5bc936f9c9b7.png)



© 2020 GitHub, Inc.
