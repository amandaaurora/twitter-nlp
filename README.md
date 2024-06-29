_This github repository is made available to support our Master's Thesis for Máster Universitario en Data Analytics for Business in UPF-BSM._
# Data-Driven Insights into Mental Health Campaigns: Aligning Public Sentiment with Government Efforts in Spain

## Description
This repository contains all the notebooks used to support the data preprocessing and analysis for the study:

1. `01_data_prep`: contains data preparation for X API data extraction to make it suitable for analysis. 
Contains the removal of PII and content cleanup from non-textual information, such as emoji, repeated words, etc.
2. `02_analysis` : analysis performed on the dataset sourced from public posts.
3. `03_Gov_Data`: analysis performed on the dataset sourced from Ministerio de Sanidad's account
4. `requirements.txt` was generated directly from the Python environment used to develop the codes.

## Methodology

NLP techniques were applied using existing models from Pysentimiento and OpenAI's GPT-4o models (see References below for complete list of pre-trained models and datasets).

## References
```bibtex
%Pysentimiento
@misc{perez2021pysentimiento,
      title={pysentimiento: A Python Toolkit for Opinion Mining and Social NLP tasks}, 
      author={Juan Manuel Pérez and Mariela Rajngewerc and Juan Carlos Giudici and Damián A. Furman and Franco Luque and Laura Alonso Alemany and María Vanina Martínez},
      year={2023},
      eprint={2106.09462},a
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}

% OpenAI GPT-4o
@techreport{openai2023gpt4,
  title = {GPT-4 Technical Report},
  author = {OpenAI},
  year = {2023},
  url = {https://www.openai.com/research/gpt-4},
  institution = {OpenAI},
}

%%%%%%%%%%%%%%%%%%%%%%%%%%
% Pre-Trained Model      %
%%%%%%%%%%%%%%%%%%%%%%%%%%

% RoBERTuito
@inproceedings{perez2022robertuito,
  title={RoBERTuito: a pre-trained language model for social media text in Spanish},
  author={P{\'e}rez, Juan Manuel and Furman, Dami{\'a}n Ariel and Alemany, Laura Alonso and Luque, Franco M},
  booktitle={Proceedings of the Thirteenth Language Resources and Evaluation Conference},
  pages={7235--7243},
  year={2022}
}
% BETO
@article{canete2020spanish,
  title={Spanish pre-trained bert model and evaluation data},
  author={Canete, Jos{\'e} and Chaperon, Gabriel and Fuentes, Rodrigo and Ho, Jou-Hui and Kang, Hojin and P{\'e}rez, Jorge},
  journal={Pml4dc at iclr},
  volume={2020},
  pages={2020},
  year={2020}
}
% BERTweet
@inproceedings{nguyen2020bertweet,
  title={BERTweet: A pre-trained language model for English Tweets},
  author={Nguyen, Dat Quoc and Vu, Thanh and Nguyen, Anh Tuan},
  booktitle={Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing: System Demonstrations},
  pages={9--14},
  year={2020}
}

%%%%%%%%%%%%%%%%%%%%%%%%%%
% Datasets               %
%%%%%%%%%%%%%%%%%%%%%%%%%%
% Sentiment Analysis
% Spanish

@article{garcia2020overview,
  title={Overview of TASS 2020: introducing emotion detection},
  author={Garc{\'\i}a-Vegaa, Manuel and D{\'\i}az-Galianoa, Manuel Carlos and Garc{\'\i}a-Cumbrerasa, Miguel {\'A} and del Arcoa, Flor Miriam Plaza and Montejo-R{\'a}eza, Arturo and Jim{\'e}nez-Zafraa, Salud Mar{\'\i}a and C{\'a}marab, Eugenio Mart{\'\i}nez and Aguilarc, C{\'e}sar Antonio and Antonio, Marco and Cabezudod, Sobrevilla and others},
  year={2020}
}


```
