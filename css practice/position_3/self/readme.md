나만의 feedback

-before : .modal 전체에 text-align: center를 적용함
이유 : h1, p, div를 가운데 정렬하려고
-> 그러나 h1,p,div는 box로 layout 관련 가운데 정렬이다.

-after : .modal 전체에 text-align을 적용하는 것이 아닌 h1,p,div에 각각 적용해주어 그 안에 text를 가운데 정렬하는게 더 의미가 있다.
-> h1,p,div는 block & p가 가장 width길이가 길어서 p를 기준으로 전체 길이가 맞춰져 있음. layout 가운데 정렬 적용이 아직은 불필요.

-translate 현재 위치한 기준점을 기준으로 요소를 x,y,z 축으로 이동한다.

-p태그 : width를 설정하면 자동으로 margin이 생성되어 text-align: center가 안먹힌다고 착각할 수 있다. 반드시 margin을 확인해볼 것
margin : 0 auto;

-position관련 : 위치를 변경할 때 요소의 top 가장 왼쪽점이 움직이는 것이다.
