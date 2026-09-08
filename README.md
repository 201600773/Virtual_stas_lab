Virtual Stats Lab
Interactive Statistics · Econometrics · Actuarial Science · Machine Learning
Run statistical tests in your browser — no installation, no server, no internet needed!

https://img.shields.io/badge/demo-live-brightgreen
https://img.shields.io/badge/deployed-GitHub%2520Pages-blue
https://img.shields.io/badge/License-MIT-yellow.svg
https://img.shields.io/badge/made%2520with-%E2%9D%A4%EF%B8%8F-red
https://img.shields.io/badge/dependencies-none-brightgreen
https://img.shields.io/badge/works-offline-blue

📊 Quick Overview
Virtual Stats Lab is a self-contained, interactive HTML application that simulates statistical tests in your browser. Like an Arduino circuit simulator for statistics, you can turn knobs, hit RUN, and watch test statistics, p-values, and charts update live.

Perfect for:

📚 Students learning statistics, econometrics, or actuarial science

🎓 Teachers demonstrating statistical concepts in the classroom

🔬 Researchers doing quick data analysis

📈 Data scientists exploring statistical methods

🤖 ML practitioners understanding classification basics

📋 Actuaries practicing reserving and credibility methods

✨ Features
📊 Statistics
Two-Sample Comparison: t-tests, Welch's test, Mann-Whitney U

Regression Analysis: Linear, polynomial, and non-linear fitting

Normality Testing: D'Agostino K² test with visual histograms

ANOVA: One-way analysis of variance with post-hoc comparisons

Chi-Square Tests: Independence testing for contingency tables

Interactive sliders for means, variances, sample sizes

📈 Econometrics
Stationarity Testing: Simplified Dickey-Fuller test

Heteroskedasticity: Breusch-Pagan test with visual fan-shape detection

Spurious Regression Demo: Shows why non-stationary series can't be regressed

VAR Models: Vector Autoregression for multivariate time series

Cointegration: Engle-Granger test for long-run relationships

📋 Actuarial Science
Mortality Studies: Chi-square GOF, SMR with confidence intervals

Credibility Theory: Bühlmann credibility calculator

Claims Reserving: Chain-Ladder method with IBNR estimation

🤖 Machine Learning
Linear Classifier: Logistic regression with decision boundary visualization

Classification Accuracy: Real-time performance metrics

Interactive Parameters: Adjust separation, noise, and sample size

🎮 Interactive Mode
Guided workflow: "What's your question?" → recommended test

Educational explanations with practical examples

Step-by-step learning path

📁 Data Management
Upload CSV/Excel: Load your own data

Random Seed Control: Reproducible simulations

Sample Data Generators: Quick data for each module

Export Results: Copy, download, or export to PDF

Session Management: Save/load settings to browser storage

📚 Tutorials
5 Interactive Tutorials: Step-by-step guided learning

Progress Tracking: See your advancement through each tutorial

Hands-on Exercises: Apply concepts in real-time

🚀 Try It Now
Live Demo
https://YOUR_USERNAME.github.io/virtual-stats-lab/

Quick Start
Open the link above

Choose a tab: Statistics, Econometrics, Actuarial, or Advanced

Adjust the sliders and click RUN

Watch results update in real-time

Try the Interactive Mode for guided analysis

Take a Tutorial to learn step-by-step

🎯 Test Selection Guide
What's Your Question?	Go To	Use Module
Compare two groups?	Statistics	Module 1 — Two-Sample Comparison
Compare three or more groups?	Statistics	Module 4 — ANOVA
Relationship between variables?	Statistics	Module 2 — Regression
Is my data normally distributed?	Statistics	Module 3 — Normality Check
Are categorical variables related?	Statistics	Module 5 — Chi-Square Tests
Is my time series stationary?	Econometrics	Module 1 — Stationarity
Is variance constant?	Econometrics	Module 2 — Heteroskedasticity
Why check stationarity before regression?	Econometrics	Module 3 — Spurious Regression
Do multiple series move together?	Advanced	Module 1 — VAR
Is there a long-run relationship?	Advanced	Module 2 — Cointegration
Can I classify data with ML?	Advanced	Module 3 — Linear Classifier
Is mortality different from the table?	Actuarial	Module 1 — Mortality Study
How credible is a group's experience?	Actuarial	Module 2 — Credibility
How much reserve is needed?	Actuarial	Module 3 — Chain-Ladder
📖 How to Use
For Students
Start with Interactive Mode (🎮 tab)

Answer "What's your question?"

Follow the recommendations

Experiment with the sliders to build intuition

Use tooltips (ⓘ icons) to learn what each parameter means

Take Tutorials for guided learning

For Teachers
Use modules to demonstrate statistical concepts in class

Show how changing parameters affects results

Use spurious regression to warn about common mistakes

Generate sample data for homework assignments

Students can copy results for their reports

Use ANOVA to demonstrate multiple group comparisons

For Researchers
Upload your data via the Data tab

Run appropriate tests

Export all results with one click

Set a random seed for reproducible analysis

Save your session for later

📸 Example Outputs
Two-Sample t-Test
text
[INDEPENDENT T-TEST (equal variance)]
Group A: mean=19.87  sd=4.12  n=20
Group B: mean=24.15  sd=3.98  n=20

t = -3.2345   dof = 38.0   p = 2.43e-3
-> ⚠️ SIGNIFICANT difference between groups
ANOVA
text
ONE-WAY ANOVA
Group 1: mean=15.2  n=30
Group 2: mean=20.1  n=30
Group 3: mean=24.8  n=30

F = 4.567   df1=2   df2=87   p = 0.0123
-> ⚠️ SIGNIFICANT difference between groups

Post-hoc comparisons:
  Group 1 vs Group 3: p=0.008 ⚠️ Significant
  Group 2 vs Group 3: p=0.021 ⚠️ Significant
Logistic Regression (ML)
text
LINEAR CLASSIFIER
Class 0: mean=-1.0, n=50
Class 1: mean=1.0, n=50

Accuracy: 92.0%
Decision boundary: x = 0.08

✅ Model successfully separates the two classes!
Chain-Ladder Reserve
text
CHAIN-LADDER DEVELOPMENT FACTORS
  0 -> 1:  1.5432
  1 -> 2:  1.1234
  2 -> 3:  1.0567
  3 -> 4:  1.0234
  4 -> 5:  1.0045

TOTAL IBNR RESERVE: 13,222
💻 Local Development
Option 1: Download and Open
bash
# Download the file
curl -O https://raw.githubusercontent.com/YOUR_USERNAME/virtual-stats-lab/main/index.html

# Open in your browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
Option 2: Clone the Repository
bash
git clone https://github.com/YOUR_USERNAME/virtual-stats-lab.git
cd virtual-stats-lab
open index.html
Option 3: Run a Local Server (Optional)
bash
# Python 3
python -m http.server 8000

# Node.js
npx serve

# Then open http://localhost:8000
📁 File Structure
text
virtual-stats-lab/
├── index.html          # Single self-contained application (~120KB)
├── README.md           # This documentation
├── LICENSE             # MIT License
└── CNAME               # Custom domain (optional)

Total: ~120KB — No dependencies, no build step, no server required!
🔧 Technical Details
Built With
Pure HTML5 — No frameworks

Vanilla CSS — Custom dark theme with responsive design

Pure JavaScript — All statistical calculations from scratch

Canvas API — Real-time plotting

Statistical Methods Implemented
Parametric Tests: t-tests (independent, Welch's), ANOVA, linear regression

Non-Parametric Tests: Mann-Whitney U, Kruskal-Wallis (planned)

Time Series: ADF test, VAR, cointegration

Categorical: Chi-square tests for independence

Survival Analysis: Kaplan-Meier (planned)

Machine Learning: Logistic regression from scratch

Actuarial: SMR, Credibility, Chain-Ladder

Distribution Fitting: Normality tests, goodness-of-fit

Browser Support
✅ Chrome 60+

✅ Firefox 55+

✅ Safari 12+

✅ Edge 79+

✅ Opera 47+

✅ Mobile browsers

🎓 Educational Resources
Built-in Learning Aids
Tooltips (ⓘ icons) — Explanations for every parameter

Interactive Mode — Guided workflow for beginners

Status Indicators — Real-time feedback on results

Sample Data — Pre-built datasets for each module

Educational Output — Explanations of what results mean

Tutorials — Step-by-step guided learning

Session Save — Continue learning where you left off

Teaching Applications
Concept	Module	Learning Outcome
Statistical Power	Two-Sample	See how n affects p-values
Type I/II Errors	Two-Sample	Observe significance at different α
Overfitting	Regression	Compare R² with different degrees
Normality	Normality	See how distributions differ
ANOVA	ANOVA	Understand F-test and post-hoc comparisons
Chi-Square	Chi-Square	Learn categorical data analysis
Stationarity	ADF	Understand unit roots
Spurious Regression	Spurious Demo	Learn why to check stationarity
VAR	Advanced	Understand multivariate dynamics
Cointegration	Advanced	Learn long-run relationships
ML Classification	Advanced	Introduction to supervised learning
Reserving	Chain-Ladder	Understand IBNR estimation
Credibility	Credibility	See how Z-scores blend experience
🤝 Contributing
Contributions are welcome! Here's how:

Fork the repository

Create a branch (git checkout -b feature/amazing-feature)

Make your changes

Commit (git commit -m 'Add amazing feature')

Push (git push origin feature/amazing-feature)

Open a Pull Request

Ideas for Contributions
Add more statistical tests (Kruskal-Wallis, Friedman, etc.)

Improve visualizations (3D plots, interactive heatmaps)

Add more ML algorithms (SVM, decision trees)

Add more actuarial methods (Mack method, bootstrap)

Support more data formats (JSON, Parquet)

Add R-like statistical summaries

Localization to other languages

📄 License
MIT License — Use it anywhere, for anything, with attribution.

text
Copyright (c) 2024 Virtual Stats Lab

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
🙏 Acknowledgments
Built with ❤️ for the statistical community.

Inspired by:

Statsmodels, SciPy, and NumPy — The Python statistical ecosystem

R and RStudio — Interactive statistical computing

Desmos — Interactive graphing

Arduino Simulator — The "turn knobs, see results" paradigm

Khan Academy — Interactive learning approach

Special thanks to:

Students and teachers who provided feedback

The open-source statistical community

GitHub Pages for free hosting

📞 Support
Issue	Where to Go
Bug Report	Open an Issue
Feature Request	Open an Issue
Usage Question	Use the Interactive Mode in the app
Documentation	Read this README
Live Demo	Click Here
🚀 Quick Deploy
Deploy to GitHub Pages
bash
# 1. Create a repository
# 2. Upload index.html
# 3. Enable GitHub Pages in Settings
# 4. Your lab is live!
Deploy to Netlify (Drag & Drop)
Go to netlify.com

Drag index.html onto the dashboard

Get a URL instantly

Deploy to Vercel (Git Integration)
Go to vercel.com

Import your GitHub repository

Automatically deploys on every push

🏆 Badges
Add these badges to your README:

markdown
[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://YOUR_USERNAME.github.io/virtual-stats-lab/)
[![GitHub Pages](https://img.shields.io/badge/deployed-GitHub%20Pages-blue)](https://pages.github.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with ❤️](https://img.shields.io/badge/made%20with-❤️-red)](https://github.com/)
[![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)]()
[![Works Offline](https://img.shields.io/badge/works-offline-blue)]()
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)]()
[![Machine Learning](https://img.shields.io/badge/ML-ready-orange)]()
[![Econometrics](https://img.shields.io/badge/Econometrics-ready-blue)]()
[![Actuarial](https://img.shields.io/badge/Actuarial-ready-green)]()
📊 Project Statistics
Metric	Value
File Size	~120KB
Lines of Code	~3,500
Number of Tests	15+
Tutorials	5
Dependencies	0
Browser Support	All modern browsers
Offline Support	✅ Yes
Session Storage	✅ Yes
PDF Export	✅ Yes
GitHub Pages	✅ Yes
Cost	Free
🗺️ Roadmap
✅ Completed
☑ Statistics modules (5)
☑ Econometrics modules (3)
☑ Actuarial modules (3)
☑ Advanced modules (3: VAR, Cointegration, ML)
☑ Interactive mode
☑ Data import (CSV/Excel)
☑ Export results (Copy, Download, PDF)
☑ Random seed control
☑ Tooltips
☑ Sample data generators
☑ Session management
☑ Mobile-optimized view
☑ Tutorials (5)
🚧 In Progress
□ More distribution types (Beta, Gamma, Weibull)
□ Kruskal-Wallis test
□ Friedman test
□ Mack method for reserving uncertainty
🔮 Future Plans
□ Two-way ANOVA
□ Mixed effects models
□ Time series forecasting (ARIMA)
□ Survival analysis (Kaplan-Meier)
□ Principal Component Analysis (PCA)
□ Clustering (k-means)
□ More ML algorithms (kNN, SVM)
□ Collaboration features (share sessions)
□ Interactive 3D plots
□ R/Python code export
□ API mode for external use
📝 Changelog
v2.0.0 (Current)
New Modules: ANOVA, Chi-Square, VAR, Cointegration, ML Classifier

New Features: Session save/load, PDF export, Tutorials

Improvements: Mobile optimization, more distribution types

UI: Enhanced tooltips, better responsive design

v1.0.0
Initial release

9 core modules

Interactive mode

Data import/export

Random seed control

🤝 Contributors
Your Name — Creator and maintainer

📧 Contact
GitHub: @YOUR_USERNAME

Email: your.email@example.com

Issues: Report here

Made with ❤️ for the statistical community

⭐ Star This Project
If you find this useful, please star the repository on GitHub!

https://img.shields.io/github/stars/201600773/virtual-stats-lab?style=social

🎓 Citation
If you use Virtual Stats Lab in your teaching or research, please cite:

text
Virtual Stats Lab (Version 2.0). (2024). 
Retrieved from https://github.com/201600773/virtual-stats-lab
📖 Quick Reference
Module	Tab	Description
1	Statistics	Two-Sample Comparison
2	Statistics	Regression Analysis
3	Statistics	Normality Check
4	Statistics	One-Way ANOVA
5	Statistics	Chi-Square Tests
1	Econometrics	Stationarity (ADF)
2	Econometrics	Heteroskedasticity
3	Econometrics	Spurious Regression
1	Actuarial	Mortality Study
2	Actuarial	Credibility
3	Actuarial	Chain-Ladder
1	Advanced	VAR (Time Series)
2	Advanced	Cointegration
3	Advanced	ML Classifier
Happy Analyzing! 🎉
