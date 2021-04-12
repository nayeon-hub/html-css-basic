### float(가로배치)

- 특징

  - float를 하는 순간 부모요소는 float된 자식요소를 인식하지 못한다.
  - float를 적용하는 순간 display:block;상태가 된다.(즉, block상태에서 적용할 수 있는 property 모두 적용 가능해진다.)
  - block상태가 됐을 때, width를 설정하지 않는 경우, 부모의 width에 의존하지 않으며 content만큼 width가 자동설정 된다. + auto margin도 사라진다.
  - 공간이 없을 경우 아래로 배치된다.

- fixed
  1. 부모에게 overflow : hidden;을 설정해준다.
  2. clearfix 사용
     - 부모가 가상요소를 만들고 clear property를 사용한다.
     - 가상요소를 만들어서 부모가 float상태의 자식요소가 있는 공간을 인식할 수 있도록 한다.
     ```
      .parent::after {
        content : "";
        display : block;
        clear: left; //clear는 display가 block일 경우만 사용 가능
      }
     ```
