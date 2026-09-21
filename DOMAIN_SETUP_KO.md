# 라이트온 교회 맞춤 도메인 연결 안내

현재 홈페이지 소스는 GitHub Pages에 올릴 준비가 되어 있습니다.

도메인을 구매한 뒤 진행할 순서:
1. GitHub 저장소 Settings → Pages에서 Custom domain에 실제 도메인을 입력합니다.
2. 도메인 업체의 DNS에서 GitHub Pages용 레코드를 설정합니다.
3. 저장소 루트에 CNAME 파일을 추가합니다.
4. DNS가 반영된 뒤 Enforce HTTPS를 켭니다.

권장:
- 짧고 기억하기 쉬운 .nz 도메인
- 루트 도메인과 www를 함께 연결
- 실제 도메인을 구입한 뒤 DNS 값은 그 도메인에 맞춰 정확히 설정
