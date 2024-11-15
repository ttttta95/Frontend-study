## Redux
리액트에서 가장 많이 사용되는 상태관리를 위한 라이브러리

### 개념
기본적인 상태관리 흐름은 context api와 유사하다. 어플리케이션의 상태를 객체로 관리하고 이를 구독하는 방식으로 움직인다는 것은 동일하다.
redux에서 사용되는 용어는 스토어, 액션, 디스패치, 리듀서가 있다.
스토어는 상태를 가지고 있으며 컴퍼넌트는 디스패치 함수를 통해 액션을 리듀서로 전달한다. 그리고 상태는 리듀서에 의해서만 변경이 가능하고 컴포넌트는 이러한 상태를 구독하게 되는 것이다.

<img https://mblogthumb-phinf.pstatic.net/MjAyMDAzMDhfMTQ2/MDAxNTgzNjMzNTQwNjUy.PXwD1gycPobFP3-IS7eiwI71_nk-ODsRk8KGiQJoU9cg.tPkdDd6GPW_gp6Uwt0l6oqkimD9Sn2kQIPNx2w_9o-0g.PNG.wj8606/JYrQR.png?type=w800 />
