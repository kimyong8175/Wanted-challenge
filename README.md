# Wanted-challenge
### Q1. 내가 생각하는 클린 코드란?
클린코드란 간결하며 직접적이기 때문에 읽기 쉽고, 각 역할마다 주어진 하나의 일만 담당하는, 따라서 복합하거나 모호하지 않은 코드라고 생각합니다.
### Q2. 내가 생각하는 (프론트엔드에서의) 클린 코드란?
프론트엔드 개발자는 백엔드 개발자, 디자이너와 같이 협업하기 때문에 코드의 파악이 쉬워야 한다고 생각합니다. 또한, 코드의 파악이 쉽기 때문에 디버깅 시간 및 유지 보수의 시간이 단축된다고 생각합니다.
### Q3. 내가 클린코드보다 중요하게 생각하는 것은?
일단 기능이 돌아가게 하는 것이 중요하다고 생각합니다. 아무리 명확하고 단순한 코드일지라도 제대로 된 기능 구현을 하지 못한다면 그 코드는 제대로 된 역할을 하지 못한다고 생각합니다.
### Q4. 다음 중 선호하는 방식과 그 이유는?
##### 1.
`Tab` vs `Space`

`Tab`을 더 선호합니다. 왜냐하면 `Tab`은 기본적으로 4칸이기 때문에 1칸인 `Space`보다 시간을 단축시켜 줍니다.

##### 2.
`세미콜론 O` vs `세미콜론 X`

코드의 끝을 명확하게 나타내 줄 수 있는 `세미콜론`이 있는 코드가 더 가독성이 좋다고 생각합니다.

##### 3.
`count++;` vs `count += 1;` vs `count = count + 1;`

`count += 1`을 선호합니다. 왜냐하면 개인의 기호로 가장 가독성이 높다고 생각합니다.

##### 4.
`if (isLogin) {}` vs `if (isLogin === true) {}`

Boolean값으로 사용하는 코드는 코드의 양을 줄여주는 `if (isLogin) {}`을 더 선호합니다.

##### 5.
`isLogin && <HelloWanted />` vs `isLogin ? <HelloWanted /> : <></>` vs `isLogin ? <HelloWanted /> : null` vs `isLogin ? <HelloWanted /> : undfined`
isLogin이 거짓인 경우에는 무시되기 떄문에 더 코드가 간결한 `isLogin && <HelloWanted />`을 선호합니다.
