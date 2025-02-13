# [Optimized YOLOv8 for multi-scale object detection (paper)](https://link.springer.com/article/10.1007/s11554-024-01582-x)

> ### To access the YAML files or request a copy of this paper please fill this short form. https://forms.gle/9Lt7A6YnvoJgjHcm9

# 1- Required packages
- ultralytics version 8.2.29
- wandb version 0.19.1

  
# 2- Models weights
- [YOLOv8-large](https://github.com/AREEG94FAHAD/yolov8-optimazation/tree/main/model-weights)
- [YOLOv8-small](https://github.com/AREEG94FAHAD/yolov8-optimazation/tree/main/model-weights)
- [YOLOv8-medium](https://github.com/AREEG94FAHAD/yolov8-optimazation/tree/main/model-weights)
- [YOLOv8-sm(small-medium)](https://github.com/AREEG94FAHAD/yolov8-optimazation/tree/main/model-weights)
- [YOLOv8-ml(medium-large)](https://github.com/AREEG94FAHAD/yolov8-optimazation/tree/main/model-weights)
- [YOLOv8-sl(small-large)](https://github.com/AREEG94FAHAD/yolov8-optimazation/tree/main/model-weights)

# 3- Object Size Classifier

This project is designed to classify objects and compute their sizes from an input image. Follow the steps below to set up the environment and run the project.

---

## **Project Setup and Instructions**

### **1. Clone the Repository**
Start by cloning the repository to your local machine:
```bash
git clone https://github.com/areeg94fahad/yolov8-optimazation.git
cd your-repository-name
```
### on Window
```bash
python -m venv venv
venv\Scripts\activate
```


### on macOs/Linux
```bash
python3 -m venv venv
source venv/bin/activate
```

Then 
```bash
pip install -r requirements.txt
```

### Run the code
```
python code.py
```

### Select the label dir 
![image](https://github.com/user-attachments/assets/486054e1-724c-429a-be31-cf50876d7d52)

If you find this work useful for your research, please consider citing the paper:


```bibtex

@article{rasheed2025optimized,
  title={Optimized YOLOv8 for multi-scale object detection},
  author={Areeg Fahad Rasheed and Zarkoosh, M},
  journal={Journal of Real-Time Image Processing},
  volume={22},
  number={1},
  pages={6},
  year={2025},
  publisher={Springer}
}
```
and 
```bibtex
@article{rasheed2024yolov11,
  title={YOLOv11 Optimization for Efficient Resource Utilization},
  author={Areeg Fahad Rasheed and M. Zarkoosh},
  journal={arXiv preprint arXiv:2412.14790},
  year={2024}
  dio={https://doi.org/10.48550/arXiv.2412.14790}
}
```



