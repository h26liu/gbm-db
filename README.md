# Glioblastoma TCGA-WSI-Annotations

This repository contains manually curated annotations for over 60 Whole Slide Images (WSIs) from the **TCGA dataset**. The annotations are provided in JSON format and can be matched with the corresponding TCGA images.

## 📂 Dataset Structure
- **annotations/**: Contains JSON files with annotation coordinates.
- **metadata.csv**: Maps TCGA image IDs to annotation files.
- **TO-DO: example/**: Example scripts for using the annotations.

## 📥 How to Download TCGA Images
1. Go to [TCGA Data Portal](https://portal.gdc.cancer.gov/)
2. Search for the **image ID** in `metadata.csv`
3. Download the corresponding WSI file

## 🛠 Example Usage
### Load an annotation file:
```python
import json

with open("annotations/TCGA-XX-XXXX-01.json", "r") as f:
    annotation = json.load(f)

print(annotation)
```

## 👩‍💻 Authors and Contact
This dataset was curated by:

- **[Eric Liu]** – [Department of Computer Science, Western University]  
- **[August Lin]** – [Department of Pathology and Lab Medicine, Western University]
- **[Pramath Kakodkar]** – [Department of Pathology and Lab Medicine, University of Saskatchewan]
- **[Yayuan Zhao]** – [Department of Pathology and Lab Medicine, University of Saskatchewan]
- **[Charles Ling]** – [Department of Computer Science, Western University]
- **[Qi Zhang]** – [Department of Pathology and Lab Medicine, Western University] 

For questions and collaborations, please contact **[TBD](mailto:your-email@example.com)**.
