# 경기천년제목

[배포처 바로가기](https://www.gg.go.kr/contents/contents.do?ciIdx=679&menuId=2457)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Gyeonggi Title`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/GyeonggiTitle.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/GyeonggiTitle.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Gyeonggi Title';
    font-weight: 300;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/GyeonggiTitle-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/GyeonggiTitle-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/GyeonggiTitle-Light.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/GyeonggiTitle-Light.ttf') format('truetype');
}
@font-face {
    font-family: 'Gyeonggi Title';
    font-weight: 500;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/GyeonggiTitle-Medium.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/GyeonggiTitle-Medium.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/GyeonggiTitle-Medium.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/GyeonggiTitle-Medium.ttf') format('truetype');
}
@font-face {
    font-family: 'Gyeonggi Title';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/GyeonggiTitle-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/GyeonggiTitle-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/GyeonggiTitle-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/GyeonggiTitle-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/subsets/GyeonggiTitle-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/GyeonggiTitle/subsets/GyeonggiTitle-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Gyeonggi Title", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
경기도 서체는 누구나 무료로 다운로드 받아 자유롭게 사용할 수 있습니다. 
영상, 인쇄, 웹 등 다양한 매체에 자유롭게 사용이 가능하며, 특별한 허가 절차 없이 사용할 수 있습니다. 
다만, 경기도 서체를 유료로 양도하거나 판매하는 등 상업적 행위는 금지하고 있습니다.
```
