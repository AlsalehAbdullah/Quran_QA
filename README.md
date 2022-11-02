# Quran_QA

This is **Team LK2022** code submission on the [Qur'an Question and Answering](https://sites.google.com/view/quran-qa-2022) shared task on [OSCAT workshop](https://osact-lrec.github.io/) at [LREC conference](https://lrec2022.lrec-conf.org/en/). Please refer to our [paper](http://www.lrec-conf.org/proceedings/lrec2022/workshops/OSACT/pdf/2022.osact-1.14.pdf).

# QA Model and Language Model
The model that was used for this expriemnt is [Simple Transformers](https://simpletransformers.ai/). As for the pre-trained language model, we used [AraBERT V0.2](https://github.com/aub-mind/arabert)


# Important note
- The notebook is designed to work on Google Colab.
- At the end of the experiment after creating the json file, please consider the following:
1. open the json file, and
2. Add the opening curly bracket "{" at the beginning of the file, and
3. Remove the comma "," at the end of the file, and
4. Adding a closing curly bracket "}" at the end of the file. 
5. Then, run the file on the submission_ckecker.py script.

## Citation
```
@InProceedings{alsaleh-EtAl:2022:OSACT,
  author    = {Alsaleh, Abdullah  and  Althabiti, Saud  and  Alshammari, Ibtisam  and  Alnefaie, Sarah  and  Alowaidi, Sanaa  and  Alsaqer, Alaa  and  Atwell, Eric  and  Altahhan, Abdulrahman  and  Alsalka, Mohammad},
  title     = {LK2022 at Qur'an QA 2022: Simple Transformers Model for Finding Answers to Questions from Qur'an},
  booktitle      = {Proceedinsg of the 5th Workshop on Open-Source Arabic Corpora and Processing Tools with Shared Tasks on Qur'an QA and Fine-Grained Hate Speech Detection},
  month          = {June},
  year           = {2022},
  address        = {Marseille, France},
  publisher      = {European Language Resources Association},
  pages     = {120--125},
  abstract  = {Question answering is a specialized area in the field of NLP that aims to extract the answer to a user question from a given text. Most studies in this area focus on the English language, while other languages, such as Arabic, are still in their early stage. Recently, research tend to develop question answering systems for Arabic Islamic texts, which may impose challenges due to Classical Arabic. In this paper, we use Simple Transformers Question Answering model with three Arabic pre-trained language models (AraBERT, CAMeL-BERT, ArabicBERT) for Qur'an Question Answering task using Qur'anic Reading Comprehension Dataset. The model is set to return five answers ranking from the best to worst based on their probability scores according to the task details. Our experiments with development set shows that AraBERT V0.2 model outperformed the other Arabic pre-trained models. Therefore, AraBERT V0.2 was chosen for the the test set and it performed fair results with 0.45 pRR score, 0.16 EM score and 0.42 F1 score.},
  url       = {https://aclanthology.org/2022.osact-1.14}
}
```
