# 100x Week 1 — Canny ControlNet Practice (ComfyUI)

Practice set for the 100x Cohort (Week 1): take a **single base image**, extract edges via **Canny ControlNet** to generate multiple stylistic variations in **ComfyUI**.  

---

## 🎯 Goals
- Use a **base image** as ControlNet Canny guidance.
- Produce **diverse variations** (styles, compositions, palettes) while **preserving structure**.
- Track parameters for **repeatable results**.

---

## 📂 Repo Layout
- `workflows/` → ComfyUI workflow JSON  
- `inputs/` → base image(s)  
- `outputs/` → generated results  

---

## 🚀 How to Run
1. Open ComfyUI → load `workflows/canny_controlnet_workflow.json`.  
2. Input `inputs/base.jpg`.  
3. Run the workflow  

---

## ✅ Checklist
- [ ] Workflow JSON  
- [ ] Base image  
- [ ] 3+ variations in `outputs/`  

---

## 📜 License
MIT (repo). Generated images follow base model license.
