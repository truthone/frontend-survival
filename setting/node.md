- node 홈페이지에 또는 npm으로 node LTS 버전 설치하기
- fnm으로 node lts 버전 설치하기 
    - node 버전을 관리하는 mpn 보다 더 빠르다.
    - windows 사용자는 Scoop 또는 Chocolatey를 사용해 설치할 수 있다.
    - scoop 설치하고 fnm 설치하기
    - powershell 또는 cmd 실행하여 scoop 설치 커맨드 실행
        ```
        > Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
        
        > Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
        ```
    - 설치후, scoop으로 fnm 설치 커맨드 실행
        ```
        > scoop bucket add extras
        > scoop install fnm
        ```
    - fnm 설치후, fnm으로 node lts 설치하기 
        ```
        > fnm install --lts
        ``` 