#### This package has forked from [react-beautiful-dnd](https://github.com/atlassian/react-beautiful-dnd.git)

## 수정내용

##### Droppable 에 droppableRangeType 옵션 추가
droppableRangeType: drop 가능 범위를 설정한다.
- center: (default) drop 가능한 범위를 아이템의 중앙으로 설정한다. 아이템이 절반 이상 벗어나는 경우 drop 되지 않는다.
- overlap: 아이템이 drop 영역과 겹쳐있다면 drop 가능하다. 완전히 밖으로 벗어난 경우 drop 되지 않는다.
- infinite: 범위 무제한. drop 영역과 무관하게 가장 근접한 위치에 drop 한다. Droppable 이 하나일때만 사용해야 함.

