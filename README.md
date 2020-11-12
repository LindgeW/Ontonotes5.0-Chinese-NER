# Ontonotes5.0 Chinese NER dataset 
Notes:
+ The data source is from [https://catalog.ldc.upenn.edu/LDC2013T19/](OntoNotes Release 5.0 - LDC2013T19)
+ The corpus contains 18 named entity types (including 7 value types)
+ The split of train/dev/test portions follows [http://conll.cemantix.org/2012/download/ids/](http://conll.cemantix.org/2012/download/ids)

## Statistics
| #doc | #sent | #word |
| --- | --- | --- |
| 1911 | 48K | 988K |

| Genre | #train | #dev | #test |
| --- | --- | --- | --- |
| BC | 7862 | 2239 | 885 |
| BN | 8149 | 949 | 985 |
| MZ | 3988 | 362 | 451 |
| NW | 3569 | 425 | 516 |
| TC | 7510 | 1129 | 643 |
| WB | 6479 | 1113 | 813 |
| #sum | 37557 | 6217 | 4293 | 


## Description
```
GENRE = {bc bn mz nw tc wb}
SPLIT = {train dev test}

{GENRE}.{SPLIT}.id: document id collections
{GENRE}.{SPLIT}.char: char-level annotated data collections
{GENRE}.{SPLIT}.txt: word-level annotated data collections
{GENRE}.{SPLIT}.raw.txt: raw sentence-level data collections
```
