# Human Activity Recognition Using Wearable Sensor Data

This project explores human activity patterns using data from wearable sensors (accelerometers and gyroscopes) collected via smartphones. The goal is to analyze and classify six common physical activities—walking, sitting, standing, lying, walking upstairs, and walking downstairs—based on sensor readings, and to generate insights that could be applied to fitness tracking or health monitoring applications.

---

## 📁 Dataset

**Source:** [UCI Machine Learning Repository – Human Activity Recognition Using Smartphones Data Set](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)

- **Subjects:** 30 individuals
- **Sensors:** Accelerometer and gyroscope (XYZ axes)
- **Sampling rate:** 50Hz
- **Labels:** Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, Laying

---

## 🧰 Tools and Libraries

- **Python** (Data analysis and modeling)
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – data visualization
- **Scikit-learn** – machine learning (classification models, evaluation)
- **Jupyter Notebook** – workflow organization

---

## 🔍 Project Workflow

1. **Data Loading & Preprocessing**
   - Merge training and testing datasets
   - Normalize signal data
   - Handle missing or duplicate values

2. **Exploratory Data Analysis (EDA)**
   - Visualize raw motion patterns across activities
   - Compare sensor signals for different subjects
   - Plot activity distributions and correlations

3. **Feature Engineering**
   - Calculate signal magnitudes
   - Extract rolling statistics (mean, std)
   - Generate time-domain features

4. **Modeling**
   - Built classification model using Random Forest
   - Evaluated performance using accuracy, confusion matrix, and cross-validation

5. **Insights & Visualizations**
   - Identified trends in physical activity
   - Visualized activity transitions and inactivity patterns
   - Highlighted potential use cases in fitness and health monitoring

---

## 📊 Results

- **Model Accuracy:** ~91% on test data
- **Top Insights:**
  - Subjects exhibited clear and consistent patterns across certain activities
  - Inactivity periods were clustered, suggesting opportunities for health alerts
  - Activity transitions can potentially be used to detect fall risks or fatigue

---

## 📌 Use Cases

- Fitness tracking and personalized coaching
- Elderly monitoring and fall detection
- Health risk analytics based on inactivity trends
