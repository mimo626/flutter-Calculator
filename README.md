# Flutter 중요 내용 정리

### 상태
- UI 요소의 속성에 적용되는 값들

### StatelessWidget
- 상태를 관리하는 요소가 없는 위젯
- 상태 관리를 하는 요소가 없기 때문에 눈에 보이는 UI요소에 대해 값을 지정하는 작업을 직접해줘야 한다.
- 비교적 구조가 간단하다.
- 눈에 보이는 요소를 위젯이 직접 관리한다.
- 어플 실행 후 종료 될 때까지 절대 변하는 부분이 없을 경우 사용한다.

### StatefulWidget
- 상태를 관리하는 요소가 있는 위젯
- 상태 관리 요소가 있기 때문에 상태 값을 변경시키는 것만으로 UI 요소에 변화를 줄 수 있다.
- 구조가 StatelessWidget 비해 조금 복잡하다.
- 눈에 보이는 요소를 상태 관리 요소가 관리한다.
- 어플 실행 후 종료 될 때까지 변하는 부분이 있는 경우 사용한다.

### Container
- 눈에 보이는 UI 요소들을 배치하는 요소
- Container는 배치되는 모양이나 기능에 따라 여러 가지가 제공된다.
- 안드로이드 네이티브에서 layout 에 해당하는 부분이다.

### Scaffold
- 눈에 보이는 화면의 전체적인 구조를 관리하는 요소이다.
- 상단 앱바, 하단 네비게이션바, 플로팅 버튼 등등을 설정할 수 있다.# Flutter 중요 내용 정리

### 상태
- UI 요소의 속성에 적용되는 값들
