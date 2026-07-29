# Welcome to Our Machine Learning & Core Intelligence Workspace 👋

We build high-performance, modular machine learning engines leveraging accelerated C++ architectures with clean Python interfaces. Our ecosystem focuses on low-level optimization, raw neural network dynamics, and efficient algorithm designs.

---

## 🛠️ Core Repositories

### 🧠 [NNEngine](https://github.com/AffineFlow/nnengine)
A lightweight but comprehensive C++ neural network computing engine featuring a native autograd tracking subsystem.
* **Architecture:** Fully custom implementation of foundational operations like `MatMulOp`, `ReLUOp`, and `LeakyReLUOp` managed via an operational tape system.
* **Components:** Includes core dense layers, standard optimizers (`SGD`, `Adam`), and loss trackers (`MSELoss`, `SoftmaxCrossEntropyLoss`).
* **Bindings:** Compiles cleanly into optimized C++ executables via CMake and exports directly to Python APIs using a customized `binding.cpp` architecture.

### 📐 [KNNEngine](https://github.com/AffineFlow/knnengine)
A high-performance C++ engine dedicated to vectorized neighborhood classification and structural data reduction.
* **Features:** Built-in matrix-driven Principal Component Analysis (`PCA.cpp`) alongside fast $K$-Nearest Neighbors classification pipelines (`KNN.cpp`).
* **Tooling:** Features deep system level building supported by multi-platform `CMakePresets.json` layouts and automated native distribution pipelines.

### 🎛️ [MLEngine](https://github.com/AffineFlow/affineflow)
The central high-level staging ground that orchestrates multiple machine learning models and operational tasks under one coherent module layout.
* **Integrations:** Smoothly wraps complex structures into clean Python modules (`knn.py` and `nn.py`) designed for production prototyping.

---

## 🚀 Our Tech Stack
* **Core Systems:** C++17 / C++20, CMake, Python 3
* **Key Patterns:** Reverse-mode Automatic Differentiation (Tape-based), Principal Component Analysis, Vector-optimized Classifiers
* **CI/CD:** Multi-platform target compilation and package validation routines engineered via automated GitHub Actions workflows

---

## 🤝 Getting Involved
All of our engines feature dedicated `examples/` folders hosting clean scripts to get you running locally in seconds. Feel free to dive into the code bases, explore our bindings, or open issues to optimize performance further!
