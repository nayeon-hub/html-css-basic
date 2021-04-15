나만의 feedback

- user-info-item 안에 있는 dt,dd는 block
- dt,dd의 width가 자동 user-info-item(부모)의 width와 같다.
- layout에 대한 가운데 정렬보다는 block 각각의 문서에 대한 가운데 정렬이 좀 더 의미가 있지 않을까(요소들이 block 상태이기 때문에)
- display:flex, justfy-content: center를 user-info-item div에 사용하기보다는 text-align : center을 쓰는게 더 맞는 것 같다.
- display:flex를 너무 남용하지 말고 문서적인 가운데 정렬인지 box layout에 대한 가운데 정렬인지 생각해볼것!

-image의 width,height를 설정할 경우 inline-block로서의 오차를 줄이기 위해 display: block으로 바꿔줄 것

-div의 불필요함? 가운데정렬을 하려고 user div를 만들 이유 없는 것 같다. profile div에서 전체를 한번에 가운데 정렬을 할 수 있다. 현재 user-info dl은 가운데 정렬이 되지 않았다.
