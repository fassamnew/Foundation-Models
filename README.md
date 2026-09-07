# Foundation Models in Practice

**Lecture 3 — Live demonstration and guided lab**  
**Presenter:** Dr. Fitsum Assamnew Andargie  
**Environment:** Google Colab + Hugging Face

This repository hosts the workshop notebook:

**Foundation Models in Practice: From Language to Science with Hugging Face**

> **Central question:** What makes a model a foundation model, and how can the same foundation-model idea be used across language, biology, vision, and Earth observation?

---

## What to do next (participants)

### 1. Open the notebook in Google Colab

Use either the badge or the link below. Both open a **personal Colab copy** of the notebook. Your edits stay in your own Colab / Google Drive session and are **not** written back to this repository.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fassamnew/Foundation-Models/blob/africa-workshop/Foundation_Models_in_Practice_Africa_Workshop.ipynb)

**Click here:** [Open the workshop notebook in Google Colab](https://colab.research.google.com/github/fassamnew/Foundation-Models/blob/africa-workshop/Foundation_Models_in_Practice_Africa_Workshop.ipynb)

### 2. Enable a GPU (recommended)

In Colab:

1. **Runtime → Change runtime type**
2. Set **Hardware accelerator** to a GPU (often **T4 GPU**)
3. Click **Save**

Step-by-step images are included at the start of the notebook (Section 0).

### 3. Run the setup cells

1. Run the library installation cell once.
2. Run the import / environment cells.
3. Confirm you see something like `CUDA available: True` (or continue on CPU if no GPU is available).

If you see a Pillow / `_Ink` import error, use **Runtime → Restart session**, then re-run from the import cell.

### 4. Work through the lab

Use the learning cycle in each section:

**Predict → Run → Observe → Modify → Explain**

You do not need to be an expert Python programmer. The goal is to understand foundation-model ideas by interacting with real models.

### 5. Save your own work (optional)

In Colab: **File → Save a copy in Drive** if you want to keep your notes and outputs.

Please **do not** try to push changes to this course repository.

---

## What the notebook covers

| Section | Topic |
|---|---|
| 0–1 | Colab setup and available compute |
| 2 | Hugging Face Hub and pretrained inference |
| 3–4 | Tokens, representations, and attention |
| 5 | Pretraining intuition and micro fine-tuning |
| 6 | Protein foundation model (ESM-2) |
| 7 | Multimodal models (images + text) |
| 8 | Earth observation models (Prithvi) |
| 9 | Responsible African application checklist |
| 10–14 | Summary, route, follow-ups, references |

Approximate duration: **90 minutes** for the core route (see Section 11 inside the notebook).

---

## Repository contents

```text
Foundation-Models/
├── README.md
├── Foundation_Models_in_Practice_Africa_Workshop.ipynb
├── images/
│   ├── colab-gpu-step1-runtime-menu.png
│   ├── colab-gpu-step2-change-runtime.png
│   └── colab-gpu-step3-verify-gpu.png
└── .gitignore
```

Branch used for this workshop: [`africa-workshop`](https://github.com/fassamnew/Foundation-Models/tree/africa-workshop)

---

## Requirements

- A Google account (for Colab)
- A modern browser
- Optional but strongly recommended: Colab GPU runtime
- Internet access to download models from the [Hugging Face Hub](https://huggingface.co)

No local Python installation is required if you use Colab.

---

## For instructors

1. Open the notebook once before the session on a fresh Colab GPU runtime.
2. Confirm package versions and model downloads work on the venue network.
3. Keep an already-executed instructor copy as a fallback for weak connectivity.
4. Use Section 14 inside the notebook for the full preparation checklist.

---

## License and reuse

Participants may open and run the notebook for learning. Models used inside the lab each have their **own licenses** on Hugging Face — always check the model card before reuse or deployment.
