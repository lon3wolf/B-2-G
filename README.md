# B-2-G
Use bing as default, change to google for search

Create a bookmarklet on your browser favorite toolbar and set this script in the url field
```
javascript:function B2G(){ var str=document.location.toString(); document.location.href=str.replace(/bing/gi,"google"); } B2G();
```
