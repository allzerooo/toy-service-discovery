# 1. Code
## 1.1 @EnableEurekaServer
Discovery 역할을 하는 애플리케이션으로 기동하겠다고 명식적으로 나타냄

## 1.2 application.yml
- eureka.client.register-with-eureka: Eureka 서버에 등록할 것인지에 대한 여부. 서비스 디스커버리 자체는 자기 자신을 등록할 필요가 없
- eureka.client.fetch-registry: 등록된 다른 서비스들의 목록을 주기적으로 갱신해서 가지고 올 것인지

# 2. Eureka 대시보드
- http://localhost:8761로 접속
## 2.1 확인할 수 있는 정보
- 언제 실행이 되었는지
- 등록된 서비스 목록
