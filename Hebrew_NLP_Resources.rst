Herbew NLP Resources
####################

This is meant to be a list of Hebrew NLP resources, both for general use and to be used as reference when discussing what existing tools can be opened, adapted or integrated to help create a good Open Source foundation for NLP in Hebrew, as part of the `NLPH Project <https://github.com/NLPH/NLPH>`_.

Additionally, a great list of NLP tools for Hebrew can be found here:
https://github.com/iddoberger/awesome-hebrew-nlp


.. contents::

.. section-numbering::


Corpora
=======

* `The MILA corpora collection <http://www.mila.cs.technion.ac.il/resources_corpora.html>`_  - The MILA center has 20 different corpora available under the GPL license, free for non-commercial use. All are available in plain text format, and most have tokenized, morphologically-analyzed, and morphologically-disambiguated versions available too.

* `Hebrew Wikipedia dumps <https://dumps.wikimedia.org/hewiki/latest/>`_ - Wikipedia the free encyclopedia, publish its content in CC-BY-SA 3.0 as XML dumps monthly. 

* `שתי שקל <https://he.wikipedia.org/wiki/%D7%95%D7%99%D7%A7%D7%99%D7%A4%D7%93%D7%99%D7%94:%D7%AA%D7%97%D7%96%D7%95%D7%A7%D7%94/%D7%A9%D7%AA%D7%99_%D7%A9%D7%A7%D7%9C>`_ - Wikiproject for correcting grammar mistakes. (Heuristic) positive annotions can be derived  from  `query <https://quarry.wmflabs.org/query/21957>`_. 

Lexicons, Dictionaries, Etc.
============================

* The BGU morphological lexicon

* Uniform - an inflection dictionary

* The morphological lexicon of the Israeli National Institute for Testing and Evaluation

* `The Hebrew Treebank <http://www.mila.cs.technion.ac.il/resources_treebank.html>`_ - The Hebrew Treebank Version 2.0 contains 6500 hand-annotated sentences of news items from the MILA HaAretz Corpus, with full word segmentation and morpho-syntactic analysis. Morphological features that are not directly relevant for syntactic structures, like roots, templates and patterns, are not analyzed. This resource can be used freely for research purposes only.

* `The MILA lexicon of Hebrew words <http://www.mila.cs.technion.ac.il/resources_lexicons_mila.html>`_ - The lexicon was designed mainly for usage by morphological analyzers, but is being constantly extended to facilitate other applications as well. The lexicon contains about 25,000 lexicon items and is extended regularly. Available under the GPL license, free for non-commercial use.

* `Hebrew WordNet <http://www.mila.cs.technion.ac.il/resources_lexicons_wordnet.html>`_ -  Hebrew WordNet uses the MultiWordnet methodology and is aligned with the one developed at IRST (and, therefore, aligned with English, Italian and Spanish). Available under the GPL license, free for non-commercial use.

* `MILA's Verb Complements Lexicon <http://www.mila.cs.technion.ac.il/resources_lexicons_verbcomplements.html>`_ - Available under the GPL license, free for non-commercial use.


Papers
======

Corpora, Lexicon and Dictionary Generation
------------------------------------------

* `Hebrew Dependency Parsing: Initial Results <https://www.cs.bgu.ac.il/~yoavg/publications/iwpt2009depbaseline.pdf>`_, IWPT-2009 (Short Paper), Yoav Goldberg and Michael Elhadad

* Alon Itai and Shuly Wintner. `"Language Resources for Hebrew." <http://cs.haifa.ac.il/~shuly/publications/lre4h.pdf>`_ Language Resources and Evaluation 42(1):75-98, March 2008.

* Noam Ordan and Shuly Wintner. `"Hebrew WordNet: A Test Case of Aligning Lexical Databases Across Languages." <http://cs.haifa.ac.il/~shuly/publications/wordnet.pdf>`_ International Journal of Translation 19(1):39-58, 2007.

* Noam Ordan and Shuly Wintner. `"Representing Natural Gender in Multilingual Lexical Databases." <http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.81.8099&rep=rep1&type=pdf>`_ International Journal of Lexicography 18(3):357-370, September 2005.

* Khalil Sima'an, Alon Itai, Yoad Winter, Alon Altman and Noa Nativ. `"Building a Tree-Bank of Modern Hebrew Text." <http://www.cs.technion.ac.il/~winter/Corpus-Project/paper.pdf>`_ Traitment Automatique des Langues, 42, 347-380. 2001.


Morphological Analysis & Disambiguation
---------------------------------------

* Shlomo Yona and Shuly Wintner. `"A Finite-State Morphological Grammar of Hebrew." <http://cs.haifa.ac.il/~shuly/publications/morphgram.pdf>`_ Natural Language Engineering 14(2):173-190, April 2008. Language Resources and Evaluation 42(1):75-98, March 2008.

* Roy Bar-Haim, Khalil Sima'an and Yoad Winter. `Part-of-Speech Tagging of Modern Hebrew Text. <http://www.cs.technion.ac.il/~barhaim/MorphTagger/HebrewPOSTaggingNLE.pdf>`_ Natural Language Engineering 14 (2):223-251. Copyright Cambridge University Press. 2008.


Code
====

Also see here:  https://github.com/iddoberger/awesome-hebrew-nlp


Tokenization
------------

* `The MILA Hebrew Tokenization Tool <http://www.mila.cs.technion.ac.il/tools_token.html>`_ - Available under the GPL license, free for non-commercial use.


Morphological Analysis & Disambiguation
---------------------------------------

* `The MILA Morphological Analysis Tool <http://www.mila.cs.technion.ac.il/tools_analysis.html>`_ - Takes as input undotted Hebrew text (formatted either as plain text or as tokenized XML following MILA's standards). The Analyzer then returns, for each token, all the possible morphological analyses of the token, reflecting part of speech, transliteration, gender, number, definiteness, and possessive suffix. Available under the GPL license, free for non-commercial use.

* `The MILA Morphological Disambiguation Tool <http://www.mila.cs.technion.ac.il/tools_disambiguation.html>`_ - Takes as input morphologically-analyzed text and uses a Hidden Markov Model (HMM) to assign scores for each analysis, considering contextual information from the rest of the sentence. For a given token, all analyses deemed impossible are given scores of 0; all n analyses deemed possible are given positive scores. Available under the GPL license, free for non-commercial use.

* `Hspell <http://hspell.ivrix.org.il/>`_ - Free Hebrew linguistic project including spell checker and  morphological analyzer. Available under AGPL v3. 
  * `HspellPy <https://github.com/eranroz/HspellPy/>`_  - Python wrapper for hspell. Available under AGPL v3.
  
Other
-----

( `HebMorph <https://github.com/synhershko/HebMorph>`_ - An open-source effort to make Hebrew properly searchable by various IR software libraries. Includes Hebrew Analyzer for Lucene. Available under AGPL v3.
