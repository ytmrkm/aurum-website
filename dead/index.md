---
layout: std
title: Is aurumOS dead?
responses:
  - "NO"
---
<h1 id="is-dead-title">Is aurumOS dead?</h1>
<div id="is-dead-response">NO</div>
<script type="text/javascript">
var responses = ["{{ page.responses | join: '","' }}"];
var idx = Math.floor(Math.random() * responses.length);
document.querySelector("#is-dead-response").innerHTML = responses[idx];
</script>
