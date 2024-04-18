### Spring Boot

- Sprint Boot로 만들 수 있는 것 : 웬만한거 다 만들 수 있다
- 리소스와 관련있는건 리퀘스트에 넣고 / 없는건 쿼리스트링으로 빼야 함
- OpenAPI 독립적
- Message Converter를 이용한 Spring Boot RESTful Service 의 특징 : @RequestBody, @ResponseBody 애너테이션 사용 / Model 객체에 Model Key-Value를 추가하는 것이 아닌 POJO 객체를 직접 리턴
- 경로변수의 용도 - path variable
- JPA 내부적으로 SQL 자동 생성
- RestController : 컨트롤러에 @ResponseBody Annotation이 내장되어 있기 때문에, 추가로 안적어줘도 됨
- 전역 예외 처리 Global exception Handler가 사용하는 Annotation : @ControllerAdvice (ResponseEntityExceptionHandler 상속받아야 함) + @ResponseBody 써줘야함
- Swagger - service 전반적인 설명 정보, 각 controller와 그 handler method에 대한 정보, 모델 객체에 대한 정보
- Rest 핵심 원칙 - 상태 유지하는 기법 사용 금지! (Session, Cookie)

### React
