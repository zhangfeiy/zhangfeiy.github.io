---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an M.S. student in Computer Science at **The George Washington University**. My research focuses on **large language model alignment, model behavior and evaluation, trustworthy AI, and AI safety**.

My current work examines specification gaming and reward seeking in language models, and how to evaluate evidence grounding in medical question answering.

> **I am applying to Ph.D. programs starting in Fall 2027.**

## Research Interests

- Trustworthy AI
- Large language model alignment
- Model behavior and evaluation
- AI safety

## Selected Publications <span class="section-link">[(Full List)](/publications/)</span>

<div class="selected-pub">
<div class="selected-pub-title">
Persona-Induced Information Asymmetry in Large Language Models
</div>
<div class="selected-pub-authors">
<strong>Zhangfei Yang</strong>
</div>
<div class="selected-pub-venue">
Manuscript preparing for submission to ACL Rolling Review (ARR)
</div>
</div>

<div class="selected-pub">
<div class="selected-pub-title">
<a href="https://doi.org/10.1609/aaaiss.v10i1.43536">Internal Coherence Maximization Under Decentralized Data</a>
</div>
<div class="selected-pub-authors">
<strong>Zhangfei Yang</strong>, Aizierjiang Aiersilan
</div>
<div class="selected-pub-venue">
Proceedings of the AAAI Symposium Series, 10(1), 1132–1139 (2026) · Trustworthy Agentic Systems (TAS 2026) · Oral presentation (presenter)
</div>
</div>

<div class="selected-pub">
<div class="selected-pub-title">
<a href="https://doi.org/10.1609/aaaiss.v10i1.43390">Moral Foundations Reward Modeling for Pluriversal LLM Alignment</a>
</div>
<div class="selected-pub-authors">
<strong>Zhangfei Yang</strong>
</div>
<div class="selected-pub-venue">
Proceedings of the AAAI Symposium Series, 10(1), 48–55 (2026) · Aligning with Whom? Pluriversal and Paraconsistent Frameworks for Value Alignment in AI Systems · Oral presentation (presenter)
</div>
</div>

<div class="selected-pub">
<div class="selected-pub-title">
<a href="https://arxiv.org/abs/2603.20999">Training-Free Adaptive 360° Video Streaming via Semantic Potential Fields</a>
</div>
<div class="selected-pub-authors">
Aizierjiang Aiersilan, <strong>Zhangfei Yang</strong>
</div>
<div class="selected-pub-venue">
Proceedings of the 35th International Conference on Computer Communications and Networks (ICCCN), 2026
</div>
</div>

<div class="selected-pub">
<div class="selected-pub-title">
<a href="https://doi.org/10.1609/aaaiss.v10i1.43557">The Variance Problem in Human Oversight of Clinical AI: Measuring Four Safeguards Across Nine Reviewers on a Nurse-Facing Deterioration Testbed</a>
</div>
<div class="selected-pub-authors">
<strong>Zhangfei Yang</strong>, Yuheng Zhao, Zhentao Fan
</div>
<div class="selected-pub-venue">
Proceedings of the AAAI Symposium Series, 10(1), 1281–1288 (2026) · Agentic and Trustworthy AI for Health and the Global AI-Ready Nursing Workforce (AT-AI4H-NW 2026)
</div>
</div>

<div class="selected-pub">
<div class="selected-pub-title">
<a href="https://doi.org/10.1609/aaaiss.v10i1.43457">Reinforcement Learning from Ecological Feedback (RLEF): A Framework for Aligning Language-Model Planning with Planetary Boundaries</a>
</div>
<div class="selected-pub-authors">
<strong>Zhangfei Yang</strong>, Aizierjiang Aiersilan
</div>
<div class="selected-pub-venue">
Proceedings of the AAAI Symposium Series, 10(1), 566–574 (2026) · Planning for a Better Planet · Oral presentation (presenter)
</div>
</div>

## Research Experience

**Research Assistant, The George Washington University**  
*Aug. 2026 – Present*  
Advisor: Prof. Shi Feng

I review studies on LLM specification gaming and reward seeking, focusing on monitoring cues that can also act as instructions.

**AiChatbox — Evidence Grounding in Medical Question Answering**  
*Oct. 2026 – Present*  
Research collaboration with Yi Zhu. Evaluation questions from Meghna Shukla (Wayne State University College of Nursing).

I developed a retrieval-augmented question-answering system for sickle cell disease education and designed a claim-level evaluation to test whether cited passages support treatment claims and whether the answers preserve qualifications that affect care guidance.

## Professional Service

- Program Committee Member, **AAAI Fall Symposium 2026**
- External Reviewer / Subreviewer, **AIES 2026**

## Education

**The George Washington University**  
M.S. in Computer Science, Sep. 2025 – Expected May 2027  
GPA: **4.0 / 4.0** · SEAS Achievement Scholarship

**Zhongnan University of Economics and Law**  
B.S. in Information Systems, 2019–2023  
GPA: **3.28 / 4.0** · National Scholarship

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
