---
layout: default
title: Подписка на блог
permalink: /subscribe/
---

## ✉️ Подписка на блог по email

Новые посты — прямо в почту. Без спама, только публикации блога.

<style>
.email-subscribe-form{margin:24px auto 6px;max-width:420px;display:flex;gap:8px;align-items:center;justify-content:center}
.email-subscribe-form input[type="text"]{font:0.9rem/1 sans-serif;padding:9px 14px;border:1px solid #c1c9cb;border-radius:6px;background:#fff;color:#333;flex:1;min-width:0;outline:none;transition:border-color .2s}
.email-subscribe-form input[type="text"]:focus{border-color:var(--esf-link);box-shadow:0 0 0 2px rgba(0,0,0,.1)}
.email-subscribe-form button{font:600 0.85rem/1 sans-serif;padding:9px 18px;border:none;border-radius:6px;background:var(--esf-link-dark);color:#fff;cursor:pointer;white-space:nowrap;transition:opacity .2s}
.email-subscribe-form button:hover{opacity:.85}
@media(max-width:480px){.email-subscribe-form{flex-direction:column}.email-subscribe-form input[type="text"],.email-subscribe-form button{width:100%}}
</style>
<script>
(function(){var a=document.querySelector('a[href]');if(a){var c=getComputedStyle(a).color;var r=document.documentElement.style;r.setProperty('--esf-link',c);var m=c.match(/\d+/g);if(m){r.setProperty('--esf-link-dark','rgb('+m.slice(0,3).map(function(v){return Math.round(v*.75)}).join(',')+')')}}})();
</script>

<form class="email-subscribe-form"
      method="POST"
      action="https://cp.unisender.com/ru/subscribe?hash=6m95c58h3jzk8f94dp6yn1btuxetiff4psyf6hjzqukgx3hdz8qzy"
      name="subscribtion_form">
  <input type="text" name="email" placeholder="Ваш email" required>
  <button type="submit">Подписаться</button>
  <input type="hidden" name="charset" value="UTF-8">
  <input type="hidden" name="default_list_id" value="4">
  <input type="hidden" name="overwrite" value="2">
  <input type="hidden" name="is_v5" value="1">
</form>

Также можно подписаться [📱 в Telegram-канале](https://t.me/IvanBekRu) или через [Atom-фид](/feed.atom).
