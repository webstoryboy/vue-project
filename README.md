# vue를 이용한 포트폴리오 사이트 만들기
Vue.js는 현대적이고 직관적인 웹 애플리케이션 프레임워크로서, 사용자 인터페이스를 개발하기 위해 사용되는 자바스크립트 프레임워크입니다.
표준 HTML, CSS 및 JavaScript를 기반으로 구축되며, 단순한 것 부터 복잡한 것 까지 사용자 인터페이스를 효율적으로 개발할 수 있는 컴포넌트 기반 프로그래밍 모델을 제공합니다.

1. 반응형 데이터 바인딩 : Vue.js는 데이터와 UI를 매우 간편하게 바인딩할 수 있습니다. 데이터의 변경이 자동으로 UI에 반영되어 화면과 상태가 항상 일치하도록 해 줍니다. 이로 인해 개발자는 직접 DOM 조작을 하지 않고도 데이터 상태 변화를 처리할 수 있어 개발 생산성을 높일 수 있습니다.
2. 컴포넌트 기반 아키텍처 : Vue.js는 컴포넌트 기반으로 구조화합니다. 즉, 작고 재사용 가능한 컴포넌트들로 구성되며, 각 컴포넌트는 자체적인 데이터와 로직을 갖습니다. 이러한 접근 방식은 코드의 가독성과 유지보수성을 높이고 개발을 단순화합니다.
3. 디렉티브 : Vue.js는 디렉티브(Directive)를 통해 HTML 요소의 동작을 확장할 수 있습니다. v-bind, v-if, v-for, v-on 등과 같은 디렉티브를 사용하여 템플릿과 데이터 간의 상호작용을 정의할 수 있습니다.
4. 이벤트 핸들링 : Vue.js는 이벤트 핸들링을 쉽게 구현할 수 있도록 지원합니다. 사용자 입력에 따른 이벤트 처리 뿐만 아니라 커스텀 이벤트도 쉽게 정의하고 사용할 수 있습니다.
5. 가상 DOM(Virtual DOM) : Vue.js는 가상 DOM을 사용하여 화면 갱신 성능을 최적화합니다. 변경된 부분만 실제 DOM에 적용하여 불필요한 렌더링을 방지하고 앱의 성능을 향상시킵니다.
6. 단방향 데이터 흐름 : Vue.js는 단방향 데이터 흐름을 따릅니다. 즉, 데이터는 항상 상위 컴포넌트에서 하위 컴포넌트로 흐르며, 하위 컴포넌트에서 직접 상위 컴포넌트의 데이터를 수정할 수 없습니다. 이로써 데이터의 흐름이 예측 가능하고 디버깅이 용이해집니다.

## 셋팅
`npm init vue@latest`
Project name: … vue-project
✔ Add TypeScript? … <span style="color: blue">No</span> / Yes
✔ Add JSX Support? … No / <span style="color: blue">Yes</span>
✔ Add Vue Router for Single Page Application development? … No / <span style="color: blue">Yes</span>
✔ Add Pinia for state management? … <span style="color: blue">No</span> / Yes
✔ Add Vitest for Unit Testing? … <span style="color: blue">No</span> / Yes
✔ Add an End-to-End Testing Solution? › <span style="color: blue">No</span>
✔ Add ESLint for code quality? … No / <span style="color: blue">Yes</span>
✔ Add Prettier for code formatting? … No / <span style="color: blue">Yes</span>

