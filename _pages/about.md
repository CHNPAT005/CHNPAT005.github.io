---
permalink: /
excerpt: "Home"
author_profile: false
title: ""
redirect_from:
  - /about/
  - /about.html
---

<style>
:root {
  --home-serif: "Charter", "Charter BT", "Source Serif 4", "Source Serif Pro", "Sitka Text", "Iowan Old Style", Georgia, "Times New Roman", Times, serif;
}
.home-page { font-family: var(--home-serif); color: #1a1a1a; line-height: 1.55; }
.home-page p, .home-page li { line-height: 1.55; }
.home-page h2 {
  font-family: var(--home-serif);
  font-size: 1.05em; font-variant: small-caps; letter-spacing: 0.08em;
  font-weight: 600; color: #1a1a1a; border-bottom: solid 1px #d8d8d8;
  padding-bottom: 4px; margin-top: 2em; margin-bottom: 0.9em;
}
.home-lead { font-size: 1.02em; }
.home-page a { text-decoration: underline; }

.home-header {
  display: flex; align-items: flex-start; gap: 1.8em;
  margin-top: 0.4em; margin-bottom: 1.8em; padding-bottom: 1.4em;
  border-bottom: solid 1px #e1e1e1;
}
.home-photo {
  width: 150px; height: 150px; object-fit: cover; object-position: center 12%;
  border-radius: 2px; flex-shrink: 0; box-shadow: 0 1px 2px rgba(0,0,0,0.08);
}
.home-meta { flex: 1; min-width: 0; }
.home-name {
  font-family: var(--home-serif); font-size: 1.7em; font-weight: 600;
  letter-spacing: 0.01em; color: #1a1a1a; margin: 0 0 0.4em 0; line-height: 1.15;
  border: none; padding: 0; text-transform: none; font-variant: normal;
}
.home-affiliation { font-family: var(--home-serif); font-size: 0.98em; color: #333; line-height: 1.5; margin-bottom: 0.9em; }
.home-affiliation .home-role { font-style: italic; }
.home-icons { font-size: 0.9em; display: flex; flex-wrap: wrap; gap: 0.2em 1.2em; }
.home-icons a { color: #444; text-decoration: none; white-space: nowrap; }
.home-icons a:hover { text-decoration: underline; }
.home-icons a i { margin-right: 0.35em; color: #666; font-size: 0.95em; }

.home-selected { list-style: none; padding-left: 0; margin-top: 0.3em; counter-reset: hp-counter; }
.home-selected > li {
  counter-increment: hp-counter; position: relative;
  padding-left: 2.4em; margin-bottom: 0.7em; font-size: 0.97em; text-align: justify;
}
.home-selected > li::before { content: counter(hp-counter) "."; position: absolute; left: 0; top: 0; font-weight: 600; color: #888; }
.home-selected .home-paper-venue { font-weight: 600; }
.home-selected a { font-size: 0.9em; color: #444; text-decoration: none; white-space: nowrap; }
.home-selected a::before { content: "["; color: #888; }
.home-selected a::after { content: "]"; color: #888; }

.home-list { padding-left: 1.2em; }
.home-list > li { margin-bottom: 0.45em; }
.home-list .home-year { font-weight: 600; font-variant: tabular-nums; }
.home-contact { font-size: 0.98em; }

@media (max-width: 600px) {
  .home-header { flex-direction: column; align-items: center; text-align: center; }
  .home-icons { justify-content: center; }
}
</style>

<div class="home-page" markdown="1">

<div class="home-header">
  <img src="{{ '/images/profile.jpg' | relative_url }}" alt="Patrick Chang" class="home-photo">
  <div class="home-meta">
    <h1 class="home-name">Patrick Chang</h1>
    <div class="home-affiliation">
      <span class="home-role">Postdoctoral Researcher</span><br>
      Oxford-Man Institute<br>
      University of Oxford
    </div>
    <div class="home-icons">
      <a href="mailto:patrick.chang@omi.ox.ac.uk"><i class="fas fa-envelope"></i>Email</a>
      <a href="https://github.com/CHNPAT005"><i class="fab fa-github"></i>GitHub</a>
      <a href="https://www.linkedin.com/in/patrick-chang-976120170"><i class="fab fa-linkedin"></i>LinkedIn</a>
      <a href="https://papers.ssrn.com/sol3/cf_dev/AbsByAuth.cfm?per_id=5235387"><i class="ai ai-ssrn"></i>SSRN</a>
      <a href="{{ '/files/cv.pdf' | relative_url }}"><i class="fas fa-file-alt"></i>CV</a>
    </div>
  </div>
</div>

## Research interests

My research studies how algorithms and artificial intelligence shape financial markets. I use theoretical, empirical, and experimental methods to examine:

- **unintended consequences of AI in finance**
- **financial economics of AI**
- **market microstructure of algorithmic trading**

## More about me

<p class="home-lead">
I am a postdoctoral researcher at the <a href="https://oxford-man.ox.ac.uk/">Oxford-Man Institute</a>, University of Oxford. I completed my DPhil in Mathematics at Oxford in 2025, with a <a href="https://ora.ox.ac.uk/objects/uuid:c8a7e461-02ac-41f0-940e-c6830632c58f">thesis</a> proving that algorithms can learn to collude by bridging the Folk theorem with learning in games. Before Oxford, I studied at the University of Cape Town, where I completed a master's in Statistics and an undergraduate degree in Actuarial Science.
</p>

{% comment %} ---- Selected papers: temporarily hidden, re-enable later ----
## Selected papers

A complete list is on the <a href="{{ '/research/' | relative_url }}">research</a> page.

<ol class="home-selected">
  <li>Álvaro Cartea, Patrick Chang, José Penalva, Harrison Waldon (2026). Algorithmic Collusion and a Folk Theorem from Learning with Bounded Rationality. <span class="home-paper-venue">Games and Economic Behavior.</span> <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4293831">link</a></li>
  <li>Jonathan Brogaard, Álvaro Cartea, Patrick Chang, Rob Graumans (2025). The Lasting Impact of Flickering Quotes. <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5963035">link</a></li>
  <li>Álvaro Cartea, Patrick Chang, Nan Chen, Mingyue Zhong (2026). AI Bubbles with Large Language Models. <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6426761">link</a></li>
</ol>
{% endcomment %}

## Events

<ul class="home-list">
  <li><span class="home-year">2024 – present</span> &mdash; <a href="https://oxford-man.ox.ac.uk/omifinanceseminar/">OMI Finance Seminar</a>.</li>
  <li><span class="home-year">2021 – present</span> &mdash; OMI Student Seminar.</li>
  <li><span class="home-year">2021 – present</span> &mdash; OMI Crossroads Seminar.</li>
  <li><span class="home-year">2026</span> &mdash; Oxford-Man Institute Microstructure and Financial Economics Workshop.</li>
  <li><span class="home-year">2024</span> &mdash; Oxford-Man Institute Financial Economics and Microstructure Workshop.</li>
  <li><span class="home-year">2023</span> &mdash; Oxford-Man Institute Algorithmic Collusion and Learning in Games Workshop.</li>
</ul>

## Media

<ul class="home-list">
  <li><a href="https://www.risk.net/markets/7961037/crossed-signals-row-over-collusion-pits-scholars-against-traders">Crossed signals: row over collusion pits scholars against traders</a>, by Luke Clancy and Mauro Cesa (Risk.net)</li>
  <li><a href="https://www.etfstream.com/articles/collusion-claims-cast-a-cloud-over-vital-role-of-etf-market-makers">Collusion claims cast a cloud over vital role of ETF market makers</a>, by Chris Flood (ETF Stream)</li>
  <li><a href="https://www.etfcentral.com/news/debunking-collusion-claims-etf-market-making-insiders-perspective">Debunking Collusion Claims in ETF Market Making: An Insider's Perspective</a>, by Nicholas Phillips</li>
  <li><a href="https://www.etfstream.com/articles/market-maker-collusion-in-etf-trades-on-euronext-amsterdam-exchange">Market maker 'collusion' in ETF trades on Euronext Amsterdam exchange</a>, by Chris Flood (ETF Stream)</li>
  <li><a href="https://www.risk.net/markets/7960070/the-curious-case-of-the-revealing-orders">The curious case of the revealing orders</a>, by Mauro Cesa and Luke Clancy (Risk.net)</li>
  <li><a href="https://www.risk.net/investing/7955568/can-algos-collude-quants-are-finding-out">Can algos collude? Quants are finding out</a>, by Faye Kilburn (Risk.net)</li>
</ul>

## Contact

<p class="home-contact">
patrick (dot) chang (at) omi (dot) ox (dot) ac (dot) uk<br>
Oxford-Man Institute, Eagle House, OX2 6ED, Oxford.
</p>

</div>
