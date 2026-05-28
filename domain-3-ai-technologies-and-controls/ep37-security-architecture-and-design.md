---
layout: default
title: "AI Security Architecture & Design: Secure by Design & Model Selection | ISACA AAISM Ep. 37"
description: "Build AI security architecture for the ISACA AAISM exam: provider/producer/customer roles, secure by design, data dependency, model selection, change management and rollbacks."
keywords: "AI security architecture, secure by design, AI model selection, AI change management, data dependency, AI provider producer customer, AI configuration management, AI emergency change, AI rollback, ISACA AAISM, AAISM exam prep, AI architecture design"
author: "RooCloud"
image: "https://img.youtube.com/vi/sm2oQ0SHZfs/maxresdefault.jpg"
permalink: /domain-3-ai-technologies-and-controls/ep37-security-architecture-and-design.html
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "AI Security Architecture & Design: Secure by Design & Model Selection",
  "description": "Build AI security architecture for the ISACA AAISM exam: provider/producer/customer roles, secure by design, data dependency, model selection, change management and rollbacks.",
  "thumbnailUrl": "https://img.youtube.com/vi/sm2oQ0SHZfs/maxresdefault.jpg",
  "uploadDate": "2026-05-01",
  "contentUrl": "https://www.youtube.com/watch?v=sm2oQ0SHZfs",
  "embedUrl": "https://www.youtube.com/embed/sm2oQ0SHZfs",
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
      "name": "What are the AI provider, producer, and customer roles?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A provider offers products or services that use AI. A producer designs, develops, tests, and deploys those AI products, including the model designers and developers who build them. A customer uses an AI product or service, either directly or by passing it to its own users. Knowing which hat you wear shapes every security decision that follows."
      }
    },
    {
      "@type": "Question",
      "name": "What does secure by design mean for AI?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Secure by design means building technology so it reasonably protects against attackers from the very start, with security woven in from inception through end of life. It rests on three principles: taking ownership of customer security outcomes, embracing radical transparency and accountability including explainability, and building the organizational structures and leadership to actually achieve security goals."
      }
    },
    {
      "@type": "Question",
      "name": "Why is data dependency a special concern for AI architecture?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "AI depends fundamentally on data, which makes it acutely sensitive to changes in that data. A model is trained to expect very specific data attributes, so an unexpected change in the input, source, or preprocessing can quietly break it. The fix is to document the exact data the model requires, confirm production inputs match, and add preprocessing to bring data back within expected tolerances when needed."
      }
    },
    {
      "@type": "Question",
      "name": "Why is model selection an architectural decision?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A model's behavior can be tuned after training through parameters, and one setting controls how varied or creative its outputs are, dramatically changing results from the same model. Swapping the underlying model itself for a new version can alter outputs significantly. Because models are often opaque and vary with data sources, training methods, and even the ethics of their developers, model choice is a serious architectural decision."
      }
    },
    {
      "@type": "Question",
      "name": "How do you handle emergency changes for AI systems?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "With ordinary software, a developer can patch a flaw in hours, but retraining an AI model can take weeks. For urgent issues, organizations rely on alternatives like rolling back to an earlier model version or adding input and output validation around the model to shield it, with all emergency changes still reviewed and approved by key stakeholders."
      }
    }
  ]
}
</script>

**[🏠 Back to Exam Syllabus](../README.md)** | **[📺 RooCloud on YouTube](https://youtube.com/@roocloud)** | **[🌐 RooCloud Practice Exams](https://roocloud.com)**

---

# AI Security Architecture and Design: Secure by Design and Model Selection

AI cannot just be bolted onto your existing systems and hoped to be safe. This episode of the **ISACA Advanced in AI Security Management (AAISM)** exam prep series unpacks the roles an organization plays with AI, the idea of **secure by design**, and the architecture considerations that make AI genuinely different from ordinary software — including data dependency, storage, configuration, model selection, regulatory impact, and change management. Understanding AI security architecture lets you build protection in from the start, anticipate the ways AI breaks the usual rules, and avoid expensive surprises once a model is live.

<div class="video-embed">
  <iframe src="https://www.youtube.com/embed/sm2oQ0SHZfs" title="AI Security Architecture & Design: Secure by Design & Model Selection" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## AI Roles: Provider, Producer, and Customer

The right architecture depends on how you engage with AI, so start with roles. A **provider** offers products or services that use AI. A **producer** designs, develops, tests, and deploys those AI products, including the model designers and developers who build them. And a **customer** uses an AI product or service, either directly or by passing it to its own users. Knowing which hat you wear shapes every security decision that follows. A producer's responsibilities for model training, evaluation, and deployment documentation look very different from a customer's responsibility to validate that an outside model fits their intended use, and a provider sits between the two, owning the productized experience and the contractual security guarantees that come with it.

## Fix What Is Broken Before You Add AI

Before expanding your architecture for AI, you must fix what is already broken. Existing problems, like poor data management or a missing security control framework, will only be magnified once AI is added, potentially deepening current vulnerabilities and creating new ones. The security professional is central here, because understanding the types of models, their components, and their intended uses is what makes a sound architecture and a credible business case possible. Treat AI adoption as a forcing function: it will surface every weak spot in your existing controls, and it is far cheaper to remediate them on your own schedule than under the pressure of a live AI incident.

## Secure by Design: Three Foundational Principles

A foundational principle is **secure by design**, which means building technology so it reasonably protects against attackers from the very start, with security woven in from inception through end of life. It rests on three principles:

1. **Take ownership of customer security outcomes**, such as proper consent management for datasets and securing data pipelines.
2. **Embrace radical transparency and accountability**, including explainability for your systems.
3. **Build the organizational structures and leadership** to actually achieve security goals.

Importantly, your secure development practices do not fundamentally change for AI, but they must be deliberately extended so that AI security is considered at every stage, whether you are using AI to assist development or building a new model yourself. Secure by design becomes the cultural backbone that makes the architectural considerations below possible — without it, each individual control becomes brittle.

## Data Dependency: The Hidden Fragility of AI Models

AI depends fundamentally on data, which makes it acutely sensitive to changes in that data. A model is trained to expect very specific data attributes, so an unexpected change in the input, or in the source or preprocessing, can quietly break it. The fix is to **document the exact data the model requires** and confirm production inputs match, adding preprocessing to bring data back within expected tolerances when needed. This data-contract approach is the architectural equivalent of input validation: you specify what the model expects, you verify what you actually receive, and you reconcile the two before anything reaches inference. Skipping that step is one of the most common ways AI systems silently degrade in production.

## Data Storage and Configuration Management

The next consideration is **data storage**. AI can generate an enormous volume of data, and both that output and the data feeding the model need somewhere to live. Even when storage is cheap, those large volumes create real exposure to **data leakage and misuse**, so the architecture must define clearly how and where AI's inputs and outputs are stored, with attention to shadow activity, drift, and access control.

**Configuration management** is another area that looks different for AI. Beyond tracking standard configuration items, AI systems have adjustable post-production parameters that must be monitored for drift from the standard. Crucially, the data preprocessing used in training must stay consistent with the preprocessing used in production, right down to using the same **tokenization**, or the model's performance becomes unreliable. Think of this as configuration drift with sharper teeth: a small preprocessing mismatch between training and production can change predictions in ways that traditional configuration controls were never designed to catch.

## Model Selection as an Architectural Decision

**Model selection** sits at the core of the system. A model's behavior can be tuned after training through parameters; one such setting controls how varied or creative its outputs are, dramatically changing the results from the very same model. Behavior can also shift when the underlying model itself is swapped for a new version, which can alter outputs significantly. Because models are often opaque, their behavior varies with data sources, training methods, and even the **ethics of their developers**, so model choice is a serious architectural decision rather than a procurement detail. The architect must weigh not just accuracy benchmarks but provenance, training data lineage, vendor stability, version control, and how the model's behavior will be re-validated whenever it changes underneath the application.

## Regulatory Impact and AI Change Management

Two broader considerations complete the picture. **Regulatory and societal impact** means recognizing that rules are still catching up to AI and that public sentiment keeps shifting; history shows technology can both eliminate and create jobs, so organizations must watch this evolving landscape. The architecture needs hooks for monitoring and adapting as new rules land, rather than assuming today's compliance posture will survive next year.

**AI change management** is essential, because building this architecture takes many groups working together, and the change process must be updated to handle AI-specific elements like **model provenance, data drift, access control, scalability, and workforce reskilling**. One change-management point deserves special attention: **emergency changes**. With ordinary software, a developer can patch a flaw in hours, but retraining an AI model can take weeks. So for urgent issues, organizations rely on alternatives like **rolling back to an earlier model version**, or adding **input and output validation** around the model to shield it, with all emergency changes still reviewed and approved by key stakeholders. Architecting these safety valves up front — known-good baseline versions, wrapper controls, and a documented fast path through change management — is what keeps the response window measured in hours, not weeks.

<div class="takeaways" markdown="1">

## Key Takeaways

* AI security architecture starts with knowing your role as provider, producer, or customer, and fixing existing weaknesses before adding AI.
* Secure by design builds protection in from inception through end of life through ownership of customer security outcomes, radical transparency and accountability, and the right organizational structures.
* Data dependency requires documenting exact input requirements, with preprocessing to keep production data within expected tolerances.
* Configuration management must keep training and production preprocessing identical, including tokenization, while monitoring post-production parameters for drift.
* Model selection is a serious architectural decision because parameters, model swaps, and developer ethics all shift behavior, and AI change management must include rollback and validation wrappers because retraining is slow.

</div>

## Frequently Asked Questions

### What are the AI provider, producer, and customer roles?
A **provider** offers products or services that use AI. A **producer** designs, develops, tests, and deploys those AI products, including the model designers and developers who build them. A **customer** uses an AI product or service, either directly or by passing it to its own users. Knowing which hat you wear shapes every security decision that follows.

### What does secure by design mean for AI?
Secure by design means building technology so it reasonably protects against attackers from the very start, with security woven in from inception through end of life. It rests on three principles: taking ownership of customer security outcomes, embracing radical transparency and accountability including explainability, and building the organizational structures and leadership to actually achieve security goals.

### Why is data dependency a special concern for AI architecture?
AI depends fundamentally on data, which makes it acutely sensitive to changes in that data. A model is trained to expect very specific data attributes, so an unexpected change in the input, source, or preprocessing can quietly break it. The fix is to document the exact data the model requires, confirm production inputs match, and add preprocessing to bring data back within expected tolerances when needed.

### Why is model selection an architectural decision?
A model's behavior can be tuned after training through parameters, and one setting controls how varied or creative its outputs are, dramatically changing results from the same model. Swapping the underlying model itself for a new version can alter outputs significantly. Because models are often opaque and vary with data sources, training methods, and even the ethics of their developers, model choice is a serious architectural decision.

### How do you handle emergency changes for AI systems?
With ordinary software, a developer can patch a flaw in hours, but retraining an AI model can take weeks. For urgent issues, organizations rely on alternatives like **rolling back to an earlier model version** or adding **input and output validation** around the model to shield it, with all emergency changes still reviewed and approved by key stakeholders.

<div class="cta" markdown="1">

### 📚 Master the ISACA AAISM Exam!

Ready to test your knowledge? Access chapter-specific **Multiple Choice Questions (MCQs)** and full-length practice exams for the ISACA AAISM certification at **[RooCloud.com](https://roocloud.com)**. Solve the chapter-wise questions to reinforce this lesson before moving to the next episode.

</div>

---

*Reference: This article is based on concepts discussed in [AI Security Architecture & Design: Secure by Design & Model Selection](https://www.youtube.com/watch?v=sm2oQ0SHZfs).*
