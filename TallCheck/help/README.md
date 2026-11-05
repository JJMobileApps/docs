# tallCheck 온라인 도움말

게시 주소: https://jjmobileapps.github.io/docs/TallCheck/help/

영문판: https://jjmobileapps.github.io/docs/TallCheck/help/en/

한국어는 루트의 HTML 5개, 영어는 `en/`의 같은 이름의 HTML 5개를 사용합니다.
앱은 Android 언어별 리소스로 URL을 선택하므로 한국어 UI는 루트, 영어 UI는 `en/`으로 연결됩니다.

GitHub Pages가 `JJMobileApps/docs` 저장소 `main` 브랜치의 루트에서 정적 파일을 게시합니다.
빌드 없이 HTML·CSS와 `assets/`를 함께 올리면 됩니다.

- `index.html`: 시작하기와 아이·기록 등록
- `prepare.html`: 준비물, 마커 크기, 수평 원점, 기준측정, 원거리 보정
- `measure.html`: 보호자와 측정·혼자 측정, 결과 확인
- `photo.html`: 모델 준비, 사진 편집·자르기·인식·저장
- `faq.html`: 측정 오차, 모델 설치, 업데이트, 프리미엄과 백업

그림은 TallCheck 앱의 한국어 측정 안내 이미지 및 사진 읽기 안내를 웹용 WebP로 변환했습니다.
영문판 측정 그림은 앱의 기본 언어용 그림에서 변환한 `en/assets/`를 사용합니다.
문자 없이 숫자와 단위로 설명하는 사진 읽기 그림은 `assets/photo.webp`를 공유합니다.
화면·메뉴가 바뀌면 설명과 그림을 함께 검토하세요.
페이지 추가 시 모든 문서의 탐색 메뉴와 이전·다음 링크를 함께 갱신합니다.
두 언어의 본문·대체 텍스트·`hreflang` 링크도 함께 갱신합니다.

로컬 확인:

```powershell
python -m http.server 8129 --directory TallCheck/help
```

모바일·데스크톱 너비에서 그림 로딩, 가로 넘침, 내부 링크와 FAQ 펼치기를 확인하세요.
