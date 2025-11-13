# 📘 Google-Classroom-Extended-TAM 
---

## 🌟 Model Badges (Các mô hình sử dụng)

![TAM](https://img.shields.io/badge/Model-TAM-blue?style=flat-square)
![ExtendedTAM](https://img.shields.io/badge/Model-Extended%20TAM-green?style=flat-square)
![PLSSEM](https://img.shields.io/badge/Method-PLS--SEM-orange?style=flat-square)
![SmartPLS](https://img.shields.io/badge/Tool-SmartPLS%204-purple?style=flat-square)

![CSE](https://img.shields.io/badge/Variable-CSE-brightgreen?style=flat-square)
![PEOU](https://img.shields.io/badge/Variable-PEOU-blue?style=flat-square)
![PU](https://img.shields.io/badge/Variable-PU-yellow?style=flat-square)
![ATT](https://img.shields.io/badge/Variable-ATT-red?style=flat-square)
![BI](https://img.shields.io/badge/Variable-BI-pink?style=flat-square)
![AU](https://img.shields.io/badge/Variable-AU-darkgreen?style=flat-square)

![SN](https://img.shields.io/badge/Variable-SN-teal?style=flat-square)
![IMG](https://img.shields.io/badge/Variable-IMG-lightgrey?style=flat-square)
![JR](https://img.shields.io/badge/Variable-JR-brown?style=flat-square)
![OQ](https://img.shields.io/badge/Variable-OQ-orange?style=flat-square)
![RD](https://img.shields.io/badge/Variable-RD-purple?style=flat-square)
![PR](https://img.shields.io/badge/Variable-PR-black?style=flat-square)
![TT](https://img.shields.io/badge/Variable-TT-indigo?style=flat-square)

---

## 📌 Overview (Tổng quan)

This project analyzes the **factors influencing students’ intention and actual use of Google Classroom**, based on the **Extended Technology Acceptance Model (TAM)**.  
*(Dự án phân tích các yếu tố ảnh hưởng đến ý định và hành vi sử dụng Google Classroom của sinh viên dựa trên mô hình TAM mở rộng.)*

Data were collected from **155 students** and analyzed using **PLS-SEM** via **SmartPLS 4.0**.  
*(Dữ liệu gồm 155 sinh viên, phân tích bằng PLS-SEM trên SmartPLS 4.0.)*

The model includes **13 hypotheses**, of which **11 were supported**.

---

## 🧩 Model Components (Các biến trong mô hình)

### **Core TAM Variables**
- **PEOU – Perceived Ease of Use** *(Cảm nhận dễ sử dụng)*
- **PU – Perceived Usefulness** *(Cảm nhận hữu ích)*
- **ATT – Attitude Toward Use** *(Thái độ sử dụng)*
- **BI – Behavioral Intention** *(Ý định hành vi)*
- **AU – Actual Use** *(Hành vi sử dụng thực tế)*

### **Extended Variables**
- **CSE – Computer Self-Efficacy** *(Tự tin vào kỹ năng công nghệ)*
- **PR – Perceived Risk** *(Rủi ro cảm nhận)*
- **SN – Social Influence** *(Ảnh hưởng xã hội)*
- **TT – Trust in Technology** *(Niềm tin công nghệ)*
- **JR – Job Relevance** *(Mức độ liên quan học tập)*
- **IMG – Self-Image** *(Hình ảnh bản thân)*
- **RD – Result Demonstrability** *(Hiệu quả hiển thị)*
- **OQ – Output Quality** *(Chất lượng đầu ra)*

---

## 📊 Research Methodology (Phương pháp nghiên cứu)

- **Approach:** Quantitative  
  *(Phương pháp: Định lượng)*  
- **Technique:** PLS-SEM  
  *(Kỹ thuật: Mô hình cấu trúc bình phương nhỏ nhất từng phần)*  
- **Tool:** SmartPLS 4.0  
- **Sample:** 155 respondents *(155 mẫu khảo sát)*  
- **Scale:** Likert 1–5  
- **Analysis steps:**  
  - Measurement Model (Outer Model)  
  - Structural Model (Inner Model)  
  - Reliability Evaluation (CA, CR, AVE)  
  - Discriminant Validity (HTMT)  
  - R², f², Q², VIF  

---

## 📈 Key Results (Kết quả nổi bật)

### ✔ **Supported Hypotheses: 11/13**
- **CSE → PEOU** (Strong positive)  
- **JR → PU**, **OQ → PU**, **RD → PU**, **SN → PU**  
- **PU → ATT**, **PR → ATT (negative)**  
- **TT → ATT**, **ATT → BI**, **BI → AU**

### ❌ **Not Supported**
- **PEOU → ATT**  
- **TT → BI**

### 🔥 Strongest Effects  
- **BI → AU (β = 0.638)**  
- **ATT → BI (β = 0.562)**  

Meaning:  
> *Behavioral Intention strongly predicts Actual Use*  
> *(Ý định hành vi là yếu tố quyết định mạnh nhất dự báo hành vi thực tế.)*

---

## 🆚 Comparison Table (Bảng so sánh TAM – Extended TAM – UTAUT)

| Model | Core Variables | Strengths | Limitations |
|------|----------------|-----------|-------------|
| **TAM** | PU, PEOU → ATT → BI | Simple, widely used (Đơn giản, phổ biến) | Limited in social/psychological factors |
| **Extended TAM (This Study)** | PU, PEOU + CSE, SN, PR, TT, JR, OQ, RD | Strong explanatory power (Giải thích mạnh), phù hợp giáo dục VN | More complex model |
| **UTAUT** | PE, EE, SI, FC | Covers behavior & environment | Requires larger samples |

---

## 📊 Model Performance (Độ phù hợp mô hình)

### **R² Values**
| Variable | R² | Interpretation (Ý nghĩa) |
|---------|-----|--------------------------|
| **PU** | 0.591 | Strong |
| **ATT** | 0.422 | Moderate |
| **AU** | 0.407 | Moderate |
| **BI** | 0.349 | Moderate |
| **PEOU** | 0.221 | Weak |

### **f² Effect Size**
- **Large:** BI → AU, ATT → BI  
- **Medium:** CSE → PEOU, PR → ATT, JR → PU  
- **Small:** RD → PU, OQ → PU, SN → PU, TT → ATT  

---

## 🔍 Interpretation (Diễn giải)

- Students with higher **technological confidence (CSE)** perceive Google Classroom easier to use.  
- **Perceived Risk (PR)** negatively affects attitude.  
- **Behavioral Intention (BI)** is the strongest predictor of actual use.  
- **Trust (TT)** slightly affects attitude but **does not** directly affect behavioral intention.

---

## 📚 Citation (Trích dẫn)

Mai Thanh Phúc, Hoàng Thị Yến Nhi, Trần Trọng Thành, Lê Nhật Tùng.
Analysis of Factors Affecting Students’ Intention and Actual Use of Google Classroom Using Extended TAM Model.

---
## 👨‍💻 Authors (Tác giả)

- **Mai Thanh Phúc**
- **Hoàng Thị Yến Nhi**
- **Trần Trọng Thành**
- **Supervisor:** Lê Nhật Tùng

---
