# 진코치 프로그레서

Tindeq Progressor(지공 훈련 기기)용 한글 웹앱입니다. 브라우저의 Web Bluetooth로 기기에 직접 연결합니다.

## 사용법
- `index.html`을 HTTPS 또는 `localhost`에서 열어 주세요 (Web Bluetooth 조건). 예: `python3 -m http.server`
- 안드로이드/PC의 크롬·엣지에서 동작합니다. iOS 사파리는 Web Bluetooth를 지원하지 않습니다.
- 기기가 없으면 "시뮬레이션 모드"로 체험할 수 있습니다.

## 기능
- 실시간 힘(kg) 표시와 최근 10초 그래프, 영점 맞추기
- 측정 방식: 자유 측정 / 최대 근력 테스트(7초) / 리피터(7초 매달리기, 3초 휴식 × 6)
- 체중 대비 %, 기록 저장(브라우저 localStorage), 추이 그래프, CSV 내보내기

비공식 앱이며 Tindeq와 무관합니다.
