---
layout: default
title: "AI Incident Response — Assess the Incident | ISACA AAISM Ep. 18"
description: "Learn the Assess phase of AI incident response for the ISACA AAISM exam: establishing timeline, scope and impact through a disciplined set of questions."
keywords: "AI incident assessment, AI incident response, AI incident scope, AI incident timeline, AI breach notification, AI evidence integrity, ISACA AAISM, AAISM exam prep, AI security investigation, incident triage"
author: "RooCloud"
image: "https://img.youtube.com/vi/YDSWWDuvnC4/maxresdefault.jpg"
permalink: /domain-1-ai-governance-and-program-management/ep18-incident-response-assess.html
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "AI Incident Response — Assess the Incident",
  "description": "Learn the Assess phase of AI incident response for the ISACA AAISM exam: establishing timeline, scope and impact through a disciplined set of questions.",
  "thumbnailUrl": "https://img.youtube.com/vi/YDSWWDuvnC4/maxresdefault.jpg",
  "uploadDate": "2026-05-01",
  "contentUrl": "https://www.youtube.com/watch?v=YDSWWDuvnC4",
  "embedUrl": "https://www.youtube.com/embed/YDSWWDuvnC4",
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
      "name": "What is the Assess phase of AI incident response?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The Assess phase means collecting facts to establish the timeline, the scope, and the impact of an AI incident once it has been detected. It should be done as quickly as possible, but never in a way that damages the integrity of the investigation, and good model documentation makes this far easier."
      }
    },
    {
      "@type": "Question",
      "name": "What questions should be asked during AI incident assessment?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "First, has the incident actually stopped or is it still unfolding. Then the core facts: who was impacted and what harm occurred, when the incident was discovered which is critical for breach-notification deadlines, what exactly happened, which AI systems and data were affected, and what attack tactics were used. Finally, what is still unknown and what do you need to know to return safely to normal operation."
      }
    },
    {
      "@type": "Question",
      "name": "Why does the discovery date matter so much?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Pinning down when the incident was discovered is critical because many laws and regulations attach mandatory breach-notification deadlines to that moment. Missing those deadlines can convert a contained incident into a legal and reputational crisis, so the discovery date must be established early and documented carefully."
      }
    },
    {
      "@type": "Question",
      "name": "How do you preserve evidence during AI incident assessment?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Move quickly to understand what happened, but take care not to trample the evidence that will explain how it happened. Think of it as being a careful first responder at a scene. Strong model documentation makes the work far easier because it gives investigators a reference point for what was normal before the incident."
      }
    }
  ]
}
</script>

**[🏠 Back to Exam Syllabus](../README.md)** | **[📺 RooCloud on YouTube](https://youtube.com/@roocloud)** | **[🌐 RooCloud Practice Exams](https://roocloud.com)**

---

# AI Incident Response — Assess the Incident

This episode of the **ISACA Advanced in AI Security Management (AAISM)** exam prep series covers the third stage of the AI Incident Response lifecycle: **Assess**. It sits between Identify and Report and the Respond phase, and it is the moment where panic must turn into a plan. A calm, structured assessment is what tells you how bad an incident really is, helps you meet any legal notification deadlines, and prevents you from contaminating the very evidence you need to understand what happened.

<div class="video-embed">
  <iframe src="https://www.youtube.com/embed/YDSWWDuvnC4" title="AI Incident Response — Assess the Incident" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## The Goal of the Assess Phase

Assessment means **collecting facts to establish the timeline, the scope, and the impact** of the incident. Those three properties are the spine of every subsequent decision. The timeline tells you when the trouble began and how it unfolded. The scope tells you what systems, data, and users were drawn in. The impact tells you what was actually harmed, in operational, legal, ethical, or human terms.

The work should be done **as quickly as possible**, but **never in a way that damages the integrity of the investigation**. Good **model documentation** makes this far easier, because investigators can compare current behaviour against a known baseline of architecture, data, and intended behaviour. Think of an assessor like a careful first responder at a scene: you move fast to understand what happened, but you take care not to trample the evidence that will explain how it happened. That balance — pace plus discipline — is what separates a competent assessment from a chaotic scramble.

## The Right Questions, in the Right Sequence

The heart of this phase is asking the right questions, and they fall into a clear sequence. The order matters, because each answer shapes what to ask next.

### 1. Has the Incident Actually Stopped?
Before anything else, determine whether the incident is over or still unfolding right now. An active incident demands a different posture from a contained one, and any assessment built on the wrong assumption will be off from the start.

### 2. The Core Facts: Who, What, When, How
Next come the core facts that define the event:

* **Who was impacted and what harm occurred** — the human and operational consequences.
* **When the incident was discovered** — critical for any breach-notification deadlines that may be triggered.
* **What exactly happened** — the chain of events as best as it can be reconstructed.
* **Which AI systems and data were affected** — the precise blast radius.
* **What attack tactics were used** — the techniques and entry points the attacker (or the failure mode) employed.

Each fact serves a purpose. *Who was impacted* shapes communications. *When it was discovered* drives regulatory timing. *Which systems and data* informs containment. *Which tactics* informs eradication. None of these can be guessed at; each must be evidenced.

### 3. The Forward-Looking Question
Finally, one forward-looking question matters most: **what is still unknown, and what do you need to know to return safely to normal operation?** Naming the gaps is what guides the response that follows. An honest list of unknowns turns the assessment into an actionable plan, rather than a snapshot that leaves the team flying blind.

## Why Discovery Date Drives Everything Legal

The episode singles out **when the incident was discovered** for special emphasis because that date often anchors mandatory **breach-notification deadlines** under laws and regulations. A regulator does not care that the investigation is still ongoing; they care that you told them within the legal window after discovery. Establishing the discovery date precisely, and documenting how you established it, protects the organization from missing a deadline that would convert a contained technical issue into a public legal one.

## Bringing It All Together

The **Assess phase** gathers the facts about an AI incident to pin down its **timeline, scope, and impact**, working quickly without harming the investigation. A structured set of questions — whether the incident is ongoing, who and what was affected, when it was found, how it happened, and what remains unknown — gives the response team the clear picture it needs to act in the next stage of the lifecycle. Pair that question-led discipline with good model documentation and careful evidence handling, and the organization can move into Respond with confidence rather than guesswork.

<div class="takeaways" markdown="1">

## Key Takeaways

* Assessment collects facts to establish the timeline, scope, and impact of an AI incident.
* Move quickly but never in ways that damage investigation integrity — treat the system like a forensic scene.
* The first question is whether the incident has actually stopped; this changes the entire response posture.
* Core facts to capture are who was impacted, when it was discovered, what happened, which AI systems and data were affected, and what attack tactics were used.
* Naming what is still unknown is what turns the assessment into a clear plan for the Respond phase.

</div>

## Frequently Asked Questions

### What is the Assess phase of AI incident response?
The Assess phase means collecting facts to establish the **timeline**, the **scope**, and the **impact** of an AI incident once it has been detected. It should be done as quickly as possible, but never in a way that damages the integrity of the investigation, and good model documentation makes this far easier.

### What questions should be asked during AI incident assessment?
First, has the incident actually stopped or is it still unfolding. Then the core facts: who was impacted and what harm occurred, when the incident was discovered (critical for breach-notification deadlines), what exactly happened, which AI systems and data were affected, and what attack tactics were used. Finally, what is still unknown, and what do you need to know to return safely to normal operation.

### Why does the discovery date matter so much?
Pinning down when the incident was discovered is critical because many laws and regulations attach mandatory **breach-notification deadlines** to that moment. Missing those deadlines can convert a contained incident into a legal and reputational crisis, so the discovery date must be established early and documented carefully.

### How do you preserve evidence during AI incident assessment?
Move quickly to understand what happened, but take care not to trample the evidence that will explain *how* it happened. Think of it as being a careful first responder at a scene. Strong model documentation makes the work far easier because it gives investigators a reference point for what was normal before the incident.

<div class="cta" markdown="1">

### 📚 Master the ISACA AAISM Exam!

Ready to test your knowledge? Access chapter-specific **Multiple Choice Questions (MCQs)** and full-length practice exams for the ISACA AAISM certification at **[RooCloud.com](https://roocloud.com)**. Solve the chapter-wise questions to reinforce this lesson before moving to the next episode.

</div>

---

*Reference: This article is based on concepts discussed in [AI Incident Response — Assess the Incident](https://www.youtube.com/watch?v=YDSWWDuvnC4).*
