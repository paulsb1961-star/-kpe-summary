# GitHub 업로드 안내

## 이 폴더 구조
```
kpe_summary/
├── README.md              ← 저장소 첫 화면 (시리즈 소개 + 40개 목차)
├── kpe_archive.json       ← 전체 데이터 (기계 판독용, 재활용)
├── volumes/
│   ├── vol01.md ~ vol30.md   ← 개별 30권
└── collections/
    └── col01.md ~ col10.md   ← 모음집 10편
```

## 안전 확인 완료 (2026-08-09)
- ✅ 원문(시구·포토 디스크립션 전문·본문 텍스트) 노출 0건
- ✅ 영문 KDP Description은 아마존 공개 카피 (노출 무방)
- ✅ 표지 이미지 파일명만 참조 (이미지는 kpe-covers 저장소)

## 재활용 채널
- **GitHub** → README.md + volumes/collections (구글 색인, 글로벌 발견)
- **kpe_archive.json** → 웹사이트 API, JSON-LD 변환, AI 크롤러, 네이버 서치어드바이저 연계

## ⚠️ 재발 방지 규칙 (필수 확인)
이 폴더의 모든 파일은 "요약 전용"입니다. Public 저장소에 올려도 안전합니다.
단, **원문이 담긴 파일(마스터 xlsx, nodes_text.csv 등)은 절대 이 폴더에 넣지 마세요.**
