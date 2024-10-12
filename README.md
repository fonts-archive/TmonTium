# 티몬 티움체

[배포처 바로가기](https://brunch.co.kr/@creative/32)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Tmon Tium`입니다.

### HTML

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/TmonTium/TmonTium.css"
  type="text/css"
/>
```

### CSS `@Import`

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/TmonTium/TmonTium.css");
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Tmon Tium';
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/TmonTium/TmonTium.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TmonTium/TmonTium.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TmonTium/TmonTium.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link 
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/TmonTium/subsets/TmonTium-dynamic-subset.css"
  type="text/css"
/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/TmonTium/subsets/TmonTium-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Tmon Tium", -apple-system, BlinkMacSystemFont, "Segoe UI",
  Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
TMON 체/TMON 티움체의 지적 재산권은 티몬에 있습니다. 
TMON 체/TMON 티움체는 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 자유롭게 수정하고 재배포하실 수 있습니다. 
단, 글꼴 자체를 유료로 판매하는 것은 금지하며 
TMON 체/TMON 티움체의 본 저작권 안내와 라이선스 전문을 포함해서 다른 소프트웨어와 번들하거나 재배포 또는 판매가 가능합니다. 
TMON 체/TMON 티움체 라이선스 전문을 포함하기 어려울 경우, TMON 체/TMON 티움체의 출처 표기를 권장합니다. 
예) 이 페이지에는 티몬에서 제공한 티움체글꼴이 적용되어 있습니다. 
TMON 체/TMON 티움체는 인쇄나 출판, 영상, 웹, 모바일 등에 자유롭게 사용할 수 있으나, 
폰트를 고치거나 다른 포맷으로 변형하는 것은 금지됩니다. 
프로그램이나 장비, 기기, 서버, 게임 등에 폰트가 임베딩 될 경우 별도의 허락이 필요하지 않으나 TMON 체/TMON 티움체가 임베딩된 프로그램 장비, 기기, 서버, 게임, 인쇄물, 광고물(온라인 포함)상 
제작물 이미지는 티몬의 프로모션을 위해 활용될 수 있습니다. 
(이를 원치 않는 사용자는 언제든지 티몬에 요청하실 수 있습니다.) 
정확한 사용 조건은 아래 TMON 체/TMON 티움체 라이선스 전문을 참고하시기 바랍니다. 
※ 참고해주세요! 
라이선스 전문의 한글은 이용자의 이해를 돕기 위해 영문 원본을 번역해 서비스하고 있으며 법적 효력은 영문에 한합니다. 이 점 참고하시기 바랍니다.
```
