var와 let, const의 가장 큰 차이는 스코프

var은 재선언 가능, let은 불가. 이미 선언되었다는 오류 발생.
var은 호이스팅으로 선언 이전에 변수 사용 가능했지만 let은 선언되지 않은 변수라 사용할 수 없다는 오류남.

const도 마찬가지로 재선언 불가, 상수이므로 재할당 불가

변수로 인한 오류를 줄이기 위해 let과 const를 사용하자.
