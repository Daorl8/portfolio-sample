# STRUCTURE — portfolio-sample (YEOBAEK STUDIO)

```
portfolio-sample/
├── index.html        # 단일 파일(인라인 CSS/JS)
├── .assetsignore
├── README.md
├── STRUCTURE.md
└── CHANGELOG.md
```

## 레이아웃
- 데스크탑: **좌측 고정 사이드바**(스튜디오 마크 + 프로젝트 인덱스 01–06 + 필터 + 연락) | **우측 메인 스크롤**.
- 모바일: 사이드바 → 상단바 + 햄버거 오버레이.

## 메인 섹션
1. `#intro` 스튜디오 선언/소개
2. `#work` **필터형 케이스 그리드**(썸네일 그레이스케일→호버 풀컬러)
3. `#about` 스튜디오 소개·클라이언트
4. `#contact` 프로젝트 의뢰 **문의** 폼(Formspree)
5. `#case` **케이스 상세 오버레이**(우측 슬라이드 인, 풀 케이스 스터디: 히어로·메타·개요·이미지 스트립·다음 프로젝트)
6. `.mbar` 모바일 하단바(이메일·Behance·문의)
7. `<script>` 프로젝트 데이터 객체, 케이스 상세 open/close, 필터, 모바일 사이드바, 스크롤 리빌(데스크탑)

## 팔레트/토큰
`--paper:#F0EDE6; --ink:#1C1A17; --slate:#5C6B70; --line:#DEDAD0; --grey:#6E6A60`
타입: Space Mono(라벨·인덱스·메타) + Pretendard(본문·제목).
