좀보이드 PNG별 이미지 검수기 v7 · 화면 전환 오류 수정

1. ZIP 압축을 해제합니다.
2. PZ_PNG_Tileset_Reviewer_v7_fixed.html 파일을 Chrome/Edge에서 엽니다.
3. PNG 폴더 전체 선택으로 기존 406개 이미지를 연결합니다.
4. PNG 미리보기 아래 '검수 열기'를 클릭하면 PNG 목록이 숨겨지고 해당 PNG의 개별 타일 검수 카드가 나타납니다.
5. 판정을 입력한 후 목록으로 돌아가 다른 PNG를 열어도 기록이 유지됩니다.
6. 전체 중간 저장 JSON을 자주 다운로드하세요. 전체 통합 검수 ZIP으로 모든 PNG의 결과를 저장할 수 있습니다.

v6 문제 원인: section display:grid CSS가 hidden 상태를 무시해서 검수 페이지가 아래에 렌더링되었습니다.
해결: [hidden]{display:none!important} 적용.
이 ZIP에는 프로그램 소스와 설명만 포함되며 원본 PNG는 포함되지 않습니다.
브라우저에서 파일을 다시 열면 원본 PNG 폴더를 다시 연결해야 합니다. 검수 기록은 브라우저 저장소 또는 JSON으로 복원 가능합니다.
