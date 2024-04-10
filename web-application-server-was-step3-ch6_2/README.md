## 세션(HttpSession) 요구사항
키워드: 쿠키, 세션  

## 요구 사항
서블릿에서 지원하는 HttpSession API의 일부를 지원해야 한다.
- 핵심 메서드: `getId()`, `setAttribute(String name, Object value)`, `getAttribute(String name)`,
`removeAttribute(String name)`, `invalidate()`
