# 모바일 청첩장 📱💒

GitHub Pages를 이용한 모바일 청첩장입니다.

## 배포 방법

1. GitHub에서 새 repository 생성
2. 이 프로젝트 파일들을 repository에 업로드
3. Settings > Pages에서 Source를 "Deploy from a branch"로 설정
4. Branch를 "main"으로 선택
5. `https://[username].github.io/[repository-name]`으로 접속

## 커스터마이징

### 개인 정보 수정
- `index.html`에서 신랑신부 이름, 날짜, 장소 등 수정
- 연락처 정보 업데이트

### 이미지 교체
현재 placeholder 이미지들을 실제 사진으로 교체하세요:
- 메인 사진: 400x600px 권장
- 갤러리 사진: 150x150px 권장 (정사각형)
- 지도 이미지: 350x200px 권장

### 스타일 수정
- `style.css`에서 색상, 폰트, 레이아웃 등 커스터마이징 가능
- 기본 색상: #c19a6b (골드), #e91e63 (핑크)

## 파일 구조
```
wedding/
├── index.html      # 메인 HTML 파일
├── style.css       # CSS 스타일
└── README.md       # 이 파일
```

## 기능
- 📱 모바일 최적화 반응형 디자인
- 💕 신랑신부 정보 표시
- 📅 결혼식 날짜 및 시간
- 📍 예식장 위치 정보
- 🖼️ 포토 갤러리
- 📞 연락처 정보
- 💌 인사말