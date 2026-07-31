# 🖼️ BLIP Image Caption Generator

A multimodal AI application that generates natural language captions for images using the **BLIP (Bootstrapping Language-Image Pre-training)** model. This project combines computer vision and natural language processing to generate descriptive captions for uploaded images using a pretrained transformer model.

---

## 🚀 Features

- 🖼️ Single Image Caption Generation
- 📂 Batch Image Captioning
- 🔍 Beam Search Comparison
- 📏 Caption Length Analysis
- 📊 Caption Statistics
- 💾 CSV Export
- 📝 Text File Export
- 🌐 Interactive Gradio Web Application

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- BLIP
- Pillow (PIL)
- Matplotlib
- Pandas
- Gradio

---

## 📁 Project Structure

```text
blip-image-caption-generator/
│
├── BLIP_Image_Caption_Generator.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
├── sample_outputs/
├── images/
└── screenshots/
```

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/blip-image-caption-generator.git
cd blip-image-caption-generator
pip install -r requirements.txt
```

Open `BLIP_Image_Caption_Generator.ipynb` and run all cells.

## 📌 Workflow

1. Upload one or more images.
2. Preprocess with BLIP Processor.
3. Generate captions using the pretrained BLIP model.
4. Compare beam search outputs.
5. Analyze caption statistics.
6. Save captions as CSV and text files.
7. Launch the Gradio interface.

## 🔮 Future Work

- Fine-tune BLIP on Flickr8k
- Evaluate using BLEU, ROUGE, and CIDEr
- Deploy on Hugging Face Spaces
- Support multilingual caption generation

## 📜 License

MIT License.
