# WIL1
1. AnimatedOpacity: 지정된 opacity가 변경될 때마다 지정된 duration동안 child의 opacity를 자동으로 애니메이션한다. 미용 메뉴에서 불투명도가 서서히 변경되도록 만듦, 체크 박스가 생기고 사라질 때 불투명도를 조절하게 만듦.
    * Properties
        - alwaysIncludeSemantics
        - child
        - opacity
    * Methods
        - createState()
        
2. AnimatedPositioned: Stack 위젯에서 자식의 위치를 제어하며, 지정된 위치가 변경될 때마다 지정된 기간동안 자식의 위치를 자동으로 애니메이션한다.
    * Properties
        - bottom
        - child
        - height
        - left
        - right
        - top
        - width
    * Methods
        - createState()

3. GestureDetector: 제스쳐 기능을 지원하지 않는 위젯에 제스쳐 기능을 제공하는 래핑 위젯
    * Properties
        - behavior
        - child
        - onTap
    * Methods
        - build

## 질문
1. Flutter Widget에 대해 잘 정리돼 있는 공식 영상이 있을까요?
2. GestureDetector를 사용하는 실제 예를 알고 싶습니다!

