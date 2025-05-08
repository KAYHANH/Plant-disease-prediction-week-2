# 🌿 PLANT-DISEASE PREDICTION

**Description**

This project focuses on the detection and classification of plant leaf diseases using deep learning techniques. It aims to assist farmers and agricultural experts by automatically identifying plant diseases from images, reducing the need for manual inspection and enabling quicker responses to disease outbreaks.

Using a transfer learning approach with ResNet50 and a robust dataset, this model attempts to accurately predict different categories of plant diseases, contributing to smarter, AI-powered agriculture.

---

## 📚 Table of Contents

* [Installation](#installation)
* [Dataset](#dataset)
* [Usage](#usage)
* [Results](#results)
* [Contributing](#contributing)
* [License](#license)

---

## 🔧 Installation

To run this project, follow these steps:

1. **Clone this repository:**

   ```bash
   git clone https://github.com/your-username/plant-disease-prediction.git
   cd plant-disease-prediction
````

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv env
   source env/bin/activate  # For Windows: env\Scripts\activate
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

---

## 📂 Dataset

This project uses a large dataset (approx. 2.7 GB) containing images of healthy and diseased plant leaves. You can access the dataset via the link below:

🔗 [Download Dataset from Google Drive](https://drive.google.com/drive/folders/1ckez4ICKnUMB2kiwfGmK9h4IMZ4S3vKH?usp=sharing)

> **Note:** After downloading, make sure to extract the files and update the file paths in the notebook accordingly if you're working locally.

---

## 🚀 Usage

### Option 1: Using Google Colab

1. Open the notebook in [Google Colab](https://colab.research.google.com/drive/13kAXbfiPUxZkYotVPJsAB2WJdBX5yys3?usp=sharing).
2. Mount Google Drive and update the dataset path.
3. Run each cell sequentially.

### Option 2: Running Locally

1. Launch Jupyter Notebook or VS Code and open `Plant_diseases_week_2.ipynb`.
2. Update dataset paths to point to your local files.
3. Run the notebook step-by-step.

---

## 📊 Results

After training, the model outputs the following (example):

* **Training Accuracy:** 85%
* **Validation Accuracy:** 82%
* **Loss:** Monotonically decreasing
* **Confusion Matrix:** (Insert your matrix or image here)

> The model demonstrates strong generalization performance with augmented data and transfer learning.

---

## 🤝 Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit and push your changes.
4. Submit a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

🔗 [View License Details](https://opensource.org/licenses/MIT)

---

## 📬 Contact

For questions or collaborations, please contact: mdkaunain2957@gmail.com

```

