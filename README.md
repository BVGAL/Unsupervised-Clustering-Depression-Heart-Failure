Unsupervised Clustering Analysis of Depression and Heart Failure Outcomes
This repository contains the workflow and documentation for a data mining project aimed at exploring the relationship between depression severity (PHQ-9 scores) and heart failure outcomes using unsupervised machine learning techniques in Orange Data Mining.

🔍 Objective
To investigate whether patients with higher levels of depression tend to experience worse clinical outcomes, including:

Lower ejection fraction

Elevated BNP/NT-BNP levels

Higher mortality

Increased hospitalization rates

📊 Dataset
The analysis is based on a publicly available dataset of 425 patients with multiple clinical and psychological variables related to heart failure and mental health.
Key features include:

PHQ-9 depression scores

Ejection fraction (%)

Blood pressure, BNP, kidney function, and demographic data

Outcomes such as hospitalization and mortality

🧪 Methodology
The analysis uses unsupervised clustering techniques to detect natural patient groupings:

K-Means (validated via Silhouette scores)

Hierarchical Clustering (average linkage, 89% height cut)

DBSCAN (epsilon selected via k-distance elbow plot)

🖼️ Visualization Tools
Box Plots for comparing depression and cardiac variables across clusters

Scatter Plots to analyze trends between PHQ-9 and outcomes (e.g., BNP, eGFR)

MDS Maps for visual separation of clusters

✅ Key Findings
Across all three clustering methods, patients with higher PHQ-9 scores consistently clustered into groups showing:

Worse heart function (lower ejection fraction)

Elevated heart failure biomarkers (BNP)

Higher death and hospitalization rates
This supports the hypothesis that depression severity is positively correlated with adverse heart failure progression.

🧠 Conclusion
The study reinforces the value of integrating mental health indicators into clinical assessment of heart failure. Clustering can be a useful tool for identifying high-risk patient profiles and may inform more holistic, patient-centered care strategies.

