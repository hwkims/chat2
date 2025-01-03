# 채팅봇 웹 애플리케이션

이 프로젝트는 간단한 HTML, CSS, JavaScript로 구현된 채팅봇 웹 애플리케이션입니다. 사용자가 입력한 메시지를 그대로 따라하는 챗봇을 구현하며, 자연스러운 애니메이션과 깔끔한 디자인을 통해 실시간 대화처럼 보이도록 만들었습니다. 채팅 UI는 iPhone 메시지 앱이나 카카오톡을 참고하여 디자인되었습니다.

## 주요 기능

- **실시간 채팅**: 사용자가 입력한 메시지를 챗봇이 즉시 반복하는 시스템입니다.
- **애니메이션 효과**: 사용자의 메시지가 나타날 때 부드러운 페이드 인 효과와 챗봇의 "생각 중..." 애니메이션을 제공합니다.
- **세련된 디자인**: iPhone 메시지 앱과 유사한 깔끔한 채팅 UI 디자인.
- **자동 스크롤**: 채팅창이 새로운 메시지로 자동으로 스크롤되어, 항상 최신 메시지를 볼 수 있습니다.

## 기술 스택

- **HTML**: 기본적인 구조
- **CSS**: 채팅 UI 디자인 및 애니메이션
- **JavaScript**: 채팅 로직 및 사용자와 챗봇 간의 상호작용 처리

## 사용 방법

1. 이 프로젝트를 다운로드하거나 클론합니다.
2. 프로젝트 폴더 내 `index.html` 파일을 더블 클릭하여 웹 브라우저에서 엽니다.
3. 페이지가 열리면 입력창에 메시지를 입력하고 `Enter` 키를 누르면 챗봇이 답변합니다.

## 기능 설명

1. **사용자 메시지**:
   - 사용자가 메시지를 입력하고 `Enter` 키를 누르면 채팅창에 메시지가 오른쪽에 표시됩니다.
   - 메시지는 자연스러운 애니메이션으로 채팅창에 나타납니다.

2. **봇의 응답**:
   - 사용자가 메시지를 보낸 후, 1.5초의 딜레이 후 봇이 입력한 메시지를 그대로 반복합니다.
   - 봇이 응답하는 동안 "생각 중..." 애니메이션이 표시됩니다.

3. **채팅 UI**:
   - 사용자와 봇의 메시지는 각각 다른 색상(파란색, 녹색)으로 구분됩니다.
   - iPhone 스타일의 메시지 창 디자인으로, 깔끔하고 직관적인 UI를 제공합니다.

## 커스터마이징

이 프로젝트는 기본적인 채팅 시스템을 제공하며, 아래와 같이 쉽게 커스터마이징 할 수 있습니다:

- **메시지 처리 로직**: `sendMessage` 함수에서 봇의 응답을 수정하여 더 다양한 응답을 구현할 수 있습니다.
- **디자인 변경**: CSS 파일에서 색상, 폰트, 레이아웃을 변경하여 디자인을 쉽게 수정할 수 있습니다.

## 문제 해결

- **메시지가 잘리거나 너무 길어지는 경우**: 채팅창의 너비를 조정하거나 `max-width`를 사용하여 메시지가 적당히 보이도록 할 수 있습니다.
- **응답 시간 수정**: 봇의 응답 시간이 `setTimeout` 함수에서 조정할 수 있습니다. 기본적으로 1.5초로 설정되어 있으므로, 필요에 따라 이 값을 변경할 수 있습니다.

## 라이센스

이 프로젝트는 **MIT 라이센스** 하에 배포됩니다. 자유롭게 사용, 수정, 배포할 수 있습니다.
