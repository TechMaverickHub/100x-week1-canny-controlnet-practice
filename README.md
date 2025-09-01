# 100x Week 1 — Canny ControlNet Practice (ComfyUI)

Practice set for the 100x Cohort (Week 1): take a **single base image**, use **Canny ControlNet** to extract edges and generate multiple stylistic variations in **ComfyUI**.  

---

## 🎯 Goals
- Use a **base image** as ControlNet Canny guidance.  
- Produce **diverse variations** (styles, compositions, palettes) while **preserving outlines/structure**.  
- Track parameters for **repeatable results**.  

---

## 🧭 What is Canny ControlNet?
**Canny ControlNet** uses the **edges/outlines** of the reference image as a structural guide while allowing the style and appearance to change.  

---

## 📂 Repo Layout
- `workflows/` → ComfyUI workflow JSON  
- `inputs/` → base image(s)  
- `outputs/` → generated results  

---

## 🚀 How to Run
1. Open ComfyUI → load `workflows/canny_controlnet_workflow.json`.  
2. Input `inputs/base.jpg`.  
3. Run the workflow.  

---

## ✅ Checklist
- [ ] Workflow JSON  
- [ ] Base image  
- [ ] 3+ variations in `outputs/`  

---

## 📜 License
MIT (repo). Generated images follow base model license.
