---
layout: index
permalink: /
---

<h1>{{ site.data.profile.full_name }}</h1>
<img src="{{ site.data.profile_photo_url }}" 
  alt="Profile photo for {{ site.data.profile.full_name }}" />
<dl>
  <dt>Institution</dt>
  <dd>{{ site.data.profile.institution }}</dd>
  <dt>Department</dt>
  <dd>{{ site.data.profile.department }}</dd>
  <dt>Title</dt>
  <dd>{{ site.data.profile.title }}</dd>
  <dt>Twitter name</dt>
  <dd>{{ site.data.profile.twitter_name }}</dd>
  <dt>GitHub name</dt>
  <dd>{{ site.data.profile.github_name }}</dd>
  <dt>Facebook url</dt>
  <dd>
    <a href="{{ site.data.profile.facebook_url }}" target="_blank">
      {{ site.data.profile.facebook_url }}
    </a>
  </dd>
</dl>
