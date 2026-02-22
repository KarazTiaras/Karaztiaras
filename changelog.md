**Description**: KaraZ Tiaras – responsive one-page e-commerce site with live Instagram feed, wishlist & smooth scroll animations.
**Files**:
- index.html: Entry point; layout & content structure. Refs: style.css, instagram.js, wishlist.js, main.js, instagram_mock.json, Tailwind CDN, Google Fonts, Lucide, GSAP.
- style.css: Custom palette, typography tweaks, scrollbar, utility overrides. Refs: Google Fonts variables.
- instagram.js: Logic to fetch/parse Instagram Shop feed through proxy or local mock, build product cards. Refs: instagram_mock.json.
- wishlist.js: LocalStorage wishlist add/remove, badge update, event delegation.
- main.js: App bootstrap, GSAP animations, smooth scroll, module coordination, lucide icon render.
- instagram_mock.json: Sample feed used when live API token absent.
