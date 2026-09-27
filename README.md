# Summary

UD_Tu-GDUD is a treebank of Tu (also called Monguor), a Mongolic language spoken in Qinghai and Gansu provinces of China, based on grammatical example sentences derived from a reference grammar.


# Introduction

The Tu GDUD (Grammar-Derived Universal Dependencies) treebank contains 77 sentences of Tu (ISO 639-3: mjg), a Mongolic language spoken by the Tu (Monguor) people primarily in Qinghai and Gansu provinces of China. Tu is one of the Mongolic languages of the Gansu-Qinghai Sprachbund and has been in extensive contact with Chinese, Tibetan, and other neighboring languages. The data consist of grammatical example sentences drawn from a reference grammar of Tu, presented in Latin transliteration and accompanied by English translations.

All sentences are manually annotated with lemmas, universal part-of-speech tags (UPOS), morphological features, and dependency relations, following the Universal Dependencies (UD) guidelines. The annotation prioritizes UD core morphological features and dependency relations. The language-specific feature `ExtPos` is used in a small number of cases, following the analysis of the reference grammar. Additional Tu-specific morphological distinctions that do not correspond to any value in the universal feature inventory are encoded in the MISC column, in accordance with UD conventions.

## Data split

Because the treebank is small (well below the 20K-word threshold), all sentences are provided as test data.

## Morphological annotation

All UD core features used in the treebank take standard universal values. The feature `ExtPos` is used to mark the external part-of-speech function of certain multiword expressions.

## Dependency annotation

UD core relations are used throughout the treebank. The language-specific subtype `acl:tmod` is used for temporal relative clauses.


# Acknowledgments

The Tu GDUD treebank was created by Wenchao Li and Haitao Liu, based on grammatical example sentences from a reference grammar of Tu. The annotation of lemmas, part-of-speech tags, morphological features, and dependency relations was carried out manually following the Universal Dependencies guidelines.

We thank Daniel Zeman for his guidance in setting up the treebank repository and for his help with the Universal Dependencies workflow, and the Universal Dependencies community for their support.


# Changelog

* 2026-11-15 v2.19
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.19
License: CC BY-SA 4.0
Includes text: yes
Genre: grammar-examples
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Li, Wenchao; Liu, Haitao
Contributing: here
Contact: widelia@zju.edu.cn
===============================================================================
</pre>
