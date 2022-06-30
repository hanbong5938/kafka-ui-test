# kafka-ui-test

kafka의 docker-compose에는 주키퍼, 카프카 1,2,3 이 포함되어있고

kafka-ui의 docker-compose에는 kafka UI 가 포함되어있다.

kafkaAll은 ui 와 kafka 2가지를 묶어 놓았다.

각각 디렉토리에서 

```
docker-compose up -d
```

를 사용하여 설치 해준다.

이후 

```
http://localhost:8989 
```
에서 화면을 확인 할 수 있다.
