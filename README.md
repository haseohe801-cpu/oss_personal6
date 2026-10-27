Deployment

배포 URL: https://oss-personal5.vercel.app/

Key Learning

이번 주에는 JavaScript의 DOM, Event, Array를 활용한 과제를 진행했다.
웹 페이지를 동적으로 만드는 방법을 배웠다.
HTML의 입력값을 JavaScript로 가져오고 Array에 저장한 뒤 다시 화면에 출력하는 과정을 직접 구현해 보았다.

CRUD Service

주제: 상품관리
데이터 Field: id, 상품명, 카테고리, 가격, 재고
Form에 입력한 상품 정보를 JavaScript Array에 추가
Read: Array의 데이터를 render() 함수로 가져와 Table에 출력
Update: 수정 버튼을 누르면 기존 데이터를 Form에 표시하고 수정한 내용을 Array에 다시 저장
Delete: 삭제 버튼을 누르면 confirm()으로 확인한 후 Array에서 해당 데이터를 삭제

JavaScript

이번 과제에서는 JavaScript를 이용하여 HTML 요소를 가져오고 사용자의 동작에 따라 화면을 변경하였다.

getElementById: HTML 요소 JavaScript에서 가져오는 데 사용
ddEventListener: 버튼 클릭이나 Form 제출 같은 이벤트 처리하는 데 사용
createElement: 새로운 HTML 요소 생성하는 데 사용
appendChild: 생성한 요소 화면에 추가하는 데 사용
Array: 상품 데이터를 저장하는 임시 데이터 저장소로 사용
push: 새로운 상품 Array에 추가
find: 수정할 상품 찾는 데 사용
filter: 삭제할 상품을 제외하여 Array를 다시 만들 때 사용
render: Array의 데이터 Table에 다시 출력하여 화면을 갱신하는 데 사용

AI / Search Usage

AI를 사용하여 JavaScript DOM과 Array를 활용한 CRUD 구현 방법을 참고하였다.
Array의 push(), find(), filter()를 CRUD 기능에 어떻게 적용하는지 확인하고 실제 코드에 적용하였다.

또한 render() 함수를 사용하여 Array의 데이터를 화면에 다시 출력하는 방법을 이해하는 데 도움을 받았다.
이를 통해 데이터를 변경한 후 Array의 데이터를 기준으로 화면을 다시 만드는 방법을 알게 되었다.

CSS 부분을 할 때 눈에 잘 띄지 않는 오류를 잡아낼 때 사용했다.

Problem & Solution

처음에는 상품을 추가하거나 삭제했을 때 JavaScript Array의 데이터와 화면의 내용이 같이 변경되어야 한다는 점이 어려웠다.
해결하기 위해 데이터를 변경한 다음 render() 함수를 호출하여 Array의 내용을 출력해 해결하였다.
CSS 부분을 할 때 쓸데없는 오타가 많아 헷갈렸다. AI에게 검수를 부탁해 오류를 찾아 해결했다.

Reflection

이번 과제를 통해 JavaScript가 HTML 요소를 직접 가져오고 변경할 수 있다는 것을 알게 되었다. 특히 Array에 데이터를 저장하고 render()를 이용하여 리로드하는 방식이 CRUD의 동작과 연결된다는 것을 이해했다.

Create와 Update에서 입력값을 검사하는 Validation을 반복적으로 하다보니 보안 관련한 것도 궁금해졌다.
