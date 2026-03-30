# AION2 어비스 보급의뢰 효율 계산기

## Netlify 배포 방법 (5분 소요)

### 1단계 — Netlify 가입
https://netlify.com 에서 무료 계정 생성 (GitHub 소셜 로그인 가능)

### 2단계 — 배포
1. netlify.com 대시보드 접속
2. **"Add new site" → "Deploy manually"** 클릭
3. `aion2-abyss` 폴더(index.html + netlify.toml 포함)를 **드래그앤드롭**
4. 자동으로 URL 생성됨 (예: `https://amazing-aion2.netlify.app`)

### 3단계 — URL 커스텀 (선택)
Site settings → Domain management → 원하는 이름으로 변경
예) `aion2-calc.netlify.app`

---

## 사용 방법

### AI 시세 자동 조회
1. **⚙️ API 키 설정** 클릭
2. https://console.anthropic.com 에서 API 키 발급
3. 키 입력 후 저장 → **✨ AI 시세 자동 조회** 클릭

> API 키는 각자 브라우저에만 저장됩니다. 친구들도 각자 키를 입력해야 합니다.
> Anthropic 무료 크레딧으로 수십 번 조회 가능합니다.

### 수동 입력
아이템 카드에 가격을 직접 입력해도 됩니다.
입력값은 브라우저에 저장되어 다음 방문 시에도 유지됩니다.

---

## 기술 스택
- 순수 HTML/CSS/JS (빌드 불필요)
- Anthropic Claude API (웹 검색 포함)
- localStorage (가격 저장)
