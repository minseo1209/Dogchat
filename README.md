# 🖥️ 프로젝트 소개
**멍채팅**은 강아지 캐릭터와 함께하는 실시간 채팅 웹 서비스입니다. 이 프로젝트는 강아지를 선택하고, 그들과 소통하며 동시에 다른 사용자들과 즐거운 채팅을 할 수 있는 독특한 경험을 제공합니다.

### 프로젝트 목적
강아지를 사랑하는 이용자들에게 색다른 온라인 경험을 제공하고자 합니다. 강아지 캐릭터들과의 상호작용과 실시간 채팅을 통해 사용자들은 편안하고 유쾌한 시간을 보낼 수 있습니다.
 
## ⏱️ 개발 기간
2024.03.01 ~ 2024.03.06

## ⚙️ 기술 스택
- **React**: 포넌트 기반의 사용자 인터페이스를 개발하기 위해 사용
- **React Router**: 애플리케이션의 클라이언트 사이드 라우팅을 지원하기 위한 라이브러리
- **Bootstrap**: CSS 프레임워크로, 빠른 스타일링을 위해 사용
- **React Hooks**: 함수형 컴포넌트에서 상태 관리와 사이드 이펙트를 처리하기 위해 사용
- **JavaScript (ES6+)**: 프론트엔드 및 기타 로직을 작성하기 위해 사용
- **Stream Chat SDK**: stream-chat 라이브러리를 사용하여 실시간 채팅 기능을 구현

## 🚀 주요 기능
- **시간대에 따른 배경 변경** : 현재 시간을 기반으로하여 배경 이미지를 다양하게 변경합니다.
- **닉네임 입력 및 강아지 선택** : 사용자는 닉네임을 입력하고, 두 가지 강아지 옵션 중 하나를 선택할 수 있습니다.
- **Stream Chat을 이용한 실시간 채팅** : Stream Chat SDK를 사용하여 실시간으로 채팅을 주고받을 수 있는 환경을 제공합니다.
- **강아지 캐릭터 이동 및 상호작용** : 키보드 입력 이벤트를 통해 강아지 캐릭터를 이동시킬 수 있습니다.

## ⛏️ 기능 개선
- **실시간 채팅** : 현재는 실시간 채팅이 어려움으로 백엔드 서버를 도입하여 채팅 메시지를 저장하고 실시간으로 클라이언트에 전달할 수 있도록 구현 예정입니다.
  ![Logs](https://github.com/minseo1209/DogChat/assets/99171055/29a60bdf-c76b-42b7-8a05-c6044a1c4af7)

- **모바일 화면 개선** : 현재는 화면 크기에 대한 반응이 미흡하여, 모바일 화면에서의 사용성이 좋지 않습니다. 모바일 환경에 적합한 디자인 및 레이아웃을 구현하여 사용자 경험을 향상시킬 예정입니다.


## ⛏️ 성능 개선
React.memo 또는 useMemo를 사용하여 불필요한 렌더링 최소화
상황에 따라 컴포넌트에 React.memo를 적용하거나 useMemo를 활용하여 불필요한 계산을 최적화할 예정입니다.

현재는 성능 이슈가 크게 나타나지 않으나, 프로젝트 규모가 커질 경우 성능 최적화를 위해 해당 부분을 개선할 예정입니다.


## 🔗 URL
링크 : <https://mydogchat.netlify.app/>

