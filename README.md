# A Comprehensive Dataset of Spelling Errors and Users’ Corrections in Croatian Language

## Short description

This dataset contains 33,382,330 entries of the form "error word → correct word" collected from 900,000 users of Croatian Academic Spelling Checker [Ispravi.me](https://ispravi.me/) between December 2008 and March 2023. 

We identified 5,584,226 unique "error word → correct word" pairs. In total, 5,296,266 unique words were misspelled, which we corrected to a total of 1,530,329 words.

The dataset is distributed as a gzipped tab-separated Unicode text file. Each file contains data for one year, and the file name is in the format “ispravime-YEAR.gz”. The rows of individual files are sorted by date (first column, YYYY-MM-DD) in ascending order. The dataset is updated every year when new files are added to the dataset.

## Usage
The dataset, compiled from the contribution of nearly 900,000 users, is a valuable resource for researchers and developers in the field of Natural Language Processing (NLP), improving spellcheck accuracy, and language learning applications. The dataset may be used to accomplish several goals: 
<ol>
  <li>improving spellchecking accuracy by incorporating common user corrections and reducing false positives and negatives;</li>
  <li>helping language learners identify common errors and learn correct spelling through targeted feedback;</li>
  <li>analyzing data trends and patterns to uncover the most common spelling errors and their underlying causes;</li>
  <li>identifying and evaluating factors that influence typing input;</li>
  <li>improving NLP applications such as text recognition and machine translation.</li>
</ol>
 
Tasks specific to Croatian language include the creation of a letter-level confusion matrix and the refinement of word suggestions based on his-torical usage of the service. This comprehensive dataset provides researchers and practitioners with a wealth of information, opening the path for advancements in spellchecking, language learning, and NLP applications in Croatian language.
