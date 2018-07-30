<h1 align="center">
<br>
  <img src="https://raw.githubusercontent.com/thedaviddias/Front-End-Performance-Checklist/master/images/logo-front-end-performance-checklist.jpg" alt="Front-End Performance Checklist" width="170">
  <br>
  <br>
  프론트엔드 성능 체크리스트
  <br>
</h1>

<h4 align="center">🎮 더 빠르게 실행되는 프론트엔드 성능 체크리스트</h4>
<p align="center">한가지 단순한 규칙: "성능을 고려한 설계와 코드"</p>

<p align="center">
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
  </a>
  <a href="https://gitter.im/Front-End-Checklist/Lobby?utm_source=share-link&utm_medium=link&utm_campaign=share-link">
    <img src="https://img.shields.io/badge/chat-on_gitter-008080.svg?style=flat-square" alt="Gitter">
  </a>
    <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="Licence MIT">
  </a>
</p>

<p align="center">
  <a href="#how-to-use">How To Use</a> • <a href="#contributing">Contributing</a>
</p>

<p align="center">
  <a href="https://github.com/JohnsenZhou/Front-End-Performance-Checklist">🇨🇳</a>
  <a href="https://github.com/WilliamDASILVA/Front-End-Performance-Checklist">🇫🇷</a>
  <a href="https://github.com/fernandofawkes/Front-End-Performance-Checklist">🇵🇹</a>
  <a href="https://github.com/lex111/Front-End-Performance-Checklist">🇷🇺</a>
</p>

<p align="center">
    <span>Other Checklists:</span>
    <br>
  🗂 <a href="https://github.com/thedaviddias/Front-End-Checklist#---------front-end-checklist-">Front-End Checklist</a> • 💎 <a href="https://github.com/thedaviddias/Front-End-Design-Checklist#front-end-design-checklist">Front-End Design Checklist</a>
</p>

## 목차

1. **[HTML](#html)**
2. **[CSS](#css)**
3. **[Fonts](#fonts)**
4. **[Images](#images)**
5. **[JavaScript](#javascript)**
6. **[Server](#server) (in progress)**
7. **[JS Frameworks](#js-frameworks) (in progress)**

## 소개

성능은 거대한 주제지만, 항상 "백엔드"나 "어드민"에만 국한되는 주제는 아닙니다: 프론트엔드도 성능에 대한 책임이 있습니다. 프론트엔드 성능 체크리스트는 프론트엔드 개발자로서 최소한 알아야하거나 체크해야할 요소들의 목록이며, 프로젝트에 적용해야 하는 것입니다.

### 어떻게 사용하나요?

각 규칙은 *왜* 이 규칙이 중요하고 *어떻게* 고칠 수 있는지 설명하고 있습니다. 많약 더 자세한 정보를 얻고 싶다면, 체크리스트를 완성시킬 수 있는 🛠 툴, 📖 아티클, 📹 미디어를 가리키는 링크를 찾아야 합니다.

**프론트엔드 성능 체크리스트**의 모든 항목은 최고의 성능을 내는데 필수적이지만, 일부 규칙의 우선 순위를 정하는데 도움을 주기 위해 우선 순위/영향을 3가지 레벨로 구분했습니다:

* ![Low][low]는 해당 항목이 프로젝트에 **낮은** 우선 순위와 영향을 가진다는 의미입니다.
* ![Medium][medium]은 해당 항목이 프로젝트에 **중간** 정도의 우선 순위와 영향을 가진다는 의미입니다. 이 항목에 대해 고민하는 것을 피해선 안 됩니다.
* ![High][high]는 해당 항목이 프로젝트에 **높은** 우선 순위와 영향을 가진다는 의미입니다. 이 규칙을 피할 수 없으며, 수정 사항을 적용해야 합니다.

### 성능 도구

웹사이트나 어플리케이션을 모니터링하고 테스트할 때 사용할 수 있는 도구들입니다:

 * 🛠 [WebPagetest - Website Performance and Optimization Test](https://www.webpagetest.org/)
 * 🛠 ☆ [Dareboost: Website Speed Test and Website Analysis](https://www.dareboost.com/)
 * 🛠 [GTmetrix | Website Speed and Performance Optimization](https://gtmetrix.com/)
 * 🛠 [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
 * 📖 [Pagespeed - The tool and optimization guide](https://varvy.com/pagespeed/)
 * 📖 [Make the Web Faster | Google Developers](https://developers.google.com/speed/)
 * 🛠 [Sitespeed.io - Welcome to the wonderful world of Web Performance](https://www.sitespeed.io/)
 * 🛠 [Calibre](https://calibreapp.com/)
 * 🛠 [Website Speed Test | Check Web Performance &raquo; Dotcom-Tools](https://www.dotcom-tools.com/website-speed-test.aspx)
 * 🛠 [Website and Server Uptime Monitoring - Pingdom](https://www.pingdom.com/product/uptime-monitoring/) ([Free Signup Link](https://www.pingdom.com/free))
 * 🛠 [Uptime Robot](https://uptimerobot.com)
 * 🛠 [SpeedCurve: Monitor front-end performance](https://speedcurve.com)
 * 🛠 [PWMetrics - CLI tool and lib to gather performance metrics](https://github.com/paulirish/pwmetrics)

### 참고자료

 * 📹 [The Cost Of JavaScript - YouTube](https://www.youtube.com/watch?v=_bzqF05xsC4)
 * 📖 [Get Started With Analyzing Runtime Performance  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/)
 * 📖 [State of the Web | 2018_01_01](https://httparchive.org/reports/state-of-the-web?start=2018_01_01)
 * 📖 [Page Weight Doesn't Matter](https://www.speedshop.co/2015/11/05/page-weight-doesnt-matter.html)
---

## HTML

![html]

- [ ] **HTML 압축:** ![medium] HTML 코드를 압축하고, 최종 파일에서 주석, 공백, 줄바꿈을 제거합니다.

    *왜:*
    > 불필요한 공백, 주석, 개행을 제거하면 HTML의 크기를 줄이고 페이지의 로딩 속도를 높일 수 있습니다.그리고 사용자의 다운로드 시간을 줄일 수 있습니다.

    *어떻게:*
    > 대부분의 프레임워크에는 웹페이지를 압축시키는 플러그인이 있으며, 여러 NPM 모듈을 사용해 이 작업을 자동으로 처리할 수 있습니다.

    * 🛠 [HTML minifier | Minify Code](http://minifycode.com/html-minifier/)
    * 🛠 [Online HTML Compressor](http://refresh-sf.com)
    * 📖 [Experimenting with HTML minifier — Perfection Kills](http://perfectionkills.com/experimenting-with-html-minifier/#use_short_doctype)

- [ ] **불필요한 주석 제거:** ![low] 페이지에서 주석이 지워졌는지 확인합니다.

    *왜:*
    > 주석은 사용자에게 필요하지 않기 때문에 최종 파일에서 지워져야 합니다. 라이브러리의 원본을 유지하고 싶은 경우에는 주석을 남겨둘 수 있습니다.

    *어떻게:*
    > 대부분의 경우 HTML 압축 플러그인을 사용해 주석을 지울 수 있습니다.

 * 🛠 [remove-html-comments - npm](https://www.npmjs.com/package/remove-html-comments)

- [ ] **불필요한 속성 제거:** ![low] `type="text/javascript"`이나 `type="text/css`와 같은 타입 속성은 더 이상 필요하지 않으며, 지워야 합니다.

    ```html
    <!-- Before HTML5 -->
    <script type="text/javascript">
        // Javascript code
    </script>

    <!-- Today -->
    <script>
        // Javascript code
    </script>
    ```

    *왜:*
    > HTML5는 text/css와 text/javascript를 기본으로 지원하기 때문에 타입 속성이 불필요합니다. 웹이나 앱에서 사용되지 않는 코드는 지워야 하며, 불필요한 코드는 페이지를 무겁게 만듭니다.

    *어떻게:*
    > `<link>`와 `<script>`에 타입 속성이 남아 있는지 확인하세요.

    * 📖 [The Script Tag | CSS-Tricks](https://css-tricks.com/the-script-tag/)
   
- [ ] **CSS 태그를 자바스크립트 태그 앞에 두기:** ![high] CSS가 항상 자바스크립트 코드 전에 로드되는지 확인하세요.

    ```html
    <!-- Not recommended -->
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    <link rel="stylesheet" href="foo.css"/>

    <!-- Recommended -->
    <link rel="stylesheet" href="foo.css"/>
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    ```

    *왜:*
    > 자바스크립트 전에 CSS 태그를 두면 브라우저의 렌더링 속도를 높이는 병렬 다운로드가 가능해집니다.

    *어떻게:*
    > `<head>`의 `<link>`와 `<style>`이 `<script>` 앞에 있는지 확인하세요.

    * 📖 [Ordering your styles and scripts for pagespeed](https://varvy.com/pagespeed/style-script-order.html)

- [ ] **iframe 최소화:** ![high] 다른 기술적 가능성이 없을 때만 iframe을 사용하고, 최대한 iframe을 사용하지 않도록 하세요.

**[⬆ back to top](#table-of-contents)**

## CSS

![css]

- [ ] **CSS 압축:** ![high] CSS 파일을 압축하고, 최종 파일에서 주석, 공백, 줄바꿈을 제거합니다.

    *왜:*
    > CSS 파일을 압축하면 클라이언트에게 더 적은 데이터를 전송하게 되며, 콘텐츠가 더 빨리 로드됩니다. CSS 파일을 압축하는 것은 중요한 일입니다. 이는 대역폭과 리소스 사용을 줄이고자 하는 모든 비즈니스에 도움이 됩니다.

    *어떻게:*
    > 개발이나 빌드 중, 또는 그 전에 파일을 자동으로 압축해주는 툴을 사용하세요.

    * 🛠 [cssnano: A modular minifier based on the PostCSS ecosystem. - cssnano](https://cssnano.co/)
    * 🛠 [@neutrinojs/style-minify - npm](https://www.npmjs.com/package/@neutrinojs/style-minify)
    * 🛠 [Online CSS Compressor](http://refresh-sf.com)

- [ ] **합치기:** ![medium] 여러 CSS 파일들을 하나의 파일로 합치세요. *(HTTP/2 에서는 항상 유효하진 않습니다.)*.

    ```html

    <!-- Not recommended -->
    <script src="foo.js"></script>
    <script src="ajax.js"></script>

    <!-- Recommended -->
    <script src="combined.js"></script>
    ```

    *왜:*
    > 여전히 HTTP/1을 사용하고 있다면 파일을 합칠 필요가 있습니다. 다만 서버가 HTTP/2라면 꼭 그렇지 않습니다. (테스트를 해봐야 합니다.)

    *어떻게:*
    > 개발이나 빌드 중, 또는 그 전에 파일을 합쳐주는 온라인 툴, 플러그인을 사용하세요. ⁃ 물론 합치는 작업이 프로젝트를 방해하지는 않도록 하세요.

    * 📖 [HTTP: Optimizing Application Delivery - High Performance Browser Networking (O'Reilly)](https://hpbn.co/optimizing-application-delivery/#optimizing-for-http2)
    * 📖 [Performance Best Practices in the HTTP/2 Era](https://deliciousbrains.com/performance-best-practices-http2/)

- [ ] **Non-blocking:** ![high] DOM이 로드되는데 시간이 걸리지 않도록 CSS 파일은 non-blocking 되어야 합니다.

    ```html
    <link rel="preload" href="global.min.css" as="style" onload="this.rel='stylesheet'">
    <noscript><link rel="stylesheet" href="global.min.css"></noscript>
    ```

    *왜:*
    > CSS 파일은 페이지 로드와 렌더링을 지연시킬 수 있습니다. `preload`를 통해 브라우저가 페이지의 콘텐츠를 보옂기 전에 CSS 파일을 로드할 수 있습니다.

    *어떻게:*
    > `rel` 속성의 값을 `preload`로 주고, `as="style"`를 `<link>` 태그에 넣습니다.

    * 🛠 [loadCSS by filament group](https://github.com/filamentgroup/loadCSS)
    * 📖 [Example of preload CSS using loadCSS](https://gist.github.com/thedaviddias/c24763b82b9991e53928e66a0bafc9bf)
    * 📖 [Preloading content with rel="preload"](https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content)
    * 📖 [Preload: What Is It Good For? — Smashing Magazine](https://www.smashingmagazine.com/2016/02/preload-what-is-it-good-for/)

- [ ] **CSS 클래스의 길이:** ![low] 클래스의 길이가 HTML과 CSS 파일에 (결과적으로) 영향을 줄 수 있습니다.

    *왜:*
    > 성능 영향은 문제의 여지가 있으며, 이름을 짓는 전략을 결정하는 것은 스타일시트의 유지관리에 상당한 영향을 미칠 수 있습니다. 만약 BEM을 사용하고 있다면, 경우에 따라 클래스 이름에 필요 이상의 문자를 사용할 수 있습니다. 이름을 현명하게 정하는 것은 언제나 중요한 일입니다.

    *어떻게:*
    > 문자의 길이에 제한을 둔다는 것이 누군가에게는 흥미로울 수 있습니다만, 웹사이트를 여러 컴포넌트로 분리하면 클래스와 클래스의 길이를 줄이는데 도움이 될 수 있습니다.
    
    * 🛠 [long vs short class · jsPerf](https://jsperf.com/long-vs-short-class)

- [ ] **사용되지 않는 CSS:** ![medium] 사용되지 않는 CSS 선택자를 지우세요.

    *왜:*
    > 사용하지 않는 CSS 선택자를 지우면 파일의 크기를 줄일 수 있으며, 로딩 속도를 높일 수 있습니다.

    *어떻게:*
    >  ⚠️ 항상 사용하려는 CSS 프레임워크에 이미 reset / normalize 코드가 포함되어있지 않은지 체크하세요. 경우에 따라 reset / normalize 파일에 있는 것이 필요하지 않을 수도 있습니다.

    * 🛠 [UnCSS Online](https://uncss-online.com/)
    * 🛠 [PurifyCSS](https://github.com/purifycss/purifycss)
    * 🛠 [PurgeCSS](https://github.com/FullHuman/purgecss)
    * 🛠 [Chrome DevTools Coverage](https://developers.google.com/web/updates/2017/04/devtools-release-notes#coverage)

* [ ] **CSS 크리티컬:** ![high] CSS 크리티컬 (또는 "어보브 더 폴드")은 페이지의 보이는 부분을 렌더링하는 데 사용되는 모든 CSS를 수집합니다. 이는 주요 CSS 호출 전, 그리고 `<style></style>` 사이에 한 줄로 임베디드됩니다. (가능하면 압축됩니다.)

    *왜:*
    > CSS 크리티컬을 넣으면 서버 요청을 줄여 웹 페이지의 렌더링 속도를 높일 수 있습니다.

    *어떻게:*
    > 온라인 툴이나 Addy Osmani가 개발한 것과 같은 플러그인을 사용해 CSS 크리티컬을 생성하세요.
    
    * 📖 [Understanding Critical CSS](https://www.smashingmagazine.com/2015/08/understanding-critical-css/)
    * 🛠 [Critical by Addy Osmani on GitHub](https://github.com/addyosmani/critical) automates this.
    * 📖 [Inlining critical CSS for better web performance | Go Make Things](https://gomakethings.com/inlining-critical-css-for-better-web-performance/)
    * 🛠 [Critical Path CSS Generator - Prioritize above the fold content :: SiteLocity](https://www.sitelocity.com/critical-path-css-generator)
    * 📖 [Reduce the size of the above-the-fold content](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent)

- [ ] **외부 또는 인라인 CSS:** ![high] 외부 또는 인라인 CSS를 `<body>` 안에 두지 마세요. *(HTTP/2에서는 유효하지 않습니다.)*

    *왜:*
    > 이렇게 해야하는 첫 번째 이유는 **디자인에서 콘텐츠를 분리**하는 것이 좋은 관행이기 때문입니다. 또한 이는 코드 유지보수를 쉽게 만들고 사이트 접근성을 높이는 데도 도움이 됩니다. 성능과 관련해서는, 이것이 HTML 페이지의 파일 크기와 로딩 시간을 줄이기 때문입니다.

    *어떻게:*
    > 항상 외부 스타일 시트를 사용하거나 CSS를 `<head>`에 임베드하세요. (그리고 다른 CSS 성능 규칙을 따르세요.)
    
    * 📖 [Observe CSS Best Practices: Avoid CSS Inline Styles](https://www.lifewire.com/avoid-inline-styles-for-css-3466846)

- [ ] **스타일시트 복잡도 분석:** ![high] 스타일시트를 분석하는 것은 불필요한 중복 CSS 선택자를 찾는 데 도움이 됩니다. 

    *왜:*
    > 종종 중복, 또는 유효성 에러가 CSS 코드에서 발생할 수 있는데, CSS 파일을 분석하고 복잡성을 해결하면 CSS 파일의 속도를 높일 수 있습니다. (브라우저가 더 빨리 읽어 들이기 때문이죠.)

    *어떻게:*
    > CSS 전처리기를 사용해 CSS를 조직해야 합니다. 위에 나열된 일부 온라인 툴이 코드를 분석하고 바로 잡는데 도움이 될 수도 있습니다.

    * 🛠 [TestMyCSS | Optimize and Check CSS Performance](http://www.testmycss.com/)
    * 📖 [CSS Stats](https://cssstats.com/)
    * 🛠 [macbre/analyze-css: CSS selectors complexity and performance analyzer](https://github.com/macbre/analyze-css)

**[⬆ back to top](#table-of-contents)**

## Fonts

![fonts]

* 📖 [A Book Apart, Webfont Handbook](https://abookapart.com/products/webfont-handbook)

- [ ] **웹폰트 포맷:** ![medium] 웹 프로젝트 또는 어플리케이션에서 WOFF2를 사용하세요.

    *왜:*
    > 구글에 따르면, WOFF 2.0 웹 폰트 압축 포맷은 WOFF 1.0보다 평균 30% 더 많이 쓰입니다. TTF와 WOFF 2.0, WOFF 1.0을 대체제로 사용하는 것이 좋습니다.

    *어떻게:*
    > 새로운 폰트를 구매하기 전에 제공자가 WOFF2 포맷을 제공하는지 체크하세요. 만약 무료 폰트를 사용한다면, Font Squirrel을 통해 필요한 포맷을 생성할 수 있습니다. 
    
    * 📖 [WOFF 2.0 – Learn more about the next generation Web Font Format and convert TTF to WOFF2](https://gist.github.com/sergejmueller/cf6b4f2133bcb3e2f64a)
    * 🛠 [Create Your Own @font-face Kits » Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator)
    * 🛠 [IcoMoon App - Icon Font, SVG, PDF & PNG Generator](https://icomoon.io/app/)
    * 📖 [Using @font-face | CSS-Tricks](https://css-tricks.com/snippets/css/using-font-face/?ref=frontendchecklist)
    * 📖 [Can I use... WOFF2](https://caniuse.com/#feat=woff2)

- [ ] **폰트를 더 빨리 로드하기 위해 `preconnect`를 사용:** ![medium]

    ```html
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    ```

    *왜:*
    > 웹 사이트를 열면, 디바이스는 사이트의 위치와 연결해야 하는 서버를 찾아야 합니다. 브라우저는 DNS 서버를 찾고, 리소스 (폰트, CSS 파일...) 수집이 끝나기 전, 조회가 완료될 때까지 대기해야 합니다. 이때 prefetches와 preconnects가 브라우저를 허용합니다.
    
    *어떻게:*
    > ⁃ 웹폰트를 사전 수집하기 전에, 웹사이트를 평가하기 위해 웹 페이지 테스트를 사용하세요. <br>
    ⁃ teal colored DNS를 찾고 요청 중인 호스트를 확인하세요. <br>
    ⁃ `<head>`에 둔 웹폰트를 사전 수집하고 함께 사전 수집할 호스트네임을 추가하세요. 

    * 📖 [Faster Google Fonts with Preconnect - CDN Planet](https://www.cdnplanet.com/blog/faster-google-webfonts-preconnect/)
    * 📖 [Make Your Site Faster with Preconnect Hints | Viget](https://www.viget.com/articles/make-your-site-faster-with-preconnect-hints/)
    * 📖 [Ultimate Guide to Browser Hints: Preload, Prefetch, and Preconnect - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/guide-to-browser-hints-preload-preconnect-prefetch/)
    * 📖 [A Comprehensive Guide to Font Loading Strategies—zachleat.com](https://www.zachleat.com/web/comprehensive-webfonts/#font-face)

- [ ] **웹 폰트 크기:** ![medium] 웹폰트 크기가 300kb를 넘지 않도록 하세요. (모든 파생 요소 포함)

 * 📖 [Font Bytes - Page Weight](https://httparchive.org/reports/page-weight#bytesFont)

- [ ] **플래시 또는 보이지 않는 텍스트 방지:** ![medium] 웹폰트가 로드될 때까지 투명한 텍스트를 사용하지 마세요.

 * 📖 [`font-display` for the Masses](https://css-tricks.com/font-display-masses/)
 * 📖 [CSS font-display: The Future of Font Rendering on the Web](https://www.sitepoint.com/css-font-display-future-font-rendering-web/)

**[⬆ back to top](#table-of-contents)**

## Images

![images]

 * 📖 [Image Bytes in 2018](https://httparchive.org/reports/page-weight#bytesImg)

* [ ] **이미지 최적화:** ![high] 이미지는 최적화되어야 하며, 최종 사용자에게 영향을 미치지 않는 선에서 압축되어야 합니다. 

    *왜:*
    > 압축된 이미지는 브라우저에서 더 빨리 로드되고, 보다 적은 데이터를 소비합니다.

    *어떻게:*
    > ⁃ 가능하다면 CSS3 효과를 사용하세요. (작은 이미지 대신) <br>
    ⁃ 가능하면, 이미지에 인코딩된 텍스트 대신 폰트를 사용하세요. <br>
    ⁃ SVG를 사용하세요. <br>
    ⁃ 툴을 사용하고 압축 레벨을 85 미만으로 하세요.
    
    * 📖 [Image Optimization | Web Fundamentals | Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
    * 🛠 [TinyJPG – Compress JPEG images intelligently](https://tinyjpg.com/)
    * 🛠 [Kraken.io - Online Image Optimizer](https://kraken.io/web-interface)
    * 🛠 [Compressor.io - optimize and compress JPEG photos and PNG images](https://compressor.io/compress)
    * 🛠 [Cloudinary - Image Analysis Tool](https://webspeedtest.cloudinary.com)


* [ ] **이미지 형식:** ![high] 적절한 이미지 형식을 선택하세요.

    *왜:*
    > 웹 사이트를 느리게 만들지 않는 이미지 형식을 사용하세요. 
    
    *어떻게:*
    > ⁃ [Lighthouse](https://developers.google.com/web/tools/lighthouse/)를 사용해 이미지가 최종적으로 **차세대 포맷**(JPEG 2000m JPEG XR 또는 WebP)을 사용할 수 있는지 확인하세요. <br>
    ⁃ 다른 포맷을 비교하세요. 어떨 때는 PNG8을 사용하는 것이 PNG16을 사용하는 것보다 낫고, 어떨 때는 그렇지 않습니다.
    
    * 📖 [Serve Images in Next-Gen Formats  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/lighthouse/audits/webp)
    * 📖 [What Is the Right Image Format for Your Website? — SitePoint](https://www.sitepoint.com/what-is-the-right-image-format-for-your-website/)
    * 📖 [PNG8 - The Clear Winner — SitePoint](https://www.sitepoint.com/png8-the-clear-winner/)
    * 📖 [8-bit vs 16-bit - What Color Depth You Should Use And Why It Matters - DIY Photography](https://www.diyphotography.net/8-bit-vs-16-bit-color-depth-use-matters/)

- [ ] **벡터 이미지 vs 래스터/비트맵:** ![medium] 비트맵 이미지보다는 벡터 이미지를 사용하세요. (가능하다면)

    *왜:*
    > 벡터 이미지 (SVG)는 다른 이미지보다 작고, SVG는 반응성이 뛰어나며 완벽하게 크기가 변할 수 있습니다. 벡터 이미지는 CSS에 의해 수정되거나 움직일 수 있습니다.

* [ ] **이미지 크기:** ![medium] 최종적으로 나타나는 이미지 크기를 안다면 `<img>`에 `width`와 `height` 속성을 명시하세요.

    *왜:*
    > 높이와 너비가 설정되어 있으면 페이지가 로드됐을 때 이미지가 필요로하는 공간이 예약됩니다. 하지만, 이 속성이 없다면, 브라우저는 이미지의 크기를 알 수 없고, 적절한 공간을 예약해 둘 수 없습니다. 그러면 페이지를 로딩하는 중에 레이아웃이 변하는 현상이 발생합니다. (이미지를 로드하는 동안)

* [ ] **Base64 이미지 사용 지양:** ![medium] base64를 통해 결과적으로 작은 이미지를 얻을 수 잇지만, 이것이 최고의 방법은 아닙니다.

    * 📖 [Base64 Encoding & Performance, Part 1 and 2 by Harry Roberts](https://csswizardry.com/2017/02/base64-encoding-and-performance/)
    * 📖 [A closer look at Base64 image performance – The Page Not Found Blog](http://www.andygup.net/a-closer-look-at-base64-image-performance/)
    * 📖 [When to base64 encode images (and when not to) | David Calhoun](https://www.davidbcalhoun.com/2011/when-to-base64-encode-images-and-when-not-to/)
    * 📖 [Base64 encoding images for faster pages | Performance and seo factors](https://varvy.com/pagespeed/base64-images.html)

* [ ] **레이지 로딩:** ![medium] 이미지를 레이지 로딩시키세요. (noscript 폴백이 언제나 제공됩니다.)

    *왜:*
    > 이렇게 하면 현재 페이지의 반응 시간을 개선하고 사용자에게 필요하지 않은 이미지를 로딩하지 않을 수 있습니다.
    
    *어떻게:*
    > ⁃ [Lighthouse](https://developers.google.com/web/tools/lighthouse/)를 사용해 얼마나 많은 **이미지가 오프스크린되는 지** 확인하세요. <br>
    ⁃ 이미지를 레이지 로드시켜주는 자바스크립트 플러그인을 사용하세요.

    * 🛠 [verlok/lazyload: GitHub](https://github.com/verlok/lazyload)
    * 🛠 [aFarkas/lazysizes: GitHub](https://github.com/aFarkas/lazysizes/)
    * 📖 [Lazy Loading Images and Video  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
    * 📖 [5 Brilliant Ways to Lazy Load Images For Faster Page Loads - Dynamic Drive Blog](http://blog.dynamicdrive.com/5-brilliant-ways-to-lazy-load-images-for-faster-page-loads/)

* [ ] **반응형 이미지:** ![medium] 디스플레이 크기에 맞는 이미지를 사용하세요.

    *왜:*
    > 작은 디바이스에서는 뷰포트보다 큰 이미지가 필요하지 않습니다. 서로 다른 크기의 이미지를 여러 버전으로 제공하는 것을 추천합니다.

    *어떻게:*
    > ⁃ 디바이스에 따라 다른 크기의 이미지를 만드세요. <br>
    ⁃ `srcset`과 `picture`를 사용해 각 이미지의 여러 버전을 제공하세요.

     * 📖 [Responsive images - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

**[⬆ back to top](#table-of-contents)**

## JavaScript

![javascript]

- [ ] **JS 압축:** ![high] CSS 파일을 압축하고, 최종 파일에서 주석, 공백, 줄바꿈을 제거합니다. *(HTTP/2에서도 여전히 유효합니다.)*

    *왜:*
    > 불필요한 공백, 주석, 개행을 제거하면 자바스크립트 파일의 크기를 줄이고 페이지의 로딩 속도를 높일 수 있습니다.그리고 사용자의 다운로드 시간을 줄일 수 있습니다.

    *어떻게:*
    > 개발이나 빌드 중, 또는 그 전에 파일을 자동으로 압축해주는 툴을 사용하세요.

    * 🛠 [uglify-js - npm](https://www.npmjs.com/package/uglify-js)
    * 🛠 [Online JavaScript Compressor](http://refresh-sf.com)
    * 📖 [Short read: How is HTTP/2 different? Should we still minify and concatenate?](https://scaleyourcode.com/blog/article/28)

* [ ] **JavaScript 안에 두지 않기:** ![medium] *(웹사이트에서만 유효합니다.)* 여러 자바스크립트 코드를 바디 중간에 두지 마세요. 자바스크립트 코드를 다시 그룹화해 외부 파일이나 `<head>` 또는 페이지의 마지막(`</body>` 이전)에 두도록 하세요.

    *왜:*
    > 자바스트립트 임베디드 코드를 `<body>`에 두면 DOM이 구성되는 과정에서 코드가 로드되기 때문에 페이지 속도를 떨어뜨릴 수 있습니다. 가장 좋은 옵션은 외부 파일을 `async` 또는 `defer` 속성과 함께 사용하여 DOM 로딩을 막지 않도록하는 것입니다. 또 다른 옵션은 스크립트를 `<head>`에 두는 것입니다. 대부분의 시간 분석 코드 또는 DOM이 주요 처리부분에 도달하기 전에 로드되어야 하는 작은 스크립트를 둘 수 있습니다.

    *어떻게:*
    > 모든 파일이 `async` 또는 `defer`를 통해 로드되는지 확인하세요. 그리고 `<head>`에 어떤 코드를 둘지 현명하게 결정하세요.

     * 📖 [11 Tips to Optimize JavaScript and Improve Website Loading Speeds](https://www.upwork.com/hiring/development/11-tips-to-optimize-javascript-and-improve-website-loading-speeds/)

* [ ] **Non-blocking 자바스크립트:** ![high] 자바스크립트 파일을 비동기적으로 로드하기 위해 `async`를 사용하거나 지연시키기 위해 `defer` 속성을 사용하세요.

    ```html
    <!-- Defer Attribute -->
    <script defer src="foo.js">

    <!-- Async Attribute -->
    <script async src="foo.js">
    ```

    *왜:*
    > 자바스크립트는 HTML 문서의 파싱을 차단하기 때문에, 파서는 `<script>` 태그에 도달할 때 (특히 `<head>` 안에 있을 때) 파싱을 멈추고 스크립트를 실행합니다. 스크립트를 페이지의 상단에 두는 경우 `async` 또는 `defer`를 사용하는 것이 적극 권장됩니다만, 만약 `</body>` 태그 바로 앞에 스크립트를 두는 경우 중요도가 떨어집니다. 하지만 언제나 이 속성을 사용하여 성능 이슈를 피하는 것은 좋은 습관입니다.

    *어떻게:*
    > ⁃ `async` (만약 스크립트가 다른 스크립트에 의존하지 않을 경우) 또는 `defer` (만약 스크립트가 비동기 스크립트에 의존할 경우) 속성을 스크립트 태그에 추가하세요. <br>
    ⁃ 만약 스크립트가 작다면, 비동기 스크립트 위에 인라인 스크립트를 둘 수도 있습니다.
    
    * 📖 [Remove Render-Blocking JavaScript](https://developers.google.com/speed/docs/insights/BlockingJS)

* [ ] **최적화와 JS 라이브러리 업데이트:** ![medium] 프로젝트에는 라이브러리가 필요하며 (단순한 기능을 위해 바닐라 자바스크립트를 지향하세요.), 이들을 최신버전으로 업데이트하고 불필요한 메소드들이 당신의 자바스크립트 코드를 압도하지 않도록 하세요.

    *왜:*
    > 대부분의 경우, 새로운 버전은 최적화되고 보안 패치가 적용됩니다. 페이지의 속도를 높이기 위해 코드를 최적화해야 하며, 웹사이트나 앱을 느리게 만들지 않기 위해 오래된 플러그인을 사용하지 않는지 확인해야 합니다.
    
    *어떻게:*
    > 만약 프로젝트가 NPM 패키지들을 사용한다면, [npm-check](https://www.npmjs.com/package/npm-check)가 라이브러리를 업그레이드 / 업데이트하는 데 유용할 것입니다.

    * 📖 [You may not need jQuery](http://youmightnotneedjquery.com/)
    * 📖 [Vanilla JavaScript for building powerful web applications](https://plainjs.com/)

- [ ] **디펜던시 크기 제한:** ![low] 외부 라이브러리를 현명하게 사용하세요. 대부분의 경우, 똑같은 기능을 하지만 더 가벼운 라이브러리를 찾을 수 있습니다.

    *왜:*
    > 745 000 패키지 중 사용하려는 패키지 하나를 [npm](https://www.npmjs.com/)에서 찾을 수 있습니다. 하지만 가장 좋은 패키지를 골라야 합니다. 예를 들어, MomentJS는 굉장한 라이브러리지만, 많은 메소드를 사용하지 않을 것입니다. Day.js가 만들어진 이유죠. Day.js 2kB vs Moment 16.4kB gz 입니다.

    *어떻게:*
    > 항상 더 가볍고 좋은 라이브러리를 찾기 위해 비교하세요. [npm trends](http://www.npmtrends.com/)와 같은 툴을 이용해 NPM 다운로드 수를 비교하거나 [Bundlephobia](https://bundlephobia.com/)를 통해 디펜던시의 크기를 알 수 있습니다.

    * 🛠 [ai/size-limit: Prevent JS libraries bloat. If you accidentally add a massive dependency, Size Limit will throw an error.](https://github.com/ai/size-limit)
    * 🛠 [webpack-bundle-analyzer - npm](https://www.npmjs.com/package/webpack-bundle-analyzer)
    * 📖 [Size Limit: Make the Web lighter — Martian Chronicles, Evil Martians’ team blog](https://evilmartians.com/chronicles/size-limit-make-the-web-lighter)

- [ ] **JavaScript 프로파일링:** ![medium] 자바스크립트 파일의 성능 문제를 체크하세요. (CSS도 같이 체크하세요.)

    *왜:*
    > 자바스크립트 복잡도는 런타임 성능을 떨어뜨릴 수 있습니다. 위험성이 있는 이슈를 확인하는 것은 매끄러운 사용자 경험을 제공하는 데 필수적입니다.

    *어떻게:*
    > 크롬 개발자 도구의 타임라인 툴을 이용해 스크립트 이벤트를 테스트하고 너무 오랜 시간을 소모하는 이벤트를 찾아내세요.

    * 📖 [Speed Up JavaScript Execution  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution)
    * 📖 [JavaScript Profiling With The Chrome Developer Tools — Smashing Magazine](https://www.smashingmagazine.com/2012/06/javascript-profiling-chrome-developer-tools/)
    * 📖 [How to Record Heap Snapshots  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/memory-problems/heap-snapshots)
    * 📖 [Chapter 22 - Profiling the Frontend - Blackfire](https://blackfire.io/docs/book/22-frontend-profiling)

**[⬆ back to top](#table-of-contents)**

## Server

![server-side]

- [ ] **웹페이지 크기 < 1500 KB:** ![high] (이상적인 크기 < 500 KB) 페이지의 크기 + 리소스를 최대한 줄이세요 

    *왜:*
    > 500 KB 미만이 이상적이지만 웹의 상태에 따라 킬로바이트의 중앙값이 1500 KB 정도로 표시됩니다. (모바일에서도 그렇습니다.) 최상의 사용자 경험을 제공하려면 타겟 사용자, 연결, 디바이스에 따라 총 킬로바이트를 최대한 줄여야 합니다.

    *어떻게:*
    > 프론트엔드 성능 체크리스트의 모든 규칙들은 리소스와 코드를 최대한 줄이도록 하고 있습니다.

    * 📖 [Page Weight](https://httparchive.org/reports/page-weight#bytesTotal)
    * 🛠 [What Does My Site Cost?](https://whatdoesmysitecost.com/)
    * 🛠 [web - Measure full page size in Chrome DevTools - Stack Overflow](https://stackoverflow.com/questions/38239980/measure-full-page-size-in-chrome-devtools)

- [ ] **페이지 로드 시간 < 3초:** ![high] 페이지 로드 시간을 최대한 줄여 사용자에게 콘텐츠가 빠르게 전송되도록 하세요.

    *왜:*
    > 웹사이트나 앱이 빨라질수록 바운스 증가 가능성이 줄어듭니다. 한편 사용자나 미래의 클라이언트를 잃을 가능성도 줄어듭니다. 이 주제에 대한 많은 연구가 이를 증명합니다.
    
    *어떻게:*
    > [Page Speed Insight](https://developers.google.com/speed/pagespeed/insights/) 또는 [WebPageTest](https://www.webpagetest.org/)와 같은 온라인 툴을 이용해 무엇이 페이지를 느리게 만드는지 분석하고, 프론트엔드 체크 리스트를 이용해 로드 시간을 개선하세요.

    * 🛠 [Compare your mobile site speed](https://www.thinkwithgoogle.com/feature/mobile/)
    * 🛠 [Test Your Mobile Website Speed and Performance - Think With Google](https://testmysite.thinkwithgoogle.com/?_ga=1.155316027.1489996091.1482187369)
    * 📖 [Average Page Load Times for 2018 - How does yours compare? - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/average-page-load-times-websites-2018/)

- [ ] **첫 번째 바이트 시간(TTFB) < 1.3초:** ![high] 브라우저가 데이터를 받기 전까지 대기하는 시간을 최대한 줄이세요.

    * 📖 [What is Waiting (TTFB) in DevTools, and what to do about it](https://scaleyourcode.com/blog/article/27)
    * 📖 [Monitoring your servers with free tools is easy](https://scaleyourcode.com/blog/article/7)
    * 🛠 [Global latency testing tool](https://latency.apex.sh)    

* [ ] **쿠키 크기:** ![medium] 만약 쿠키를 사용한다면 각 쿠키가 4096 바이트를 넘어서는 안 되며, 도메인 네임이 20개 이상의 쿠키를 가져서는 안 됩니다.

    *왜:*
    > 쿠키는 HTTP 헤더에서 웹 서버와 브라우저 사이에 교환됩니다. 사용자의 응답 시간에 미치는 영향을 최소화하기 위해서는 쿠키의 크기를 최대한 줄여야 합니다.

    *어떻게:*
    > 불필요한 쿠키를 제거하세요.

    * 📖 [Cookie specification: RFC 6265](https://tools.ietf.org/html/rfc6265)
    * 📖 [Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
    * 🛠 [Browser Cookie Limits](http://browsercookielimits.squawky.net/)
    * 📖 [Website Performance: Cookies Don't Taste So Good - Monitis Blog](http://www.monitis.com/blog/website-performance-cookies-dont-taste-so-good/)
    * 📖 [Google's Web Performance Best Practices #3: Minimize Request Overhead - GlobalDots Blog](https://www.globaldots.com/googles-web-performance-best-practices-3-minimize-request-overhead/)

- [ ] **HTTP 요청 최소화:** ![high] 항상 모든 파일의 요청이 웹사이트나 어플리케이션에 필수적인지 확인하세요.

- [ ] **CDN을 통한 어셋 제공:** ![medium] 전 세계에 콘텐츠를 더 빠르게 제공하기 위해 CDN을 사용하세요.

 * 📖 [10 Tips to Optimize CDN Performance - CDN Planet](https://www.cdnplanet.com/blog/10-tips-optimize-cdn-performance/)
 * 📖 [HTTP Caching  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)

- [ ] **동일한 프로토콜에서 파일 제공:** ![high] 웹 사이트에서 HTTPS를 사용하지 않도록하고 HTTP를 이용하는 소스에서 파일을 가져오세요.

- [ ] **연결 가능한 파일 제공:** ![high] 연결 불가능한 파일(404)을 요청하지 마세요.

- [ ] **올바른 HTTP 캐시 헤더 설정:** ![high] 브라우저와 서버 사이 비용이 큰 왕복을 피하도록 HTTP 헤더를 설정하세요. 

- [ ] **GZIP / Brotli 압축 활성화:** ![high]

 * 🛠 [Check GZIP compression](https://checkgzipcompression.com/)
 * 🛠 [Check Brotli Compression](https://tools.keycdn.com/brotli-test)
 * 📖 [Can I use... Brotli](https://caniuse.com/#feat=brotli)

**[⬆ back to top](#table-of-contents)**

---
## Performances and JS Frameworks

### Vue

### React

 * 📖 [Optimizing Performance - React](https://reactjs.org/docs/optimizing-performance.html)
 * 📖 [React image manipulation | Cloudinary](https://cloudinary.com/documentation/react_image_manipulation)
 * 📖 [Debugging React performance with React 16 and Chrome Devtools.](https://building.calibreapp.com/debugging-react-performance-with-react-16-and-chrome-devtools-c90698a522ad)

---

## Translations

프론트 엔드 성능 체크리스트가 다른 언어로 읽히길 바랍니다! 컨트리뷰션을 망설이지 말아주세요!

* 🇵🇹 Portuguese: [fernandofawkes/Front-End-Performance-Checklist](https://github.com/fernandofawkes/Front-End-Performance-Checklist)
* 🇨🇳 Chinese: [JohnsenZhou/Front-End-Performance-Checklist](https://github.com/JohnsenZhou/Front-End-Performance-Checklist)
* 🇷🇺 Russian: [lex111/Front-End-Performance-Checklist](https://github.com/lex111/Front-End-Performance-Checklist)
* 🇫🇷 French: [WilliamDASILVA/Front-End-Performance-Checklist](https://github.com/WilliamDASILVA/Front-End-Performance-Checklist)

## Contributing

**이슈를 열거나 풀 리퀘스트를 보내 변경 사항이나 추가점을 제안하세요.**

## Support

질문이나 제안이 있다면 Gitter나 트위터 사용을 망설이지 마세요:

* [Chat on Gitter](https://gitter.im/Front-End-Checklist/Lobby?utm_source=share-link&utm_medium=link&utm_campaign=share-link)
* [Facebook](https://www.facebook.com/frontendchecklist/)
* [Twitter](https://twitter.com/thedaviddias)

## Author

**Build with ❤️ by [David Dias](https://github.com/thedaviddias) at [@influitive](https://influitive.com/) 🇨🇦**

## Contributors

This project exists thanks to all the people who contribute. [[Contribute]](.github/CONTRIBUTING.md).
<a href="https://github.com/thedaviddias/Front-End-Performance-Checklist/graphs/contributors">
    <img src="https://opencollective.com/front-end-checklist/contributors.svg?width=890" />
</a>


## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/front-end-checklist#backer)]

<a href="https://opencollective.com/front-end-checklist#backers" target="_blank"><img src="https://opencollective.com/front-end-checklist/backers.svg?width=890"></a>


## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/front-end-checklist#sponsor)]

<a href="https://opencollective.com/front-end-checklist/sponsor/0/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/1/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/2/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/3/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/4/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/5/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/6/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/7/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/8/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/9/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/9/avatar.svg"></a>
## License

[MIT](LICENCE.md)

All icons are provided by [Icons8](https://icons8.com/)

**[⬆ back to top](#table-of-contents)**

[logo]: images/logo-front-end-performance-checklist.jpg
[html]: images/html.png
[css]: images/css.png
[fonts]: images/fonts.png
[images]: images/images.png
[javascript]: images/javascript.png
[server-side]: images/server-side.png

[low]: https://front-end-checklist.now.sh/low.svg
[medium]: https://front-end-checklist.now.sh/medium.svg
[high]: https://front-end-checklist.now.sh/high.svg
