### Spring Boot
- Sprint Boot로 만들 수 있는 것 : 웬만한거 다 만들 수 있다
- REST : 리소스와 관련있는건 URI에 넣고 / 없는건 쿼리스트링으로 빼야 함
- OpenAPI 서비스 만드는 법 : REST 말고도 많은데, http 안쓰는 것도 있음
- Message Converter를 이용한 Spring Boot RESTful Service 의 특징 : @RequestBody, <em>@ResponseBody</em> 애너테이션 사용 / Model 객체에 Model Key-Value를 추가하는 것이 아닌 POJO 객체를 직접 리턴
- 경로변수의 용도 - @PathVariable : URI 경로 상에 있는 것을 변수로 사용하는 것
- 전역 예외 처리 Global exception Handler가 사용하는 Annotation : <em>@ControllerAdvice</em> (ResponseEntityExceptionHandler 상속받아야 함) + @ResponseBody 써줘야함
- 반복적으로 사용되는 SQL은 JPA 내부적으로 자동 생성됨 (JPQL)
- Swagger - service 전반적인 설명 정보, 각 controller와 그 handler method에 대한 정보, 모델 객체에 대한 정보 / parameter를 문서화할 수 있음!
- Rest 핵심 원칙 - 상태 유지하는 기법 사용 금지! (Session, Cookie)
- RestController : 컨트롤러에 @ResponseBody Annotation이 내장되어 있기 때문에, 추가로 안적어줘도 됨


### React
- 리액트에서 상태와 속성에 대한 설명 중 잘못된 것은?
    - 상태 : 정의된거에서 변경하는거 / 상태가 바뀌면 자식 컴포넌트에서 Rerender 일어남
    - 속성 : 자식이 부모에게 받은 속성은 함부로 변경 불가
    - ★ 상태와 속성은 같이 사용할 수 있다
- 조건부 렌더링 시, 삼항연산자 이용
- React에서의 상태변경 : useState()를 호출해 리턴받은 setter 함수를 이용
- Context Api의 장점 : props로 속성 전달을 많이 하지 않아도 되고, Componenet의 재사용성이 높음. 상태 변경 기능을 중앙집중화하여 관리 가능
- UseEffect 훅 : 생명주기 중에 Side Effect 효과를 일으키고 싶을 때 사용
- jsx의 표기법 : javascript 문법 따름
    - Camel Casing, 단일 루트 엘리먼트, 시작/마감 태그 쌍 (ex. '<A>'</A> or '<A/> )
- Virtual DOM 에서 차이가 나는 부분에서만 가져옴 / Browser DOM에 직접 접근하는게 아님
- React Router의 기능 : 리액트 기반의 강력한 라우팅 라이브러리 (react-router)
- react-router가 제공하는 hook (문제 - 다음 중 react-router가 제공하는 hook이 아닌 것은?)
  - useMatch(경로패턴), useParams(), useSearchParams(), useLocation(), useNavigate(), useOutletContext()
