# Unity Hub 'modules.json'
This is a collection of ‘modules.json’ files for Unity Hub

## Why use it?
It is used when the following error occurs after manually installing Unity and adding it to Unity Hub.
 
- When ‘Add Modules’ does not appear
- Unity 2022.3.20f1 is no longer available from the Hub. For a better experience, we recommend the latest LTS (Long-Term Support) version. You can find all Editor versions in the Installs Archive.

## 사용방법

1) 유니티 허브가 설치된 폴더(기본값> C:\Program Files\Unity\Hub\Editor)에 추가하려는 버전의 이름으로 폴더를 생성합니다.
2) 생성한 폴더에 버전에 맞는 'modules.json'파일을 넣어줍니다.
3) 생성한 폴더에 별도로 설치한 유니티(유니티 에디터)의 설치폴더(기본값> C:\Program Files\Unity [버전])에있는 'Editor'폴더를 옮깁니다.

이제 유니티 허브를 실행하면 추가한 버전이 표시되고 'Add Modules'도 정상적으로 동작합니다.