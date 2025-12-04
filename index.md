---
layout: default
title: "Home"
---

<style>
  /* Hide the default site chrome so it feels like Andy's page */
  .site-header,
  .site-footer {
    display: none;
  }

  .page-content {
    padding: 48px 16px 80px;
  }

  /* Main centered column */
  .s-shell {
    max-width: 760px;
    margin: 0 auto;
    font-size: 16px;
    line-height: 1.6;
  }

  /* Hero area: image + intro */
  .s-hero {
    display: flex;
    gap: 24px;
    align-items: flex-start;
    flex-wrap: wrap;
    margin-bottom: 32px;
  }

  .s-hero img {
    width: 190px;
    max-width: 100%;
    border-radius: 8px;
    flex-shrink: 0;
  }

  .s-hero-text h1 {
    margin-top: 0;
    margin-bottom: 8px;
    font-size: 28px;
  }

  .s-hero-text p {
    margin: 0 0 10px 0;
  }

  .s-hero-text a {
    text-decoration: underline;
  }

  hr {
    margin: 32px 0;
    border: none;
    border-top: 1px solid #e5e5e5;
  }

  .s-section-title {
    font-weight: 600;
    margin-bottom: 12px;
  }

  .s-work-list {
    list-style: none;
    padding-left: 0;
    margin: 0;
  }

  .s-work-list li {
    margin-bottom: 8px;
  }

  .s-work-list a {
    text-decoration: underline;
  }
</style>

<div class="s-shell">

  <section class="s-hero">
    <!-- 🔁 CHANGE this src to match your real image path if needed -->
    <img src="/sagun.jpg" alt="Sagun">

    <div class="s-hero-text">
      <h1>Hi, I'm Sagun 👋</h1>

      <p>
        I’m a consumer PM with a TPM backbone, obsessed with building products that combine
        <strong>deep user empathy</strong> with <strong>scalable, data-informed decisions</strong>.
      </p>

      <p>
        It’s all about people for me: empowering teams, amplifying their ideas, and listening closely
        to users and the problems they trust us to solve.
      </p>

      <p>
        These days, I’m a TPM at <strong>Experian</strong>, coordinating 40+ teams across fraud, data,
        and mainframe-to-cloud migrations—keeping timelines on track, fixing handoffs, and making
        progress easy to see.
      </p>

      <p>
        If you’d like to chat, you can find me on
        <a href="https://www.linkedin.com/" target="_blank">LinkedIn</a>
        or email me at
        <a href="mailto:you@example.com">you@example.com</a>.
      </p>
    </div>
  </section>

  <hr>

  <section>
    <div class="s-section-title">Cool past work</div>

    <ul class="s-work-list">
      <li>
        <strong><a href="https://example.com" target="_blank">Experian (TPM)</a></strong> – Coordinated 40+ teams across fraud, data, and mainframe-to-cloud migrations.
      </li>
      <li>
        <strong><a href="https://example.com" target="_blank">Venture Docx (Marketing)</a></strong> – Ran day-to-day marketing across LinkedIn, the website, WhatsApp, and events.
      </li>
      <li>
        <strong><a href="https://example.com" target="_blank">Skyhive (Product)</a></strong> – Talked to users, wrote PRDs, and improved onboarding flows for an AI workforce product.
      </li>
      <li>
        <strong><a href="https://example.com" target="_blank">Vimana (APM)</a></strong> – Turned customer feedback and support tickets into a clear feature roadmap and designed predictive maintenance features.
      </li>
      <li>
        <strong><a href="https://example.com" target="_blank">Next Tech (Head)</a></strong> – Led a 250+ student AI lab, set priorities, ran weekly cadences, and secured funding.
      </li>
      <li>
        <strong><a href="https://example.com" target="_blank">Guvi (SWE Intern)</a></strong> – Helped build an adaptive testing platform that adjusts questions to each learner.
      </li>
    </ul>
  </section>

</div>
