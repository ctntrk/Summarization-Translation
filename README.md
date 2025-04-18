# 📝 A Simple Python App to Summarize English Texts and Translate Them into Turkish

This project is a simple Python app that takes long and complex English texts, summarizes them, and translates the summary into Turkish. It's especially useful for people who want to understand English content more easily.

---

# 📌 What Does It Do?

- Takes a long English text  
- Creates a short summary  
- Translates the summary into Turkish  
- Prints both the English summary and the Turkish translation

---

# 🧰 What You Need

To run this app, you need:

- A computer with Python installed  
- Internet connection (to download the models)  
- Required libraries installed:

```bash
pip install transformers sentencepiece
```

---

# ⚙️ How It Works

Here's how it works:

1. You give the program an English text  
2. It generates a short summary  
3. Then translates that summary into Turkish  
4. It prints the results

---

# 🔍 Example Usage

```python
long_text = """
Artificial intelligence (AI) is transforming every aspect of our lives...
"""

summary, translation = process_text(long_text)

print("English Summary:\n", summary)
print("\nTurkish Translation:\n", translation)
```

📌 **Example Output:**

```
English Summary:
Artificial intelligence (AI) is transforming every aspect of our lives...

Turkish Translation:
Yapay zeka (AI), hayatımızın her yönünü dönüştürüyor...
```

---

# 🌍 Where Can You Use It?

This app can be helpful for:

- Creating short news summaries  
- Understanding academic articles more easily  
- Making content accessible to non-English speakers  
- Simplifying educational materials

---
