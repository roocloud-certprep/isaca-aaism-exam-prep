---
layout: default
title: "Types of AI: ANI, AGI, ASI, Generative, Agentic & Machine Learning | ISACA AAISM Ep. 36"
description: "Master types of AI for the ISACA AAISM exam: ANI, AGI, ASI, reactive, limited memory, generative, agentic, predictive, neural networks and machine learning paradigms."
keywords: "types of AI, ANI, AGI, ASI, narrow AI, generative AI, agentic AI, machine learning, deep learning, neural networks, supervised learning, unsupervised learning, reinforcement learning, large language models, transformers, ISACA AAISM, AAISM exam prep"
author: "RooCloud"
image: "https://img.youtube.com/vi/9q5dt8uAl-o/maxresdefault.jpg"
permalink: /domain-3-ai-technologies-and-controls/ep36-types-of-ai.html
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "Types of AI: ANI, AGI, ASI, Generative, Agentic & Machine Learning",
  "description": "Master types of AI for the ISACA AAISM exam: ANI, AGI, ASI, reactive, limited memory, generative, agentic, predictive, neural networks and machine learning paradigms.",
  "thumbnailUrl": "https://img.youtube.com/vi/9q5dt8uAl-o/maxresdefault.jpg",
  "uploadDate": "2026-05-01",
  "contentUrl": "https://www.youtube.com/watch?v=9q5dt8uAl-o",
  "embedUrl": "https://www.youtube.com/embed/9q5dt8uAl-o",
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
      "name": "How do AI, machine learning, deep learning, and generative AI relate to each other?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Picture a set of nested circles. The widest is artificial intelligence, the broad goal of machines doing tasks that normally need human intelligence. Inside it sits machine learning, where systems learn patterns from data. Inside that sits deep learning, which uses many-layered networks to learn abstract features. And generative AI lives within deep learning, creating brand-new content from the patterns it has absorbed."
      }
    },
    {
      "@type": "Question",
      "name": "What are ANI, AGI, and ASI?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Artificial narrow intelligence, or ANI, is sometimes called weak AI and is limited to one specific domain like translating languages; it is essentially all the AI in use today. Artificial general intelligence, or AGI, could handle any intellectual task a human can but does not yet exist. Artificial superintelligence, or ASI, is a hypothetical stage where machine intelligence would surpass the best human minds across every field, and remains purely a concept."
      }
    },
    {
      "@type": "Question",
      "name": "What is the difference between generative, agentic, and predictive AI?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Generative models, such as generative adversarial networks, create new content like images or audio by pitting two networks against each other. Agentic AI makes autonomous decisions and takes actions to achieve a goal, with fewer hallucinations than ordinary generative AI but still needing human oversight. Predictive models use historical data to forecast future events such as equipment failures."
      }
    },
    {
      "@type": "Question",
      "name": "What are the three main machine learning paradigms?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Supervised learning trains on labeled data and covers regression for continuous numbers and classification for categories. Unsupervised learning works on raw, unlabeled data and performs clustering, association rules, and dimensionality reduction. Reinforcement learning has an agent learn by trial and error through rewards and penalties, suiting autonomous control."
      }
    },
    {
      "@type": "Question",
      "name": "What are overfitting and underfitting in machine learning?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Underfitting means a model is too simple to capture the patterns in the data. Overfitting means a model has memorized the training data, including the noise, and fails on anything new. Both are central concepts that every security professional should understand when evaluating model reliability."
      }
    }
  ]
}
</script>

**[🏠 Back to Exam Syllabus](../README.md)** | **[📺 RooCloud on YouTube](https://youtube.com/@roocloud)** | **[🌐 RooCloud Practice Exams](https://roocloud.com)**

---

# Types of AI: ANI, AGI, ASI, Generative, Agentic and Machine Learning

You cannot secure or govern a technology you do not understand. This episode of the **ISACA Advanced in AI Security Management (AAISM)** exam prep series builds a clear mental map of the whole AI field: how AI, machine learning, and deep learning nest together, the types of AI by function and by capability, the major model families, how machines actually learn, and the key terms every security professional should know. The payoff is being able to ask the right questions about any system you encounter, judge what a model can and cannot do, and spot where its particular design creates risk. This is the vocabulary the rest of Domain 3 is built on.

<div class="video-embed">
  <iframe src="https://www.youtube.com/embed/9q5dt8uAl-o" title="Types of AI: ANI, AGI, ASI, Generative, Agentic & Machine Learning" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## AI, Machine Learning, Deep Learning, and Generative AI: The Nested Circles

Start by untangling some words that often get muddled. Picture a set of nested circles. The widest is **artificial intelligence**, the broad goal of machines doing tasks that normally need human intelligence. Inside it sits **machine learning**, where systems learn patterns from data instead of being hand-coded. Inside that sits **deep learning**, which uses many-layered networks to learn ever more abstract features. And **generative AI** lives within deep learning, creating brand-new content from the patterns it has absorbed. With that map in mind, there are two ways to categorize AI: by what it can do functionally, and by how capable it is overall. The functional view gives four types, and the capability view gives three. The exam expects you to know both lenses.

## The Four Functional Types of AI

The first two functional types are the simplest. **Reactive machines** respond to the current input with no memory of the past, like a reflex that fires the same way every time it is triggered. **Limited memory** systems go a step further by using recent data to inform decisions, much like a driver glancing at the last few seconds of road and traffic before changing lanes. The vast majority of today's AI sits in this limited-memory category.

The next two functional types are far more advanced and largely aspirational. **Theory of mind** describes a machine that could understand human emotions and intentions, in effect reading the room and adjusting its behavior to people's mental states; we see only early, partial hints of this today. **Self-aware AI**, the final type, would possess consciousness of its own mind and feelings. This does not exist, and remains purely theoretical.

## The Three Capability Tiers: ANI, AGI, and ASI

Now the capability lens, starting with **artificial narrow intelligence, or ANI**. Sometimes called weak AI, this is a system limited to one specific domain, like a tool that only translates languages or only sorts images. Despite the name, narrow AI is enormously useful and is essentially all the AI in use today. It performs its single task with great accuracy but has no awareness or general understanding beyond that narrow lane.

The next step up is **artificial general intelligence, or AGI**, a system that could handle any intellectual task a human can. To qualify, it would need broad capabilities like sensory perception, problem-solving, natural-language understanding, creativity, and social-emotional engagement. Real progress is happening in areas like vision and language, but human-level common sense and fine motor skills remain out of reach, so AGI does not yet exist.

Beyond even that lies **artificial superintelligence, or ASI**, a hypothetical stage where machine intelligence would surpass the best human minds across every field, solving problems and creating innovations beyond our current imagination. It is, for now, purely a concept.

## Major Model Families: Generative, Agentic, and Predictive

Move next to the major model families, beginning with **generative models**. A landmark design here is the **generative adversarial network**, which pits two neural networks against each other. One network generates fake samples while the other tries to tell fakes from real, like a forger and an art authenticator locked in competition. As they train, both improve until the forger's output becomes so convincing the authenticator can no longer tell the difference, which is how these systems learn to produce strikingly realistic images, audio, and more.

A fast-rising family is **agentic AI**, the next evolution beyond simple assistants. An AI agent can make autonomous decisions and take actions to achieve a goal, such as keeping a process running efficiently. Its benefits include greater specialization on granular tasks, easy experimentation, and, thanks to stronger reasoning, fewer hallucinations than ordinary generative AI. But it still needs human oversight, because vague goals lead it badly astray.

Another family is **predictive models**, which use historical data and machine learning to forecast future events and trends, spotting patterns in the past to anticipate what comes next. They power things like equipment-failure prediction and forecasting. The key risk is that decision-makers must genuinely understand how a prediction was derived, so that choices rest on verifiable reasoning rather than blind faith.

## Machine Learning Paradigms: Supervised, Unsupervised, and Reinforcement

At the heart of it all is **machine learning**, where machines learn from data using mathematical models. A crucial concept is the **label**, the known answer a model is trained to predict. Labels are not always easy to get: hand-labeling millions of data points is slow and expensive, some categories are genuinely ambiguous and need expert judgment, and in brand-new domains there may be no known correct answer at all. This challenge shapes which learning approach you choose.

* **Supervised learning** trains on labeled data, like studying with an answer key. It splits into **regression**, which predicts a continuous number such as forecasting next month's energy demand, and **classification**, which sorts items into categories such as judging whether a piece of fruit in a photo is ripe or unripe. Variations like semi-supervised and self-supervised learning help when labels are scarce or costly.
* **Unsupervised learning** works on raw, unlabeled data with no answer key, finding hidden structure on its own. It does three main things: **clustering** groups similar items together, like sorting a music library by sound without being told the genres; **association rules** uncover relationships between items; and **dimensionality reduction** simplifies data with many variables down to the few that matter most. Its main drawback is weak explainability, so a human in the loop is important.
* **Reinforcement learning** has an agent learn by trial and error, earning rewards for good actions and penalties for bad ones. Imagine a robotic cleaner gradually discovering the most efficient path through a home by being rewarded for covering more floor. It suits autonomous control, like adaptive intrusion detection, but its independence makes safety and human oversight essential.

## Neural Networks, Deep Learning, and Algorithms

Underpinning much of this are **neural networks**, collections of algorithms loosely inspired by the brain. A network has three kinds of layers: an **input layer** that receives data, one or more **hidden layers** where the real computation and learning happen, and an **output layer** that produces the result, rather like an assembly line transforming raw materials into a finished product. Worth knowing: **feedforward networks** pass information in one direction, suiting tasks like image recognition; **recurrent networks** have loops that handle sequences, suiting language and speech; and **convolutional networks** specialize in grid-like data such as images, detecting edges, textures, and objects. When a network has many layers, it becomes **deep learning**, which can extract features automatically, and an automated technique called **neural architecture search** can even help design the best network, though always with human oversight.

**Algorithms** are the step-by-step rules that power all of this. In machine learning, algorithms let models analyze data, find patterns, and make predictions, and each comes with **hyperparameters**, the dials you set before training to tune how it learns, such as the learning rate. Algorithms fall into classes matched to the learning paradigms: supervised ones like linear and logistic regression, decision trees, and support vector machines; unsupervised ones like clustering and principal component analysis; and reinforcement ones like Q-learning. Choosing the right class matters as much as tuning it, and **ensemble modeling**, which combines several models, can improve accuracy and reduce the weaknesses of any single one.

## Essential Vocabulary: LLMs, Transformers, Drift, and AI as a Service

A handful of terms round out your vocabulary. A **large language model** is trained on huge amounts of text using a transformer architecture to understand and generate human-like language. A **prompt** is the input that triggers a generative system, and output quality depends heavily on how specific that prompt is. **Foundation models** are broadly trained and adaptable to many tasks. And **transformers** use a mechanism called **attention** to weigh relationships in data efficiently.

A few more matter for risk. **Natural language processing** lets computers understand and generate human language, and **sentiment analysis** uses it to judge whether text is positive, negative, or neutral. **Underfitting** means a model is too simple to capture the patterns, while **overfitting** means it memorized the training data, including the noise, and fails on anything new. And **AI as a service** lets organizations subscribe to AI tools in the cloud without seeing how the model was built, which is convenient but carries its own hidden risk.

<div class="takeaways" markdown="1">

## Key Takeaways

* AI contains machine learning, which contains deep learning, which contains generative AI as a set of nested circles.
* AI is categorized functionally as reactive, limited memory, theory of mind, and self-aware, and by capability as ANI, AGI, and ASI, with only narrow AI in use today.
* Model families include generative (such as GANs), agentic, and predictive, each carrying distinct risks and benefits.
* Machines learn through three paradigms: supervised, unsupervised, and reinforcement, often powered by neural networks and deep learning.
* Key terms like large language models, transformers, prompts, hyperparameters, overfitting, underfitting, and AI as a service complete the foundational vocabulary every AAISM candidate needs.

</div>

## Frequently Asked Questions

### How do AI, machine learning, deep learning, and generative AI relate to each other?
Picture a set of nested circles. The widest is **artificial intelligence**, the broad goal of machines doing tasks that normally need human intelligence. Inside it sits **machine learning**, where systems learn patterns from data. Inside that sits **deep learning**, which uses many-layered networks to learn abstract features. And **generative AI** lives within deep learning, creating brand-new content from the patterns it has absorbed.

### What are ANI, AGI, and ASI?
**Artificial narrow intelligence (ANI)**, sometimes called weak AI, is limited to one specific domain like translating languages, and is essentially all the AI in use today. **Artificial general intelligence (AGI)** could handle any intellectual task a human can but does not yet exist. **Artificial superintelligence (ASI)** is a hypothetical stage where machine intelligence would surpass the best human minds across every field, and remains purely a concept.

### What is the difference between generative, agentic, and predictive AI?
Generative models, such as generative adversarial networks, create new content like images or audio by pitting two networks against each other. Agentic AI makes autonomous decisions and takes actions to achieve a goal, with fewer hallucinations than ordinary generative AI but still needing human oversight. Predictive models use historical data to forecast future events such as equipment failures.

### What are the three main machine learning paradigms?
**Supervised learning** trains on labeled data and covers regression for continuous numbers and classification for categories. **Unsupervised learning** works on raw, unlabeled data and performs clustering, association rules, and dimensionality reduction. **Reinforcement learning** has an agent learn by trial and error through rewards and penalties, suiting autonomous control.

### What are overfitting and underfitting in machine learning?
**Underfitting** means a model is too simple to capture the patterns in the data. **Overfitting** means a model has memorized the training data, including the noise, and fails on anything new. Both are central concepts that every security professional should understand when evaluating model reliability.

<div class="cta" markdown="1">

### 📚 Master the ISACA AAISM Exam!

Ready to test your knowledge? Access chapter-specific **Multiple Choice Questions (MCQs)** and full-length practice exams for the ISACA AAISM certification at **[RooCloud.com](https://roocloud.com)**. Solve the chapter-wise questions to reinforce this lesson before moving to the next episode.

</div>

---

*Reference: This article is based on concepts discussed in [Types of AI: ANI, AGI, ASI, Generative, Agentic & Machine Learning](https://www.youtube.com/watch?v=9q5dt8uAl-o).*
