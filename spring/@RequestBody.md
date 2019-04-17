## @RequestBody

### json 객체를 받아 VO 객체에 매핑시키려 할 때
- @RequestBody 어노테이션을 붙여야 한다
- 415 에러가 났을 때, servlet-context.xml 에 <mvc:annotation-driven />가 추가되어 있는지 확인