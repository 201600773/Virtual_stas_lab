Virtual Stats Lab
Interactive Statistics · Econometrics · Actuarial Science Lab
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

🤖 Anyone who wants to understand statistical tests interactively

✨ Features
📊 Statistics
Two-Sample Comparison: t-tests, Welch's test, Mann-Whitney U

Regression Analysis: Linear, polynomial, and non-linear fitting

Normality Testing: D'Agostino K² test with visual histograms

Interactive sliders for means, variances, sample sizes

📈 Econometrics
Stationarity Testing: Simplified Dickey-Fuller test

Heteroskedasticity: Breusch-Pagan test with visual fan-shape detection

Spurious Regression Demo: Shows why non-stationary series can't be regressed

📋 Actuarial Science
Mortality Studies: Chi-square GOF, SMR with confidence intervals

Credibility Theory: Bühlmann credibility calculator

Claims Reserving: Chain-Ladder method with IBNR estimation

🎮 Interactive Mode
Guided workflow: "What's your question?" → recommended test

Educational explanations with practical examples

Step-by-step learning path

📁 Data Management
Upload CSV/Excel: Load your own data

Random Seed Control: Reproducible simulations

Sample Data Generators: Quick data for each module

Export Results: Copy or download all results

🚀 Try It Now
Live Demo
https://YOUR_USERNAME.github.io/virtual-stats-lab/

Quick Start
Open the link above

Choose a tab: Statistics, Econometrics, or Actuarial

Adjust the sliders and click RUN

Watch results update in real-time

Upload your own data or use the Interactive Mode

🎯 Test Selection Guide
What's Your Question?	Go To	Use Module
Compare two groups?	Statistics	Module 1 — Two-Sample Comparison
Relationship between variables?	Statistics	Module 2 — Regression
Is my data normally distributed?	Statistics	Module 3 — Normality Check
Is my time series stationary?	Econometrics	Module 1 — Stationarity
Is variance constant?	Econometrics	Module 2 — Heteroskedasticity
Why check stationarity before regression?	Econometrics	Module 3 — Spurious Regression
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

For Teachers
Use modules to demonstrate statistical concepts in class

Show how changing parameters affects results

Use spurious regression to warn about common mistakes

Generate sample data for homework assignments

Students can copy results for their reports

For Researchers
Upload your data via the Data tab

Run appropriate tests

Export all results with one click

Set a random seed for reproducible analysis

📸 Screenshots
Two-Sample t-Test
text
[INDEPENDENT T-TEST (equal variance)]
Group A: mean=19.87  sd=4.12  n=20
Group B: mean=24.15  sd=3.98  n=20

t = -3.2345   dof = 38.0   p = 2.43e-3
-> ⚠️ SIGNIFICANT difference between groups
Regression Fit
text
TRUE SHAPE: quadratic   FIT DEGREE: 2
n=40  noise=1.5

fitted: y = 0.603·x² - 6.045·x + 20.567
R² = 0.9432

✅ Good fit: the polynomial captures the true shape well.
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
├── index.html          # Single self-contained application
├── README.md           # This documentation
├── LICENSE             # MIT License
└── CNAME               # Custom domain (optional)

Total: ~85KB — No dependencies, no build step, no server required!
🔧 Technical Details
Built With
Pure HTML5 — No frameworks

Vanilla CSS — Custom dark theme with responsive design

Pure JavaScript — All statistical calculations from scratch

Canvas API — Real-time plotting

Statistical Methods Implemented
t-tests (independent, Welch's)

Mann-Whitney U test

Linear regression with R²

Polynomial regression (degree 1-4)

D'Agostino K² normality test

Simplified Dickey-Fuller test

Breusch-Pagan heteroskedasticity test

Chi-square goodness-of-fit

Standardized Mortality Ratio (SMR)

Bühlmann credibility

Chain-Ladder reserving

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

Teaching Applications
Concept	Module	Learning Outcome
Statistical Power	Two-Sample	See how n affects p-values
Type I/II Errors	Two-Sample	Observe significance at different α
Overfitting	Regression	Compare R² with different degrees
Normality	Normality	See how distributions differ
Stationarity	ADF	Understand unit roots
Spurious Regression	Spurious Demo	Learn why to check stationarity
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
Add more statistical tests (ANOVA, chi-square, etc.)

Improve visualizations

Add more sample data generators

Translate to other languages

Add dark/light theme toggle

Mobile app version

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
📊 Project Statistics
Metric	Value
File Size	~85KB
Lines of Code	~2,500
Number of Tests	10+
Dependencies	0
Browser Support	All modern browsers
Offline Support	✅ Yes
GitHub Pages	✅ Yes
Cost	Free
🎯 Roadmap
✅ Completed
☑ Statistics modules (3)
☑ Econometrics modules (3)
☑ Actuarial modules (3)
☑ Interactive mode
☑ Data import (CSV/Excel)
☑ Export results
☑ Random seed control
☑ Tooltips
☑ Sample data generators
🚧 In Progress
□ ANOVA module
□ Chi-square tests
□ More distribution types
□ Mobile-optimized view
🔮 Future Plans
□ User accounts (save sessions)
□ Export to PDF/CSV
□ More advanced econometrics (VAR, cointegration)
□ Machine learning basics (linear classifiers)
□ Interactive tutorials
📝 Changelog
v1.0.0 (Current)
Initial release

9 core modules

Interactive mode

Data import/export

Random seed control

Full documentation

🤝 Contributors
Your Name — Creator and maintainer

📧 Contact
GitHub: @201600773

Email: your.email@example.com

Made with ❤️ for the statistical community

⭐ Star This Project
If you find this useful, please star the repository on GitHub!

https://img.shields.io/github/stars/201600773/virtual-stats-lab?style=social

🎓 Citation
If you use Virtual Stats Lab in your teaching or research, please cite:

text
Virtual Stats Lab (Version 1.0). (2024). 
Retrieved from https://github.com/201600773/virtual-stats-lab
