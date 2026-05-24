
---

### 2. GenMed_LLM README.md

```markdown
<div align="center">
  <h1>GenMed_LLM</h1>
  <h3>Fine-tuned GPT-2 for Healthcare — Physician-Quality Medical Guidance</h3>
</div>

---

**Re-implemented GPT-2 from scratch in PyTorch and fine-tuned it on a curated medical dataset** to generate coherent, domain-specific healthcare responses.

### 🎯 Project Goal
Create a small but powerful domain-specific LLM capable of giving high-quality medical guidance that outperforms zero-shot baselines.

### 🔧 What I Built
- Re-implemented full GPT-2 architecture (from scratch) in PyTorch
- Integrated pre-trained weights
- Fine-tuned on carefully curated medical dataset
- Achieved **domain-specific coherence** and significantly better performance than zero-shot prompting

### 🛠️ Tech Stack
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97_Hugging_Face-FFD21E?style=for-the-badge)
Transformers • GPT-2 Medium

### 📁 Project Structure
- `index.ipynb` → Full fine-tuning + evaluation notebook
- `med_data.jsonl` → Curated medical training data
- `gpt_download3.py` → Weight downloading script

### 🚀 How to Run
```bash
git clone https://github.com/NajeebAhmad00/GenMed_LLM.git
cd GenMed_LLM
jupyter notebook index.ipynb
```

### 📈 Results
- Produced physician-quality responses on held-out healthcare prompts
- Measurable improvement over zero-shot baseline in domain coherence and relevance
