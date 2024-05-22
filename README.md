# Depressed Users on Twitter

Repository for [Classifying Social Media Users Before and After Depression Diagnosis via their Language Usage: A Dataset and Study](https://aclanthology.org/2024.lrec-main.289/) paper, published in LREC-COLING 2024.  All updates on this public dataset can be found in this repository.

The dataset provided here includes an updated version of the original dataset, with ~500k tweets annotated to two classes (before / after) The classes are annotated based on the disclosed date of depression diagnosis : 
* Depressed_users_labels.csv: contains ~500k rows, where every row consists of a unique Tweet ID and its according annotation
* Depression_symptoms_lexicon.txt: contains 598 words related to depression symptoms and diagnosis

You can access tweets/posts' texts by retrieving them from X (Twitter) using the tweet IDs in the file. You can do so using X [developer account for academic research](https://developer.x.com/en/use-cases/do-research/academic-research) 

_**Please cite the paper in any published work that uses any of these resources.**_
```
@inproceedings{alhamed-etal-2024-classifying-social,
    title = "Classifying Social Media Users before and after Depression Diagnosis via Their Language Usage: A Dataset and Study",
    author = "Alhamed, Falwah  and
      Ive, Julia  and
      Specia, Lucia",
    editor = "Calzolari, Nicoletta  and
      Kan, Min-Yen  and
      Hoste, Veronique  and
      Lenci, Alessandro  and
      Sakti, Sakriani  and
      Xue, Nianwen",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    month = may,
    year = "2024",
    address = "Torino, Italy",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-main.289",
    pages = "3250--3260",
}
```


For any further questions contact felwah.alhamed at gmail dot com
