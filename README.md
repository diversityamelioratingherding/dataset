# Dataset ranking competition with diversity


## Dataset Description

The dataset comprises data from two different competitions:

| Competition   | Ranking Function
|---------------|-----------------|
| R (Relevance) | E5              |
| D (Diversity) | E5 + MMR        |

Every competition consists of:
- 15 games with 15 queries.
- 7 rounds per game.
- 4 players per game.

Included in the dataset:
- 840 documents submitted by students, 497 of which are unique.
- 15 initial documents, one per topic.

Documents are stored in "trectext" format.

DOCNO Format: "ROUND-\<round_number\>-\<topic_id\>_\<competition\>-\<author_id\>"

Competition B is signed as '0'; competition D is signed as '1'.

## Queries

From the TREC 2009-2012 datasets, we selected topics with commercial intent likely to stimulate competition. 
Each topic is associated with a query.

The full list of selected queries is provided in "queries.txt".


## Relevance Judgments

Relevance was assessed by five annotators on Cloudresearch’s Connect platform, based on the topic title and the description. 
Documents were rated relevant based on their alignment with the stated information need. 
A document’s relevance grade is the count of judges deeming it relevant.

Relevance grades can be found in "documents.rel".


## Quality Judgments

The quality of documents authored by students was also judged by five Cloudresearch annotators. Documents were evaluated as:
1. **Keyword-stuffed** - Contains unnatural repetition of keywords.
2. **Spam** - Content does not meet any conceivable information need.
3. **Valid** - Contents is neither spam nor keyword-stuffed.
A quality grade represents the count of judges who deemed a document valid.

Quality grades can be found in "documents.quality".


## Positions

The position of every docno (from 1 to 4) can be found in 'documents.position'.

## Citations

XX

XXXXXXXXXXXX

