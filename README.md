# My-link-page
<!doctype html> 
<html lang="en"> 
<head> 
<meta charset="utf-8"> 
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no"> 
<meta name="theme-color" content="#000000"> 
<title>Open Link</title> 
<style> 
html,body{margin:0;height:100%;overflow:hidden;background:#000;font-family:system-ui,sans-serif} 
.wrap{position:fixed;inset:0;display:flex;align-items:center;justify-content:center;transform-origin:center center;animation:zoom 12s ease-in-out infinite} 
.card{text-align:center;padding:24px;text-decoration:none;color:#fff;cursor:pointer} 
.card:active{opacity:0.7}
.big{font-size:10vw;line-height:1.05;font-weight:700;letter-spacing:.02em} 
.sub{margin-top:12px;font-size:4vw;opacity:.8} 
.stop{position:fixed;right:16px;bottom:16px;background:#fff;color:#000;border:0;border-radius:999px;padding:12px 16px;font-size:14px;cursor:pointer} 
@keyframes zoom{0%{transform:scale(1)}50%{transform:scale(1.18)}100%{transform:scale(1)}} 
</style> 
</head> 
<body> 

<!-- Changed the wrapper div into a clickable anchor link -->
<div class="wrap" id="wrap">
  <a href="https://example.com" class="card" target="_blank" rel="noopener noreferrer">
    <div class="big">Open</div>
    <div class="sub">Tap to launch web link</div>
  </a>
</div> 

<button class="stop" onclick="document.getElementById('wrap').style.animation='none'">Stop</button> 
</body> 
</html>
