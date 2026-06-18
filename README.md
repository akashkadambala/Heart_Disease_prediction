# 🫀 Heart Disease Prediction using Metaheuristic Algorithms

A machine learning project that applies **bio-inspired (metaheuristic) optimization algorithms** for feature selection and predictive modeling to detect heart disease with optimized accuracy.

---

## 📌 Overview

Heart disease remains one of the leading causes of death worldwide. Rising stress, poor diet, and modern work culture have made it increasingly prevalent across all age groups. This project goes beyond standard ML approaches by using **nature-inspired algorithms** to intelligently select the most relevant features and improve prediction accuracy.

The system compares four metaheuristic algorithms side by side and visualizes their performance through an interactive GUI.

---

## 🧠 Algorithms Implemented

| Algorithm | Inspiration | Key Strength |
|-----------|-------------|--------------|
| **ACO** (Ant Colony Optimization) | Ant foraging & pheromone trails | Discrete optimization & feature selection |
| **BAT** (Bat Algorithm) | Echolocation behavior of bats | Continuous domain & nonlinear optimization |
| **BEE** (Bee Algorithm) | Honeybee nectar foraging patterns | Multi-modal optimization & feature subset selection |
| **GA** (Genetic Algorithm) | Natural selection & genetics | Feature selection, model optimization, rule generation |

---

## 📁 Project Structure

```
Heart_Disease_prediction/
│
├── __pycache__/              # Compiled Python bytecode (BAT, BEE)
├── heart_dataset/
│   ├── Dataset_information   # Metadata about the dataset
│   ├── Url_dataset           # Source URL for the dataset
│   ├── Dataset               # Training data
│   └── Test                  # Test data (replace with real patient data)
│
├── ACO.py                    # Ant Colony Optimization logic
├── BAT.py                    # Bat Algorithm logic
├── BEE.py                    # Bee Algorithm logic
├── GA.py                     # Genetic Algorithm logic
├── Main.py                   # Entry point — integrates all algorithms + GUI
├── instructions.txt          # Required Python libraries
└── README.md
```

---

## ⚙️ Setup & Installation

### Prerequisites
- Python **3.7 or above**
- pip (Python package manager)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/akashkadambala/Heart_Disease_prediction.git
   cd Heart_Disease_prediction
   ```

2. **Install dependencies**
   ```bash
   pip install -r instructions.txt
   ```

3. **Run the application**
   ```bash
   python Main.py
   ```

---

## 🖥️ Output

- Launches a **Tkinter GUI** to interact with and run all algorithms
- Displays a **comparison graph** showing accuracy of each algorithm
- Provides a **text-based prediction** of heart disease stage based on test data

---

## 📊 Dataset

The dataset is located in the `heart_dataset/` folder. You can replace the `Test` file with real patient data to get predictions. Refer to `Dataset_information` for metadata and feature descriptions.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
