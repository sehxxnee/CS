Fire and forget : (=async no reply 구조) 비동기적으로 작업을 전송한 뒤, 응답을 기다리지 않고 바로 다음 로직으로 진행하는 구조 
- 로그 수집 및 모니터링/푸시 알림 발송/이벤트 버스(메시지 큐에 publish만 하고 다른 서비스가 추적하지 않음)
- 장점 : 발신자가 응답을 기다리지 않아 i/o 블로킹이 줄고, 메시지 큐 활용하면 임시 장애 시에도 메시지 보존 가능
- 단점 : 무응답성, 데이터 손실 가능성

-> 일반 비동기 요청과 차이는?

-> 왜 응답을 기다리지 않는 구조를 사용하는가?

-> 어떤 상황에서 적합한가?

- DLQ란?


## BLoC 패턴 
 Bussiness Logic Component
 UI 와 Bussiness Logic 을 분리하여, 각각 코드의 의존성을 낮추게한다.

https://pks2974.medium.com/bloc-%EC%9D%B4%ED%95%B4-%ED%95%98%EA%B8%B0-%EB%B0%8F-%EA%B0%84%EB%8B%A8-%EC%A0%95%EB%A6%AC-%ED%95%98%EA%B8%B0-7dc705e4c640

-> Flutter에서 setState와 차이는?

- Stream 기반 구조란?

- Bloc과 MVVM 차이?

- Provider / Riverpod / Redux

- 테스트 용이성이 왜 좋아지는가?
- 비동기 API 호출은 어디서 처리하는가?

## Webview Bridge (Flutter-React) 
WebView Bridge가 무엇인가?
왜 Flutter와 React(Web)를 연결했는가?
Native ↔ Web 간 통신은 어떻게 이루어지는가?
인증 토큰은 어떻게 전달했는가?
React에서 Flutter로 데이터 전달 어떻게 하나?
JavascriptChannel 설명 가능?
WebView 보안 이슈 아는가?
XSS 위험은?
JS Injection 위험 대응?
민감한 데이터 전달 시 고려사항?
외부 URL 로딩 제한 어떻게 했는가?
Bridge 통신 타이밍 이슈 겪어봤는가?
WebView 렌더링 느린 문제 어떻게 해결?
Android/iOS 차이 있었는가?
앱 뒤로가기 처리 어떻게 했는가?
쿠키/세션 동기화 문제 경험?
딥링크와 WebView 같이 쓴 경험?
