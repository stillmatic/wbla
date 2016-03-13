---
layout: home
permalink: /
image:
  feature: skyline.jpg
page.title: Wharton Business & Law Association
---

<div class="row"><p class="post-excerpt">Wharton Business Law Association seeks to unite all Penn students interested in law and show them how they could integrate a business education with law aspirations.</p></div>  

<div class="tiles">

<div class="tile">
  <h2 class="post-title">Events</h2>
  <p class="post-excerpt">Great events with nationally recognized speakers and content tailored to Penn students.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Networking</h2>
  <p class="post-excerpt">Meet like-minded students and professionals.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Recruiting</h2>
  <p class="post-excerpt">Packed with advice and outreach for top firms.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">LSAT Prep</h2>
  <p class="post-excerpt">Advice and workshops for the LSAT and the rest of the law school admissions process.</p>
</div><!-- /.tile -->
</div><!-- /.tiles -->

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
