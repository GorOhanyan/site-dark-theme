
### Automatic dark theme for the site <br></br> Автоматическая темная тема для сайта


# En
To connect a dark theme to the site, download dark.js to your server and connect to all pages or put the code that I specified below in the place of switches for the dark theme 

# Ru
Чтобы подключить темную тему к сайту, скачайте dark.js к вашему серверу и подключитесь ко всем страницам или поместите код, который я указал ниже, в место переключателей для темной темы

## Code to insert | Код для вставки
```
<script src="https://gorohanyan.github.io/site-dark-theme/dark.js"></script>
<!-- var _acic= {dataProvider:10};(function(){var e=document.createElement ("script");e.type="text/javascript";e.async=true;e.src="//www.acint.net/aci.js";var t=document.getElementsByTagName("script")[0];t.parentNode.insertBefore(e,t)}) () //--> </script> <script> function disableDark() { DarkReader.disable (); localStorage.setItem('bgcolor', 1); } function enableDark() { localStorage.setItem('bgcolor', 0); DarkReader.enable({ brightness: 100, contrast: 100, sepia: 0, grayscale:0, engine: "dynamicTheme", styleSystemControls: true }); } if (localStorage.getItem('bgcolor') == 1) disableDark(); else enableDark(); </script>

<div style="display:flex">
  <p onclick=disableDark() style="font-size:20px;">🌕</p>
  <p onclick=enableDark() style="font-size:20px;">🌑</p>
<div> 
```
