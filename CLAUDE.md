# OCRKit 프로젝트 지침

## 프로젝트 개요
- **사이트명:** WooaOCR
- **URL:** https://wooaocr.wooahouse.com
- **배포:** GitHub Pages (main 브랜치 → root)
- **테마 컬러:** #F97316 (orange)

## 기술 스택
- 순수 HTML / CSS / JS (프레임워크 없음)
- OCR: Tesseract.js v5 (클라이언트 사이드, 서버 전송 없음)
- PDF 렌더링: PDF.js 3.11.174
- PWA: manifest.json + sw.js + js/pwa-install.js

## 도구 목록
- image-ocr.html — 이미지 텍스트 추출 (JPG/PNG/WebP/BMP)
- pdf-ocr.html — PDF OCR (스캔 PDF 텍스트 추출)

## 작업 규칙
- 새 도구 추가 시 index.html 카드 + sitemap.xml 업데이트
- 다운로드/인식 버튼: id="downloadBtn" 또는 id="startOcrBtn" (PWA 트리거)
- GA ID: G-9ZGENFSXWC (공통)
