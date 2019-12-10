## WeKid(위키드)
![wekidphoto1](https://user-images.githubusercontent.com/50092350/70494999-a6eb6600-1b50-11ea-8581-2895a5f6f461.png)
+ 개발 기간 : 2019/02/28 ~ 2019/05/28
+ 최근 이슈가 되고 있는 유치원 문제 2가지(버스 관련 안전 사고, 교사-학부모 간 사생활 침해 문제)를 해소하기 위해 만든 안드로이드 어플리케이션

## 주요 기능
+ 유치원 버스 탑승 체크
1. Raspberry Pi를 이용한 Beacon Scanner로 자동 버스 탑승 체크
+ 원아 갇힘 알림
1. 버스 운행 종료 후에도 인식되는 Beacon이 있다면 갇힘 알림 발생
+ 메신저
1. Firebase를 이용한 실시간 채팅
2. 오픈되지 않는 개인 전화번호
3. 교사 퇴근 시 메시지가 전송되지 않음 (교사의 퇴근 시간 동안 전송된 메시지는 내부에 보관되었다가 출근 시 일괄 전송)

## 설계보완점 및 목표구현 정도
+ 버스 탑승원아 현황 실시간 확인 & 메신저 기능(텍스트 송수신, 사진 송수신, 교사 퇴근시 메시지 보관 및 출근시 일괄 전송)이 완벽하게 수행되는 것이 기존의 목표였음
+ 메신저 기능은 목표 달성
+ 버스 탑승원아 현황을 확인하는데는 5~10초 정도의 딜레이 발생

## 향후 개선사항
+ 향후 추가적 구현을 하게 된다면
1. 메신저 기능을 추가(프로필 사진 등록/수정/삭제, 대화명 설정 기능 등),
2. 버스 탑승원아 현황을 5초 이내로 확인할 수 있도록 보완할 것임
