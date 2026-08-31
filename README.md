# LaTales_runner

**This is a fan-made software utilizing assets from LaTale. To respect the original IP and due to internal reasons, the source code is private.** 


라테일 캐릭터가 내 데스크톱 위를 자유롭게 돌아다니는 데스크톱 펫 프로그램입니다.  
화면 위를 걸어 다니는 캐릭터를 마우스로 잡아서 다른 창 위에 올려둘 수도 있고, 원하는 코디로 자유롭게 꾸밀 수 있어요.  <br>

A desktop pet application where LaTale characters freely roam around your desktop. <br>
You can grab characters walking across your screen with your mouse to place them on top of other windows, and freely customize their appearance with various outfits.

![LaTales_runner](screenshots/hero.gif)


<br>


## 다운로드 및 설치 / Download & Installation

[Releases](../../releases) 페이지에서 최신 버전을 받아 실행하면 자동으로 설치됩니다.  
Release 페이지 하단의 **Assets** 목록 파일 3개 중 **`Latales_runner-Setup-X.X.X.exe`** 하나만 받으시면 됩니다.   <br>

Download and run the latest version from the [Releases](../../releases) page to install automatically.
You only need to download **`Latales_runner-Setup-X.X.X.exe`** from the 3 files listed in the **Assets** section at the bottom of the Release page.

![다운로드할 파일 선택](screenshots/release-assets.jpg)

- 관리자 권한이 필요 없고, 라테일 클라이언트를 따로 설치하지 않아도 바로 실행됩니다.  
- 설치 후 우클릭 메뉴에서 언제든 최신 버전인지 확인/업데이트할 수 있습니다. <br>

- No administrator privileges required, and runs immediately without needing the LaTale client installed.
- After installation, you can check for updates or update to the latest version anytime via the right-click context menu.

<br>


### 다운로드가 안 되거나 파일이 지워진다면 / If download fails or the file is automatically deleted

Edge/Chrome 등 브라우저가 "이 파일 형식은 일반적으로 다운로드되지 않습니다" 같은 경고를 띄우며 파일을 자동으로 지우는 경우 다음과 같이 다운로드 하시면 됩니다! <br>
배포용 인증서(코드 서명)가 없는 개인 제작 프로그램이라 생기는 안내일 뿐, 악성 파일이라서 뜨는 경고가 아니에요.   <br>

If browsers such as Edge or Chrome display warnings like "This type of file isn't commonly downloaded" and automatically delete the file, please follow the steps below! <br>
This warning appears simply because it is an independently developed application without a commercial code-signing certificate, not because it contains malicious software.

![다운로드 경고 처리 방법](screenshots/download-warning.png)

1. 다운로드 목록에서 파일 오른쪽의 **`...`(더보기)** 클릭 (Click **`...` (More options)** on the right side of the file in your download list.)
2. **자세히** 클릭해서 옵션 펼치기 (Click **Show details** / **Details** to expand options.)
3. **유지** 클릭 (Click **Keep** / **Keep anyway**.)


<br>

### 설치 파일 실행 시 "Windows의 PC 보호" 경고가 뜬다면 / If "Windows protected your PC" warning appears

인증서로 서명되지 않은 프로그램이라 Microsoft Defender SmartScreen이 "인식할 수 없는 앱"이라는 경고를 띄울 수 있어요. 마찬가지로 정상적인 안내이니 아래처럼 진행하면 돼요.   <br>
Because the program is not signed with a digital certificate, Microsoft Defender SmartScreen may display an "Unrecognized app" warning. This is expected behavior; please follow these steps to proceed:

![SmartScreen 경고 처리 방법](screenshots/smartscreen-warning.jpg)

1. **추가 정보** 클릭 (Click **More info**)
2. 새로 나타나는 **실행** 버튼 클릭 (Click the newly revealed **Run anyway** button)

## 사용법 / How to Use

- **좌클릭 드래그**: 캐릭터를 들어서 원하는 위치나 다른 창 위에 올려두기  
  (**Left-click Drag**: Pick up the character and place them anywhere on the screen or on top of other open windows.)
- **우클릭**: 코디 편집 / 이모티콘 / 캐릭터 관리 / 크기·투명도 / 기타 설정 메뉴 열기  
  (**Right-click**: Open the context menu - Outfit Customization / Emoticons / Character Management / Size & Opacity / Other Settings.)


<br>

## 주요 기능 / Key Features

### 자유로운 코디 편집 / Free Outfit Customization
헤어/피부/의상 등 원하는 조합으로 자유롭게 꾸미기 가능! 프리셋으로 저장/불러오기도 가능해요. 최대 5캐릭터 까지 각자 다른 코디로 동시에 둘 수 있어요.   <br>
Freely customize your character with any combination of hair, skin, outfits, and more! Preset save and load functionality is also supported. You can place up to 5 characters on screen simultaneously, each with a different outfit.

![코디 편집 및 캐릭터 관리](screenshots/customize.gif)

<br>


### 다른 창 위로 올라타기 / Climbing On Top of Windows
화면(멀티 모니터 지원) 위를 자유롭게 다니고 열려있는 다른 창(브라우저, 탐색기 등) 위에도 올라갈수 있어요.   <br>
Characters move freely across screens (multi-monitor supported) and can climb on top of open application windows (browsers, file explorers, etc.).

![창 위 상호작용](screenshots/window-interact-1.gif)
![창 위 상호작용 2](screenshots/window-interact-2.gif)


<br>

### 들어올리기 & 던지기 / Pick Up & Throw
마우스로 들어올려서 원하는 곳에 놓을수 있습니다. <br>
높은곳에서 떨어지면 일반 착지와 다른 모션을 보여주며, 화면 양쪽 가장자리로 세게 던지면 핀볼처럼 벽에 튕기기도 해요.  
Pick up characters with your mouse and drop them wherever you like. <br>
Dropping them from high places triggers unique landing animations, and throwing them hard against screen boundaries makes them bounce off like a pinball!

<br>

### 이모티콘 재생 / Emote Animations
게임 속 다양한 동작(이모티콘)을 즉시 재생하거나, 가만히 있을 때 자동으로 재생되도록 설정할 수 있어요.   <br>
Trigger various in-game action emotes instantly, or configure them to play automatically when idling.

![이모티콘 재생](screenshots/emoticon.gif)

<br>

### 크기 / 투명도 조절 / Size & Opacity Adjustment
캐릭터 크기와 투명도를 필요에 따라 조절할 수 있어요.  <br>
Adjust character size and transparency according to your preference.

![크기 조절](screenshots/scale.jpg)
![투명도 조절](screenshots/opacity.gif)

<br>

### 그 외 세부 설정 / Other Detailed Settings
윈도우 상호작용 켜기/끄기, 제자리에 서있기, Windows 시작 시 자동 실행 등을 지원합니다!  <br>
Supports toggling window interactions, standing idle in place, launch on Windows startup, and more!

![자율 이동](screenshots/idle-walk.gif)


<br>

## 제작자 / Creator
kimbap918(chipok)
![](https://i.imgur.com/cMyuo3o.png)



이 프로그램은 라테일(원작: Actoz Soft) 팬메이드 도구이며, 원작의 저작권은 Actoz Soft에 있습니다.  <br>
This program is a fan-made desktop tool for LaTale All original game copyrights belong to Actoz Soft.
