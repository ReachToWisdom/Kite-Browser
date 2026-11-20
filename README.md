# Kite Browser

Windows용 **Kite Browser**와 **AI Kite** 통합 설치 프로그램입니다.

## 설치 파일

[Windows 설치 파일 다운로드 (2026.11.20 r3)](Kite-Browser-Setup-2026.11.20-r3.exe) · [릴리스 기록](https://github.com/ReachToWisdom/Kite-Browser/releases)

### 주요 변경 사항 (2026.11.20 r3)
- **AI Kite 탭 설정 영속화 버그 수정**: 환경설정에서 삭제·편집한 AI 탭이 재기동 시 되살아나던 이중 JSON 직렬화 버그 수정(디렉터리 자동 생성 및 구 이중 인코딩 파일 자동 복구 포함)
- **AI Kite 기본 탭 정리**: Codex 탭 제거(ChatGPT 통합) 및 Claude 초기 주소를 `https://claude.ai/new`로 교정
- **탭 전환·닫기 유령 탭 버그 수정**: 활성 탭 닫기 시 DOM 즉시 제거 및 동기화 보강, `✕` 닫기 버튼 드래그 가로채기 차단(`18px` 확대), 닫기 시 임의 탭 깜빡임 제거, `▼ 열린 탭 목록` 연속 닫기 지원
- **Kite Core + 4종 내장 확장 SSOT 통합**: `AI 카이트(9223)`, `코카이트`, `하카이트(9232)`, `유튜브 카이트(9224)`, 시크릿(`9225`) 상호 배타 프로필·CDP 포트·HWND 격리 및 `kite://settings` 확장 관리 탭
- **Brave 방식 Kite 쉴드 & Firefox 스타일 팝업 차단**: 네트워크·코스메틱 자동 차단, 웹 요소 클릭 수동 차단 및 하나씩 클릭해 제외 모드, 주소창 팝업 차단 팝오버

설치 중 Chrome·Firefox·Edge 북마크를 한 화면에서 골라 가져올 수 있으며, 업데이트 설치 시 실행 중인 두 모드를 정상 종료한 뒤 안전하게 교체합니다. 제거해도 사용자 설정과 북마크는 보존됩니다.

SHA-256: `B2AD7805C140E54AAAF21C60D6D951FB68066F2FB2D18CA0DACD911130755809`
