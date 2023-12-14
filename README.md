# NLP-Datasets

These resources includes articles related to the field of natural language processing (NLP).

NLP-Сorpus is sourced from open information available at [Habr](https://habr.com/ru/articles/). The articles in this corpus span from January 1, 2010, to September 20, 2023. 

Datasets were created based on a fragment of the NLP-Corpus with BIO-format tagging. Both datasets can be used in solving NER tasks. The first dataset includes term tagging, while the second one involves tagging of ontology entities. Read more [here](./datasets/system_of_entities.md).

Example from the first dataset: 
```
# text =   Заметки об NLP (Natural Language Processing).
Заметки O
об O
NLP B-TERM
( O
Natural B-TERM
Language I-TERM
Processing I-TERM
) O
. O
```

Example from the second dataset: 
```
# text =   Заметки об NLP (Natural Language Processing).
# relations = "Science_IsAlternativeNameFor_Science 0 1"
Заметки O
об O
NLP B-Science
( O
Natural B-Sciencef
Language I-Science
Processing I-Science
) O
. O

```

