---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an M.S. student in Computer Science at **The George Washington University**. My research focuses on **trustworthy artificial intelligence**, with particular interests in **large language model alignment, model behavior and evaluation, and reliable knowledge elicitation**.

I am broadly interested in understanding how language models adapt their behavior across different users, objectives, and deployment settings, and in developing methods that make these systems more reliable, interpretable, and aligned.

> **I am applying to Ph.D. programs starting in Fall 2027.** I am particularly interested in trustworthy AI, LLM alignment, model behavior and evaluation, and related problems in AI safety.

## Research Interests

- Trustworthy and safe large language models
- LLM alignment, model behavior, and evaluation
- Knowledge elicitation and decentralized model adaptation

## Selected Publications <span class="section-link">[(Full List)](/publications/)</span>

<div class="selected-pub">
<div class="selected-pub-title">
Persona-Induced Information Asymmetry in Large Language Models
</div>
<div class="selected-pub-authors">
<strong>Zhangfei Yang</strong>
</div>
<div class="selected-pub-venue">
Under review at EMNLP 2026
</div>
</div>

<div class="selected-pub">
<div class="selected-pub-title">
Internal Coherence Maximization under Decentralized Data
</div>
<div class="selected-pub-authors">
<strong>Zhangfei Yang</strong>, Aizierjiang Aiersilan
</div>
<div class="selected-pub-venue">
Submitted to the AAAI Fall Symposium Series, 2026
</div>
</div>

<div class="selected-pub">
<div class="selected-pub-title">
Moral Foundations Reward Modeling for Pluriversal LLM Alignment
</div>
<div class="selected-pub-authors">
<strong>Zhangfei Yang</strong>
</div>
<div class="selected-pub-venue">
Submitted to the AAAI Fall Symposium Series, 2026
</div>
</div>

<div class="selected-pub">
<div class="selected-pub-title">
OrbitStream: Training-Free Adaptive 360-degree Video Streaming via Semantic Potential Fields
</div>
<div class="selected-pub-authors">
<strong>Zhangfei Yang</strong>, Aizierjiang Aiersilan
</div>
<div class="selected-pub-venue">
ICCCN 2026
</div>
<div class="selected-pub-links">
<a href="https://arxiv.org/abs/2603.20999" target="_blank" rel="noopener">arXiv</a>
</div>
</div>

## Research Experience

**Research Assistant, The George Washington University**  
*Aug. 2026 – Present*

Research on trustworthy large language models, with a focus on decentralized knowledge elicitation, federated model adaptation, and internal coherence maximization under heterogeneous data settings.

## Professional Service

- Program Committee Member, **AAAI Fall Symposium 2026**, AT-AI4H-NW 2026
- External Reviewer / Subreviewer, **AIES 2026**

## Education

**The George Washington University**  
M.S. in Computer Science, Sep. 2025 – Expected May 2027  
GPA: **4.0 / 4.0** · SEAS Achievement Scholarship

## Contact

Email: [yzf5140@gmail.com](mailto:yzf5140@gmail.com)

<style>
.section-link {
  font-size: 0.72em;
  font-weight: 500;
}

/* =========================
   Selected Publications
   ========================= */

.selected-pub {
  margin: 1.35rem 0 1.6rem 1rem;
}

.selected-pub-title {
  color: var(--global-text-color);
  font-weight: 600;
  line-height: 1.45;
  margin-bottom: 0.22rem;
}

.selected-pub-authors {
  color: var(--global-text-color);
  font-size: 0.94em;
  line-height: 1.5;
  margin-bottom: 0.08rem;
}

.selected-pub-venue {
  color: var(--global-text-color);
  opacity: 0.82;
  font-size: 0.92em;
  font-style: normal;
  line-height: 1.45;
}

.selected-pub-links {
  margin-top: 0.28rem;
  font-size: 0.88em;
}

.selected-pub-links a {
  font-weight: 500;
}


/* =========================
   Research Experience
   Professional Service
   Education
   Contact
   ========================= */

/*
   给首页这些 section 下方的正文统一缩进。
   标题仍保持左对齐。
*/

.page__content h2 + p,
.page__content h2 + ul,
.page__content h2 + dl {
  margin-left: 1rem;
}

/*
   Research Experience:
   标题后通常是：
   <p><strong>Research Assistant...</strong><br>...</p>
   再跟一个描述 paragraph
*/

.page__content h2#research-experience ~ p {
  margin-left: 1rem;
}

/* Professional Service */
.page__content h2#professional-service + ul {
  margin-left: 1rem;
  padding-left: 1.2rem;
}

/* Education */
.page__content h2#education ~ p {
  margin-left: 1rem;
}

/* Contact */
.page__content h2#contact ~ p {
  margin-left: 1rem;
}


/* =========================
   Mobile
   ========================= */

@media screen and (max-width: 768px) {
  .selected-pub {
    margin-left: 0.35rem;
  }

  .page__content h2 + p,
  .page__content h2 + ul,
  .page__content h2 + dl,
  .page__content h2#research-experience ~ p,
  .page__content h2#education ~ p,
  .page__content h2#contact ~ p {
    margin-left: 0.35rem;
  }
}

/* =========================
   Research Experience
   Professional Service
   Education
   ========================= */

#research-experience + p,
#research-experience ~ p {
  margin-left: 1rem;
}

#professional-service + ul {
  margin-left: 1rem;
  padding-left: 1.15rem;
}

#education + p,
#education ~ p {
  margin-left: 1rem;
}

/* Experience / Education 主信息 */
#research-experience + p strong,
#education + p strong {
  color: var(--global-text-color);
  font-weight: 600;
}

/* 日期 */
#research-experience + p em {
  color: var(--global-text-color);
  opacity: 0.82;
}

/* Experience 描述 */
#research-experience ~ p {
  color: var(--global-text-color);
}

/* Professional Service */
#professional-service + ul li {
  margin-bottom: 0.45rem;
  line-height: 1.55;
}

/* Section spacing */
#research-experience,
#professional-service,
#education {
  margin-top: 2.5rem;
}

/* Mobile */
@media screen and (max-width: 768px) {
  #research-experience + p,
  #research-experience ~ p,
  #professional-service + ul,
  #education + p,
  #education ~ p {
    margin-left: 0.35rem;
  }
}
</style>
