# 🔴JCode_Extension_Documentation
## JCode에서 사용이 가능한 확장들을 정리한 문서

우리가 공부하기 전에 책상정리를 하는 것 처럼
코딩을 하기 전에 우리가 사용할 개발 환경을 각자에 맞게 정리하고, 꾸미고, 확장 시킨다면 어떨까요?

코딩을 하다가 지루하시다면 차 ☕ 한잔 하면서 천천히 읽으며 하나씩 설치 해 보시는건 어떨까요?

**코딩이 재미 없다면 먼저 꾸며보세요!**

*(본 문서의 Extension은 JCode에서 원활히 작동하는 것을 원칙으로 하며, 작성자의 주관이 들어가있음을 알립니다.)*



---------



### - [VSIX 파일로 Extension 설치하기](https://github.com/GangSSun/JCode_Extension_Documentation/blob/52d4bdcd45f38dd4cb3eff582a313802cf119199/Docs/how_to_install_vsix.md)
  

  
  
**각 항목을 클릭하면 해당 Extension의 marketplace로 이동합니다.**

**문단명 아래의 펼치기를 클릭하시면 접혀 있던 설명이 펼쳐집니다!**

# Extra Feature 

VS Code에 새로운 기능을 추가하는 익스텐션들입니다.



## [- C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
<details> <summary> 펼치기 </summary> 

**⚠C/C++ Extension의 경우 JCode의 마켓플레이스에서 다운 받아 설치하게 될 경우 arm버전이 설치됩니다.**
  
**JCode의 프로세서는 x86이기 때문에 Extension의 모든 기능을 온전히 사용할 수 없습니다.**

**번거롭더라도 linux_x86_64버전을 상단의 [VSIX파일로 Extension 설치하기][1] 를 참고하여 설치하셔야 합니다.**
  
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

  

### How to Use?
  
  </details>
    
## [- diff](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-diff )
  
<details> <summary>펼치기</summary> 
  
### What is It?


### How to Use?
  
  </details>
  
---------

# UI / Theme

VS Code 전반에서 사용되는 UI 요소와 관련된 익스텐션들입니다.

**각 항목을 클릭 하시면 접혀 있던 설명이 펼쳐집니다!**
    
## [- Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2 )
  
<details> <summary>펼치기</summary> 
  
### What is It?


### How to Use?
  
  </details>
      
## [- Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) 
  
<details> <summary>펼치기</summary> 
  
### What is It?


### How to Use?
  
  </details>
      
## [- Better C++ Syntax](https://marketplace.visualstudio.com/items?itemName=jeff-hykin.better-cpp-syntax )
  
<details> <summary>펼치기</summary> 
  
### What is It?


### How to Use?
  
  </details>
      
## [- C-mantic](https://marketplace.visualstudio.com/items?itemName=tdennis4496.cmantic )
  
<details> <summary>펼치기</summary> 
  
### What is It?


### How to Use?
  
  </details>
      
## [- indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow )
  
<details> <summary>펼치기</summary> 
  
### What is It?


### How to Use?
  
  </details>
      
## [- panda thema](https://marketplace.visualstudio.com/items?itemName=tinkertrain.theme-panda )
  
<details> <summary>펼치기</summary> 
  
### What is It?



### How to Use?
  
  </details>
      
## [- vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons )
  
<details> <summary>펼치기</summary> 
  
### What is It?


### How to Use?
  
  </details>
      
## [- Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme )
  
<details> <summary>펼치기</summary> 
  
### What is It?


### How to Use?
  
  </details>
      
## [- Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme )
  
<details> <summary>펼치기</summary> 
  
### What is It?


### How to Use?
  
  </details>
      
## [- Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight )
  
<details> <summary>펼치기</summary> 
  
### What is It?


### How to Use?
  
  </details>
      
## [- One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme )
  
<details> <summary>펼치기</summary> 
  
### What is It?


### How to Use?
  
  </details>
  

**수정할 내용이 있거나, 추천해주고 싶은 Extension이 있다면 언제든지 Pull requests 해주세요!**

[1]: https://github.com/GangSSun/JCode_Extension_Documentation/blob/52d4bdcd45f38dd4cb3eff582a313802cf119199/Docs/how_to_install_vsix.md "VSIX"
