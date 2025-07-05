
# ✈️ Aircraft Damage Detection & Captioning

This deep learning project performs **aircraft damage classification** and generates **image captions/summaries** using a combination of **Keras** and **BLIP** (Bootstrapped Language Image Pretraining). It supports both detection and descriptive captioning for aircraft damage images like dents, scratches, etc.

---

## 📂 Project Structure

```
classification and captioning/
├── model.ipynb                # Main notebook with training and inference
├── requirement.txt            # List of dependencies
├── aircraft_damage_dataset_v1 # (ignored in Git) dataset folder
├── .gitignore
└── model.keras                # Trained classification model (ignored in Git)
```

---

## 🚀 Features

- 📸 Load and preprocess aircraft damage images
- 🔍 Classify image damage type using a Keras CNN model
- 🧠 Generate image captions/summaries with the BLIP model
- 🗃️ Ignore large files and dataset folders using `.gitignore`

---

## 🛠️ Requirements

Install required libraries:

```bash
pip install -r requirement.txt
```

---

## 🧪 How to Use

### 1. Clone the repo:

```bash
git clone https://github.com/<your-username>/deep-learning.git
cd deep-learning
```

### 2. Activate your virtual environment:

```bash
# Example for Windows
myenv\Scripts\activate
```

### 3. Run the notebook:

Open `model.ipynb` in Jupyter or VS Code and run all cells.

---

## 🧠 Model Details

- **Classifier**: Trained with Keras Sequential model (`.keras` format)
- **Captioning**: Uses the `transformers` library and BLIP model for vision-language tasks
- **Custom Layer**: Includes a custom Keras layer (`BlipCaptionSummaryLayer`) for integration

---

## 🧾 Notes

- Dataset folder `aircraft_damage_dataset_v1/` is not pushed to GitHub (it's ignored via `.gitignore`)
- Use your own image samples inside the `test` subfolder to try predictions and captions

---

## 🤝 Contributing

Feel free to open issues or submit pull requests to improve the model or add new features.

---

## 📄 License

MIT License — you are free to use and modify this project with credit.
