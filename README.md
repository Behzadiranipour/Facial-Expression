# Facial Expression Recognition

A simple and educational implementation of facial expression recognition using deep learning.  
The project focuses on building a minimal workflow for handling image files and training models without relying on extra utilities such as `tqdm` or complex dataset loaders.

---

## 🚀 Project Goals
- Provide the **simplest possible workflow** for working with image files and training a CNN.  
- Avoid unnecessary dependencies and keep the code easy to understand.  
- Serve as a baseline for facial expression recognition experiments.

---

## ⚙️ Technical Details
- **Frameworks:** TensorFlow / Keras, NumPy, OpenCV.  
- **Hardware:** CPU only (no GPU acceleration).  
- **Training:** Limited to **10 epochs** to keep training time reasonable on CPU.  
- **Dataset:** Images organized by class folders (e.g., `happy`, `sad`, `angry`, etc.).  
- **Model:** Convolutional Neural Network (CNN) for image classification.

---

## 📂 Project Structure
Facial-Expression-Recognition/ │ ├── models/ │ ├── model2.ipynb 
│ ├── pytorch.ipynb # Placeholder – PyTorch implementation coming soon │ 
│ ├── data/ # Dataset (not included in repo) 
├── requirements.txt # Dependencies 
└── README.md


---

## 🖥️ Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Behzadiranipour/Facial-Expression.git
   cd Facial-Expression

pip install -r requirements.txt


📌 Notes

    Training is intentionally capped at 10 epochs because CPU-only training is slow.

    This project is meant as a minimal, educational baseline rather than a production-ready solution.

    PyTorch implementation is coming soon — you will be able to compare TensorFlow/Keras vs. PyTorch and see the differences in workflow and performance.

📜 License

This project is released under the MIT License. Feel free to use, modify, and share with proper attribution.

