2020-01-14
2주차 규칙정하기

# 하늬  
- **종속 함수 배치** : 한 함수가 다른 함수를 호출한다면(종속 함수) 두 함수는 세로로 가까이 배치한다.  
써야하는 이유 : 함수 내에 사용되는 메소드가 무엇인지 궁금할 때 바로 다음에 메소드 구현한 모습을 볼 수 있기 때문에 가독성이 올라가기 때문  
-> 종속 메소드인 경우 세로로 가깝게 배치한다.
# 현주, 이식
- **기차 충돌** : 여러 객체가 한 줄로 이어진 기차처럼 보여지는 것  
써야하는 이유 : 코드 너비도 짧아지고 구조를 딱 보여주니까 좋은 것 같음  
-> 여러 개의 객체를 한 줄로 쓸 때 코드가 너무 길어지면 분리해서 쓰도록 한다.
# 근우
- **수직 거리** : 서로 밀접한 개념은 세로로 가까이 둬야 한다.  
써야하는 이유 : 코드를 쓴 사람의 의도를 파악할 수 있고 가독성이 올라감  
-> 서로 밀접한 개념은 세로로 가까이 두고 쓰도록 한다.
# 이식
- **DTO 사용**  
써야하는 이유 : 캡슐화를 위해서 써야한다.    
-> 공통적인 데이터는 DTO를 사용해서 쓰도록 한다.  

정해진 규칙  
1. 종속 메소드인 경우 세로로 가깝게 배치한다.  
2. 여러개의 객체를 한 줄로 쓸 때 코드가 너무 길어지면 분리해서 쓰도록 한다.  
3. 서로 밀접한 변수나 메소드들은 세로로 가까이 두고 쓰도록 한다.  
4. 공통적인 데이터들은 DTO를 사용해서 쓰도록 한다.   
