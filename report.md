---
layout: default
title: Report a Security Issue
permalink: /report/
---

{% if site.hackerone_url %}
	<script type="text/javascript">
		window.location = "{{ site.hackerone_url }}";
	</script>
{% elsif site.bugcrowd_url %}
	<script type="text/javascript">
		window.location = "{{ site.bugcrowd_url }}";
	</script>
{% else %}
# Report a security issue

### Our reporting procedure

To be specified by the {{ site.company_name }} Security Team.

<!--<iframe src="https://bugcrowd.com/{{ bugcrowd_id }}/external/report" style="width: 100%; height: 2480px; border: medium none; overflow: hidden;" scrolling="no" id="iFrameResizer0"></iframe>-->
{% endif %}

{% if site.hackerone_embed_form %}
	<script async src="https://hackerone.com/{{ site.hackerone_embed_form }}/embedded_submissions/script" data-url="https://hackerone.com/{{ site.hackerone_embed_form }}/embedded_submissions/new" data-name="h1-embedded-submission"></script>
{% endif %}