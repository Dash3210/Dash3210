# Daksh Shah

**Machine Learning Engineer** - computer vision, explainable AI, and the engineering that makes a
model survive contact with real data.

First-Class Physics, then an MSc in Data Science & AI (Distinction). I care less about which model
wins a benchmark than about why one fails when the data moves underneath it.

---

## Currently building: gridcast

A forecasting service for Great Britain's half-hourly **grid carbon intensity**: daily 48-hour
forecasts, a CI accuracy gate, and a public scoreboard that measures it against the National Energy
System Operator's own forecast.

![Nightly forecast and scoreboard](https://github.com/Dash3210/gridcast/actions/workflows/nightly.yml/badge.svg)

- **Catches its own leakage.** Every feature is built only from what existed at the issue instant,
  with a test that fails when future data leaks in - and mutants that prove the test has teeth.
- **Frozen evaluation.** 15 origins, 1,440 scored periods, pinned to a committed fixture so a
  published number cannot drift as the archive is revised underneath it.
- **Publishes where it loses.** The scoreboard reports the operator's forecast beside the model's,
  including the horizons where the operator is plainly better.

**[gridcast](https://github.com/Dash3210/gridcast)**

---

## Selected work

| Project | What it is | Stack |
|---|---|---|
| [gridcast](https://github.com/Dash3210/gridcast) | 48-hour grid carbon-intensity forecast service: CI accuracy gate, public scoreboard, containerised | Python, FastAPI, LightGBM, Docker, GitHub Actions |
| [Sports-Analytics](https://github.com/Dash3210/Sports-Analytics) | End-to-end CV pipeline over match footage: detection, tracking, pitch-line segmentation, jersey OCR, and a hybrid deep + classical fallback for domain shift | PyTorch, YOLOv11, ByteTrack, OpenCV, EasyOCR |
| [Cryptogame](https://github.com/Dash3210/Cryptogame) | Cross-platform cryptogram puzzle app: 12 subject archives, daily cipher, timed mode, coin economy, 24 test suites | React Native, TypeScript (strict), Jest |
| **Cricket outcome modelling** *(MSc dissertation)* | XGBoost, Random Forest, SVM and Swin Transformer over ~38,000 deliveries, with SHAP attribution and a deliberately modest, defended result | scikit-learn, XGBoost, PyTorch, SHAP |
| **Cricket sequence modelling** *(research, paper in prep)* | LSTM, BiLSTM, GRU and CNN with attention pooling across 5/10/15-ball contexts, benchmarked against gradient-boosted baselines | PyTorch |
| **Medical image classification** | ResNet18/50, DenseNet121 and Swin benchmark on a 7-class white blood cell task | PyTorch |
| **FairRide** | On-chain ridesharing: real-time reverse auction in Solidity on 300ms blocks, built in seven hours at Monad Blitz London | Solidity, Monad |

---

## How I work

- **Leakage first.** Projects open with a failing test for leakage, not a model. Most forecasting
  work leaks at the seam between issue time, arrival time and serving time, and cannot prove it does
  not.
- **A check that can pass for the wrong reason is not a check.** Every guard gets a mutant: if
  deliberately breaking the thing does not turn the suite red, the guard was decoration.
- **Publish the honest number.** Frozen evaluation, versioned fixtures, and results that survive being
  re-run a week later.

---

## Toolkit

`Python` / `PyTorch` / `OpenCV` / `YOLO` / `scikit-learn` / `XGBoost` / `LightGBM` / `SHAP` /
`FastAPI` / `Docker` / `GitHub Actions` / `SQL (PostgreSQL, MySQL)` / `MongoDB` /
`AWS (SageMaker, S3)` / `Power BI` / `TypeScript`

---

## Open to

**Machine Learning Engineer, Data Scientist and Computer Vision Engineer** roles in London.
Full right to work in the UK - no sponsorship required.

[LinkedIn](https://www.linkedin.com/in/daksh-shah-24a4b9279) / dakshshah3210@gmail.com
