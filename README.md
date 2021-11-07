# Spring-study

## 1일차
- API 사용법
- `@ResponseBody`를 사용하게 되면
  - HTTP의 BODY에 문자 내용을 직접 반환
  - `viewResolver` 대신에 `HttpMessageConverter`가 동작
  - 기본 문자처리 : `StringHttpMessageConverter`
  - 기본 객체처리 : `MappingJackson2HttpMessageConverter`
    - Jackson은 객체를 Json으로 바꿔주는 라이브러리 
  - byte 처리 등등 기타 여러 `HttpMessageConverter`가 기본으로 등록되어 있음
