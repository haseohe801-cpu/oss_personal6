Deployment: GitHub URL, Vercel URL, MockAPI Endpoint URL

///////////////////////////////////////////////////////

Service: 주제, Field, CRUD 기능

주제: 상품관리
Field: id, name, category, price, stock

CRUD 기능
Create: Form 상품 정보를 fetch의 POST로 MockAPI에 추가하고 목록을 다시 불러온다.
Read: 페이지가 열릴 때 fetch의 GET으로 목록을 가져와 render 함수로 출력한다.
Update: 수정 버튼을 누르면 데이터를 Form에 표시하고, 수정한 내용을 PUT으로 서버에 반영한다.
Delete: 삭제 버튼 누르면 confirm으로 확인한 후 DELETE로 서버에서 삭제한다.
추가_
Validation: 상품명 비어 있음 / 상품명 20글자 이하 / 카테고리 선택 / 가격 0 초과 / 재고 0 이상 정수

///////////////////////////////////////////////////////

Key Learning: fetch(), JSON, async/await, REST API 등 배운 내용 3가지

fetch()로 서버에 요청을 보내고 await로 응답을 기다리는 방법을 배웠다.
response로 성공 여부를 확인하고 try/catch로 오류를 처리하는 것을 알게 되었다.
response.json으로 서버 응답을 JavaScript 배열로 바꿔 화면에 출력하는 방법을 알게 되었다. 서버에 데이터를 보낼 때는 JSON.stringify로 body에 담아 보낸다는 흐름을 배웠다.

GET POST PUT DELETE가 조회 추가 수정 삭제에 해당한다는 것을 배웠다.
수정과 삭제는 주소 뒤에 id를 붙여서(/products/id) 어떤 데이터인지 알려줘야 했다. (몰라서 조금 헤멨음)

///////////////////////////////////////////////////////

AI / Search Usage: 사용 내역과 본인 추정 AI 코드 기여율(%)

이번 과제에서 form.addEventListener 부분의 코드가 매우 어려워서
AI를 이용하여 문법적 오류 검사에 사용하였다. 또한 논리흐름을 AI에게 알려주고, 세부적인 작성을 AI에게 맡겼다. 이러한 개인적으로 AI가 이 코드에 기여한 비율은 50%라고 생각한다. 왜냐하면 Tab키를 이용한 자동 완성기능을 적극적으로 사용하였고, 세부적인 문법에서 AI를 사용해 체크를 하였기 때문이다.

///////////////////////////////////////////////////////

Problem & Solution / Reflection: 문제 해결 및 느낀 점

mockAPI 웹사이트에서 id가 undefined 된 문제점이 있었다.
이 문제를 AI를 활용하여 Edit 부분의 변수 이름을 고쳐 해결하였다.
개인적으로 try catch 구문은 1학년 자바 스트립트를 할 때 빼고는 사용해 보지 못했다. 그래서 form.addEventListener이 부분을 구현할 때 어려움을 겪었다. async function 또한 처음에 어려웠지만, 과제를 하며 익숙해져 나갔다.