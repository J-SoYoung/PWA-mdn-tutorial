# pwa_study
### [MDN Progressive web app tutorial study](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps) 
📲 https://pwa-mdn-tutorial.netlify.app/<br>
<br>
- 기본 HTML과 CSS로 마크업을 시작합니다.
- PWA를 배포하려면 web의 보안 연결(https)을 통해 파일을 배포해야 한다. <br>
  - ([보안 컨텍스트를 사용하여 구현할 수 있는 web platform 기능들 관련 MDN](https://developer.mozilla.org/en-US/docs/Web/Security/Secure_Contexts/features_restricted_to_secure_contexts))<br>
  - PWA는 https를 사용한 보안적인 환경에서 개발하여야 한다. 그렇지 않으면 service-worker나 manifest.json이 제대로 동작하지 못한다.
- manifest.json 설정하기
  - manifest.json파일은 PWA가 사용자의 기기에 설치되었을 때 앱처럼 동작할 수 있도록 정보를 제공하는 JSON파일이다. PWA의 이름, icon, 표시 지침 등의 메타데이터 정보가 포함되어 있다. 
