---
layout: default
title: "AI Life Cycle Phases: From Plan & Design to Decommission | ISACA AAISM Ep. 38"
description: "Walk through the seven AI life cycle phases for the ISACA AAISM exam: plan, data, build, test, deploy, operate, retire, with red teaming, explainability and risk."
keywords: "AI life cycle, AI life cycle phases, plan and design AI, AI data collection, AI model build, AI red teaming, AI deployment, AI operate and monitor, AI decommissioning, AI risk management, ISACA AAISM, AAISM exam prep"
author: "RooCloud"
image: "https://img.youtube.com/vi/L5LWrbFarSI/maxresdefault.jpg"
permalink: /domain-3-ai-technologies-and-controls/ep38-ai-life-cycle-phases.html
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "AI Life Cycle Phases: From Plan & Design to Decommission",
  "description": "Walk through the seven AI life cycle phases for the ISACA AAISM exam: plan, data, build, test, deploy, operate, retire, with red teaming, explainability and risk.",
  "thumbnailUrl": "https://img.youtube.com/vi/L5LWrbFarSI/maxresdefault.jpg",
  "uploadDate": "2026-05-01",
  "contentUrl": "https://www.youtube.com/watch?v=L5LWrbFarSI",
  "embedUrl": "https://www.youtube.com/embed/L5LWrbFarSI",
  "publisher": {
    "@type": "Organization",
    "name": "RooCloud",
    "logo": {
      "@type": "ImageObject",
      "url": "https://roocloud.com/assets/logo.png"
    }
  }
}
</script>
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What are the seven phases of the AI life cycle?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The AI life cycle moves through seven phases: plan and design, collect and process data, build or adapt models, test and validate, make available for use or deploy, operate and monitor, and finally retire or decommission. Each carries its own risk, from bias in design and data, through explainability and red teaming in build and test, to compatibility in deployment and obsolescence at retirement."
      }
    },
    {
      "@type": "Question",
      "name": "Why is the plan and design phase so important?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Plan and design is where you articulate the system's concept, objectives, assumptions, and requirements, define clear goals and success metrics, document the business use case, and engage stakeholders early. It is also where you run an initial risk assessment, hunt for bias in data or algorithms, plan mitigations, and lay a foundation for data governance. Done well, this phase becomes the blueprint for the entire life cycle."
      }
    },
    {
      "@type": "Question",
      "name": "What is the difference between verification and validation in AI?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Verification checks the model was built correctly to specification, while validation checks it actually serves its intended purpose with accurate, reliable output. The phase uses several techniques including model testing against benchmarks like accuracy and recall, stress testing with extreme cases, comparative analysis against baselines, bias and fairness checks, and scenario analysis."
      }
    },
    {
      "@type": "Question",
      "name": "What is AI red teaming?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "AI red teaming is a standout practice in the test and validate phase where you emulate real adversaries to find blind spots and weaknesses, both in the base model and at the application level. Whatever the testing reveals should drive fixes before production, with any remaining risk documented in the risk register and the solution authorized for release through change management."
      }
    },
    {
      "@type": "Question",
      "name": "When should an AI system be decommissioned?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Retirement usually happens when a solution becomes obsolete, a better alternative emerges, or ongoing risk assessment finds the risk now exceeds appetite. Once the decision is made, create a detailed decommissioning plan through change management covering data migration or deletion, system disentanglement, and continuity of operations, with clear communication to stakeholders to minimize disruption."
      }
    }
  ]
}
</script>

**[🏠 Back to Exam Syllabus](../README.md)** | **[📺 RooCloud on YouTube](https://youtube.com/@roocloud)** | **[🌐 RooCloud Practice Exams](https://roocloud.com)**

---

# AI Life Cycle Phases: From Plan and Design to Decommission

Risk shows up differently at every phase of an AI system's life, and catching it early is far cheaper than fixing it late. This episode of the **ISACA Advanced in AI Security Management (AAISM)** exam prep series walks through the full life of an AI solution — from planning and data, through building, testing, and deployment, to operation and finally retirement — and the risks to manage at each stage. Understanding the life cycle lets you ask the right questions at the right moment, and recognize that everyone involved shares responsibility for a trustworthy result.

<div class="video-embed">
  <iframe src="https://www.youtube.com/embed/L5LWrbFarSI" title="AI Life Cycle Phases: From Plan & Design to Decommission" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## The AI Life Cycle: Setting the Frame

The AI life cycle runs from the moment an organization adopts a solution for a business problem all the way to decommissioning it, and it closely resembles the familiar **system development life cycle**. A key insight is that risk looks different depending on where you stand and when you look. Some risk is latent early on and grows as the system adapts, and a developer who releases a model sees different risk than the deployer who applies it to a specific use. Everyone involved shares responsibility for a system that is **trustworthy and fit for purpose** — a useful lens to carry through every phase that follows.

## Phase 1: Plan and Design

The first phase is **plan and design**, where you articulate the system's concept, objectives, assumptions, and requirements, and perhaps build a prototype. This is where you define clear goals and success metrics, document the business use case, and engage stakeholders early to surface needs and constraints. This phase is also where you run an initial risk assessment, hunting for **bias in data or algorithms**, planning mitigations, and laying a foundation for **data governance**. Prototyping lets teams validate ideas through quick iteration, catching problems before full-scale build. Done well, this phase becomes the blueprint for the entire life cycle, and shortcuts taken here echo through every subsequent stage as rework, technical debt, and surprise risk.

## Phase 2: Collect and Process Data

The second phase is **collect and process data**, and since data quality directly drives a model's reliability, this is critical. It begins with gathering data from many sources, obtaining proper **consent** to avoid breaking privacy law, and then cleaning it by removing duplicates, errors, and inconsistencies. A vital part is checking **completeness, quality, relevance, and timeliness**, and documenting the dataset's **provenance**: how it was created, where it came from, what it contains, what it is meant for, and how it has been maintained over time. Good documentation here is what gives the whole system **transparency and accountability** later on, because no one can audit decisions made by a model trained on data with no clear history.

## Phase 3: Build or Adapt the Models

The third phase is **build or adapt the models**, transforming data into actionable insight. You select an appropriate model or algorithm, then calibrate and train it — an iterative cycle of testing and tuning to sharpen accuracy. Two things matter especially here:

* **Explainability**, so you can understand how the model reaches its decisions and build trust with stakeholders.
* **Automated event recording plus human-in-the-loop oversight**, so a person validates the model's decisions at critical points, blending human judgment with machine efficiency.

These two design choices are also how you keep options open in later phases. A model whose decisions cannot be explained is impossible to defend in an audit or fix when it starts misbehaving, and a system without human-in-the-loop checkpoints offers no graceful place to intervene when something goes wrong.

## Phase 4: Test, Evaluate, Verify, and Validate

The fourth phase is **test, evaluate, verify, and validate**. **Verification** checks the model was built correctly to specification, while **validation** checks it actually serves its intended purpose with accurate, reliable output. This involves several techniques: model testing against benchmarks like **accuracy and recall**, **stress testing** with extreme cases, **comparative analysis** against baselines, **bias and fairness checks**, and **scenario analysis**.

A standout practice here is **AI red teaming**, where you emulate real adversaries to find blind spots and weaknesses, both in the base model and at the application level. Whatever the testing reveals should drive fixes before production, with any remaining risk documented in the **risk register** and the solution authorized for release through **change management**. The discipline is to treat the risk register as a living artifact rather than a checkbox: anything you accept here is something the operate-and-monitor phase will be quietly watching for the rest of the system's life.

## Phase 5: Make Available for Use (Deploy)

The fifth phase is **make available for use**, or deploy, which means moving into live production. This starts with **piloting in a controlled environment** as a proof of concept, then ensuring **compatibility with existing and legacy systems** to avoid disruption. It also means giving clear deployment instructions to any third parties or downstream deployers, maintaining detailed technical documentation that doubles as **evidence of compliance**, and managing the human side through training, communication, and monitoring of user experience. Deployment is rarely a single moment; it is a graduated handover from build teams to operating teams, and the documentation produced here becomes the operational rulebook for everyone who comes after.

## Phase 6: Operate and Monitor

The sixth phase is **operate and monitor**, a continuous process of keeping the solution running while systematically evaluating its performance and quality. You need mechanisms to assess both the **intended and unintended consequences** of the system's actions, confirming it stays aligned with business objectives and ethical standards. Establishing a **quality management system**, with ongoing documentation, audits, and updates, helps maintain compliance and build trust. This is also where drift, degradation, and emergent behavior actually surface — the operational monitoring loop is what closes the gap between the risks accepted at release and the reality the model encounters every day.

## Phase 7: Retire or Decommission

The seventh and final phase is **retire or decommission**, which concludes the life cycle. Retirement usually happens when a solution becomes **obsolete**, a better **alternative emerges**, or ongoing risk assessment finds the **risk now exceeds appetite**. Once the decision is made, create a detailed decommissioning plan through change management, covering **data migration or deletion, system disentanglement, and continuity of operations**, with clear communication to stakeholders to minimize disruption. A clean retirement is what stops a sunset AI system from quietly continuing to influence decisions, leaking data, or holding integrations open long after the business has moved on.

<div class="takeaways" markdown="1">

## Key Takeaways

* The AI life cycle has seven phases: plan and design, collect and process data, build or adapt models, test and validate, deploy, operate and monitor, and retire.
* Risk appears differently at every phase, and every actor — from developer to deployer — shares responsibility for a trustworthy, fit-for-purpose system.
* Build the foundation early with clear goals, bias checks, prototypes, and rigorous data provenance and consent, since shortcuts here echo through every later phase.
* Explainability, human-in-the-loop oversight, AI red teaming, and a documented risk register turn build and test into a defensible release gate.
* Operate and monitor watches intended and unintended consequences, and a clean decommissioning plan ensures data, systems, and stakeholders are handled responsibly at end of life.

</div>

## Frequently Asked Questions

### What are the seven phases of the AI life cycle?
The AI life cycle moves through seven phases: **plan and design, collect and process data, build or adapt models, test and validate, make available for use or deploy, operate and monitor, and retire or decommission**. Each carries its own risk, from bias in design and data, through explainability and red teaming in build and test, to compatibility in deployment and obsolescence at retirement.

### Why is the plan and design phase so important?
Plan and design is where you articulate the system's concept, objectives, assumptions, and requirements, define clear goals and success metrics, document the business use case, and engage stakeholders early. It is also where you run an initial risk assessment, hunt for bias in data or algorithms, plan mitigations, and lay a foundation for data governance. Done well, this phase becomes the blueprint for the entire life cycle.

### What is the difference between verification and validation in AI?
**Verification** checks the model was built correctly to specification, while **validation** checks it actually serves its intended purpose with accurate, reliable output. The phase uses several techniques including model testing against benchmarks like accuracy and recall, stress testing with extreme cases, comparative analysis against baselines, bias and fairness checks, and scenario analysis.

### What is AI red teaming?
AI red teaming is a standout practice in the test and validate phase where you emulate real adversaries to find blind spots and weaknesses, both in the base model and at the application level. Whatever the testing reveals should drive fixes before production, with any remaining risk documented in the risk register and the solution authorized for release through change management.

### When should an AI system be decommissioned?
Retirement usually happens when a solution becomes obsolete, a better alternative emerges, or ongoing risk assessment finds the risk now exceeds appetite. Once the decision is made, create a detailed decommissioning plan through change management covering data migration or deletion, system disentanglement, and continuity of operations, with clear communication to stakeholders to minimize disruption.

<div class="cta" markdown="1">

### 📚 Master the ISACA AAISM Exam!

Ready to test your knowledge? Access chapter-specific **Multiple Choice Questions (MCQs)** and full-length practice exams for the ISACA AAISM certification at **[RooCloud.com](https://roocloud.com)**. Solve the chapter-wise questions to reinforce this lesson before moving to the next episode.

</div>

---

*Reference: This article is based on concepts discussed in [AI Life Cycle Phases: From Plan & Design to Decommission](https://www.youtube.com/watch?v=L5LWrbFarSI).*
