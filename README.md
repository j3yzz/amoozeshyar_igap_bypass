# amoozeshyar_igap_bypass
Amoozeshyar iGAP ByPass | دور زدن کد احراز هویت سامانه‌ی آموزشیار

<h3 align="center">دور زدن کد احراز هویت سامانه آموزشیار</h3>

<hr>




<p style="direction: rtl;">
  <ul>
      <li>
         بر روی آیکون اکستنش کلیک کنید و بر روی
        <strong> Create a new script... </strong>
        کلیک کنید.
      </li>
      <li>
        کد زیر را وارد کنید و 
        <strong> Cntrl + S </strong>
        را بزنید.
      </li>
    <li>
      حالا مثل روال سابق وارد آموزشیار بشید 😁
    </li>
   </ul>
</p>

```
// ==UserScript==
// @name         Amoozeshyar IGAP ByPass
// @namespace    http://tampermonkey.net/
// @version      1
// @match        http://stdn.iau.ac.ir/Student/captchaProcess
// @match        http://stdn.iau.ac.ir/Student/manageAccount
// ==/UserScript==

(function() {
    'use strict';

      var style = document.createElement('style');
      style.innerHTML = `
          #captcha { display: unset !important; }`;
    document.head.appendChild(style);
})();
```
