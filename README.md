# 🐛 Bug Detection and Fixing using Deep Learning

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)
![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-ff69b4)

This project is developed as part of the **Intel Unnati Industrial Training Program 2025**. It aims to **detect and fix bugs in source code** using deep learning models such as **CodeBERT** and **CodeT5**. The tool analyzes buggy code snippets and automatically generates the corrected version, helping developers write better and cleaner code.

---

## 🚀 Features

- 🧠 **Bug Detection**: Detects bugs in code using transformer-based models.
- 🔧 **Bug Fixing**: Automatically fixes the detected bugs.
- 💻 **GUI Interface**: User-friendly graphical interface for interacting with the model.
- 📊 **Model Training & Evaluation**: CodeBERT and CodeT5 integrated for fine-tuning and inference.
- 🗃️ Uses custom dataset: `bug_dataset_v1.0_20250327_160057.csv`

---

## 🛠️ Tech Stack

- Python
- PyTorch / Transformers
- CodeBERT / CodeT5
- Streamlit or Tkinter (for GUI)
- Jupyter Notebook

---

## 📂 Project Structure

```bash
├── dataset/
│   └── bug_dataset_v1.0_20250327_160057.csv
├── models/
│   └── codebert_model/
│   └── codet5_model/
├── notebooks/
│   └── training_pipeline.ipynb
├── gui/
│   └── app.py
├── LICENSE
├── README.md
└── requirements.txt

📥 Installation

Clone this repository:
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

Install dependencies:
pip install -r requirements.txt

Run the GUI:
python gui/app.py

📊 Model Training
You can fine-tune CodeBERT or CodeT5 using our Jupyter Notebook located in the notebooks/ directory. Make sure the dataset is in place and dependencies are installed.

👩‍💻 Contributors
Khushi Chauhan
Arpit Kakran
Harsh Chauhan

📄 License
This project is licensed under the MIT License.

🤝 Acknowledgments
Thanks to Intel Unnati for the training platform and resources.
Hugging Face Transformers
OpenAI for guidance and support

💡 Future Work
Add support for multiple programming languages
Improve bug-fix accuracy with larger datasets
Deploy as a web app for real-time usage
