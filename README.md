# Hi, I'm Daksh

Machine Learning Engineer working on **computer vision** and **explainable AI**. First-Class Physics,
then an MSc in Data Science & AI (Distinction).

I care less about which model wins a benchmark and more about why one fails in production — which is
why most of my work ends up in the space between deep learning and classical CV, or between a model
and the person who has to trust it.

---

### What I'm working on

- **Sports computer vision** — detection, tracking, pitch-line segmentation and OCR over match
  footage. The interesting problem was domain shift: when the model moved from football to hockey it
  broke, so I built a hybrid system that falls back to classical CV (background subtraction, Hough
  transforms) wherever deep learning stops being reliable.
- **Explainable AI & sequence modelling** — MSc dissertation benchmarked XGBoost, Random Forest, SVM
  and a Swin Transformer on ~38,000 cricket deliveries with SHAP attribution. Continuing with my
  supervisor: LSTM, BiLSTM, GRU and CNN models with attention pooling across 5/10/15-ball contexts,
  towards a paper.
- **Agentic engineering** — I build with AI agents as a tool, and I refactor what they produce until
  it's something a team could maintain.

---

### Selected projects

| Project | What it is | Stack |
|---|---|---|
| [Sports-Analytics](https://github.com/Dash3210/Sports-Analytics) | End-to-end CV pipeline for sports footage: detection, tracking, segmentation, jersey OCR | Python, PyTorch, YOLOv11, OpenCV, EasyOCR |
| *Cricket XAI (dissertation)* | XGBoost/RF/SVM + Swin Transformer benchmark on ~38k deliveries, with SHAP attribution | scikit-learn, XGBoost, PyTorch, SHAP |
| *Cricket sequence modelling* | LSTM / BiLSTM / GRU / CNN with attention pooling, 5/10/15-ball contexts, vs CatBoost/LightGBM (paper in prep) | PyTorch, attention, SHAP |
| *Medical image classification* | ResNet / DenseNet / Swin benchmark on a 7-class white blood cell task | PyTorch |
| *FairRide* | On-chain ridesharing: real-time reverse auction in Solidity on 300ms blocks | Solidity, Monad |

*Repos for the last three are being prepared for release — this table will be updated as they land.*

---

### Toolkit

`Python` · `PyTorch` · `OpenCV` · `YOLO` · `SHAP` · `pandas` · `SQL (PostgreSQL, MySQL)` ·
`MongoDB` · `AWS (SageMaker, S3)` · `Docker` · `Git LFS` · `Power BI`

---

### Currently

- Building a multi-ATS job application autofiller (Workday, Greenhouse, Lever) — reverse-engineering
  the interaction model, then writing my own.
- Open to **Machine Learning Engineer / Data Scientist / Computer Vision** roles in London.
  Full right to work in the UK, no sponsorship needed.

📫 [LinkedIn](https://www.linkedin.com/in/daksh-shah-24a4b9279) · dakshshah3210@gmail.com
