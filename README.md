# Buck Converter Digital Twin & Fault Diagnosis

This project develops a **digital twin** of a buck converter to simulate both normal and faulty operations. The software model replicates the dynamic behavior of a real buck converter, enabling performance monitoring, control evaluation, and fault detection without requiring physical hardware.

---

## Features

* **Buck Converter Simulation**: Models PWM switching, inductor current, capacitor voltage, and load behavior.
* **Fault Scenarios**: Switch short/open, load disturbances, input voltage variations, and component aging.
* **Feature Extraction**:

  * **Time-domain**: Mean, RMS, skewness, kurtosis, entropy.
  * **Frequency-domain**: Spectral centroid, bandwidth, energy.
* **Machine Learning Models**: Random Forest, Decision Tree for fault classification using extracted features.
* **Deep Learning Models**: MLP, CNN, LSTM, CNN+LSTM for sequence-based classification on raw signals.
* **Evaluation**: Accuracy metrics, confusion matrices, training curves, and residual/adaptive threshold analysis.

---

## Usage

1. Run the simulation scripts to generate voltage and current signals.
2. Extract features or use raw sequences for training.
3. Train ML/DL models for fault detection and classification.
4. Evaluate model performance using classification reports and confusion matrices.

```bash
python simulate_buck.py
python feature_extraction.py
python train_ml_models.py
python train_dl_models.py
```

---

## Outputs
<img width="608" height="496" alt="image" src="https://github.com/user-attachments/assets/8a34903d-da32-41d6-99eb-72d80bce6c6f" />
<img width="1189" height="790" alt="image" src="https://github.com/user-attachments/assets/c28c4541-9333-4893-adcb-1215633e6b06" />
<img width="1189" height="790" alt="image" src="https://github.com/user-attachments/assets/bd04c0db-3063-4c54-8f40-fbf2e03c0bb5" />
<img width="841" height="547" alt="image" src="https://github.com/user-attachments/assets/da37a0e3-fc05-40f0-abd0-d2a1647f3212" />
<img width="1089" height="590" alt="image" src="https://github.com/user-attachments/assets/b3447f08-2527-4476-bf6a-c283ce759c69" />
<img width="846" height="498" alt="image" src="https://github.com/user-attachments/assets/32c422e8-e43e-4a3d-8049-ed642539b422" />
<img width="592" height="484" alt="image" src="https://github.com/user-attachments/assets/79bda194-a091-4547-b336-45742811df63" />
<img width="592" height="484" alt="image" src="https://github.com/user-attachments/assets/9af37254-b8ac-4b18-91eb-57cbd98afdad" />
<img width="592" height="484" alt="image" src="https://github.com/user-attachments/assets/fa0fb6e6-f4e3-4d8b-84af-d76c3ec6e9c3" />
<img width="592" height="484" alt="image" src="https://github.com/user-attachments/assets/4d86e940-37a7-4992-baa3-59219a507d8c" />
<img width="596" height="561" alt="image" src="https://github.com/user-attachments/assets/5698e87c-f963-437d-99ba-aab160f38436" />
<img width="1589" height="790" alt="image" src="https://github.com/user-attachments/assets/5c6961da-fd27-4886-8853-08703016d8e9" />
<img width="562" height="470" alt="image" src="https://github.com/user-attachments/assets/4ba02675-fcf6-4fd0-83f7-4e92762bb50e" />

---

## Requirements

* Python 3.8+
* numpy, pandas, matplotlib, seaborn
* scikit-learn
* tensorflow (for deep learning models)
* scipy

---

## Author

Saurav Avachat, B.Tech, Electronics and Communication Engineering
