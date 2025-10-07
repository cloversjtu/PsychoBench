# 🧠 PsychoBench Dataset (Partial Release)

## Overview
**PsychoBench** is a benchmark dataset designed to evaluate the **psychological intelligence** of Large Language Models (LLMs).  
The dataset is inspired by the **U.S. National Counselor Examination (NCE)** — a professional licensure exam for counselors — and aims to assess whether LLMs possess the psychological knowledge and reasoning abilities required for counseling-related tasks.

This repository provides a **partial release** of the PsychoBench dataset.  
The **full dataset** will be publicly released after the acceptance of the associated research paper.


---

## 📘 Dataset Description

- **Total questions (full version):** 2,252  
- **Current release:** Partial subset  
- **Format:** Multiple-choice (single correct answer: A/B/C/D)  
- **Language:** English  

Each entry follows this structure:

```json

 {
    "id": 3,
    "question": "An individual's self-esteem is most likely to improve when they credit their success to which of the following?",
    "options": {
      "a": "Factors within themselves",
      "b": "Factors outside themselves",
      "c": "Indirect factors",
      "d": "Random factors",
      "e": "Unstable factors"
    },
    "answer": "a"
  }

```

---



## 🪪 License: CC-BY-NC-ND 4.0


This dataset is released under the **CC BY-NC-ND 4.0** license.  
You are **free to share** — copy and redistribute the material in any medium or format — **under the following terms:**

| Condition | Description |
|------------|-------------|
| 🏷️ **Attribution** | You must give appropriate credit, provide a link to the license, and indicate if changes were made. |
| 💼 **NonCommercial** | You may not use the material for commercial purposes. |
| ⚙️ **NoDerivatives** | You may not remix, transform, or build upon the material. |
| 🚫 **No additional restrictions** | You may not apply legal or technological measures that restrict others from doing anything the license permits. |

📘 **Full license text:**  
[Creative Commons CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)

---




---
## 📄 Citation

If you use this dataset in your research, please cite:

```bibtex

@article{zeng2025pychobench,
  title={PsychoBench: Evaluating the Psychology Intelligence of Large Language Models},
  author={Zeng, Min},
  journal={arXiv preprint arXiv:2510.01611},
  year={2025}
}

