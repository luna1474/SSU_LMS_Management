# SSU LMS Management
LMS 강의 자동재생 프로그램입니다.

출석되지 않은 강의를 찾아서 2배속으로 강의를 재생합니다.

<br>

LMS 관리 프로그램은 크롬 브라우저 기반으로 동작하므로 **꼭 크롬을 설치하시기 바랍니다.**

LMS 관리 프로그램은 학번과 비밀번호를 외부로 유출, 수집하지 않습니다. 프로그램 내부에서 로그인 용도로만 사용합니다.

LMS 관리 프로그램을 사용함으로써 발생하는 문제의 책임 소재는 모두 **본인**에게 있음을 알려드립니다.


## 설치 방법

### Mac OS
java를 설치하고 JAR를 실행시키면 이용 가능합니다.
### Windows OS
java를 설치하고 exe를 실행시키면 이용 가능합니다.

### 다운로드 링크

[LMS 프로그램 다운로드](https://github.com/luna1474/SSU_LMS_Management/releases/tag/beta)

[JAVA 다운로드](https://java.com/download)

## 사용 방법



<img width="762" alt="로그인 화면 샘플 이미지" src="https://user-images.githubusercontent.com/24191595/188301056-13f30912-c961-4796-b179-040ad19a8185.png">


> **[로그인 탭]** 프로그램을 처음 실행하면 나타나는 화면으로 학번, 비밀번호를 입력하여 로그인을 시도합니다.

<br><br>




<img width="762" alt="강의 선택 화면 샘플 이미지" src="https://user-images.githubusercontent.com/24191595/188301108-cc4d4e61-6d80-4b73-b7b3-c8a139bfda50.png">

> **[강의 선택 탭]** 로그인을 하면 강의 목록을 불러오고 재생되지 않은 강의를 자동으로 선택합니다. '**시작**'을 눌러서 자동재생을 시작합니다.

<br><br>



<img width="762" alt="로그 화면 샘플 이미지" src="https://user-images.githubusercontent.com/24191595/188301113-3c3f7166-96a7-494c-be84-c00cc67731f4.png">

> **[로그 탭]** 프로그램의 로그를 확인할 수 있습니다. 버그 리포트시에는 Log.txt 파일을 첨부 해주시면 도움이 됩니다.

<br><br>

## 추후 업데이트가 필요한 기능
* 로그인 정보 저장

## 업데이트 내역
* beta v1.0
  * 초기버전 출시
* beta v1.1
  * 진행표시줄 추가, 현재 재생 중인 강의시간 표시, 기타 버그 Fix
* beta v1.1.1
  * chromedriver_path 윈도우 체크 옵션 추가, 기타 Bug Fix
* beta v1.1.2
  * UI 폰트 변경, 기타 Bug Fix
* beta v2.0
  * UI/UX 개선, 크롬 숨기기 지원, 컴퓨터 종료 지원
* beta v2.0.1
  * 컴퓨터 종료 버그 Fix, 안내 메시지 수정
* beta v2.0.2
  * 크롬 드라이버 다운로드 안내 메시지 수정
* beta v2.0.3
  * 2배속을 지원하지 않는 강의 대응
    
## 문제 발생시 해결 방법
> 베타 버전이기 때문에 오류 발생의 소지가 다분합니다.  버그 발견시 Issues탭에 Log파일과 함께 제보 부탁드립니다 :)

<br>

* 크롬 브라우저가 자동으로 켜지 않습니다.

   -> 크롬 드라이버가 없거나 구버전이기 때문에 발생합니다. 자동 업데이트 기능을 지원하므로 다시 시도하면 대부분의 문제가 해결됩니다.<br><br>
   
* 강의 자동재생이 정상적으로 되지 않습니다.

   -> 크롬 숨기기 기능이 꺼져있다면 켜서 사용해주세요. 크롬을 숨기지 않으면 오류 발생의 가능성이 높아집니다.<br><br>

* 로그인이 되지 않습니다.

   -> 학번과 비밀번호가 올바른지 확인해주시기 바랍니다. 로그인에 문제가 있다면 먼저 [스마트캠퍼스](https://class.ssu.ac.kr)에서 로그인을 시도해보시기 바랍니다.<br><br>

* 프로그램이 켜지지 않습니다.

   -> SSU LMS 관리 프로그램은 자바를 기반으로 개발했습니다. 따라서 사전에 자바가 설치되어 있어야 합니다. [자바 다운로드](https://java.com/download)<br><br>
   
* 프로그램의 디자인이 예제 사진과 다르게 나옵니다.

   -> 맥 플랫폼으로 개발했기 때문에 윈도우 환경에서는 사용자 경험이 다를 수 있습니다.<br><br>
   
* 크롬 숨기기, 영상 음소거 옵션이 정상적으로 반영되지 않습니다.

   -> 로그인 버튼을 누르기 전에 옵션을 선택해주세요. 로그인 이후에는 옵션이 반영되지 않습니다.<br><br>
   
* 컴퓨터 종료 옵션이 제대로 작동하지 않습니다.

   -> 컴퓨터 종료 옵션은 윈도우 전용 기능입니다. 맥에서 사용중인지 확인 해주세요.<br><br>
  
  
* 재생되지 않은 강의가 남아 있습니다.

   -> LMS 관리 프로그램은 현재 주차 강의 영상만 자동재생하도록 개발되었습니다. 혹시 지난 주차 강의가 남아 있는지 확인해주세요.<br><br>
   
* 강의 영상 로딩 속도가 느립니다.

   -> 팝업창 유무를 확인하기 위해서 대기 시간을 10초 정도로 설정했습니다. 컴퓨터마다 속도차가 있는 상황을 고려한 설정값입니다.<br><br>

## 정보

유휘준 – peulling@soongsil.ac.kr


Apache License 2.0 라이센스를 준수하며 ``LICENSE``에서 자세한 정보를 확인할 수 있습니다.

## Reference
* [SSU_LMSAutoplayer](https://github.com/Sensol2/SSU_LMSAutoplayer) - 참고한 프로그램

* [selenium](https://www.selenium.dev/) - 크롬 제어

* [jsoup](https://jsoup.org/) - Selenium ChromeDriver 다운로드 용도

* [zip4j](https://github.com/srikanth-lingala/zip4j) - Selenium ChromeDriver 압축 해제

* [launch4j](http://launch4j.sourceforge.net/) - 윈도우 exe 실행파일 생성

