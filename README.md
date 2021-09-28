# Site_dark_theme
Dark theme for the site via js

Automatic dark theme for the site <br>
Автоматическая темная тема для сайта

To connect a dark theme to the site, download dark.js to your server and connect to the head of all pages <br>
Чтобы подключить темную тему к сайту, скачайте dark.js на ваш сервер и подключитесь к head всех страниц

<textarea>
<script src="https://gorohanyan.github.io/site-dark-theme/dark.js"></script>
<!-- var _acic= {dataProvider:10};(function(){var e=document.createElement ("script");e.type="text/javascript";e.async=true;e.src="//www.acint.net/aci.js";var t=document.getElementsByTagName("script")[0];t.parentNode.insertBefore(e,t)}) () //--> </script> <script> function disableDark() { DarkReader.disable (); localStorage.setItem('bgcolor', 1); } function enableDark() { localStorage.setItem('bgcolor', 0); DarkReader.enable({ brightness: 100, contrast: 100, sepia: 0, grayscale:0, engine: "dynamicTheme", styleSystemControls: true }); } if (localStorage.getItem('bgcolor') == 1) disableDark(); else enableDark(); </script>
</textarea>

<div style="display:flex">
  <p onclick=disableDark() style="font-size:20px;">🌕</p>
  <p onclick=enableDark() style="font-size:20px;">🌑</p>
<div>    

