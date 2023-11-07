# vite를 이용한 포트폴리오 사이트 만들기
https://green-vite-project.netlify.app/

## vite를 사용하는 이유
vite란? [vite](https://ko.vitejs.dev/guide/)

vite는 JavaScript 애플리케이션을 개발하기 위한 빠르고 경량화된 도구로,
주로 프레임워크와 함께 사용되며, 더 빠르고 효율적인 웹 애플리케이션 개발을 위해 채택되고 있다.

vite의 번들링을 사용하면 사이트가 가벼워져 속도가 빨리진다
webpack을 사용하지 않은 이유는 번거롭고 버그가 많다

### 특징
1. 빠른 개발 환경: Vite는 개발 서버를 실행하고 코드를 빌드하는 데 최적화되어 있어 매우 빠른 개발 반복을 가능하게 합니다. 코드 수정 시 브라우저에서 즉시 반영되며, Hot Module Replacement (HMR)를 지원하여 페이지 새로 고침 없이 변경 사항을 볼 수 있습니다.

2. 모듈 번들링: Vite는 ES 모듈을 사용하여 개발 및 프로덕션 환경에서 모듈 번들링을 수행합니다. 이는 브라우저에서 더 작은 번들 크기와 더 빠른 로딩을 의미합니다.

3. 다양한 언어 지원: Vite는 JavaScript, TypeScript, Vue.js, React, Svelte 및 다양한 다른 언어 및 프레임워크를 지원합니다. 따라서 프로젝트에서 선호하는 언어 및 프레임워크를 사용할 수 있습니다.

4. 미들웨어 시스템: Vite는 미들웨어 시스템을 제공하여 개발 환경을 확장할 수 있으며, 예를 들어 프록시, 서버 사이드 렌더링 (SSR) 또는 사용자 정의 로직을 추가할 수 있습니다.

5. 플러그인 생태계: Vite에는 다양한 플러그인이 제공되며, 이를 사용하여 프로젝트에 추가 기능을 쉽게 통합할 수 있습니다.

## 구현 기능
- 구글 폰트 적용
- smooth 효과 적용 https://lenis.studiofreight.com/
- JavaScript로 메뉴 클릭 이동 효과 적용
- JavaScript 모듈 기능 적용
- GSAP를 이용한 가로 효과
- 웹표준 준수를 위한 스킵 메뉴 및 aria, role 적용
- vite build 작업 `npm run build`
- netilfy 배포 작업
## 트러블 슈팅
<details>
<summary>git 업로드 버그</summary>
권한으로 인한 업로드 버그 > 해결
git remote set-url origin https://chfhr11@github.com/chfhr11/vite-project2023.git

</details>
