Web Page Translator from Spanish to English

Project Overview:
This project is a Python-based tool that downloads Spanish HTML web pages, translates their visible text into English using a MarianMT Transformer model, and saves the translated page locally. It combines web scraping, machine translation, and HTML manipulation.

Features:
- Download Spanish web pages via URL.
- Extract visible text (ignoring scripts/styles).
- Translate Spanish to English using a pre-trained Transformer.
- Preserve the original HTML structure.
- Save translated output as a .html file.

Technologies Used:
- Python 3.9+
- BeautifulSoup4
- Hugging Face Transformers
- Torch (PyTorch)
- SentencePiece
- Requests

Installation:
pip install transformers
pip install sentencepiece
pip install beautifulsoup4
pip install torch
pip install requests

Usage:
- Run the script or Jupyter Notebook.
- Provide a Spanish URL.
- Translated HTML saved locally as 'translated_page_en.html'.

Performance Notes:
- Suitable for small to medium-sized pages.
- Torch uses CPU threads; GPU can be enabled manually.

Future Enhancements:
- Batch translation optimization.
- Error handling improvements.
- GUI development.
- Multiple language support.

References:
- Sutskever et al., 2014 (Seq2Seq Learning)
- Wu et al., 2016 (Google NMT)
- Vaswani et al., 2017 (Transformer architecture)
- Hugging Face MarianMT
- Ott et al., 2018 (Scaling NMT)

Acknowledgments:
Thanks to Hugging Face, PyTorch, BeautifulSoup, and SentencePiece open-source communities.

