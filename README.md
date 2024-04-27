[![GitHub license](https://img.shields.io/github/license/SINGHxTUSHAR/ANUVADAK.svg)](https://github.com/SINGHxTUSHAR/ANUVADAK/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/SINGHxTUSHAR/ANUVADAK.svg)](https://GitHub.com/SINGHxTUSHAR/ANUVADAK/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/SINGHxTUSHAR/ANUVADAK.svg)](https://GitHub.com/SINGHxTUSHAR/ANUVADAK/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/SINGHxTUSHAR/ANUVADAK.svg)](https://GitHub.com/SINGHxTUSHAR/ANUVADAK/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


[![GitHub watchers](https://img.shields.io/github/watchers/SINGHxTUSHAR/ANUVADAK.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/ANUVADAK/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/SINGHxTUSHAR/ANUVADAK.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/ANUVADAK/network/)
[![GitHub stars](https://img.shields.io/github/stars/SINGHxTUSHAR/ANUVADAK.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/ANUVADAK/stargazers/)

[![Open in Visual Studio Code](https://img.shields.io/static/v1?logo=visualstudiocode&label=&message=Open%20in%20Visual%20Studio%20Code&labelColor=2c2c32&color=007acc&logoColor=007acc)](https://open.vscode.dev/SINGHxTUSHAR/ANUVADAK)

# BHASHA BADLO 🗣️ 💬:
![Designer (4)](https://github.com/SINGHxTUSHAR/ANUVADAK/assets/113624520/5a190084-d75f-410f-af7e-645d63635ad3)
This project tackles machine translation using the Transformer architecture, a powerful tool in Natural Language Processing (NLP). Unlike traditional models, Transformers process entire sentences simultaneously, thanks to the self-attention mechanism. This allows the model to understand the relationships between words and capture context more effectively.

Here's a breakdown of the process:

Encoder-Decoder Architecture:

`Encoder:` This reads the source language sentence, analyzing each word's meaning and its connection to others.

`Decoder:` Informed by the encoder's analysis, the decoder generates the target language sentence word by word, attending to both the source sentence and previously generated words.

`Attention Mechanism:` This is the heart of the Transformer. It allows each word in the sentence to "attend" to other relevant words, focusing on crucial information for translation. This is particularly helpful for capturing long-range dependencies and complex sentence structures.

`Training:` The model is trained on large datasets of parallel sentences in different languages. It learns to map the source language sentence structure and meaning to the target language, progressively improving its translation accuracy.

By leveraging the Transformer's capabilities, this project aims to achieve high-quality, nuanced translations, even for complex languages and sentence structures.

## Problem Statement 💼:
Despite significant advancements in machine translation, achieving natural and accurate translations, especially for complex languages like English and French, remains a challenge. Existing models often struggle with:

* `Capturing Long-Range Dependencies:` The meaning of a word can be influenced by words far apart in the sentence. Traditional models might miss these subtle connections, leading to inaccurate translations.
* `Preserving Sentence Structure:` Sentence structure differs between languages. Models might translate literally, resulting in grammatically incorrect or awkward phrasing in the target language (French).
* `Nuance and Idioms:` Accurately conveying the intended meaning requires understanding cultural context and idiomatic expressions, which can be difficult for traditional models.

This project aims to address these issues by developing a self-designed Transformer architecture specifically for translating English sentences to natural and grammatically correct French. The model will leverage the Transformer's strengths, particularly the self-attention mechanism, to:
* `Focus on Meaningful Relationships:` By attending to relevant words throughout the sentence, the model can capture long-range dependencies and understand the overall context.
* `Learn Sentence Structure:` The model will be trained on parallel English-French sentence pairs, allowing it to learn the appropriate word order and grammatical structures for French.
* `Improve Nuance and Idiom Handling:` By incorporating techniques like back-translation and attention regularization, the model can be better equipped to handle nuanced language and idiomatic expressions.

The success of this project will be measured by the model's ability to generate accurate, fluent, and natural-sounding French translations that preserve the intended meaning of the original English sentence.


## Data Dictionary 📄✏ :
The Dataset is taken from the <a href="https://www.manythings.org/anki/"> manythings.org</a>.

## Requirements💻 :

Ensure you have the following dependencies installed:

- Python (version 3.12)
- GPU (T-4), use collab or can use the Dedicated graphics card.
- Jupyter Notebook || PyCharm || collab || vs-code
- Other dependencies (refer to the requirements.txt)

You can install the required Python packages using:

```bash
pip install -r requirements.txt
```


## Setup 💿:

- Clone the repository:
```bash
git clone https://github.com/SINGHxTUSHAR/ANUVADAK.git
cd ANUVADAK
```
- Create a virtual environment (optional but recommended):
```bash
python -m venv venv
```
- Activate the virtual environment:
  - On Windows:
   ```bash
   venv\Scripts\activate
   ```
  - On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```

## Contributing 📌:
If you'd like to contribute to this project, please follow the standard GitHub fork and pull request process. Contributions, issues, and feature requests are welcome!

## Suggestion🚀: 
If you have any suggestions for me related to this project, feel free to contact me at tusharsinghrawat.delhi@gmail.com or <a href="https://www.linkedin.com/in/singhxtushar/">LinkedIn</a>.

## License 📝:
This project is licensed under the <a href="https://github.com/SINGHxTUSHAR/ANUVADAK/blob/main/LICENSE">MIT License</a> - see the LICENSE file for details.



