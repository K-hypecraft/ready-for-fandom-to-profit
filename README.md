# Kim Jiyeon - AI Marketer Portfolio

사이버펑크 스타일의 반응형 포트폴리오 웹사이트입니다.

## 🎨 주요 개선사항

### 1. **이미지 콘텐츠 추가**
- ✅ 각 프로젝트에 고품질 Unsplash 이미지 통합
- ✅ 호버 효과로 이미지 확대/축소 애니메이션
- ✅ 프로젝트 모달에 이미지 갤러리 추가

### 2. **비디오 임베드**
- ✅ YouTube 비디오 2개 임베드 (16:9 반응형)
- ✅ 프로젝트 쇼케이스용 비디오 섹션
- ✅ 자동 반응형 비디오 래퍼

### 3. **이미지 갤러리 섹션**
- ✅ 6개의 프로젝트 이미지 그리드
- ✅ 호버 시 오버레이 효과 및 설명 표시
- ✅ 자동 반응형 레이아웃 (모바일/태블릿/데스크톱)

### 4. **소셜 미디어 카드**
- ✅ Instagram 스타일의 포스트 카드 3개
- ✅ 좋아요/댓글 수 시각화
- ✅ 프로필 이미지 및 사용자명 표시

### 5. **향상된 UX/UI**
- ✅ 프로젝트 모달에 임팩트 정보 추가
- ✅ 이미지 로딩 최적화
- ✅ 푸터 섹션 추가 (소셜 링크 포함)
- ✅ 갤러리 메뉴 항목 추가

## 📂 구조

```
webapp/
├── index.html          # 메인 포트폴리오 페이지
└── README.md          # 프로젝트 문서
```

## 🚀 사용 방법

1. **로컬에서 실행**
   ```bash
   cd /home/user/webapp
   python3 -m http.server 8000
   ```
   
2. 브라우저에서 `http://localhost:8000` 접속

## 🎯 주요 기능

### 인터랙티브 요소
- Three.js 3D 파티클 배경
- 커스텀 네온 커서
- 스크롤 진행률 표시
- Fade-in 애니메이션
- 프로젝트 상세 모달
- AI 챗봇 시뮬레이션

### 콘텐츠 섹션
1. **HERO** - 메인 소개
2. **PROJECTS** - 3개의 주요 프로젝트
3. **GALLERY** - 비디오, 이미지, 소셜 미디어
4. **JOURNEY** - 경력 타임라인 & 스킬
5. **CONTACT** - AI 아이디어 생성기

## 🖼️ 이미지 교체 방법

원하는 이미지로 교체하려면 HTML에서 해당 `src` 속성을 찾아 변경하세요:

```html
<!-- 예시 -->
<img src="YOUR_IMAGE_URL_HERE" alt="Description">
```

### 프로젝트 메인 이미지 위치
- 라인 151: KKOJILLAND 프로젝트
- 라인 172: SUWON MEDIA 프로젝트  
- 라인 193: BAEKHO 프로젝트

### 갤러리 이미지 위치
- 라인 243-244: YouTube 비디오 URL
- 라인 268-311: 이미지 갤러리 (6개)
- 라인 318-377: 소셜 미디어 카드 (3개)

## 🎨 커스터마이징

### 색상 변경
CSS 변수 또는 Tailwind 클래스에서 다음 색상을 찾아 변경:
- `#0affff` - 시안/네온 블루
- `#ff00aa` - 네온 핑크
- `#bd00ff` - 네온 퍼플

### 비디오 임베드 변경
YouTube 비디오 ID만 교체:
```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" ...>
```

## 📱 반응형 디자인

- **모바일**: 단일 컬럼 레이아웃
- **태블릿**: 2컬럼 그리드
- **데스크톱**: 풀 그리드 + 커스텀 커서

## 🔧 기술 스택

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (Vanilla)
- Three.js (3D 효과)
- Lucide Icons
- Google Fonts (Orbitron, Noto Sans KR)

## 📝 라이선스

© 2025 Kim Jiyeon. All rights reserved.

---

**Note**: 현재 사용된 이미지는 모두 Unsplash의 무료 라이선스 이미지입니다. 
실제 프로젝트 이미지로 교체하여 사용하세요.
