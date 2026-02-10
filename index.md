---
layout: default
title: Home
---

<section class="hero">
  <div class="hero-inner">
    <h1>Reliability &amp; Asset Performance Insights</h1>
    <p>Practical guidance for IBM Maximo &amp; EAM leaders — focused on reliability strategies, operational maturity, and measurable asset performance outcomes.</p>
  </div>
</section>

<div class="grid">
  <section class="card">
    <h2>Latest Insights</h2>
    <p>Monthly perspectives and practical guidance.</p>
    <ul>
      {% for post in site.posts limit:3 %}
        <li>
          <strong>{{ post.date | date: "%B %Y" }}:</strong>
          <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        </li>
      {% endfor %}
    </ul>
    <div style="margin-top:14px;">
      <a class="button" href="{{ "/monthly-insights" | relative_url }}">View all insights</a>
    </div>
  </section>

  <section class="card">
    <h2>Executive Glossary</h2>
    <p>Key terms and definitions for reliability, asset management, and Maximo programs.</p>
    <a class="button" href="{{ "/glossary" | relative_url }}">View glossary</a>
  </section>

  <section class="card">
    <h2>Field Kits &amp; Tools</h2>
    <p>Practical checklists and templates for EAM and reliability initiatives.</p>
    <ul>
      <li>Upgrade readiness checklist</li>
      <li>Reliability strategy framework</li>
      <li>Work management scorecards</li>
    </ul>
    <div style="margin-top:14px;">
      <a class="button" href="{{ "/field-kits" | relative_url }}">Explore kits</a>
    </div>
  </section>
</div>

<p class="section-title">Positioning</p>
<div class="card">
  <strong>Expertise in IBM Maximo, Reliability Strategies, and Asset Performance</strong>
  <p style="margin-top:8px;">Driving operational excellence through proven practices, implementation experience, and clear guidance for asset-intensive organizations.</p>
</div>
