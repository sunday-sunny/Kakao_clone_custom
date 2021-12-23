

# ![GitHub-Mark-32px](https://user-images.githubusercontent.com/42857790/146734747-d934d609-b24a-4f31-9592-faf39fe74957.png) KaKao Desktop App Custom (ver.Github Desktop theme)

  

![index-capture](https://user-images.githubusercontent.com/42857790/146737561-8b299247-14cf-4931-b924-19309ceccdc8.JPG)

  

### 🔮 작고 귀여운 PC 카카오톡 ver. Github Desktop theme
- 평소에 정말 예쁘다고 생각했던 `Github desktop 홈페이지`와 `Discord desktop App`을 참고하여 진행한 `PC 카카오톡 Cloning 프로젝트`입니다!
- HTML, CSS를 사용하여 페이지를 구현하였습니다. 
- Media Query를 적용하여 브라우저 너비 700px 내에서 확인 가능합니다.
<br/>

### ✨ Click here to view my Github page!
👉🏻 [kakao talk customizing page](https://sunday-sunny.github.io/Kakao_clone_custom/)
<br/>
<br/>
<br/>



## 🔮 Concept
### Layout & Theme Reference
- 🔮 [Github Desktop homepage](https://desktop.github.com/) 
- 👾 Discord Desktop App
- 💬 KaKao Talk Desktop App

### Font
- [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)

### Icon
- [Font Awesome](https://fontawesome.com/)
<br/>
<br/>


## Detail
### 구성

### 1. Login Screen & 2. Friend Screen
<img src="https://user-images.githubusercontent.com/42857790/146933063-d3b3bb7c-3ec2-42fe-8808-b0f97c4fb6f0.gif" width="40%" /> <img src="https://user-images.githubusercontent.com/42857790/146955837-e66a59a4-4f40-4e98-9407-4c0e78626db1.gif" width="40%" /> 
#### Login Screen
- 로그인 화면입니다.
- Discord Desktop App 로그인 화면을 참고하여 디자인 했습니다.
- 메인색과 포인트색은 Github Desktop 홈페이지 색을 참고하였습니다.

#### Friends Screen
- 친구 목록 화면입니다.
- 전체적인 레이아웃은 카카오톡 PC버전 화면을 참고했습니다.
- 아이콘과 친구 목록에 hover를 적용하여 사용자 인지를 쉽게 하였습니다.
<br/>
<br/>


### 3. Chats Screen & 4. Chat Screen
<img src="https://user-images.githubusercontent.com/42857790/146955843-9d237f87-27b1-4ca3-967d-3b95836abc04.gif" width="40%" /> <img src="https://user-images.githubusercontent.com/42857790/146956950-ea415fcf-613c-4bc2-a8ff-7cb67c824a2c.gif" width="40%" />
#### Chats Screen
- 채팅 목록 화면입니다.
- 채팅 목록에 hover 적용을 하였으며, 클릭시 채팅방으로 이동합니다.

#### Chat Screen
- 채팅창 화면입니다.
- 아이콘에 모두 hover 적용하였으며, 상단 `<` 버튼을 누르면 채팅목록 화면으로 돌아가게 하였습니다.
<br/>
<br/>


### 5. More Screen & Link my Github!
<img src="https://user-images.githubusercontent.com/42857790/146958360-a19d376c-7f35-4938-b4d5-8cbf5ece77c7.gif" width="40%" /> <img src="https://user-images.githubusercontent.com/42857790/146958369-f5354b05-77ec-4cf0-8298-e79121afe0da.gif" width="40%" />
#### Chat Screen
- 더보기 화면입니다.
- 모든 아이콘에 hover 적용을 하였습니다.
- `My GitHub` 탭을 따로 만들어 클릭시 제 깃허브로 이동하게 하였습니다😆

<br/>
<br/>


### Point
* media query
<br/>
<br/>
<br/>




## Dev Enviroment
**🌍 OS** / windows10 <br/> 
**💻 IDE** / VSCode <br/>
**🚀 Deployment** / Github pages
<br/>
<br/>
<br/>



## 후기
HTML과 CSS를 복습하면서 진행했던 카카오톡 클론을 평소에 정말 예쁘다고 생각했던 `GitHub Desktop 홈페이지` 테마로 커스터마이징 해보았습니다😊!

프로그램을 다운받기 위해 이곳저곳 방문하다보면 정말 예쁘다고 생각되는 홈페이지들이 몇 있는데 그 중 하나가 깃헙 데스크탑 홈페이지입니다. 외국 홈페이지들은 UI가 넘 깔끔해서 볼 때마다 감탄하는데요, 왜 외국인들이 우리나라 사이트를 보면(N사....) 촌스럽다고 생각하는지 이해가 되곤 합니다.

마침 배운걸 복습차 커스터마이징 하려고 했는데 테마로 잡기 딱이다 싶었고, 이와 더불어 색상이랑 레이아웃이 비슷한 `디스코드 데스크탑 앱`을 함께 참고하여 진행했습니다. 

*조금 끔찍한 혼종이 된 거 같기도 하지만...* 다크테마여서 그런지 만들수록 예뻐졌습니다👻. 그런 김에 카톡은 PC톡도 다크모드를 내는건 어떠신지..?


1. 이름짓기 정말 힘들다!
2. 변수 설정, 공통 컴포넌트, 통일된 마진, 패딩 잡기 정말 힘들다!!
3. 마구잡이식 css 적용에 눈물이ㅠㅠ...
<br/>
<br/>


## 추가 구현 사항

 - 채팅방
	 - [ ] 채팅방 화면 input 버튼
	 - [x]  채팅방 `<` 버튼 추가
 - 채팅목록, 친구목록 
	 - [x] hover시 background color change
	 - [x] focus시 background color change
- Detail
	 - [x] screen header 부분 이모티콘 hover 적용
	 - [ ] navigation cog 클릭시 옵션박스 띄우기

