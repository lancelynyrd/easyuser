# 사용자

회원 관리 패키지


## 사용법


여러분이 사용하는 앱에서 `easyuser` 패키지를 추가하여 사용하는데, 그 앱에서 추가한 다른 패키지들 중 하나가 `easyuser` 패키지를 사용할 수도 있습니다. 그냥 같이 사용을 하면 됩니다. 일반적으로 어떤 패키지가 `easyuser` 패키지를 사용 할 경우, 앱에서 사용하면 (초기화를 하면) 패키지에서는 초기화를 하지 않습니다.



## 초기화

`UserService.instance.init()` 함수는 한번만 초기화를 하도록 되어져 있습니다. 그래서 앱에서 초기화를 하는 경우, 종속된 패키지가 `easyuser` 패키지를 사용한다고 해도 두 번 초기화를 하지 않고, 앱의 초기화 된 설정을 이어서 계속 진행합니다.







## 사용된 패키지 목록

```yaml
  cached_network_image: ^3.3.1
  cloud_firestore: ^5.0.2
  date_picker_v2: ^0.0.4
  easy_helpers: ^0.0.3
  easy_storage: ^0.0.2
  firebase_auth: ^5.1.1
  firebase_ui_firestore: ^1.6.4
  memory_cache: ^1.2.0
  rxdart: ^0.27.7
```


