# Project 1 – Password Strength Analyzer + Claude Explainer

Interactive password strength checker using `zxcvbn` for entropy/pattern analysis + Anthropic Claude for factual, professional-strength reports.

## Features
- Real-time scoring (0–4) and offline crack-time estimation
- Visual strength bar
- Weakness detection + suggestions
- Neutral, technical AI-generated analysis report

## Files in this folder
- `password_strength_analyzer.ipynb`          → Main Jupyter notebook
- `Password Strength Analyzer NonTechnical.pdf` → Beginner-friendly explanation
- `Password Strength Analyzer Technical.pdf`   → Detailed technical brief

## How to run
1. Activate environment: `conda activate cyber-llm`
2. Launch Jupyter: `jupyter notebook`
3. Open `password_strength_analyzer.ipynb`
4. Make sure `.env` exists in the project root with your Anthropic API key

## Demo Screenshots

**Strong Passphrase Example** (Score 4/4, centuries to crack):
![Strong Password Demo](docs/screenshots/project1_demo_strong_passphrase.png)

**Weak Common Password Example** (Score 0/4, instant crack):
![Weak Password Demo](docs/screenshots/project1_demo_weak_common_password.png)

Created by Robert Gravelle  
January 2026