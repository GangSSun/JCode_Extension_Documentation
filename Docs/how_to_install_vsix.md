# vsix파일로 Extension 설치하기

## 해당 문서의 extension의 경우 대부분 market place 혹은 Github에서 vsix 파일을 제공합니다.

1. vsix 파일을 먼저 다운로드하여 디렉토리에 추가합니다.

      a. 설치하려는 디렉토리에서 wget 명령어를 통해 vsix파일을 다운로드합니다.
      
      ``` wget https://github.com/microsoft/vscode-cpptools/releases/download/1.7.1/cpptools-linux.vsix ```
  
      b. 설치하려는 extension의 vsix 파일을 다운로드 한 뒤, 파일을 그대로 드래그 하여 JCode 상의 디렉토리에 옮겨 복사합니다.
      
2. Market Place의 기타 작업에서 VSIX에서 설치를 선택합니다.

     ![image](https://user-images.githubusercontent.com/87172228/144238347-fc684169-8f80-4984-b5d3-69516c024b34.png)

3. 설치하려는 VSIX파일의 경로를 입력해줍니다.

    ![image](https://user-images.githubusercontent.com/87172228/144238608-6c9311ea-fcc6-4161-8379-8820b2b9f5cd.png)

    ![image](https://user-images.githubusercontent.com/87172228/144238710-94be01b8-bdc5-4767-830a-cde765873d0a.png)

4. 설치 완료 메세지 확인 후 ctrl+shift+p를 눌러 Reload Window 명령어를 실행해 창을 Reload 해줍니다.

    ![image](https://user-images.githubusercontent.com/87172228/144238823-7fafa7b1-623e-412b-a9d5-fcbd13c28a50.png)
    
    ![image](https://user-images.githubusercontent.com/87172228/144239070-1ac5c4b8-b63e-457c-84e6-3b9fe98b2560.png)
