# 유니티 허브(Unity Hub)용 'modules.json'
유니티 허브(Unity Hub)용 'modules.json' 파일 모음입니다.
유니티(Unity)를 설치하자마자 추출한 파일입니다.

유니티를 수동으로 설치하면 유니티 허브에서 재대로 인식을 하지 못하는 경우가 있습니다.
이럴 때 유니티를 재설치하지 않고 유니티 허브에서 동작시키기 위한 파일입니다.

[github에서 보기](https://github.com/dang-gun/UnityHub_ModulesJson)


## 왜 필요합니까?
유니티(Unity)를 수동으로 설치하고 유니티 허브(Unity Hub)에 추가한 후 다음과 같은 오류가 발생할 때 사용됩니다.
 
- 'Add Modules'가 나타나지 않는 경우
![When ‘Add Modules’ ?](https://raw.githubusercontent.com/dang-gun/UnityHub_ModulesJson/main/Images/UnityHub_error_001_001.png)

- 'Unity 2022.3.20f1 is no longer available from the Hub. For a better experience, we recommend the latest LTS (Long-Term Support) version. You can find all Editor versions in the Installs Archive.' 오류
![no longer available](https://raw.githubusercontent.com/dang-gun/UnityHub_ModulesJson/main/Images/UnityHub_error_001_002.png)


## 사용방법

1. 유니티 허브(Unity Hub)가 설치된 폴더(기본값> C:\Program Files\Unity\Hub\Editor)에 추가하려는 버전 이름으로 폴더를 생성합니다. (예> 2022.3.20f1)
![Create a folder](https://raw.githubusercontent.com/dang-gun/UnityHub_ModulesJson/main/Images/UnityHub_error_001_003.png)

1. 생성한 폴더에 버전(예> 2022.3.20f1)에 맞는 'modules.json' 파일을 넣습니다.

1. 따로 설치한 유니티(Unity Editor)의 설치 폴더에 있는 'Editor' 폴더(기본값> C:\Program Files\Unity [버전])를 생성한 폴더(예> 2022.3.20f1)로 옮깁니다.
![Move the ‘Editor’](https://raw.githubusercontent.com/dang-gun/UnityHub_ModulesJson/main/Images/UnityHub_error_001_004.png)

이제 유니티 허브(Unity Hub)를 싱행하면 추가된 버전이 표시되고 'Add Modules'가 제대로 작동합니다.
![works properly](https://raw.githubusercontent.com/dang-gun/UnityHub_ModulesJson/main/Images/UnityHub_error_001_005.png)


## 기여
자신이 가지고 있는 ‘modules.json’파일을 올리고 싶다면 '풀 리퀘스트(pull request)'를 통해 기여해 주시기를 바랍니다.

#### 기여 시 주의 사항

- 버전에 맞는 파일만 올려주세요.
- 다른 파일은 수정하지 마세요.


## 해결되지 않은 문제
유니티 허브(Unity Hub)의 'Locate'로 추가하기만 하면 돼야 할 것 같은데 되지 않습니다.
반듯이 유니티 허브가 설치된 폴더에서만 동작합니다.
이 문제에 대한 해결법을 아신다면 이슈에 남겨주세요.