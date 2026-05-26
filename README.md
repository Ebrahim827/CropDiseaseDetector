# Crop Disease Detector 🌿

A deep learning model that identifies 15 plant diseases from leaf 
images using transfer learning with ResNet18, achieving **92.2% accuracy**.
Built to address Pakistan's agricultural losses from undetected crop 
disease — Agriculture contributes 24% of Pakistan's GDP.

## Results
| Metric | Value |
|--------|-------|
| Test Accuracy | 92.2% |
| Dataset | PlantVillage |
| Classes | 15 disease types |
| Model | ResNet18 (transfer learning) |

## Disease Classes Detected
- Tomato Leaf Mold
- Tomato Bacterial Spot
- Tomato Healthy
- Potato Late Blight
- Pepper Bell Bacterial Spot
- *(and 10 more)*
- 
## How It Works
1. Farmer uploads a leaf image
2. ResNet18 CNN classifies the disease
3. Returns disease name + confidence score
4. Rejects unknown inputs below 70% confidence

## Tech Stack
Python · PyTorch · Torchvision · Gradio · Google Colab

## Try It Yourself
First click run all codes at top

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OJcHpH3NBN_mXuHaXGvICJRkZV1LzIjp?usp=sharing)

## Limitations
- Trained on PlantVillage lab-style images
- Does not recognise plants outside its 15 trained classes
- Confidence threshold rejects unknown inputs

---

## Future Work
- Expand to 38 disease classes
- Fine-tune on real-world field photos from Pakistan
- Deploy as offline mobile app for rural farmers
- Add treatment recommendations in Urdu

---

## Author
Muhammad Ebrahim Imran
BS Artificial Intelligence — NUST SEECS, Islamabad, Pakistan
