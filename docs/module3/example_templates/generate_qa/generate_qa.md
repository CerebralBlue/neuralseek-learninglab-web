---
title: Generate Q&A
permalink: /module3/example_templates/generate_qa
parent: example_templates
order: 8
---

# Generate Q&A

## Scenario Overview

A project manager, pressed for time after a significant meeting, utilizes CerebralBlue's NeuralSeek Explore. By inputting the meeting transcript, the AI swiftly generates essential question-answer pairs from the discussion. This concise summary helps the manager prioritize tasks, address uncertainties, and guide follow-up discussions with the team efficiently, ensuring a clear direction for the project.

## Open Example Template

In the NeuralSeek user interface, navigate to Explore.

![image]

Start Exploring with an Example Template.
- Click the "**Generate Q&A**" template.

![image]


## Retrieve Insights

- Click the "**Text**" box to edit the prompt.
- Add the given prompt: **Generate questions and answer pairs from our meeting. Questions and answers should be in 3rd person. Here is the meeting transcript:**

[image]

- Click the "**Local Document**" box to add the name of the document. In this example, <<name: Transcript>>. 
- Click the "**Summarize**" box to edit the desired summary length in characters. In this example, the desired summary length is set to 9500.
- Optionally, you can add text to prioritize building the summary around.
  
[image]

- Click the "**Send to LLM** box to edit the prompt.
- Add the given prompt: "**Refine these questions and answer pairs and focus on << name: Focus_Area >>**"

## Evaluate Results

- Click "Evaluate" to generate a response.

[image]

## Iterate and Refine

Leverage NeuralSeek Explore's feedback capabilities to analyze the draft. Refine the language, tone, and relevance of the content based on the insights provided by the tool.
