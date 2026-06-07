# kang.claude.gpt.ai-best
claude and gpt ai project
# WebMotion

가볍고 의존성 없는 **복사-붙여넣기형 웹 애니메이션 컴포넌트 모음**입니다.
HTML / CSS / 순수 JavaScript만으로 동작하며, 아임웹·워드프레스·일반 HTML 사이트 어디에든 코드 한 조각만 넣으면 바로 적용됩니다.

> 별도 빌드 과정, 프레임워크, 라이브러리가 필요 없습니다. 그냥 붙여넣으세요.

---

## ✨ 특징

- **의존성 0** — jQuery·React 같은 외부 라이브러리 불필요
- **가벼움** — 컴포넌트당 평균 2~3KB 내외
- **반응형** — 모바일/데스크탑 모두 대응
- **커스터마이징 쉬움** — CSS 변수(`--`)로 색상·속도·크기 조절
- **노코드 친화** — 아임웹 등 코드 삽입 위젯에 그대로 사용 가능

---

## 📦 컴포넌트 목록

| 컴포넌트 | 설명 |
| --- | --- |
| `marquee-text` | 흐르는 텍스트(마퀴) — 스크롤 트리거 등장, 속도 조절 가능 |
| `scroll-reveal` | 스크롤 시 요소가 부드럽게 나타나는 효과 |
| `text-through-photo` | 텍스트 안에 사진이 비치는 블렌드 효과 |
| `count-up` | 숫자가 0부터 목표값까지 올라가는 카운터 |
| `hover-card` | 마우스 오버 시 살짝 떠오르는 카드 |

> 컴포넌트는 계속 추가될 예정입니다.

---

## 🚀 사용법

### 1. 코드 복사
원하는 컴포넌트 폴더에서 HTML + CSS + JS 코드를 복사합니다.

### 2. 붙여넣기
사이트의 원하는 위치에 붙여넣습니다.

```html
<!-- 예시: marquee-text -->
<div class="wm-marquee" style="--wm-speed: 20s;">
  <span>안녕하세요 · WebMotion · 가볍고 빠른 웹 애니메이션 ·</span>
</div>
```

### 3. 옵션 조절
CSS 변수로 손쉽게 커스터마이징합니다.

```css
.wm-marquee {
  --wm-speed: 15s;     /* 흐르는 속도 */
  --wm-color: #222;    /* 글자 색 */
  --wm-size: 1.5rem;   /* 글자 크기 */
}
```

---

## 📁 폴더 구조

```
WebMotion/
├── components/
│   ├── marquee-text/
│   │   ├── index.html
│   │   ├── style.css
│   │   └── script.js
│   ├── scroll-reveal/
│   └── text-through-photo/
├── docs/
│   └── (각 컴포넌트 사용 가이드)
├── examples/
│   └── (적용 예시 페이지)
└── README.md
```

---

## 🤝 기여하기

새로운 컴포넌트나 개선 아이디어가 있다면 언제든 환영합니다.

1. 이 저장소를 Fork 합니다.
2. 새 브랜치를 만듭니다. (`git checkout -b feature/새컴포넌트`)
3. 변경 사항을 커밋합니다. (`git commit -m "Add: 새 컴포넌트"`)
4. 브랜치에 Push 합니다. (`git push origin feature/새컴포넌트`)
5. Pull Request를 보냅니다.

---

## 📄 라이선스

이 프로젝트는 [MIT License](./LICENSE)를 따릅니다.
자유롭게 사용·수정·배포하되, 저작권 고지는 유지해 주세요.

---

> Made with ☕ and CSS
