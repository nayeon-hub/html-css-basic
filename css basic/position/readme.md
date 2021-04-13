### position

- position의 종류 : static / relative / absolute / fixed / sticky

- 각 position의 특징들

  1. static
  2. relative

     - 자신이 있었던 자리를 기준으로 움직인다.
     - 부모도 relative상태의 자식요소를 인식하여 부모요소의 공간적 변화는 없다.

  3. absolute

     - float와 특징이 비슷하다.

       - 부모가 absolute 상태인 자식요소를 인식하지 못한다.
       - display : block이지만 auto margin이 없다.
       - inline 요소들이 이 요소를 인식하지 못한다.(float와의 차이점)

     - 부모나 조상의 요소가 "relative/absolute/fixed/sticky" 상태라면 그 부모나 조상을 기준으로 움직인다.

  4. fixed

     - absolute와 특징이 비슷하다. 차이점이라면 기준점이 fixed는 viewport이다.
