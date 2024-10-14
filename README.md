# AI Risk Pulse Survey

## Overview
The AI Risk Pulse Survey is a comprehensive survey instrument designed to measure and track anxiety related to artificial intelligence (AI) across various demographics. It assesses respondents' experiences, beliefs, and concerns about current and future AI developments, providing insights into the factors contributing to AI-related anxiety.

## Purpose
The rapid advancement of AI technologies has sparked widespread discussion and concern about their potential impacts on society, employment, privacy, and even human existence. However, there is a lack of empirical data on how these concerns manifest across different populations and how they relate to individuals' backgrounds and experiences with AI.

The AI Risk Pulse Survey aims to:
1. Quantify levels of AI-related anxiety across diverse demographics
2. Identify correlations between AI anxiety and factors such as education, experience, and general anxiety predisposition
3. Track changes in AI anxiety over time as AI technologies evolve
4. Provide data-driven insights to inform AI policy, research directions, and public communication strategies
5. Contribute to a more nuanced understanding of public perception and concerns regarding AI

By gathering this data, the project seeks to bridge the gap between expert assessments and public perceptions of AI risks, potentially leading to more aligned policies, focused research priorities, and effective public engagement strategies.

## Methodology
The AI Risk Pulse Survey employs a rigorous methodology to ensure reliable and comprehensive data collection:

1. **Likert Scales**: Questions are answered on a 5-point Likert scale (Strongly Disagree to Strongly Agree), allowing for nuanced responses and quantitative analysis.
2. **Split-Half Consistency**: Each category contains an equal number of positively and negatively framed questions to reduce response bias and ensure internal consistency.
3. **Polar Questions**: The survey uses pairs of opposing statements to capture the full spectrum of opinions on each topic.
4. **Comprehensive Categorization**: The index is divided into 12 distinct categories, covering demographics, current perceptions, and future projections.
5. **Regular Administration**: The survey is designed to be administered periodically, allowing for longitudinal analysis of AI anxiety trends.

## Repository Contents and Usage

This repository contains the necessary files to generate and use the **AI Risk Pulse Survey** tool. It includes a CSV file with all the survey questions, a Python script to generate the HTML widget, and the resulting HTML file that can be used to administer the survey.

### Repository Files

| File Name          | Description                                                  |
|--------------------|--------------------------------------------------------------|
| `README.md`        | This file, containing information about the project and repo |
| `generate_widget.py` | Python script to generate the HTML widget from the CSV file |
| `questions.csv`    | CSV file containing all 240 questions for the survey         |
| `widget.html`      | The generated HTML file containing the interactive survey tool |

### How to Use

1. **Clone the Repository**:
   ```bash
   git clone [repository URL]
   ```
2. **Navigate to the Repository Directory**:
   ```bash
   cd [repository directory]
   ```
3. **Ensure Python is Installed**:
   - Make sure you have Python 3 installed on your system.
   - You can check by running:
     ```bash
     python --version
     ```
4. **Generate the Survey Widget**:
   - Run the Python script to generate or update the `widget.html` file:
     ```bash
     python generate_widget.py
     ```
5. **Open the Survey**:
   - Open `widget.html` in a web browser to use the **AI Risk Pulse Survey** tool.
   - You can do this by double-clicking the `widget.html` file or opening it from within your browser.

### Notes

- **Updating Questions**:
  - If you need to update or modify the survey questions, edit the `questions.csv` file accordingly.
  - After making changes, rerun `generate_widget.py` to regenerate the `widget.html` file with the updated questions.

- **Customizing the Survey**:
  - You can modify the styling or functionality by editing the `generate_widget.py` script.
  - Ensure that any changes are compatible with the existing structure to maintain proper functionality.

- **Testing**:
  - The survey includes debug buttons that allow you to set all responses to a specific value for testing purposes.
  - These can be removed or commented out in the HTML if not needed.

## Categories
1. Direct AI Experience: Assesses hands-on experience with AI and machine learning.
2. Adjacent Tech Experience: Measures broader technology experience and skills.
3. AI-Related Education: Evaluates formal education in AI and related fields.
4. Conspiracy Theory Risk Factors: Identifies predisposition to anxiety and conspiracy beliefs.
5. AI Research Awareness: Gauges knowledge of current AI research and developments.
6. AI Research Beliefs: Assesses perceptions of the adequacy of current AI safety research.
7. AI Governance Perception: Measures trust in current AI regulation and oversight.
8. Current AI Concerns: Evaluates anxiety about present-day AI applications.
9. AI Existential Risks: Assesses beliefs about long-term, catastrophic AI risks.
10. Future Governmental Response: Gauges trust in future government handling of AI challenges.
11. Future AI Capabilities: Measures beliefs about potential future AI advancements.
12. Future Corporate Accountability: Assesses trust in private enterprises' future AI safety efforts.

## Categories (Continued)

1. **Direct AI Experience**
   This category measures respondents' hands-on experience with AI and machine learning technologies. It aims to quantify the depth and breadth of practical AI knowledge, including experience in building, training, and deploying AI models. Questions in this category help establish a baseline of direct AI interaction, which may correlate with levels of AI anxiety.

2. **Adjacent Tech Experience**
   This section assesses broader technology experience and skills that, while not directly AI-related, may influence perceptions of AI. It includes experience with data center management, cloud architecture, programming, and other technical fields. This category helps identify how general tech savviness might impact AI anxiety levels.

3. **AI-Related Education**
   This category evaluates formal education specifically related to AI and associated fields. It covers degrees in computer science, data science, robotics, and other STEM fields directly applicable to AI. The goal is to understand how specialized education correlates with AI anxiety levels.

4. **Conspiracy Theory Risk Factors**
   This unique category assesses general risk factors associated with susceptibility to conspiracy theories and heightened anxiety. It includes questions about social isolation, chronic health issues, and general anxiety levels. This helps identify how underlying psychological and social factors might influence AI-specific anxieties.

5. **AI Research Awareness**
   This category gauges respondents' awareness and understanding of current AI research. It assesses how closely individuals follow AI developments, their familiarity with primary sources, and their overall knowledge of the AI research landscape. This helps correlate research awareness with anxiety levels.

6. **AI Research Beliefs**
   Building on the previous category, this section focuses on subjective beliefs about the current state of AI research, particularly regarding safety and ethics. It aims to understand perceptions about the adequacy and direction of current AI research efforts.

7. **AI Governance Perception**
   This category evaluates trust and perceptions regarding current AI governance structures, including corporate policies, government regulations, and international oversight. It assesses beliefs about the effectiveness and adequacy of existing AI governance frameworks.

8. **Current AI Concerns**
   This section delves into specific worries about present-day AI applications, covering areas such as surveillance, manipulation, misinformation, and privacy infringements. It aims to quantify anxiety levels related to various current AI use cases.

9. **AI Existential Risks**
   This category assesses beliefs about potential long-term, catastrophic risks posed by AI. It covers topics such as the likelihood of AI-driven human extinction, belief in an AI "takeover," and perceptions of humanity's long-term prospects in an AI-driven future.

10. **Future Governmental Response**
    This section gauges trust in future government actions regarding AI challenges. It assesses beliefs about the ability of governments to effectively regulate and manage advanced AI systems, and their capacity to address potential AI-driven crises.

11. **Future AI Capabilities**
    This category measures beliefs about potential future AI advancements, including concepts like the technological singularity, artificial general intelligence (AGI), and superhuman AI. It aims to understand expectations and anxieties about future AI capabilities.

12. **Future Corporate Accountability**
    The final category assesses trust in private enterprises' future efforts in AI safety and ethics. It covers perceptions of corporate responsibility, the effectiveness of industry self-regulation, and beliefs about the alignment of corporate interests with societal wellbeing in the context of AI development.
