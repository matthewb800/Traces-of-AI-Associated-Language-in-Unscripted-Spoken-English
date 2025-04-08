# Traces of AI-Associated Language in Unscripted Spoken English

## Abstract
In recent years, written language, particularly in the domains of science and education, has undergone remarkable shifts in word usage. These changes are widely attributed to the growing influence of Large Language Models (LLMs), which frequently rely on a distinct and recognisable lexical style. While these shifts are often linked to using AI directly as a tool to generate text, it remains unclear whether the changes reflect broader changes in the human language system itself. To explore this question, we constructed a dataset of 20 million words from unscripted spoken language drawn from conversational science and technology podcasts. We analysed lexical trends before and after 2022, focusing on 34 words commonly associated with LLM output. Our results reveal a moderately positive trend in the usage of these words following the release of ChatGPT, suggesting a mild alignment between human word choices and LLM-associated patterns. In contrast, baseline synonym words showed no consistent directional shift. These findings contribute to ongoing discussions around AI-induced language change. However, it remains an open question whether this trend represents a natural progression of language change or a novel shift driven directly or indirectly by exposure to AI-generated language.

## Repository Contents
- **Dataset snippets**: Due to copyright restrictions, only selected excerpts are available.
- **Scripts**: Python scripts used for data transcription, preprocessing, and analysis.
- **Full results**:
  - **Target words analysis (34 words)**
  - **Baseline synonyms analysis (127 words)**
- **Appendices**:
  - **A**: Computing resources used
  - **B**: Comprehensive list of analyzed AI-associated words
  - **C**: List of podcasts included in the dataset
  - **D**: Detailed statistical results for target words
  - **E**: Detailed statistical results for baseline words

## Requirements and Running the Code

### Requirements
- **Python 3.x**
- **OpenAI Whisper Base Model** (for audio transcription)
- **spaCy** (for POS tagging and lemmatization)
- **Python libraries**: spaCy, scipy 

Install dependencies via pip:
```bash
pip install openai-whisper spacy pandas numpy scipy
python -m spacy download en_core_web_sm
```

### Running the Analysis

1. **Transcribe podcast audio** (if transcripts are not provided):
```bash
whisper podcast_audio.mp3 --model base --language en
```

2. **Lemmatize and POS-tag transcriptions**:
```bash
python ""
```

3. **Conduct lexical trend analysis**:
```bash
python ""
```

## Notes on Code
- Transcripts not provided by podcasts were generated using **OpenAI Whisper (base model)**.
- Lemmatization and POS-tagging were done using spaCy's **`en_core_web_sm` model**.
- Lexical frequency analysis was conducted using occurrences per million (**OPM**).
- Statistical significance was assessed using the **chi-square contingency table test**.

## License
This project is licensing has not been determined.

## Contact
For questions or collaboration requests, please submit an issue or pull request on this repository. All interactions should remain anonymous to preserve privacy.
