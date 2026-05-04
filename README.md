# MSO 월간 업무 보고서

(주)더원인러브 · 쉬즈성형외과 MSO 월간 보고서 아카이브입니다.

🔗 **보고서 보기**: https://purify0902.github.io/mso-reports/

---

## 📁 폴더 구조

```
mso-reports/
├── index.html          ← 월별 목록 메인 페이지
├── 2025-04/
│   └── index.html      ← 4월 보고서
├── 2025-05/
│   └── index.html      ← 5월 보고서 (추가 예정)
└── ...
```

## 📋 매달 업데이트 방법

1. 새 폴더 생성 (예: `2025-05`)
2. 해당 월 보고서 `index.html` 파일 폴더 안에 업로드
3. 메인 `index.html`에서 해당 월 카드의 `empty` 클래스 제거 + 링크 연결

```html
<!-- 변경 전 -->
<a class="report-card empty" href="#">

<!-- 변경 후 -->
<a class="report-card" href="./2025-05/index.html">
```

4. GitHub Pages에서 자동 배포 완료 ✅
