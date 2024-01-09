---
title: Call Prep
permalink: /module3/example_templates/call_prep
parent: example_templates
order: 7
---
# Write A Memo

## Scenario Overview

A pharmaceutical executive, tasked with leading an earnings call, turns to CerebralBlue's NeuralSeek Explore. They input diverse datasets—sales figures, R&D investments, clinical trial outcomes, and market trends—into the AI tool. NeuralSeek rapidly processes the data, uncovering critical patterns and market indicators. Armed with this distilled insight, the executive crafts a concise, data-driven presentation. During the earnings call, armed with precise analysis from NeuralSeek Explore, they confidently discuss the company's performance, strategies, and growth opportunities. The AI-driven insights not only anticipate investor queries but also impress stakeholders, instilling confidence in the company's direction and performance.

## Open Example Template

In the NeuralSeek user interface, navigate to Explore.

![image]

Start Exploring with an Example Template.
- Click the "**Call Prep**" template.

![image]


## Retrieve Insights

- Click the "**Text**" box to edit the prompt.
- Add the given prompt: **We need to prep for our earnings call.  Here is a transcript of questions from our last call:**

[image]

- Click the "**Local Document**" box to add a document name. In this example, <<name: Questions_Transcript>>.
- Click the "**Split**" box to take input text and extract a section from it, while optionally removing headers and footers. In this example, "QUESTIONS AND ANSWERS" defines where in the text the split will start. Optionally, you can add an option to find text to end the split. The remove detected Headers and Footers option is automatically set to true.
- Click the "**Send to LLM**" box and add the given prompt: **Summarize these questions by analyst name.**. 

[image]

- Click the "**Text**" box to edit the prompt.
- Add the given prompt: **Then, with those previous questions predict what each analyst's top 3 questions might be for this earnings call  and give proposed answers based on this documentation:**

[image]

- Click the "**Local Document**" box to add a document name. In this example, <<name: Earnings_Call>>.
- Click the "**Split**" box to take input text and extract a section from it, while optionally removing headers and footers. In this example, "PRESENTATION" defines where in the text the split will start, and "QUESTIONS AND ANSWERS" defines where in the text to end the split. The remove detected Headers and Footers option is automatically set to true.
- Click the "**Summarize**" box to set the desired summary length in characters. In this example, it is set to 6500. Optionally, you can add text to prioritize building the summary around. 

[image]

## Craft the Memo

- Click "Evaluate" to generate a response.

[image]

## Iterate and Refine

Leverage NeuralSeek Explore's feedback capabilities to analyze the call prep draft. Refine the language, tone, and relevance of the content based on the insights provided by the tool.
