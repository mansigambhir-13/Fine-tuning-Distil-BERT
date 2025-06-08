# Fine-tuning-Distil-BERT




````markdown
# 🚀 LoRA Fine-Tuned DistilBERT - Sentiment Classifier

A lightweight and efficient sentiment classification demo built on top of **DistilBERT fine-tuned with LoRA (Low-Rank Adaptation)**. The model is served via a **Gradio web interface** for real-time predictions.

---

## ✨ Project Highlights

- 🔧 **Base Model**: [distilbert-base-uncased](https://huggingface.co/distilbert/distilbert-base-uncased)
- 🎯 **LoRA Fine-Tuning**: Memory-efficient adaptation for custom dataset
- 🖼️ **UI**: Built using [Gradio](https://gradio.app/)
- ☁️ **Deployable** on Hugging Face Spaces or Streamlit

---

## 📦 Demo

Try it out locally:

```bash
git clone https://github.com/your-username/lora-distilbert-sentiment.git
cd lora-distilbert-sentiment
pip install -r requirements.txt
python app.py
````

Or deploy on Hugging Face Spaces by uploading the files!

---

## 🧠 How It Works

* The model was fine-tuned using PEFT + LoRA techniques for a binary sentiment classification task (Positive/Negative).
* The trained model was uploaded to Hugging Face:
  👉 [`mansigambhir/distilbert-lora-sentiment`](https://huggingface.co/mansigambhir/distilbert-lora-sentiment)
* The prediction function uses the Hugging Face `transformers` and `torch` libraries to infer sentiment probabilities.
* The Gradio UI accepts user input and displays prediction confidence.

---

## 🔍 Example

*Input*:

```
This product is amazing and works like a charm!
```

*Output*:

```
✅ Positive: 97.3%
❌ Negative: 2.7%
```

---

## 🧪 Requirements

See `requirements.txt` for details. Key packages include:

* `transformers`
* `peft`
* `gradio`
* `torch`
* `accelerate`

Install all with:

```bash
pip install -r requirements.txt
```

---

## 📁 File Structure

```
lora-distilbert-sentiment/
├── app.py              # Gradio interface
├── requirements.txt    # Required dependencies
└── README.md           # Project documentation
```

---

## 👩‍🔬 Author

**Mansi Gambhir**
🔗 [Hugging Face](https://huggingface.co/mansigambhir)
📫 Feel free to connect for collaborations in GenAI!

---

## 🛡 License

MIT License - feel free to use, modify, and share.

---

## 🙌 Acknowledgements

* Hugging Face Transformers & PEFT libraries
* Gradio for the intuitive frontend
* Dataset used for sentiment classification

```

---

Would you like me to bundle this with `app.py` and `requirements.txt` into a zip file for upload?
```
