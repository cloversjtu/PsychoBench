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



## 🪪 License: CC-BY-NC-ND

This dataset is licensed under the **Creative Commons Attribution–NonCommercial–NoDerivatives International License**.

You are free to:
- **Share** — copy and redistribute the material in any medium or format.

Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.  
- **NonCommercial** — You may not use the material for commercial purposes.  
- **NoDerivatives** — If you remix, transform, or build upon the material, you may not distribute the modified material.  
- **No additional restrictions** — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

To view a copy of this license, visit:  
🔗 [https://creativecommons.org/licenses/by-nc-nd/4.0/](https://creativecommons.org/licenses/by-nc-nd/4.0/)
