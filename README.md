# 🧠 Predicting Online Social Support

> BERT + LLM Feature Engineering  
> Score prediction (0–2) for Emotional / Informational Support  
> (Two independent BERT models: emt / inf)

---

## 📌 Overview

이 프로젝트는 온라인 커뮤니티 게시글/댓글을 기반으로

- **감정적 지원 (Emotional Support, emt)**  
- **정보적 지원 (Informational Support, inf)**  

각각의 **지원 정도(0, 1, 2 점수)** 를 예측하는 NLP 모델입니다.

---

## ✨ Key Features

| 항목 | 설명 |
|------|------|
| **LLM 기반 Feature Engineering** | 게시글을 LLM에 전달하여 신호를 추출 (“조언 요청 / 감정 표현 / 해결책 요청 등”) |
| **BERT Score Prediction** | feature 텍스트를 입력으로 score 예측 |
| **두 개의 독립 모델** | 감정(emotional), 정보(informational) 각각 별도 학습 |
| **Ordinal / Multi-class (0‧1‧2)** | 점수 예측 문제에 최적화된 방식 |

---

## 🛠 Tech Stack

- Python, Pandas, Scikit-learn
- HuggingFace Transformers
- BERT
- OpenAI / LLM API (prompt 기반 feature 생성)

---

## 🚀 Code Overview
```
predicting-online-social-support/
 predicting-online-social-support
├─ notebook/
│  ├─ final_prompt.ipynb     # LLM Prompt → feature 생성
│  └─ final_model.ipynb      # BERT 기반 점수 예측 (inf/emt)
├─ README.md
└─ .gitignore
```
---

📧 Contact: qkrek921@naver.com

