# Jordan Allred — Data Scientist & React tinkerer

Hi — I'm Jordan. I build reliable, reproducible classical machine learning systems in Python and ship them with Docker. Lately I've been expanding into React for lightweight web UIs and demos.

[Website — contact form](https://jordanallred.dev)

- 🔬 Focus: classical ML (scikit-learn, feature engineering, model validation)
- 🐍 Primary language: Python
- 🐳 Deployment: Docker / docker-compose
- ⚛️ Frontend: React (Vite)
- ☁️ Interests: model reproducibility, lightweight inference APIs, pragmatic MLOps
- 👪 Fun fact: I'm a triplet

## About me
I enjoy turning data into reliable predictions and shipping them in a maintainable way. My work emphasizes solid validation, clear data contracts, and repeatable environments (tests + containers). On the front end I favor small, focused React apps for demos and tooling.

## Skills & tools
- Modeling: scikit-learn, statsmodels, feature engineering, cross-validation, hyperparameter tuning
- Data: pandas, numpy, SQL
- Deployment & infra: Docker, docker-compose, basic CI, REST APIs (FastAPI)
- Languages: Python, JavaScript (React)
- Testing & reproducibility: unit & integration tests, deterministic pipelines, reproducible envs

## Typical project structure
- model training & experiments in Python (notebooks or scripts)
- model export (joblib / ONNX / well-documented artifact)
- small FastAPI service that loads the artifact and exposes /predict
- lightweight React frontend for demos, wired in docker-compose for local runs

## Featured projects
- Live Object Detection — real-time object detection demo and utilities  
  https://github.com/jordanallred/Live-Object-Detection

- Rock Paper Scissors — an interactive demo/game (frontend + optional model or logic)  
  https://github.com/jordanallred/rock-paper-scissors

- Friend — tooling / demo project (see repo for README and live/demo notes)  
  https://github.com/jordanallred/friend

## Model card (example)
- Model type: classical classifier / regressor (scikit-learn)
- Dataset: short description + link
- Evaluation: primary metrics (AUC, RMSE, calibration)
- Limitations: known biases, small sample issues
- Intended use: production inference for X; not to be used for Y

## Badges & status (examples)
- CI: ![build](https://img.shields.io/badge/build-passing-brightgreen)
- Coverage: ![coverage](https://img.shields.io/badge/coverage-90%25-blue)
- Add GitHub Readme Stats: https://github-readme-stats.vercel.app

## Resume & contact
- Website & contact form: https://jordanallred.dev
