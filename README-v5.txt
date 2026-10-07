insurance-guide v5 medical cache fix

수정 이유:
- v4 파일 자체에는 의료정보가 들어 있었지만 실제 Pages에서 일부 기존 상세 HTML이 표시되는 현상을 피하기 위해 고객용 상세페이지 파일명을 모두 -v5로 새로 생성했습니다.
- index.html 링크도 새 -v5 파일로 변경하고 ?v=5를 붙여 브라우저/CDN 캐시 영향을 줄였습니다.
- 모든 20개 상세페이지에 공공 의료정보 영역이 포함되어 있습니다.

배포:
이 폴더 안의 내용 전체를 GitHub 저장소 root에 업로드 후 Commit changes.
기존 파일은 삭제하지 않아도 됩니다.
