# shakit_text_design
The Powerful Tweet App "Shakit Text"

# File information
* AI - Shakit Text에서 사용되는 백터 그래픽 리소스입니다.
* PSD - .psd파일이 포함되어 있습니다.
* resource-xxxhdpi - XXXHDPI 해상도의 리소스 파일입니다.
* icons - 각 쓰임과 해상도로 분리된 아이콘들이 존재합니다.
* Screenshots - 앱의 디자인 스크린샷입니다.

# Resource Information
* `btn_widget_picture.png` - 위젯에서 사진 첨부 버튼 아이콘입니다.
* `btn_widget_take_photo.png` - 위젯에서 사진 찍기 버튼 아이콘입니다.
* `btn_widget_tweet.png` - 위젯에서 트윗 버튼 아이콘입니다.
* `profile_widget_none.png` - 위젯에서 프로필 사진 기본값입니다.
* `profile_main_none.png` - 메인화면 계정 부분 프로필 기본값입니다.
* `title_about.png` - About 부분 로고입니다.
* `title_about_team.png` - About 부분 팀 로고입니다.
* `title_tutorial_frame.png` - 튜토리얼 1페이지 기기 스크린샷입니다.

# Color Information
* `#55ACEE` - 메인 컬러
* `#3A8DCC` - 상단바 컬러 / 서브컬러
* `#757575` - 앱 글씨 컬러
* `#BDBDBD` - 앱 서브 글씨 컬러

---

* `#55ACEE` - 트위터 블루 테마 타이틀 부분
* `#F5F5F5` - 트위터 블루 테마 배경 부분
* `#F06292` - 느와르 핑크 테마 타이틀 부분
* `#424242` - 느와르 핑크 테마 배경 부분
* `#26C6DA` - 서티나인 민트 테마 타이틀 부분
* `#424242` - 서티나인 민트 테마 배경 부분
* `#F48FB1` - 소프트 핑크 테마 타이틀 부분
* `#F5F5F5` - 소프트 핑크 테마 배경 부분
* 플로팅 위젯 트윗하기 버튼 `#FFF`에 불투명도 값 .5 /* 외곽선은 투명도 없음 */
* 튜토리얼 3-1페이지 비활성화된 시작 버튼 불투명도 값 .4

#App Stroyboard
* Shakit의 시스템을 응용하여 언제 어디서나 쉽고 빠르게 트윗을 작성하고 보낼 수 있는 앱입니다.
* 메인화면에서는 위젯의 미리보기와 함께 위젯을 설정하는 부분으로 되어 있습니다. 설정은 아래와 같습니다.
~~~
* 계정
계정 사진과 닉네임, 아이디가 존재하며 변경 버튼으로 계정을 새로 변경할 수 있습니다.
~~~
~~~
* Shakit 플로팅 위젯 설정
테마 설정 - 플로팅 위젯의 테마를 변경할 수 있습니다.
흔들어 보내기 - 트윗을 작성하고 다시 흔들어 보낼 수 있습니다.
~~~
~~~
* 세부 기능 설정
감도 설정 - 흔드는 감도를 세부적으로 조절합니다 /* Shakit의 기능과 동일 */
가로모드에서 사용 안함 - 가로모드에서는 등장하지 않습니다. /* Shakit의 기능과 동일 */
위젯 작동 제한 - 게임 등에서 앱이 등장하지 않도록 설정합니다. /* Shakit의 기능과 동일 */
부팅시 자동 실행 - 휴대전화가 켜질때 자동으로 앱을 시작합니다. /* Shakit의 기능과 동일 */
햅틱 반응 - 위젯이 등장할 때 햅틱 피드백을 합니다. /* Shakit의 기능과 동일 */
앱 종료 - 앱을 완전히 종료합니다. 위젯이 작동하지 않습니다. /* Shakit의 기능과 동일 */
~~~
~~~
* 기타
앱 정보 보기 - Shakit Text의 앱 정보를 확인합니다.
튜토리얼 다시보기 - 튜토리얼을 다시한번 확인합니다.
~~~
* 위젯은 총 4가지 테마가 존재합니다. 테마이름은 아래와 같으며 색은 위에 Color information을 참고하세요.
~~~
1. 트위터 블루
2. 느와르 핑크
3. 서티나인 민트
4. 소프트 핑크
~~~
* 별도로 스크린샷이 존재하지 않는 부분 /* 다이얼로그같은 */ 부분은 전부 기본적인 Material이거나 Shakit과 동일합니다.
* 튜토리얼 순서와 내용은 아래와 같습니다.
~~~
1. Tutorial 1 페이지
2. Twitter 로그인 페이지 /* 여긴 트위터에서 로그인해야하기 때문에 별도의 디자인이 없음 */
3-1. 감도 설정 페이지 
3-2. 감도를 흔들면 시작 버튼이 활성화
~~~
