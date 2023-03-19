# Kosovo-Parliament-Transcriptions

The dataset comprises transcripts of speeches delivered by members of the Kosovo Assembly during parliamentary sessions, spanning from 2007 to March 2023. The goal of this repository is to provide a valuable resource for researchers and professionals interested in natural language processing, or political discourse analysis.

# Data source

The dataset was compiled from publicly available transcripts published on the current and old official website of the Kosovo Assembly (https://kuvendikosoves.org/).

# Data Preperation

The dataset was compiled by downloading PDF files and converting them to a text format using OCR. The resulting text was then cleaned to fix punctuation and spelling errors. It's important to note that due to the complexity of the PDF-to-text conversion process, the dataset may still contain typos and other errors. As a result, the dataset is provided "as is". Additionally, it should be noted that the dataset includes speeches given in languages other than Albanian.

# To do

- [ ] Conduct additional quality assurance checks to identify and correct any remaining errors in the dataset.
- [ ] Add a column for the language of the speech.
- [ ] Add a column for the party of the speaker.

# Dataset structure

The dataset contains the following fields: text, speaker, date, id.

# Usage

```python

from datasets import load_dataset

dataset = load_dataset('Kushtrim/Kosovo-Parliament-Transcriptions')

```

# License

The dataset is licensed under the Creative Commons Attribution 4.0 International License (https://creativecommons.org/licenses/by/4.0/).

# Citation

If you use this dataset in your research, please consider citing this repository.

```
@misc{alpaca,
  author = {Kushtrim Visoka},
  title = {Kosovo-Parliament-Transcriptions},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/Kushtrimvisoka/Kosovo-Parliament-Transcriptions}},
}
```
