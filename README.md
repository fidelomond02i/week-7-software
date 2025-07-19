# week-7-software
Assignment: Understanding the AI Development Workflow
Course: AI for Software Engineering
Duration: 7 days
Total Points: 100

Objective & Guidelines

This assignment tests your ability to apply the AI Development Workflow to a real-world problem. You will demonstrate understanding of key stages—from problem definition to deployment—and critically analyze challenges and ethical considerations.

The assignment should be handled in peer groups. 

Submission Guidelines

PDF, 5–10 pages (excluding diagrams). Include section headings and references.

GitHub Repository with all codes well commented. 

Share the PDF as an article in the PLP Academy Community .

Grading Rubric

Completeness: All sections addressed (30%).

Accuracy: Technical correctness (40%).

Critical Analysis: Depth of ethical and practical insights (20%).

Clarity: Organization and presentation (10%).




Choose a hypothetical AI problem (e.g., "Predicting student dropout rates," "Customer churn prediction for a telecom company," "Optimizing traffic flow in a city"). For your chosen problem, address the following:

1. Problem Definition (6 points)
Define: Clearly state your chosen hypothetical AI problem.

Objectives: List 3 specific objectives for your AI solution.

Stakeholders: Identify 2 key stakeholders who would be impacted by or benefit from this AI system.

KPI: Propose 1 Key Performance Indicator (KPI) to quantitatively measure the success of your AI system.

2. Data Collection & Preprocessing (8 points)
Data Sources: Identify 2 potential data sources for your problem (e.g., internal databases, public datasets, APIs, web scraping).

Potential Bias: Explain 1 potential bias that might exist in the data you identified and how it could arise.

Preprocessing Steps: Outline 3 specific preprocessing steps you would apply to your raw data (e.g., handling missing data, normalization, categorical encoding, text tokenization). Provide a brief explanation for each.

3. Model Development (8 points)
Model Choice: Choose a specific AI model (e.g., Random Forest, Gradient Boosting, Neural Network, Support Vector Machine) and justify your choice in the context of your problem and data.

Data Splitting: Describe how you would split your data into training, validation, and test sets, including the typical proportions used.

Hyperparameters: Name 2 specific hyperparameters you would tune for your chosen model and briefly explain why tuning them is important for your problem.

4. Evaluation & Deployment (8 points)
Evaluation Metrics: Select 2 evaluation metrics relevant to your problem (e.g., Accuracy, Precision, Recall, F1-score, RMSE, MAE) and explain their significance.

Concept Drift: Explain what concept drift is in the context of AI models. How would you monitor for concept drift once your model is deployed in production?

Technical Challenge: Describe 1 technical challenge you anticipate during the deployment phase of your AI model (e.g., scalability, latency, integration with existing systems, version control).

Part 2: Case Study Application (40 points)
Scenario: A hospital wants an AI system to predict patient readmission risk within 30 days of discharge. This system aims to identify high-risk patients who could benefit from targeted interventions to reduce readmissions.

Tasks:
Problem Scope (5 points):

Define the core problem the AI system is solving.

State 3 clear objectives for this AI system from the hospital's perspective.

Identify 3 key stakeholders for this project within the hospital or patient community.

Data Strategy (10 points):

Data Sources: Propose at least 3 specific data sources within a hospital environment that could be used for this prediction task (e.g., Electronic Health Records (EHRs), patient demographics, lab results, discharge summaries).

Ethical Concerns: Identify 2 significant ethical concerns related to using patient data for this AI system (e.g., patient privacy, data security, potential for discrimination).

Preprocessing Pipeline: Design a conceptual preprocessing pipeline. Include at least 4 distinct steps, specifically detailing how you would handle data cleaning, normalization, and feature engineering steps relevant to healthcare data (e.g., creating features for comorbidity counts, length of stay, medication adherence scores).

Model Development (10 points):

Model Selection & Justification: Select an appropriate AI model (e.g., Logistic Regression, Gradient Boosting Machine, Recurrent Neural Network if time series data is considered) for predicting readmission risk. Justify your choice, considering the nature of the problem (binary classification) and potential data characteristics.

Confusion Matrix & Metrics: Assume your model has been trained. Create a hypothetical confusion matrix (labeling True Positives, False Positives, etc., with illustrative numbers) based on predicting patient readmission. Based on this hypothetical matrix, calculate the Precision and Recall for the "readmitted" class. Explain what these metrics mean in the context of this hospital scenario.

Deployment (10 points):

Integration Steps: Outline at least 4 key steps to integrate the trained AI model into the hospital’s existing IT system (e.g., as an API service, directly within the EHR system, integrating into clinical decision support).

Regulatory Compliance: How would you ensure the deployment and ongoing operation of this AI system complies with relevant healthcare regulations (e.g., HIPAA in the US, or comparable data protection regulations in Kenya like the Data Protection Act, 2019, which is highly relevant given the Eldoret, Kenya context)? Name at least 2 specific compliance considerations.

Optimization (5 points):

Overfitting Mitigation: Propose 1 specific method to address overfitting during the model training phase for this readmission prediction task (e.g., regularization, early stopping, cross-validation, more data). Explain how it helps.

Part 3: Critical Thinking (20 points)
Ethics & Bias (10 points):
Impact of Bias: How might biased training data (e.g., skewed towards certain demographics, incomplete records for specific patient groups) negatively affect patient outcomes or exacerbate health disparities in the hospital readmission prediction case study? Provide a specific example.

Bias Mitigation: Suggest 1 concrete strategy (e.g., re-sampling, algorithmic fairness techniques, feature engineering) to mitigate the bias identified above in the healthcare context.

Trade-offs (10 points):
Interpretability vs. Accuracy: Discuss the fundamental trade-off between model interpretability (understanding why a model makes a certain prediction) and accuracy in the context of the healthcare readmission prediction system. Which is more critical for this specific application and why?

Resource Constraints: If the hospital has limited computational resources (e.g., older servers, budget constraints for cloud computing), how might this impact the choice of AI model for the readmission prediction system? What compromises might need to be made?

Part 4: Reflection & Workflow Diagram (10 points)
Reflection (5 points):
Most Challenging Part: Reflect on the entire assignment process. What was the most challenging part of applying the AI development workflow, and why?

Improvement: If you had more time or resources, how would you improve your approach to this assignment or the AI system development process?

Workflow Diagram (5 points):
Sketch: Create a clear, high-level flowchart diagram of the generic AI Development Workflow. Label all the core stages (e.g., Problem Definition, Data, Model, Evaluation, Deployment, Monitoring). You can either create this digitally or sketch it and include a clear image in your PDF.

Grading Rubric
Completeness (30%): All sections addressed thoroughly, and all required deliverables (PDF report, GitHub repository) are complete and submitted correctly.

Accuracy (40%): Technical concepts are accurately described and applied. Problem formulation, data strategies, model choices, and evaluation methods are technically sound. Code (if applicable) is syntactically correct and logically sound.

Critical Analysis (20%): Depth of insight into challenges (technical, ethical, practical). Thoughtful discussion of ethical implications and proposed mitigation strategies. Demonstration of understanding beyond mere description.

Clarity (10%): Report is well-organized, coherent, and easy to read. Language is precise and professional. Diagrams (if any) are clear and informative. GitHub repository is well-structured and commented.

