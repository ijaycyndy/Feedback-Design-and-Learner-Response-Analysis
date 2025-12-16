## Feedback Design and Learner Response Analysis

This project examines how learners are likely to respond to different AI feedback designs in writing tasks.
The focus is on clarity, actionability, and cognitive load rather than text generation.

It builds on Projects 1 (Multi-Persona AI Writing Assistant) and 2 (Learning Analytics Dashboard for Writing Improvement) by shifting attention from what feedback is produced to how feedback design may affect learners.

## Open in Google Colab

Use the link below to run the full analysis notebook in Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ijaycyndy/Feedback-Design-and-Learner-Response-Analysis/blob/main/Feedback_Design_and_Learner_Response_Analysis.ipynb)


## Research Focus

The project explores three core questions:

1 How do different feedback styles affect clarity and actionability?

2 What trade-offs exist between detailed feedback and cognitive load?

3 Do structured styles reduce learner effort while maintaining usefulness?

The aim is to support evidence-informed design of AI feedback for education.

## Data Source

The dataset is derived from earlier projects in this portfolio.

Each row represents one feedback variant and includes:

1 Persona generating the feedback

2 Feedback style (raw, short_actions, step_by_step, questions_first)

3 Feedback text

4 LLM-based scores (1–5 scale): (clarity, actionability, cognitive_load)

All scoring is reproducible and documented in the notebook.

## Method Overview

1 Multiple feedback variants were generated for the same writing samples

2 An LLM was used as a consistent scoring instrument

3 Scores were validated to ensure: (valid JSON output, no missing values, consistent scale usage)

4 Results were aggregated by persona and feedback style

5 Visual analysis was used to highlight design trade-offs

## Key Analyses

The notebook includes:

1 Summary tables by persona and style

2 Actionability comparisons across feedback styles

3 Cognitive load comparisons across feedback styles

4 Identification of design trade-offs between brevity and depth

The analysis prioritises transparency and interpretability.

## Educational Relevance

This project aligns with AI for Education research by:

1 Treating feedback as a learning intervention

2 Examining learner effort, not only correctness

3 Highlighting design choices that affect usability

4 Demonstrating how learning analytics can guide feedback design

The approach reflects realistic constraints in educational settings.

## Files in This Repository

feedback_design_analysis.ipynb
Full analysis notebook with scoring, aggregation, and visualisations

project3_feedback_design_rows.csv
Row-level feedback variants and scores

project3_feedback_design_summary.csv
Aggregated results by persona and style

README.md
Project documentation

## Related Projects

Project 1: Multi-Persona AI Writing Assistant
Focus on feedback generation and orchestration

Project 2: Learning Analytics Dashboard for Writing Improvement
Focus on before-and-after writing changes

This project completes the pipeline by analysing feedback design impact.

## Notes on Scope

Small exploratory dataset

Results are illustrative, not generalisable

Emphasis is on method, reasoning, and evaluation design

The project is intended as a research-ready prototype rather than a production system.
