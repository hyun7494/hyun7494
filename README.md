## 📌 컨벤션
- 변수 명칭 정하기 
  - True : 11
  - False : 99

- PathVariable에는 Camel Case사용하지 않기 → snake case(product_id)

- Commit❗

  - `Feat` :새로운 기능 추가

  - `Fix` : 버그 수정

  - `Docs` : 문서 수정

  - `Style` : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우

  - `Refactor` : 코드 리펙토링

  - `Test` : 테스트(테스트 코드 추가, 수정, 삭제, 비즈니스 로직에 변경이 없는 경우)

  - `Chore` : 위에 걸리지 않는 기타 변경사항 (빌드 스크립트 수정, assets image, 패키지 매니저 등)
  - 

  - `Design` : CSS 등 사용자 UI 디자인 변경

  - `Comment` : 필요한 주석 추가 및 변경

  - `Init` : 프로젝트 초기 생성

  - `Rename` :파일 혹은 폴더명 수정하거나 옮기는 경우

  - `Remove` :파일을 삭제하는 작업만 수행하는 경우

### Branch:man_technologist:
#### 1. main

제품으로 출시 될 수 있는 브랜치

- 모든 기능이 추가되고 버그가 수정되어 **배포가능한 release 브랜치를 병합**한다.

#### 2. develop branch

다음 출시 버전을 개발하는 브랜치

- 기능 개발을 위한 브랜치 (feature) 를 병합하기 위해 사용한다.
- **새로운 기능에 대한 feature 브랜치를 병합**한다.

#### 3. Supporting branches

- **feature branch**
    
    기능을 개발하는 브랜치
    
    - **기능마다 feature 브랜치를 생성**한다.
    - **개발이 완료된 기능만 frontend / backend 브랜치로 병합**한다.
    - 병합한 이후에는 **feature 브랜치를 삭제**한다.
- **hotfix branch**
    
    출시 버전에서 발생한 버그를 수정하는 브랜치
    
    - 배포 버전에서 긴급하게 수정을 해야 할 필요가 있는 경우 **main 브랜치를 분기하여 수정을 하기 위한 브랜치**이다.
