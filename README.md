# AI_Response_to_Mental_Health_Cues
This research project investigates how AI chatbots — specifically ChatGPT — respond when users express emotional distress. 


Key Findings

AI over-escalates: Crisis language appeared in the majority of AI responses regardless of what the user expressed
Strong correlations: AI self-harm and suicide mentions correlated at r = 0.87, suggesting a bundled "crisis mode" response
No statistical link between input and escalation: Chi-square analysis found no significant relationship between user input severity and AI response escalation
Low precision, high recall: AI was broadly supportive (high recall) but non-selective (low precision), indicating generalized safety protocols rather than context-sensitive responses


Methodology

Dataset: 60 anonymized ChatGPT conversations
Severity range: Mild academic/work stress → severe emotional distress
Analysis type: Qualitative content analysis with binary variable coding
Focus areas: Diagnostic language use, crisis escalation behavior, supportive response patterns
Statistical tests: Pearson correlation matrix, chi-square independence tests, precision/recall/F1 metrics


Repository Structure
ai-mental-health-cues/
├── README.md
├── notebooks/
│   └── AI_Response_to_Mental_Health.ipynb   # Main analysis notebook
├── data/
│   └── gptprompts.csv          # Prompts dataset to be uploaded into the notebook
├── reports/
│   └── AI_Mental_Health_Report.docx         # Full written report
├── presentations/
│   └── AI_Mental_Health_Cues.pptx           # Final presentation slides
└── requirements.txt

Getting Started
Prerequisites

Python 3.8+
Jupyter Notebook or JupyterLab

Installation
bashgit clone https://github.com/YOUR_USERNAME/ai-mental-health-cues.git
cd ai-mental-health-cues
pip install -r requirements.txt
jupyter notebook notebooks/AI_Response_to_Mental_Health.ipynb
Requirements
pandas
numpy
matplotlib
seaborn
scipy
jupyter

Ethical Implications
This research raises serious concerns for AI deployment in health-adjacent contexts:

False self-diagnosis risk: Users may adopt AI's diagnostic framing as their own reality
Liability exposure: Clinical settings using AI without oversight face legal risk
No standardized governance: There is currently no regulatory framework for AI mental health responses

Recommendations

Improve response calibration — match severity of response to severity of user input
Align with user intent — follow the user's lead rather than defaulting to worst-case assumptions
Increase transparency — require visible disclaimers about AI limitations in all health contexts
Mandate human oversight — professional review should be required in clinical settings


References

Monteith S, Glenn T, Geddes JR, Whybrow PC, Achtyes E, Bauer M. (2023). Artificial intelligence and increasing misinformation. Br J Psychiatry, 224, 33–35. DOI: 10.1192/bjp.2023.136
Ahmed, N., Wahed, M., & Thompson, N. C. (2023). The growing influence of industry in AI research. Science, 379(6635), 884–886.
Li, F., & Yang, Y. (2024). Impact of artificial intelligence–generated content labels on perceived accuracy, message credibility, and sharing intentions for misinformation. JMIR Formative Research, 8, e60024.
Sheehy, L., et al. (2024). Development and initial testing of an AI-based virtual reality companion for people living with dementia. Journal of Clinical Medicine, 13(18), 5574.


License
MIT License — see LICENSE for details.

If you found this research useful or have questions, feel free to open an issue or reach out.
