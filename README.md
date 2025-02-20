# Machine Learning for Networking - Lab Exercises

This repository contains a collection of **Jupyter Notebook lab exercises** developed for the *"Machine Learning for Networking"* course at **Politecnico di Torino**, as part of the **Master's degree in Cybersecurity**. The exercises aim to provide hands-on experience in applying machine learning techniques to various networking challenges, including cybersecurity-related scenarios.

## 📑 Table of Contents

- [Course Overview](#course-overview)
- [Repository Structure](#repository-structure)
- [Requirements](#requirements)
- [Installation and Usage](#installation-and-usage)
  - [1. Clone the Repository](#1-clone-the-repository)
  - [2. Set Up a Virtual Environment (Optional)](#2-set-up-a-virtual-environment-optional)
  - [3. Install Dependencies](#3-install-dependencies)
  - [4. Run the Jupyter Notebooks](#4-run-the-jupyter-notebooks)
- [Covered Topics](#covered-topics)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Course Overview

The *"Machine Learning for Networking"* course focuses on the intersection of **machine learning (ML)** and **networking**, providing students with both theoretical knowledge and practical skills. The primary goal is to understand how ML techniques can be leveraged to solve complex networking problems, particularly in the **cybersecurity** domain.

### ✅ Key Learning Objectives:
- Develop proficiency in **Python** programming for ML applications.
- Understand and implement **data preprocessing** and **feature extraction** techniques.
- Apply **supervised** and **unsupervised learning** methods to networking datasets.
- Explore **anomaly detection** and **traffic classification** for network security.
- Analyze real-world **internet measurements** and **network traffic data**.

## Repository Structure

```
Machine-Learning-For-Networking/
├── labs/
│   ├── lab1                               
│   ├── lab2                               
│   ├── lab3                               
│   ├── lab4                               
│   ├── lab5                               
│   ├── lab6
│   ├── lab7
│   ├── lab9
│   └── lab10
├── requirements.txt                      # Python package dependencies
├── .gitignore                            # Git ignore rules
├── LICENSE                               # License information
└── README.md                             # Project documentation
```

## Requirements

To run the lab exercises, you will need:
- **Python 3.7+**
- **Jupyter Notebook or JupyterLab**
- The libraries listed in `requirements.txt`, including:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `seaborn`
  - `jupyter`

Install dependencies with:

```bash
pip install -r requirements.txt
```

## Installation and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/sroman0/Machine-Learning-For-Networking.git
cd Machine-Learning-For-Networking
```

### 2. Set Up a Virtual Environment (Optional)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebooks

```bash
jupyter notebook
```

Navigate to the `labs/` directory and open the desired notebook.

## Covered Topics

The lab exercises cover a variety of topics, including but not limited to:

- **Data Preprocessing**: Handling missing values, normalization, and feature selection.
- **Supervised Learning**: Techniques such as decision trees, support vector machines (SVM), and neural networks.
- **Unsupervised Learning**: K-means clustering, hierarchical clustering, and PCA.
- **Anomaly Detection**: Identifying unusual patterns in network data.
- **Traffic Classification**: Categorizing network traffic for improved security monitoring.
- **Visualization**: Using tools like `matplotlib` and `seaborn` to interpret data and model performance.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request. Make sure to follow the existing code style and include clear commit messages.

## License

This project is licensed under the **GNU General Public License v3.0**.  
See the [LICENSE](https://github.com/sroman0/Machine-Learning-For-Networking/blob/main/LICENSE) file for details.

## Acknowledgments

- Developed for the *"Machine Learning for Networking"* course at **Politecnico di Torino** - Master's degree in **Cybersecurity**.
- Special thanks to the course instructors for their guidance and to fellow classmates for their collaboration.
- Datasets used in these labs are either publicly available or provided by the course instructors.

---

For any questions, feel free to open an issue or contact the repository maintainer.
