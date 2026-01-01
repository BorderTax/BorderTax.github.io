---
layout: default
title: BorderTax — Free US→Portugal Tax Expert Matching
---

<style>
/* Page container (keeps content readable on large screens) */
.bt-container {
  max-width: 900px;
  margin: 2.5rem auto;
  padding: 1rem;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  color: #222;
  line-height: 1.6;
}

/* Hero */
.bt-hero h1 {
  margin: 0 0 0.25rem 0;
  font-size: 1.9rem;
}
.bt-hero h2 {
  margin: 0 0 0.75rem 0;
  font-size: 1.05rem;
  font-weight: 500;
  color: #444;
}
.bt-lead {
  margin: 0.5rem 0 1.25rem 0;
  color: #333;
}

/* Form card */
.form-container {
  background: #f8f9fa;
  padding: 1.25rem;
  border-radius: 10px;
  box-shadow: 0 1px 4px rgba(20,20,20,0.04);
  margin: 1.5rem 0;
}

/* Responsive iframe */
.form-container iframe {
  width: 100%;
  min-height: 560px;
  border: 0;
  border-radius: 6px;
}

/* Secondary text / footer */
.bt-foot {
  margin-top: 1.25rem;
  font-size: 0.95rem;
  color: #666;
}

/* Lightweight button style (progressive enhancement) */
.bt-btn {
  display: inline-block;
  background: #0366d6;
  color: #fff !important;
  padding: 0.45rem 0.8rem;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 600;
  margin-top: 0.5rem;
}
@media (max-width: 520px) {
  .bt-hero h1 { font-size: 1.5rem; }
  .bt-hero h2 { font-size: 1rem; }
}
</style>

<div class="bt-container">
  <header class="bt-hero">
    <h1>BorderTax</h1>
    <h2>Free US → Portugal tax expert matching</h2>
    <p class="bt-lead">Answer 5 quick questions, get matched with vetted specialists, and resolve your cross‑border tax questions fast.</p>
  </header>

  <section class="form-container" aria-labelledby="get-match">
    <h3 id="get-match">Get your free match</h3>

    <!-- Replace the `src` value below with your Google Form / embed URL -->
    <iframe
      src="YOUR_GOOGLE_FORM_URL_HERE"
      title="BorderTax matching form"
      loading="lazy"
      allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
    ></iframe>

    <p style="margin-top:0.6rem;">
      If the form doesn't load, <a href="YOUR_GOOGLE_FORM_URL_HERE" class="bt-btn" target="_blank" rel="noopener">open the form in a new tab</a>.
    </p>
  </section>

  <section>
    <h4>How it works</h4>
    <ul>
      <li>We match you with vetted tax experts who know both US and Portugal rules.</li>
      <li>Matches are free — experts only pay a referral fee if you hire them.</li>
      <li>We focus on clarity and fast responses for small businesses and freelancers.</li>
    </ul>
  </section>

  <section class="bt-foot">
    <p><strong>Free MVP by BorderTax</strong> — AI-assisted matching and hand-reviewed matches.</p>
    <p style="margin-top:0.5rem;">If you'd like a different layout, or prefer this as a standalone HTML page (not using the site theme), tell me and I will produce that file.</p>
  </section>
</div>
