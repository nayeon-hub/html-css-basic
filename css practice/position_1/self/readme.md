나만의 feedback

- clearfix class 만들기

  float를 사용하여 가로배치할 때 따로 클래스를 지정해줘서 코드 중복을 하지 않도록!

  ```
  .clearfix::after {
    content: "";
    display: block;
    clear: both;
  }
  ```

- status div vs span

-position을 위한 html 구조
status box는 전체(body or card div)에서의 상대적인 위치보다는 photo img와의 상대적인 위치가 더 의미있다.
