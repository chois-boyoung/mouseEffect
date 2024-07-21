jquery를 사용한 mouse effect

clientX : 브라우저 페이지를 기준으로 X좌표의 위치를 반환
clientY : 브라우저 페이지를 기준으로 Y좌표의 위치를 반환
offsetX : 선택한 객체를 기준으로 X좌표의 위치를 반환
offsetY : 선택한 객체를 기준으로 Y좌표의 위치를 반환
pageX : 브라우저 페이지를 기준으로 X좌표의 위치를 반환
pageY : 브라우저 페이지를 기준으로 Y좌표의 위치를 반환
screenX : 모니터 스크린을 기준으로 X좌표의 위치를 반환
screenY : 모니터 스크린을 기준으로 Y좌표의 위치를 반환

- 최솟값 구하기
let min = Math.min(100, 200)

- 최댓값 구하기
let max = Math.max(100, 200)


//
let xx = 100;
let yy = 200;
let zz = Math.min(xx, yy);

- 배열로 구하기
arr = [100, 200, 300]
let max = Math.max(...arr)

- 주어진 숫자보다 크거나 같은 숫자 중 가장 작은 숫자
let ceil = Math.ceil(0.95) //1 (반올림)

- 주어진 수 이하의 가장 큰 함수
let floor = Math.floor(39.36) //39

- 입력값을 반올림한 값과 가장 가까운 정수 출력
let round = Math.round(20.49) //20
let round = Math.round(20.6) //21

//랜덤 0-1 사이의 값
let random = Math.round(Math.random() * 10) //정수로 나옴