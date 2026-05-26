Fire and forget : (=async no reply 구조) 비동기적으로 작업을 전송한 뒤, 응답을 기다리지 않고 바로 다음 로직으로 진행하는 구조 
- 로그 수집 및 모니터링/푸시 알림 발송/이벤트 버스(메시지 큐에 publish만 하고 다른 서비스가 추적하지 않음)
- 장점 : 발신자가 응답을 기다리지 않아 i/o 블로킹이 줄고, 메시지 큐 활용하면 임시 장애 시에도 메시지 보존 가능
- 단점 : 무응답성, 데이터 손실 가능성


## BLoC 패턴 
 Bussiness Logic Component
 UI 와 Bussiness Logic 을 분리하여, 각각 코드의 의존성을 낮추게한다.

https://pks2974.medium.com/bloc-%EC%9D%B4%ED%95%B4-%ED%95%98%EA%B8%B0-%EB%B0%8F-%EA%B0%84%EB%8B%A8-%EC%A0%95%EB%A6%AC-%ED%95%98%EA%B8%B0-7dc705e4c640



## Webview Bridge (Flutter-React) 

