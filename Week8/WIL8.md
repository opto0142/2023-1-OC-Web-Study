# Javascript

Hello world

console.log('hello world');


javascript는 타 언어와 다르게, 변수를 선언할 때 데이터 타입을 미리 지정하지 않고, 변수에 할당된 값의 타입에 의해 동적으로 변수의 타입이 결정된다. -> 동적 타이핑


원시 타입(Primitive Data Type)은 immutable한 값이며, pass-by-value.


javascript는 C언어와 달리 특별한 시작점이 없으며, 즉시 해석되고 실행되므로 전역변수 선언 위치의 제약이 없다. 따라서 전역변수 선언을 남발할 수 있는데, 이러다보면 변수의 이름이 중복될 수 도 있고, 의도치 않은 재할당이 일어날 수 도 있다.->주의하자


var VS let VS const

ES6은 var를 사용하지 않는다.

let: 재할당이 필요한 경우(변수의 스코프는 최소화 한다)

const: 재할당이 필요 없는 경우, 원시 값과 객체에는 const를 사용하는 것이 안전하다.(재할당을 못하게 하므로)