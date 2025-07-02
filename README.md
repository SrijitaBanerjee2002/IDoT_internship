# 🚧 Illinois Department of Transportation (IDoT) Visualizations Project

This project was created as part of my internship with the **Illinois Department of Transportation (IDoT)**. It uses object detection, dataset annotation, and Python-based visualizations to extract meaningful insights from real road footage.

## 📊 Project Scope

- Vehicle type tagging (e.g., ambulance, squad car)
- Road condition context (Highway vs Non-Highway)
- Weather/environment detection (Raindrops on lenses)
- Annotated image previews using COCO-style bounding boxes
- Clean visualizations via Python, Matplotlib, Seaborn

## 🖼️ Sample Visualizations

- ✅ Highway vs. Non-Highway: Donut charts, bar plots
- ✅ Emergency vs. Non-Emergency Vehicles
- ✅ Rain condition tagging frequency
- ✅ Annotated vehicle previews from camera footage - This model was trained using Roboflow's 2.1 Instance Segmentation pipeline to distinguish between the front and back of vehicles in traffic footage. It achieved a mAP@50 of 71.6%, Precision of 68.8%, and Recall of 65.6% on the test set, with bounding box predictions visualized using the Roboflow dashboard. Due to platform constraints, direct inference wasn't conducted via code, but this model can be integrated via Roboflow's Python SDK using API endpoints for real-time inference.


## 📂 Files in This Repo

- `IDoT_Visualizations.ipynb`: Main Jupyter Notebook for data visualization
- `IDOT Presentation.pdf`: Project summary for reviewers
- `accident images/`: Supporting visuals from dataset

## 🔗 Links available
- Full dataset available via [Google Drive](https://drive.google.com/file/d/1RlXaxoTCfnEkwtVVOQgU0sZD75CTQ9bD/view?usp=sharing).
- Notebook available via [Google Colab](https://colab.research.google.com/drive/1lNyqeUdJy0OACanQ3rBZDV9eaVyWwwW3?usp=sharing)
- Instance Segmentation model metrics available via [Google Drive](https://drive.google.com/drive/folders/1B4Bm3vVYhU5r8BHf8EkmabIRAbL3tRbj?usp=sharing)

## 🛠️  Tools Used

- Python (Pandas, Matplotlib, Seaborn, PIL)
- Roboflow

# 😊 About Me
Hi! I’m Srijita Banerjee, a recent Computer Science graduate from UIC. I love using code to solve real-world problems — especially ones that make life a little easier, safer, or more human.

I’ve worked on projects in data visualization, object detection, and backend development. I’ve also taught coding to underrepresented girls in India, interned at the Illinois Department of Transportation, and TA’d a course on ethics in tech.

Feel free to connect or reach out 🫶  
📧 Email: [banerjeesrj@gmail.com]  
🔗 LinkedIn: [https://www.linkedin.com/in/srijitabanerjee/]
