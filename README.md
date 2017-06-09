# Java-Interview-QnA
자바 면접 질문과 답

### Q1. 기본 자료형(primitive data type)과 참조 자료형(reference data type)에 대해 설명하시오.
기본 자료형은 byte, short, int, long, float, double, char, boolean이 존재합니다. 기본 자료형으로 생성한 변수에는 값 자체가 저장됩니다. 사용전에 반드시 선언되어야하며 OS에 따라 자료형의 길이가 변하지 않고 null 값을 갖을수 없는 특징이 있습니다.

참조 자료형은 class, interface, array, enum이 존재합니다. 참조 자료형으로 생성한 변수에는 객체의 주소값이 저장됩니다. 생성자를 이용하여 새로운 객체의 주소를 가리키거나 null 값을 이용하여 해제할 수 있습니다.

### Q2. 객체지향 프로그래밍(object-oriented programming)에 대해 설명하시오.

### Q3. 다형성(polymerphism)에 대해 설명하시오.

### Q4. 접근제어자(access modifier)에 대해 설명하시오.
접근제어자는 객체지향 프로그래밍에서 클래스의 멤버 변수 또는 메소드에 설정하는 키워드로 접근 영역을 제한하는데 사용합니다.

public, default, protected, private이 존재합니다. 접근제어자를 사용하지 않았을 경우에는 기본적으로 default를 갖습니다. public은 접근 제한을 하지 않음을 의미합니다. default는 같은 패키지 내에서만 접근이 가능함을 의미합니다. protected는 같은 패키지 내 혹은 다른 패키지의 자식 클래스에서 접근이 가능함을 의미합니다. private는 같은 클래스 내에서만 접근이 가능함을 의미합니다.
