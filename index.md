---
layout: default
title: Data Science Portfolio
---

<div class="hero">
  <p class="eyebrow">DATA SCIENCE PORTFOLIO</p>
  <h1>SONG Xuhuiyang</h1>
  <p class="lead">I build reproducible analyses that turn raw data into clear, decision-ready findings.</p>
  <div class="actions">
    <a class="button" href="https://github.com/kaiserreich001/data-science-project">View project repository</a>
    <a class="button secondary" href="#project">Explore the case study</a>
  </div>
</div>

## About me

I am a data science learner interested in statistical reasoning, machine learning, and communicating evidence through readable visualizations. My work emphasizes reproducibility: fixed random seeds, documented data sources, clear project structure, and instructions that let another person rerun the analysis.

## Technical skills

<div class="skills">
  <span>Python</span><span>pandas</span><span>NumPy</span><span>scikit-learn</span><span>matplotlib</span><span>seaborn</span><span>Jupyter</span><span>Git &amp; GitHub</span>
</div>

## Project showcase

<div class="project-card" id="project" markdown="1">

### Study Habits and Academic Performance

**Research question:** To what extent are weekly study hours, attendance, prior GPA, tutoring access, and first-generation status associated with exam performance?

<p class="status"><strong>Status:</strong> Completed</p>

![Scatter plot showing a positive association between weekly study hours and exam scores]({{ '/assets/images/study_hours_vs_score.svg' | relative_url }})

**What the analysis found:** Weekly study time showed a positive association with exam score, with an estimated increase of about 1.4 points per additional weekly study hour after accounting for the other variables. Students with tutoring access scored about 4.5 points higher on average. The held-out linear regression achieved an R² of approximately 0.53, indicating that substantial variation remains unexplained.

**Methods:** A reproducible synthetic dataset, exploratory data analysis, linear regression, a fixed train-test split, and visual communication using Python.

**Limitation:** The dataset is synthetic, so the results demonstrate workflow and interpretation rather than evidence about real students. No causal claim is intended.

[View the complete project repository](https://github.com/kaiserreich001/data-science-project)

</div>

## What I will improve next

I plan to repeat this workflow with a licensed real-world education dataset, add uncertainty estimates, and compare the linear baseline with a non-linear model. I will also refine the portfolio using feedback from a classmate on whether the project purpose, main finding, and limitation are immediately clear.
