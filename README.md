# 🚀 AstroGuard – Near-Earth Asteroid Hazard Detection

AstroGuard is a Machine Learning-based project that predicts whether a Near-Earth Object (asteroid) is potentially hazardous based on its physical and orbital characteristics.

The project uses asteroid data from 1910–2024 and applies machine learning classification to identify potentially hazardous asteroids.

---

## 🎯 Objective

The main objective of AstroGuard is to provide an ML-based approach for detecting potentially hazardous asteroids using important asteroid characteristics such as size, velocity, magnitude, and miss distance.

---

## 🧠 Machine Learning

### Dataset

The dataset contains **338,199 asteroid records** with information about Near-Earth Objects.

### Features Used

- Absolute Magnitude
- Estimated Diameter (Minimum)
- Estimated Diameter (Maximum)
- Relative Velocity
- Miss Distance

### Target

`is_hazardous`

The model classifies an asteroid into:

- **Hazardous**
- **Non-Hazardous**

---

## 📊 Model Performance

| Metric | Score |
|---|---:|
| Accuracy | **91.86%** |
| Precision | **73.31%** |
| Recall | **56.92%** |
| F1-Score | **64.08%** |

These results demonstrate the model's ability to classify potentially hazardous Near-Earth Objects based on their available physical and orbital characteristics.

---

## 🔗 Project Links

### 📓 Google Colab – ML Model
[Open AstroGuard ML Notebook](https://colab.research.google.com/drive/1BQr7JU7U11Ts9Xj8IJ95X-RqhRjEw0y5?usp=sharing)

### 🎥 AstroGuard ML Demo Video
[Watch AstroGuard ML Demo](https://drive.google.com/file/d/1c4VsGhKhIwIr88JFtOCnpM2zwWUtCsWO/view?usp=drivesdk)

---

## ⚙️ Project Workflow

```text
Asteroid Dataset
       ↓
Data Preprocessing
       ↓
Feature Selection
       ↓
Train-Test Split
       ↓
Machine Learning Model
       ↓
Model Prediction
       ↓
Hazardous / Non-Hazardous
```

---

## 🛰️ Input Parameters

The AstroGuard ML model uses the following values as input:

- Absolute Magnitude
- Minimum Estimated Diameter
- Maximum Estimated Diameter
- Relative Velocity
- Miss Distance

The model then predicts whether the asteroid is potentially hazardous.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Machine Learning
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 👩‍💻 Team

**Bhavana S**  
**Sahana A**

---

## 📌 Future Scope

- Integrate real-time asteroid data from NASA APIs
- Improve model performance using advanced ML algorithms
- Develop a real-time asteroid monitoring dashboard
- Add interactive visualizations
- Provide automated hazard alerts for potentially hazardous objects

---

## 📚 Conclusion

AstroGuard demonstrates how Machine Learning can be applied to Near-Earth Object data to classify potentially hazardous asteroids. By analyzing asteroid size, velocity, magnitude, and miss distance, the system provides an automated approach to asteroid hazard detection.
