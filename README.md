# Amoozeshyar igap bypass
&rlm; روشی راحت برای دور زدن اجبار نصب آی گپ برای احراز هویت در سامانه آموزشیار  &lrm;

&rlm; 1. نصب افزونه ی زیر در مرورگر خود &lrm;
**Link:** [tampermonkey](https://www.tampermonkey.net/)

&rlm; 2.در مرحله ی بعد روی آیکون افزونه کلیک کنید &lrm;
![]()
&rlm; 3. سپس روی گزینه ی ساخت اسکریپ جدید کلیک کرده &lrm;

&rlm; 4. در اخر متن زیر را کپی کرده و در ادیتور باز شده جای گذاری کنید &lrm;
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
<div dir="rtl">
با دکمه های ترکیبی <strong> Ctrl + S </strong> فایل را ذخیره کنید 
</div>
