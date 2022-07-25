# Domain Pre-Train Language models
---

## Awesome Domain Pre-Train Language models

|id|year|venue|name|paper|url|domain|vocab|text corpus origin|text corpus size|input length|batchsize|epoch|hardware arch|Task|Group|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|1|2019|ACL|SciBERT|SCIBERT: A Pretrained Language Model for Scientific Text|[1](https://github.com/allenai/scibert)|scientific|**SciVocab**|1.14M, 18% CS + 82% bimedical|3.17B tokens|128, 512|-|-|a single TPU v3 with 8 cores **1 week**|NER, PICO Extraction, Text Classification, Relation Classification, Dependency Parsing|AllenAI|
|2|2019|BioInformatics|BioBERT|BioBERT: a pre-trained biomedical language representation model for biomedical text mining|[1](https://github.com/naver/biobert-pretrained), and [2](https://github.com/dmis-lab/biobert) |biomedicine|original BERT vocabulary|BERT Corpus and PubMed abstracts and PMC full text articles|20B tokens||||23 days on eight NVIDIA V100 GPUs|NER, RE, QA|Clova AI Research|
|3|2019||ClincalBERT|||biomedicine|original BERT vocabulary|clinical text from the MIMIC-III database|
|4|2021||PubMedBERT｜
|5|2020|EMNLP-Findings|LEGAL-BERT|LEGAL-BERT: The Muppets straight out of Law School|[1](https://huggingface.co/nlpaueb)|legal|Bert and newly create|12 GB of diverse English legal text from several fields  scraped from publicly available resources||128, 512|26|40, (further pretrain 3,4 epochs|**exp. on 11GB NVIDIA-2080TI**, train on v3 TPUs with 8 cores from Google Cloud Compute Services|NER, Classification|University of Sheffield|


## Biomedical Pre-Train Language Models

![bio ptm](/NLP/PTM/bioptm.png)

## Interesting Domain Pre-train Models

- Math
    - **Word2Vec**: Math-word embedding in math search and semantic extraction