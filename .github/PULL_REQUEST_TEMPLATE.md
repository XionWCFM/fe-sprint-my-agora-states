# Description

Section1에서 배운 내용을 총 동원하여 나만의 멋진 아고라 스테이츠를 만듭니다.

- [코드스테이츠 fe-sprint-my-agora-states 리포지토리](https://github.com/codestates-seb/fe-sprint-my-agora-states)에서 자신의 리포지토리로 fork후 과제 진행합니다.

## 배포 링크

Github Page 배포 링크를 아래 작성합니다.

## Bare Minimum Requirement Self Checklist

스스로 구현 완료한 부분까지 체크하여 제출합니다.

- [O] 디스커션 나열 기능
  - [O] `script.js`를 수정하여 `agoraStatesDiscussions` 배열의 데이터를 나열할 수 있게 구현합니다.
- [O] CSS
  - [O] 아고라 스테이츠 질문 리스트가 중앙으로 와야 합니다.
  - [O] `style.css`를 수정하여 멋지고 아름답게 나만의 아고라 스테이츠를 꾸밉니다.
  - [O] [colorhunt](https://colorhunt.co/palettes/popular), [dribbble](https://dribbble.com/)에서 적절한 색 조합, 디자인을 참고합니다.
- [O] 디스커션 추가 기능
  - [O] `script.js`를 수정하여 디스커션 추가 기능을 구현합니다.
  - [O] `section.form__container` 요소에 새로운 아고라 스테이츠 질문을 추가할 수 있는 입력 폼을 제작합니다. 형식은 자유입니다.
  - [O] 아이디, 본문을 입력하고 버튼을 누르면 실제 화면에 디스커션이 추가되어야 합니다.
  - [O] `agoraStatesDiscussions` 배열에 추가한 데이터가 실제 쌓여야 합니다.
- [O] Github Page 배포
  - [O] Github Page 배포 기능을 이용하여 누구나 볼 수 있게 배포합니다.
- [O] [코드스테이츠 fe-sprint-my-agora-states 리포지토리](https://github.com/codestates-seb/fe-sprint-my-agora-states)로 Pull Request
  - [O] 나만의 아고라 스테이츠를 코드스테이츠 깃허브에 Pull request합니다.
  - [O] 주어진 Pull request 형식에 따라주세요.

## Advanced Challenge Self Checklist

스스로 구현 완료한 부분까지 체크하여 제출합니다.

- [O] 현지 시간 적용
  - [O] 샘플 시간을 잘 변형하여, 현지 시간에 맞게 표현합니다. (ex. 오전 10:02:17)
- [O] 페이지네이션 기능
  - [O] 페이지네이션에 대해서 스스로 학습합니다.
  - [O] 한 페이지에 10개씩 디스커션이 보여야 합니다.
  - [O] 다음 페이지로 넘어갈 수 있어야 합니다.
  - [O] 이전 페이지로 돌아올 수 있어야 합니다.
  - [O] 다음 페이지가 없거나, 이전 페이지가 없는 경우 페이지를 유지해야 합니다.
- [O] 디스커션 유지 기능
  - [O] LocalStorage에 대해서 스스로 학습하고, 새롭게 추가하는 Discussion이 페이지를 새로고침해도 유지되도록 제작합니다.

### My Own Self Checklist

자신이 추가로 더 구현한 기능이 있으면 아래 적어주세요.

- [O] 질문을 추가하더라도 한페이지에 표시되는
- []
- []

### 배포 시연 화면

아래 예시를 지우고, 자신의 과제 시연 화면을 추가합니다.

![image](https://s3.ap-northeast-2.amazonaws.com/urclass-images/NB0JkuHQnLg8X1woSRS84-1652915757557.gif)

### 가장 자랑하고 싶은 기능

> 적어주세요

### 구현하고 싶었는데 하지 못한 아쉬운 기능

> 클래스를 이용해 서로 관련있는 함수들을 묶어주고 모듈로 만들어 관리하고 싶었는데
> 거기까지 생각이 닿은 이후엔 너무 많은 코드를 짠 상태여서 엄두를 내지 못했습니다..

### 도움을 받고 싶은 부분

> 재사용성을 높이기 위해 함수를 많이 만들어서 사용하는 식으로 코드를 작성했는데
> 그렇게 했더니 인자 관리, 참조오류에 관한 문제가 발생했습니다.
> 또한 함수 안에서 호출의 호출이 이어지며 함수의 동작을 예측하기 힘들고
> 모든 함수의 트리거가 되는 핵심 함수를 찾아다니게되었습니다.

-> 해결방안.. 클래스로 같은 일을 하는 함수들을 묶어주고 모듈로 나눠주어 관리를 용이하게한다.
핵심함수의 네이밍을 좀 더 돋보이게 지어야할 것 같다.

### 도움을 받고 싶은 부분

페이지네이션을 할 때 submit으로 인해 칸이 늘어나 뒤로 밀리게되면
그만큼 페이지를 추가로 생성해주어야한다.

1-5 페이지 -> 6-10 페이지로 가게하는 로직이 필요함.
