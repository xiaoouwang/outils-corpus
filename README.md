# Outils de traitement de corpus — Master Plurital

## Pratique

~~6 séances les lundis de 9h à 12h dans l'amphi 5 de l'INALCO, PLC, 65 rue des grands moulins, 75013 Paris.~~  
6 séances les lundis de 10h à 12h sur Discord.

## Évaluation

Un devoir à rendre après chaque séance.  
6 séances, 6 devoirs, 6 notes. La note finale sera la moyenne des notes.

Vous pouvez vérifier que j'ai bien reçu vos devoirs sur [cette page](devoirs-rendus.md)

## Séances

### 16 mars 2020

* [intro, définitions, formats d'annotations, outils de requêtes](outils_corpus-1.html)

* Devoir : trouver et renseigner, à l'aide des 6 critères vus en cours, 4 corpus dont 1 *gros* corpus. 

### 23 mars 2020
* [Mots, types, tokens](outils_corpus-2.html)
* [Extraction d'informations](outils_corpus-3.html)

* devoir : calculer le ratio type/token pour les discours sur l'état de l'Union de [2016](files/stateoftheunion2016.txt) et [2017](files/stateoftheunion2017.txt)

  Pour la tokenization, utilisez le [tokenizer de Stanford](https://nlp.stanford.edu/software/tokenizer.shtml), [NLTK](http://www.nltk.org) ou [Spacy](https://spacy.io/)
  Vous devez envoyer le résultat ainsi que la description de vos traitements (scripts, outils, …)

### 30 mars 2020

* [Graphes, Grew, Spacy](outils_corpus-4.html)
* [notebook](outils_corpus-4.ipynb)

* devoirs : 
  - Avec [Grew-match](http://match.grew.fr/?corpus=UD_French-Sequoia@2.5#), trouvez dans le corpus UD_French-Sequoia@2.5 :
     - tous les triplets sujet, verbe, objet
     - les phrases avec sujets inversés  
  *Vous me rendez deux requêtes (dans le corps de mail ou un fichier txt)*

  - Avec l'aide du module Spacy, extrayez les triplets (sujet, verbe, objet) des phrases suivantes et commentez les éventuelles erreurs ou manques.

    « Les enfants n'aiment pas trop les asperges. »  
    « Les Français réclament moins d'impôts. »  
    « Les acacias donnent un miel ambré, limpide et fluide. »  
    « L'équipe fait porter le chapeau à l'arbitrage. »  
    « Des nuées de milliards d'insectes, venus de la péninsule Arabique, s'abattent sur la Corne de l'Afrique et dévorent les cultures, mettant en péril la sécurité alimentaire de la région. »  
  *Vous me rendez le notebook completé ou un script Python commenté*



### 20 avril 2019

* Spacy


### 27 avril 2019

* Étiquetage en POS


### 4 mai 2019

* Word embeddings

## Références

  * Tony McEnery and Andrew Wilson. Corpus  Linguistics. Edinburgh: Edinburgh University Press, 2001 (second edition).
  * Céline Poudat et Frédéric Landragin. Explorer un corpus textuel : Méthodes – pratiques – outils. De Boeck Supérieur, 2017.
  * Daniel Jurafsky and James H. Martin.Speech and Language Processing. Pearson, 2008 (second edition). [pdfs de la troisième édition en cours](https://web.stanford.edu/~jurafsky/slp3/)
  * [Lecture Slides from the Stanford Coursera course by Dan Jurafsky and Christopher Manning](https://web.stanford.edu/~jurafsky/NLPCourseraSlides.html)
  * [Site de Sébastien Ruder](http://ruder.io/)
  * [Cours interactif sur Spacy par Ines Montani](https://course.spacy.io/)
