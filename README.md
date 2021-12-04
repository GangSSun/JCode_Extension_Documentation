# Extension For JCode❕
## JCode에서 사용이 가능한 확장들을 정리한 문서

우리가 공부하기 전에 책상정리를 하는 것 처럼

코딩을 하기 전에 우리가 사용할 개발 환경을 각자에 맞게 정리하고, 꾸미고, 확장 시킨다면 어떨까요?

코딩을 하다가 지루하시다면 차 ☕ 한잔 하면서 천천히 읽으며 하나씩 설치 해 보시는건 어떨까요?

**코딩이 재미 없다면 먼저 꾸며보세요!**

*(본 문서는 JCode에서 원활히 작동하는 Extension만 기재하는 것을 원칙으로 하며, 작성자의 주관이 들어가있음을 알립니다.)*

*(본문에 간략히 설명된 기능에 대한 자세한 설명은 market place에서  Extension의 설명을 참고하길 바랍니다.)*

---------



### - [VSIX 파일로 Extension 설치하기](https://github.com/GangSSun/JCode_Extension_Documentation/blob/52d4bdcd45f38dd4cb3eff582a313802cf119199/Docs/how_to_install_vsix.md)
  

  
  
1. **각 항목을 클릭하면 해당 Extension의 marketplace로 이동합니다.**
2. **문단명 아래의 펼치기를 클릭하시면 접혀 있던 설명이 펼쳐집니다!**
3. **모든 Extension 및 Theme 설치 후엔 ```Ctrl + Shift + P``` 를 눌러 명령어 창에서 ```Reload Window``` 를 실행해주어야 설치가 완료됩니다.**
4. **별도의 추가 설정이나 설명이 필요없는 Extension의 경우 How Use가 생략되어 있습니다.**
5. **자세한 설명은 Extension별 Market Place를 참조해주세요.**


# Extra Feature 

VS Code에 새로운 기능을 추가하는 Extension입니다.



## [- C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
<details> <summary> 펼치기 </summary> 

**⛔C/C++ Extension의 경우 JCode의 마켓플레이스에서 다운 받아 설치하게 될 경우 arm버전이 설치됩니다.**
  
**⛔JCode의 프로세서는 x86이기 때문에 Extension의 모든 기능을 온전히 사용할 수 없습니다.**

**⛔번거롭더라도 linux_x86_64버전을 상단의 [VSIX파일로 Extension 설치하기][1] 를 참고하여 설치하셔야 합니다.**
  
**기존 JCode에서 gcc 컴파일러 자체로는 편의기능이 전무하기에 거의 필수라고 할 수 있는 Extension입니다.**
  
### What is It?
  

  - error squiggles(오류 표시선)을 통한 간편한 디버깅 제공.
  - Intellisense(코드 자동완성) 제공.
  - 오류에 따른 솔루션 제공.
  - 정의 및 선언, 참조로의 간편한 이동.
  - 여러 기본 테마 제공.
  - 사실상 visual studio와 유사한 환경을 제공.
  
  
  </details>
  
## [- Korean Language Pack](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-ko )
  
<details> <summary>펼치기</summary> 
  
### What is It?
- VS Code의 UI 환경을 한국어로 번역해주는 Extension입니다.
- 단순히 메뉴만 번역해주는 것이 아니라, 오류 검출 후 디버깅 메세지 또한 한글로 출력해 줍니다.
  
  </details>
  
## [- Code Runner ](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner )
  
<details> <summary>펼치기</summary> 
  
### What is It?
  
  
  - 명령어를 통한 컴파일 및 실행을 할 필요 없이, 오른쪽 상단의 버튼 혹은 단축키를 통한 간단한 컴파일, 실행이 가능합니다.
    ![image](https://user-images.githubusercontent.com/87172228/144563585-4a27a0d7-2b5f-43a3-b1a2-1406fc55fb39.png)

  - 하단의 이미지의 내용 처럼 수많은 언어의 실행을 지원합니다.
    ![image](https://user-images.githubusercontent.com/87172228/144563125-ca671793-08e9-4814-b294-e59a215fe1b5.png)
  
  - 기본 출력창에서 출력을 하게 될 경우 input을 따로 입력할 수 없기 때문에 터미널통한 출력을 권장합니다.
    ![image](https://user-images.githubusercontent.com/87172228/144564503-c829ff1e-7fa8-48a6-8d01-148204f6b726.png)


### How to Use?
  - 단축키 
    - 실행 : Ctrl + Alt + N
    - 실행중지 : Ctrl + Alt + M
    - 언어를 선택하여 실행 : Ctrl + Alt + J
  
  - 권장 기본 설정 : Extension창에서 Code Runner 우클릭 후 확장 설정에서 진행
    - Run IN Terminal : 코드를 실행했을 때 터미널 창에서 코드를 실행하여 input을 넣을 수 있습니다.
    - Save File Before Run : 코드를 실행할 경우 실행 전에 자동으로 파일 저장을 해줍니다.
  
  </details>
  
    
## [- Code Spell Checker ](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker )
  
<details> <summary>펼치기</summary> 
  
### What is It?
  - 코드 작성시에 오타를 squiggles(물결선)을 통해 표시해 줍니다.
  - 변수명으로 사용한 영단어의 맞춤법 뿐만 아니라 주석을 작성 할 때에도 맞춤법을 검사해줍니다.
    ![image](https://user-images.githubusercontent.com/87172228/144565597-c6c8e8ed-5e2b-4855-95b5-8a2872bb67ac.png)
  - 영어 뿐만 아니라 다양한 언어의 Spell Check를 지원합니다.

### How to Use?
  - 본인이 합성어를 사용하였거나 사전에 단어를 추가 하고 싶을경우
    - Ctrl + Shift + P를 입력하여 명령어 창에서 ```Add word to Dictionary``` 를 통해 단어를 추가 할 수 있습니다.
  
  </details>
    
## [- Error Lens ](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens )
  
<details> <summary>펼치기</summary> 
  
### What is It?
  - Warning message나 error message를 해당 라인에 오버레이 형식으로 표시해 줍니다.
  - 기존엔 error 발생시 마우스를 올려야 확인가능 했지만 에러 발생시 간편하게 바로 확인이 가능합니다.
    ![image](https://user-images.githubusercontent.com/87172228/144567522-2d81a256-be5d-418e-a2af-d00dd12fd877.png)
  - 설정에서 글꼴, 크기, 아이콘 표시 유무여부 등 사용자에 맞춰 다양한 수정이 가능합니다.
  
  </details>
    
## [- TabOut](https://marketplace.visualstudio.com/items?itemName=albert.TabOut )
  
<details> <summary>펼치기</summary> 
  
### What is It?
  - 현재 키보드 커서가 따옴표, 괄호 등의 안에 있을 경우 tab키를 통한 이동을 가능하게 해줍니다.
    ![tab_preview](https://user-images.githubusercontent.com/87172228/144570154-3432cb3e-4a08-431d-b5f9-4e7b74d7dc36.gif)
  - 이동시에 마우스나 방향키를 연타 할 일이 매우 적어집니다!

### How to Use?
  - Toggle TabOut명령어를 통해 On/Off가 가능합니다.
  
  </details>
    
## [- Diff](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-diff )
  
<details> <summary>펼치기</summary> 
  
### What is It?
  - 빠르고 간편하게 두 파일간의 diff(비교)를 할 수 있게 해줍니다.
    ![diff_preview](https://user-images.githubusercontent.com/87172228/144573279-536b6cb1-10c2-4fec-ab2c-b03ab8fedc25.gif)
  - 단순하게 선택한 두 문단의 비교 뿐만 아니라 여러 상황의 비교를 지원합니다.


### How to Use?
  
  - 비교하려는 문단을 드래그 후 우클릭
    
    ![K-003](https://user-images.githubusercontent.com/87172228/144575373-d15397ff-1e57-465f-8538-ed6c5f9934c3.png)

  
  1. Select Text for Compare
    - 비교하기 위한 원본으로 선택
  2. Compare Text with Previous Selection
    - 원본과 현재 선택한 문단을 비교
  3. Compare Text with Clipboard
    - Clipboard의 내용과 현재 선택한 문단을 비교
  4. Compare Text in Visible Editors
    - 현재 열려있는 두개의 편집기에서 각자 선택된 내용을 비교
  
  
  </details>
  
---------

# UI / Theme

VS Code 전반에서 사용되는 UI 요소와 관련된 Extension입니다.

**각 항목을 클릭 하시면 접혀 있던 설명이 펼쳐집니다!**
    
## [- Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2 )
  
<details> <summary>펼치기</summary> 
  
### What is It?
  - 괄호별로 짝을 지어 색을 입혀 가독성을 높여줍니다.
    ![image](https://user-images.githubusercontent.com/87172228/144596677-16abacfd-9f20-4caa-a2ce-c04b10833fab.png)
  
  *(성능을 높힌 버전 2가 있지만, JCode에선 동작오류가 있기에 버전 1 사용을 권장합니다.)*


### How to Use?
  - 확장 설정에서 각 괄호별 색을 직접 정할 수 있습니다.
  
  </details>
      
## [- Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) 
  
<details> <summary>펼치기</summary> 
  
### What is It?
  - 주석에서 ```todo``` 등 설정한 키워드에 대해 하이라이트 해주는 Extension입니다.
  - 주석을 각 상활별로 구별 할 수 있게 해줍니다.
    - ex) 경고문은 빨강, 동작 설명은 초록, 추가 구현이 필요한 부분은 주황 등
  ![image](https://user-images.githubusercontent.com/87172228/144597461-f87bb1dc-5622-4cc6-9da7-9aa599a3fe61.png)


### How to Use?
  - ```better-comments.tags``` 에서 더 많은 키워드를 설정하거나 각 키워드별 색상을 변경 할 수 있습니다.
  
  </details>
      
## [- Better C++ Syntax](https://marketplace.visualstudio.com/items?itemName=jeff-hykin.better-cpp-syntax )
  
<details> <summary>펼치기</summary> 

### What is It?
  - 구문 등을 강조 하여 코드 전체의 가독성을 크게 높여줍니다.
  - 매개변수 강조, 템플릿 정의 구문에 대해 강조해줍니다.
  - Before
    ![image](https://user-images.githubusercontent.com/87172228/144598340-07df0ab1-5729-445f-a8d2-aaac39e606a2.png)
  - After
    ![image](https://user-images.githubusercontent.com/87172228/144598353-5a164618-0295-45af-b858-95ad0ed93d03.png)
 
  
  </details>
      
## [- C-mantic](https://marketplace.visualstudio.com/items?itemName=tdennis4496.cmantic )
  
<details> <summary>펼치기</summary> 
  
  **⛔JCode상의 Market Place에서 설치가 불가능하므로 상단의 [VSIX파일로 Extension 설치하기][1] 를 참고하여 설치하셔야 합니다.**
  
### What is It?
  - 코드 생성 및 리팩토링을 제공해 줍니다.
  - 정의 및 선언 추가, 변수의 getter 및 setter 생성 등을 라인 오른쪽의 전구를 눌러 쉽게 할 수 있습니다.
  
  - 정의 추가 : 함수를 선언한 뒤 정의문을 쉽게 생성해 줍니다.
  
    ![add_definition](https://user-images.githubusercontent.com/87172228/144599550-83d69697-2c08-41ef-8632-f5a32943c524.gif)
  
  - Getter & Setter 생성 : 비공개 멤버(private)에 대한 Getter와 Setter를 간편하게 생성해 줍니다.
  
    ![generate_accessors](https://user-images.githubusercontent.com/87172228/144599780-2667e79b-1603-402c-97e9-1ecdfaa6a0a0.gif)
  
  </details>
      
## [- indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow )
  
<details> <summary>펼치기</summary> 
  
### What is It?
  
  - 들여쓰기 단계에 따라 공백 부분의 색상을 다르게 칠하여 구분해 줍니다.
  
    ![image](https://user-images.githubusercontent.com/87172228/144601064-38542df6-3777-4406-819e-aaa2be04e564.png)

  - 동일한 단계의 들여쓰기에서 불필요한 공백이 추가 되었을 경우 빨갛게 칠하여 알려줍니다.
  
    ![image](https://user-images.githubusercontent.com/87172228/144601109-a8f95482-f036-43d0-b0ed-0cdf2020d151.png)

  
  </details>
      
      
## [- Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight )
  
<details> <summary>펼치기</summary> 
  
### What is It?
  
  - 파일에서 css/web 색상이 발견되면 해당 코드를 그에 맞는 색으로 색칠해 줍니다.
  
    ![image](https://user-images.githubusercontent.com/87172228/144601574-9cf15819-f42f-4725-a6cd-8c0955969cef.png)
  
  - 색을 변경 할 수 있는 Theme나 Extension에서 원하는 색으로 변경할 때에 유용합니다.


  
  </details>
  
---------

# Theme

### ⚠테마나 아이콘의 경우 하단의 Extension을 둘러보고, 본인의 취향에 맞게 더 찾아보시길 권장합니다.

- 코드 및 아이콘을 꾸며주는 테마에 관련된 Extension입니다.
- 작성자가 사용해 본 테마와 아이콘만 기재되었습니다.

각 테마를 설치 하신 후 자동 적용되지 않는 다면 왼쪽 하단의 톱니바퀴를 눌러 색 테마에서 변경하시면 됩니다.

**각 항목을 클릭 하시면 접혀 있던 설명이 펼쳐집니다!**
      
## [- Panda Theme](https://marketplace.visualstudio.com/items?itemName=tinkertrain.theme-panda )
  
<details> <summary>펼치기</summary> 
  
### What is It?

  - 특유의 파스텔톤의 색상이 전체적으로 어두운 배경와 어우러져 알록달록 하지만 밝지않아 눈이 편한 테마.
    ![image](https://user-images.githubusercontent.com/87172228/144703983-146f66c8-a315-4b77-9899-1b2eab9b5c60.png)

  
  </details>
  
  
## [- One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme )
  
<details> <summary>펼치기</summary> 
  
### What is It?

  - 모든 요소에 색을 입히되 구분은 확실히 해놓아 가독성이 좋은 테마.
      ![image](https://user-images.githubusercontent.com/87172228/144704110-c3043506-0ee8-4065-bc69-f734b8b980dd.png)

  
  - 별도의 json파일의 변경없이 설정을 변경하기 쉬움.
    ![image](https://user-images.githubusercontent.com/87172228/144704115-98033dc5-9d84-45c2-8a65-518995bd92dd.png)



  
  </details>

## [- Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme )
  
<details> <summary>펼치기</summary> 
  
### What is It?

  - 사용량이 제일 많은 테마 중 하나로 깔끔하며 기본적으로 배경이 아주 살짝 뿌옇게 보이는 것이 특징
    ![image](https://user-images.githubusercontent.com/87172228/144704362-838e837e-2fc0-4576-86a0-7c82d49642ff.png)

    
  - 하나의 테마가 아니라 material theme 안에서 여러 버전의 테마를 지원함.
    ![K-005](https://user-images.githubusercontent.com/87172228/144704412-8e61ebda-3e54-4f05-a212-b5de4053deed.png)

  
  </details>
        
## [- vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons )
  
<details> <summary>펼치기</summary> 
  
### What is It?
  
  - VSCode에서 만든 아이콘으로 자체적으로 만든 만큼 간결하고 깔끔한 아이콘이 특징.
  - 확장자 및 폴더 별 아이콘을 추가해줍니다.
    ![screenshot](https://user-images.githubusercontent.com/87172228/144704468-be034062-a574-45f4-a5b2-4ded2b8151d7.gif)

      
  </details>
      
      
## [- Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme )
  
<details> <summary>펼치기</summary> 
  
### What is It?
  
  - 파일 확장자 별 아이콘들과 폴더 다양한 폴더 아이콘들을 새롭게 추가해줍니다.
  
  - VSCode에서 읽거나 수정 가능한 거의 모든 파일에 대한 아이콘이 추가되어있음.
    ![image](https://user-images.githubusercontent.com/87172228/144704515-8d3980a4-a3ab-4b98-bce4-6069b7bd1b47.png)
  
  - 자주 분류되는 항목이나, 키워드, 언어별 폴더 아이콘들 또한 추가됩니다.
    ![image](https://user-images.githubusercontent.com/87172228/144704555-63b70889-eeb6-47cd-b395-6377dee8c4ef.png)


  

### How to Use?
  
  </details>


## 이외에도 유명한 테마들이 많으니 취향에 맞는 테마들을 직접 찾아보는 것도 하나의 재미가 아닐까요?

------

**수정할 내용이 있거나, 추천해주고 싶은 Extension이 있다면 언제든지 PR 해주세요!**

[1]: https://github.com/GangSSun/JCode_Extension_Documentation/blob/52d4bdcd45f38dd4cb3eff582a313802cf119199/Docs/how_to_install_vsix.md "VSIX"
