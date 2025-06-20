# 클래식 테니스 게임

HTML5 Canvas와 JavaScript로 제작된 클래식한 Pong 스타일 테니스 게임입니다.

## 특징

- **싱글 플레이어 vs AI**: 똑똑한 컴퓨터 상대와 대전
- **부드러운 조작**: W/S 키 또는 화살표 키로 패들 조작
- **점수 기록**: 포인트와 실수 횟수를 추적
- **일시정지 기능**: 스페이스바로 게임 일시정지/재개
- **반응형 디자인**: 다양한 화면 크기에 맞는 깔끔한 중앙 정렬 레이아웃

## 게임 방법

1. 웹 브라우저에서 `tennis-game.html`을 열기
2. 다음 조작법 사용:
   - **W** 또는 **↑** (위쪽 화살표): 패들을 위로 이동
   - **S** 또는 **↓** (아래쪽 화살표): 패들을 아래로 이동
   - **스페이스바**: 게임 일시정지/재개
3. AI 상대에게 공을 쳐서 되돌려 보내기
4. AI가 공을 놓치면 점수 획득
5. 점수 카운터로 성과 추적

## 게임 메커니즘

- 왼쪽 패들은 플레이어가 조작
- 오른쪽 패들은 자동으로 공을 따라가는 AI가 조작
- 공은 위아래 벽에서 튕김
- 타격 시 패들의 움직임에 따라 공의 각도가 약간 변화
- AI가 공을 되돌리지 못할 때 점수 증가
- 플레이어가 공을 되돌리지 못할 때 실수 횟수 증가

## 기술 세부사항

- 순수 HTML5, CSS3, JavaScript로 제작
- 부드러운 60fps 렌더링을 위한 Canvas API 사용
- 충돌 감지 및 물리 시뮬레이션 구현
- 반응형 키보드 입력 처리

## 브라우저 호환성

HTML5 Canvas를 지원하는 모든 최신 브라우저에서 작동:
- Chrome 4+
- Firefox 4+
- Safari 4+
- Edge 12+
- Opera 10+

## 설치

설치가 필요하지 않습니다! HTML 파일을 다운로드하여 웹 브라우저에서 열기만 하면 됩니다.

```bash
# 저장소 클론
git clone https://github.com/quanwenxing/tennis-game.git

# 게임 열기
open tennis-game.html
```

## 라이선스

이 프로젝트는 오픈 소스이며 MIT 라이선스 하에 사용할 수 있습니다.