# AI-Impact---Hugging-Face

# The Impact of ChatGPT on Open-Source LLM Adoption


## Introduction and Research Question

### Selected Technology

Open-source Large Language Models (LLMs)

### Objectives

Measure changes in the adoption of open-source LLMs before and after the release of ChatGPT.

### Research Question

**Did the release of ChatGPT in November 2022 differentially boost the adoption of LLM-based text-generation models compared to non-LLM models on Hugging Face?**

---

## Background and Context

### What Are LLMs?

Large Language Models are AI models trained for language understanding and text generation.

### What Is Hugging Face?

Hugging Face is a major open-source AI model-sharing platform.

### Why Does It Matter?

- AI is growing at a rapid rate.
- Generative AI is reshaping productivity and workflows.
- Open-source platforms make AI models more accessible to businesses, researchers, and developers.

---

## Dataset and Methodology

### Dataset

- **Source:** Hugging Face API
- **Total models:** 360,487
- **Time period:** March 2022–December 2025

### Groups

#### Treatment Group

- Text-generation models
- Approximately 298,000 models

#### Control Group

- Non-text AI models
- Approximately 62,000 models

### Methodology

The analysis used a **Difference-in-Differences (DiD)** approach to compare:

- Model creation before and after the release of ChatGPT
- Text-generation models against non-text AI models
- Pre-treatment trends through a parallel trends test
- Changes in the treatment effect over time through an event study analysis

---

## Results

Text-generation model creation grew **3.8 times faster** than non-text model creation following the release of ChatGPT. This result was statistically significant, with a p-value of **0.006**.

| Metric | Result |
|---|---:|
| DiD coefficient | 1.343 |
| p-value | 0.006 |
| Estimated effect | 3.8x increase |
| Parallel trends p-value | 0.847 |

![Deliverable 4 Presentation](Deliverable%20%234%20Presentation.png)


### Event Study Analysis

- Pre-treatment trends were parallel before November 2022, supporting the validity of the Difference-in-Differences approach.
- The estimated effect continued to grow throughout 2024 and 2025.
- By 2025, the treatment effect exceeded 2.0 on the log scale.

![Deliverable 4 Presentation - Continued](Deliverable%20%234%20Presentation%20%281%29.png)
---

## Economic Impact Analysis

### Market Dynamics

- ChatGPT acted as a **General Purpose Technology (GPT) shock**.
- Text-generation models grew 3.8 times faster than non-text models after November 2022.
- Hugging Face recorded 142,848 text-generation models in 2025.

### Cost Structure Changes

- Open-source LLMs reduced AI development costs.
- These models lowered barriers to entry for startups and researchers.

### Capital Reallocation

- Venture capital shifted toward generative AI.
- Generative AI startup funding reached **$25.2 billion in 2023**.

---

## Organizational Restructuring

### New AI Skills and Roles

- Prompt engineering
- Model fine-tuning
- AI-assisted productivity, with reported gains of 34%

### Build-vs.-Buy AI Strategies

- Organizations are evaluating whether to build AI systems internally or purchase external solutions.
- Open-source models create more opportunities for internal AI customization.

### Implementation Challenges

- Organizations need reliable data pipelines and monitoring systems.
- Rapid model turnover makes long-term implementation and governance more difficult.

---

## Productivity and Competitive Advantage

- Faster adopters may gain a competitive advantage.
- Successfully adopting AI requires organizations to redesign workflows rather than simply add new tools.

---

## Societal Consequences

### Access and Equity

- Open-source AI expands global access to advanced AI technologies.
- Bias and underrepresentation remain significant concerns.

### Misinformation Risks

- Generative AI makes synthetic content easier to create.
- Fine-tuned models can be used to spread misinformation.
- Detection tools continue to lag behind the growth of AI-generated content.

### Policy and Regulation

- Open-source AI may complicate accountability.
- AI governance frameworks are still evolving.

---

## Recommendations

### For Businesses

- Monitor developments in open-source AI.
- Invest in generative AI tools and organizational capabilities.
- Redesign workflows to effectively integrate AI.

### For Researchers

- Continue studying the long-term impacts of AI adoption.
- Examine how open-source model development changes across different AI categories.

### For Policymakers

- Understand how AI innovation spreads through open-source ecosystems.
- Develop governance frameworks that balance innovation, access, safety, and accountability.

---

## Conclusion

- ChatGPT accelerated open-source AI innovation.
- Generative AI became a dominant category within the open-source AI ecosystem.
- Open-source ecosystems respond rapidly to major technological breakthroughs.
- Future research should consider whether the control group would naturally experience growth due to developments in other AI categories, such as audio and video models.

Note:

This project was a group effort by Luisa Garate & Drake Niepoetter
