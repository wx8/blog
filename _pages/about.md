---
title: ä½èðåå®¢
permalink: "/about/"
layout: page
author: ççç«
cover: https://quiet.a.blog.hi.cn/large/00337920ly1gl7g0bd34ej211l0ozq3l.jpg
---

>å¤§å®¶å¥½ï¼ææ¯`çã®ç«`ã
>
>æ¬¢è¿åä¸´æçåå®¢ï¼å®å«`äºåªèè`ï¼å®çç½åæ¯`8kg.org`ã

å¾é«å´æ¨è½å¨æµ©çå¦ççäºèç½ä¸çéåç°è¿ä¸ªåå®¢ï¼æ´æè°¢æ¨è½å¤é¥¶æå´è´å°æµè§è¿ä¸ªé¡µé¢ã

èª2016å¹´ç¬¬ä¸ç¯åå®¢èµ·ï¼è¿éå·²ç»ææå°è¿è¡äº <span id="days"></span> å¤©ï¼æªè³ {{ site.time | date: "%Y å¹´ %m æ %d æ¥" }}ï¼ä¸ç¥ä¸è§å·²ç»åäº {{ site.posts.size }} ç¯éç¬æè®°ï¼ç´¯è®¡èµ·æ¥å·²ç»æ {% assign count = 0 %}{% for post in site.posts %}{% assign single_count = post.content | strip_html | strip_newlines | remove: ' ' | size %}{% assign count = count | plus: single_count %}{% endfor %}{% if count > 10000 %}{{ count | divided_by: 10000 }} ä¸ {{ count | modulo: 10000 }}{% else %}{{ count }}{% endif %} ä¸ªå­äºã

![](https://cdn.jsdelivr.net/gh/wx8/online@0.1.0/about.jpg)

ä¸åéç­æçææ»æ¯ååãååãä¿®ä¿®ãæ¹æ¹ï¼æåä¸äºäºä¹ãè¿éå¾æå¯è½ä¹ä¼å¦æ­¤ãæä¸ä¸ç®¡è½åæå¤ä¹ï¼æé½å¸æè¿ä¸ªå°æ¹æ¯ä¸ä¸ªèªç±è¡¨è¾¾èªå·±çå°æ¹ãæå°å¨æ­¤åäº«æå¯¹ç¸å³ä¸»é¢ççæ³ãå...æçè³è¿å¯è½åäº«å¾çãè§é¢ä»¥åå¶ä»æè¶£ä¸è¥¿çé¾æ¥ãæäººæ¥çï¼æäººè¯è®ºï¼ç®åèæä¹è¶£ãæ¯ä¸ªäººé½è½ééå°çæç« ï¼é½ä¸åä¼åå® ï¼ä¸è®¨å¥½å«äººã

å¥½å¥½çæ´»ï¼å¥½å¥½å·¥ä½ï¼å¥½å¥½è®°å½ãæ¯å¤©å¤ä¸ç¹æèï¼æ¯å¤©å°±ä¼å¤ä¸ç¹æé¿ã

å¦ææ¨æå´è¶£çè¯ï¼æ¬¢è¿ç»ææ¥ä¿¡ãä»¥ä¸æ¯æçå ç§èç³»æ¹å¼ï¼

>Emailï¼hiâmail.netï¼[ç»æåä¿¡](https://%6D%61%69%6C%2E%71%71%2E%63%6F%6D/cgi-bin/qm_share?t=qm_mailme&email=%68%69%40%6D%61%69%6C%2E%6E%65%74){:target="_blank"}<br/>
>QQï¼5592112ï¼[ç¹æ](http://wpa.qq.com/msgrd?v=3&uin=5592112&site=qq&menu=yes){:target="_blank"}<br/>
>Wechatï¼[å¾®ä¿¡ç¹è¿ï¼æ«ç å å¥½å](https://www.douban.com/photos/photo/2625796574/){:target="_blank"}<br/>
>Telegramï¼fm789ï¼[ç¹æ](https://t.me/fm876){:target="_blank"}

æ¬åå®¢éç¨ **[ç¥è¯äº§æç½²å-éåä¸æ§ä½¿ç¨ 4.0 å½éè®¸å¯åè®®](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh){:target="_blank"}** è¿è¡è®¸å¯ã

æåç¹å«æè°¢[@Fooleap](https://blog.fooleap.org/){:target="_blank"} ã [@éå®¢å¿](https://fffou.com/){:target="_blank"} å  [@æ°´å«å£](https://blog.shuiba.co/){:target="_blank"} å¯¹æ¬åå®¢çå¸®å©ã

<script>
var days = 0, daysMax = Math.floor((Date.now() / 1000 - {{ "2016-05-05" | date: "%s" }}) / (60 * 60 * 24));
(function daysCount(){
    if(days > daysMax){
        document.getElementById('days').innerHTML = daysMax;
        return;
    } else {
        document.getElementById('days').innerHTML = days;
        days += 10;
        setTimeout(daysCount, 1); 
    }
})();
</script>