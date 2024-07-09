# android-map-keyword
**카카오 테크 캠퍼스 STEP2 Android 3주차 미션 - 검색어 저장**
## 기능 요구사항
### 1단계 기능
- 검색어를 입력하면 검색 결과가 15개 이상 표시된다.
- 검색 결과 목록은 세로 스크롤이 된다.
- 입력한 검색어는 X를 눌러서 삭제할 수 있다.
- 검색 결과 목록에서 하나의 항목을 선택할 수 있다.
- 선택된 항목은 검색어 저장 목록에 추가된다.
- 저장된 검색어 목록은 가로 스크롤이 된다.
- 저장된 검색어는 X를 눌러서 삭제할 수 있다.
- 저장된 검색어는 앱을 재실행하여도 유지된다.
### 2단계 기능
- 앱을 처음 실행하면 지도 화면을 표시한다.
- 검색창을 선택하면 검색 화면으로 이동한다.
- 검색 화면에서 뒤로 가기를 하면 지도 화면으로 돌아온다
## 프로그래밍 요구사항
### 1단계 요구사항
- 검색 데이터는 카카오로컬 API를 사용한다.
- 카카오 API 사용을 위한 앱 키를 외부에 노출하지 않는다.
- 가능한 MVVM 아키텍처 패턴을 적용하도록 한다.
- 코드 컨벤션을 준수하며 프로그래밍한다.
### 2단계 요구사항
- 카카오지도 SDK를 사용한다.
- 가능한 MVVM 아키텍처 패턴을 적용하도록 한다. 
- 코드 컨벤션을 준수하며 프로그래밍한다.
## 구현할 기능 목록
### 1단계 기능
- [x] DTO 생성
- [x] RetroFit을 이용한 API 호출
- [x] 검색 결과 15개 이상 표시
- [x] MVVM 패턴 적용
### 2단계 기능
- [ ] 카카오 지도 SDK 적용
- [ ] 검색창 클릭 시 검색 액티비티 이동
- [ ] MVVM 적용
