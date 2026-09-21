# DESIGN.md - 티크크 (Tea-K-K) 디자인 시스템

## 1. Visual Theme & Atmosphere
- **Core Mood:** 따뜻하고 아늑한(Cozy), 차분한 다도의 분위기, 수제 노트 같은 아날로그 감성
- **Tone & Manner:** 과하지 않은 미니멀리즘, 둥근 모서리와 부드러운 파스텔·우드톤 조합을 통한 친근함 제공
- **Target Experience:** 사용자가 차를 마시는 듯한 여유와 기록의 즐거움을 느낄 수 있도록 함

---

## 2. Color Palette (색상 토큰)
- **Primary (주조색):** 
  - `#79553D` (딥 우드 브라운 - 주요 버튼, 강조 텍스트, 핵심 아이콘)
  - `#624430` (다크 우드 - Primary Hover 상태)
- **Background (배경색):**
  - `#FBF9F5` (웜 아이보리 - 전체 페이지 기본 배경)
  - `#F5F2EC` (라이트 베이지 - 서브 카드, 헤더, 인포박스 배경)
- **Surface & Border (카드 및 경계선):**
  - `#FFFFFF` (카드 기본 배경)
  - `#E8E2D5` (소프트 보더 - 카드 테두리 및 구분선)
  - `#E3DFD5` (입력폼 테두리)
- **Text (텍스트 컬러):**
  - `#3C3633` (딥 차콜 - 주요 제목, 강조 텍스트)
  - `#5C524B` (서브 텍스트)
  - `#736A61` / `#8C8279` (캡션 및 보조 설명, 플레이스홀더)
  - `#A89F91` (비활성/아이콘 컬러)

---

## 3. Typography (타이포그래피)
- **Font Family:** `Pretendard Variable`, Pretendard, -apple-system, sans-serif
- **Scale & Hierarchy:**
  - **Header Title:** 14px ~ 15px, Bold (`#5C524B` or `#3C3633`)
  - **Section Title:** 12px ~ 13px, Semi-bold / Bold, Uppercase/Normal (`#79553D`)
  - **Body Text:** 11px ~ 12px, Regular (`#3C3633` or `#5C524B`)
  - **Caption / Badge:** 9px ~ 10px, Medium (`#8C8279`)

---

## 4. Component Stylings (컴포넌트 규칙)
- **Border Radius (모서리 둥글기):**
  - Card & Modal Content: `16px` ~ `24px` (부드러운 느낌 강조)
  - Button & Input: `8px` ~ `12px` (알약형 또는 부드러운 사각형)
  - Tags & Badges: `9999px` (완전한 알약형)
- **Shadows (그림자):**
  - 미세하고 은은한 입체감: `0 1px 2px rgba(0,0,0,0.02)`
- **Buttons:**
  - Primary Button: 배경색 `#79553D`, 텍스트 `white`, 패딩 `8px 12px` (또는 대형 `12px`)
  - Secondary Button: 배경색 `#EAE4D8`, 텍스트 `#5C524B`

---

## 5. UI/UX Guidelines (원칙)
- **Spacing:** 컴포넌트 간 간격은 12px~16px 중심으로 여유 있게 배치할 것.
- **Feedback:** 상태 변화(수색 선택, 탭 전환 등) 시 즉각적인 시각적 피드백(테두리 강조, 스케일 변화) 제공.
- **Mobile First:** 최대 너비 440px의 모바일 뷰포트 환경을 최우선으로 고려하여 컴포넌트 터치 영역(최소 44px 권장) 확보.
