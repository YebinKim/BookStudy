"**객체가 수행하는 행동에 의하여 객체의 타입이 결정**된다."

"행동에 따라 객체를 분류하기 위해서는 **객체가 외부에 제공해야하는 행동 고려**해야한다."

"**일반화는 추상화를 위한 도구**이다."

## 추상화를 통한 복잡성 극복

### 추상화

- 특정 절차나 물체를 의도적으로 생략하거나 감춤으로써 복잡도를 극복하는 방법
- 추상화는 **복잡성을 이해하기 쉬운 수준으로 단순화**하는 것이다.
- 2가지의 차원
  - 차이점을 버리고 **공통점만을 취하는 일반화**
  - 불필요한 세부사항을 제거하여 **중요한 부분을 강조**

## 객체지향과 추상화

- 객체 

  - 명확한 경계를 가지고 서로 구별할 수 있는 구체적인 것

    = 특정 개념을 적용할 수 있는 구체적인 사물

### 개념

- 공통점을 기반으로 개체들을 묶기 위한 그릇

- **분류(classification)**

  - **개념을 이용하여, 객체를 여러 그룹으로 분류**할 수 있다.

    = 객체에 특정한 개념을 적용하는 작업이다.

- 개념이 객체에 적용되었을 때, 객체를 개념의 **인스턴스(instance)** 라고 한다.

- 객체들의 복잡성을 극복하기 위한 추상화 도구이다.

- 3가지의 관점

  - 심볼(Symbol) : 개념을 가리키는 이름 혹은 명칭
  - 내연(Intension) : 개념의 완벽한 정의
  - 외연(Extension) : 개념에 속한 모든 객체의 집합

## 타입

- 타입과 개념은 동일하다.

  - 공통점을 기반으로 객체들을 묶기 위한 틀이다.

- **객체가 수행하는 행동에 의하여 객체의 타입이 결정**된다.

  - 동일한 책임을 수행하는 객체는 동일한 타입에 속한다.

- 객체의 내부 표현은 외부로부터 감춰진다.

### 다형성

  - 동일한 요청에 대해 서로 다른 방식으로 응답할 수 있는 능력
  - 동일한 행동 = 동일한 책임 = 동일한 메세지의 수신
    
- 단, 내부의 로직은 다를 수 있다.
  
### 캡슐화

- 외부에 행동만을 제공하고 데이터는 행동의 뒤로 감추는 것

- 행동에 따라 객체 분류하기 위해서는 객체가 외부에 제공해야하는 행동 고려해야한다.

  1. 객체가 외부에 제공해야 하는 책임을 결정
  2. 책임을 수행하는 데 적합한 데이터를 결정
  3. 데이터를 외부 인터페이스 뒤로 캡슐화

### 데이터 타입

- 타입은 '데이터가 어떻게 사용되느냐에 관한 것' 이다.
  - '어떤 데이터에 어떤 연산자를 적용할 수 있느냐'가 데이터의 타입을 결정한다.
- 타입에 속한 데이터를 메모리에 어떻게 표현하는지는 외부로부터 감추어진다.
- 데이터 타입은 메모리 안에 저장된 **데이터의 종류를 분류하는 데 사용하는 메모리 집합에 관한 메타데이터**이다.
- 데이터에 대한 분류는 **어떤 종류의 연산이 해당 데이터에 대해 수행될 수 있는지를 결정**한다.

## 타입의 계층

### 일반화/특수화

- 일반화/특수화 간계의 결정은 객체의 행동이다.
- 일반적인 타입 : 특수한 타입이 가진 모든 행동들 중 일부 행동만을 가지는 타입
- 특수한 타입 : 일반적인 타입이 가진 모든 타입을 포함하며, 추가적이 행동을 가지는 타입
- 일반적인 타입은 특수한 타입에 비하여 큰 크기의 외연 집합을 갖는다.
- 일반적인 타입을 '슈퍼타입'이라 칭하고, 특수한 타입을 '서브타입'이라고 칭한다.
- **일반화는 추상화를 위한 도구이다.**

## 정적 모델

- 타입은 시간과 무관한 정적인 모습으로 다룰 수 있게 해준다.
- **타입은 추상화이다.**
  - 타입을 이용하여 객체의 동적인 특성을 추상화할 수 있다.
    - 상태변경이라는 복잡성으 단순화
