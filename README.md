# 網頁切版直播班｜2025 夏季 第四堂 - 六角｜鞋子電商-W3、W4

## 設計稿 
```
https://www.figma.com/design/CYjKvZQo3db8xYCp6DCkKj/%E5%85%AD%E8%A7%92%EF%BD%9C%E9%9E%8B%E5%AD%90%E9%9B%BB%E5%95%86-W3%E3%80%81W4-%EF%BC%88student-ver.%EF%BC%89?node-id=12008-13571&t=zmmNB1HA9XFnyqiT-0
```

## 講義連結
https://chalk-freedom-ec6.notion.site/2296ab47eb48805c9b5ad190c7437e36?pvs=74


## 安裝node.js
- npm -v (看有沒有安裝node.js 出現版本)
- npm install (安裝node_modules套件) 
- npm run dev (執行網頁)
- npm run build (編譯網頁)

## 結構
- assest
- |-images(圖片)
- |-scss(css or scss)
- layout
- |-.ejs(每頁都有的header or footer)
- pages
- |-.html(放置每個頁面如index.html or story.html)


## CSS to SCSS
- 1.Sass用縮排省略大括號(跟python一樣)
- 2.SCSS最前方加入底線_，編譯工具會略過，使用@import不用加入底線 _
- 3.css變數改由$ var(--xxx-color) => $xxx-color
