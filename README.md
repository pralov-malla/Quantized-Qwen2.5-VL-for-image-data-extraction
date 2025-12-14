# Semantic Visual Data Extraction (IELTS Writing Task 1)

This repository contains a Google Colab notebook for **extracting structured semantic information from IELTS Academic Writing Task 1 images** using a **Vision–Language Model (Qwen2.5-VL)**.

The notebook converts charts, graphs, maps, and process diagrams into **machine-readable JSON**, enabling downstream **text-only AI models** (e.g., automated IELTS essay scoring systems) to understand visual content without directly processing images.

---

## What This Notebook Does

- Loads an IELTS Task 1 image dataset from Google Drive
- Uses **Qwen2.5-VL** to analyze Task 1 visuals
- Extracts key visual elements such as:
  - Chart/diagram type
  - Axes, labels, and units
  - Trends, comparisons, and stages
- Outputs **one strict JSON object per image**
- Designed for use in automated Task Achievement evaluation

---

## Tech Stack

- Python
- Google Colab
- PyTorch
- Hugging Face Transformers
- Qwen2.5-VL
- pandas, accelerate, bitsandbytes

---

## How to Run

1. Open the notebook in **Google Colab**
2. Enable GPU (`Runtime → Change runtime type → GPU`)
3. Mount Google Drive
4. Ensure the dataset path is correct
5. Run all cells sequentially

---

## Notes

- The notebook is cleaned for GitHub compatibility (no widget metadata).
- Clear outputs before committing if you modify it in Colab.

---

## Author

**Pralov Malla**

Research-focused project on **Vision-Language Models and automated IELTS evaluation**.
