---
layout: default
---

{% capture about_me %}{% include sections/about_me.md %}{% endcapture %}
{{ about_me | markdownify }}

{% capture honors %}{% include sections/honors.md %}{% endcapture %}
{{ honors | markdownify }}

{% capture career_timeline %}{% include sections/career_timeline.md %}{% endcapture %}
{{ career_timeline | markdownify }}

{% capture publications %}{% include sections/publications.md %}{% endcapture %}
{{ publications | markdownify }}

{% capture articles %}{% include sections/articles.md %}{% endcapture %}
{{ articles | markdownify }}
