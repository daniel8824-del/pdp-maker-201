# 상세페이지 마법사 2.0

상품 이미지만 올리면 AI가 상세페이지를 자동으로 만들어주는 웹앱입니다.

## 실행

```bash
pnpm install
pnpm --filter @runacademy/web dev
```

## 사용 모델

- 분석: `gemini-2.5-flash`
- 이미지 생성: `gemini-3.1-flash-image-preview` (Nano Banana 2)

## 기능

- 상품 이미지 업로드 → Gemini AI가 브랜드 분위기/섹션 구조 분석
- 모델 이미지 추가 (히어로/전체 모델컷)
- 비율 선택 (1:1, 3:4, 9:16, 4:3, 16:9)
- 톤 선택 (프리미엄, 모던, 테크, 미니멀 등)
- 섹션별 이미지 생성
- 초안 저장/불러오기 (IndexedDB)
- 개인 Gemini API 키로 동작
