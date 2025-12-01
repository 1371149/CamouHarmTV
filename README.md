# **CAMHARMTI Dataset (Subset Release)**
Dataset for the paper: **“When Harmful Content Gets Camouflaged: Unveiling Perception Failure of LVLMs with CAMHARMTI”**

---

## **Folder Structure**

Each category (`Comp_Text`, `Obj_Text`, `Lum_Text`) contains **more than 1500 sample folders**.  
Each sample folder includes exactly two files:

- `img.png` — the image with camouflaged harmful content  
- `data.json` — the corresponding text annotation

The JSON fields include:

| Field | Description |
|-------|-------------|
| `"text sentence"` | image-pair text​ — contextual text for images. |
| `"camouflaged words"` | Text in the image, where words enclosed in <> are hidden. |
| `"violated category"` | The reason for the violation of the meaning composed of images and text. |