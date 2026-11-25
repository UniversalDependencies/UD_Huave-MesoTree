# Summary

UD Huave-MesoTree consists of example sentences in San Mateo del Mar Huave annotated as part of the
NSF-funded project "Syntactically-annotated corpora for endangered languages in areal contact"
(MesoTree).

# Introduction

Huave (_ombeayiüts_) is a language isolate spoken on the Pacific coast of the Isthmus of Tehuantepec
in Oaxaca, Mexico. The treebank is of the variety of San Mateo del Mar.

The sentences are example sentences (with Spanish translation) sourced from the _Diccionario huave
de San Mateo del Mar_ (Stairs Kreger & Scharfe de Stairs 1981). The sentence IDs give the position of the
example in the dictionary: in `0274-034:06`, `034` is the page.

The dictionary is written in the older SIL orthography. In the treebank, the sentences are respelled in
the orthography used in recent Huave materials (_k_ and _kw_ instead of _c_, _qu_ and _cu_; _g_ instead of
_gu_ before _e_ and _i_). The original spelling is kept in `text[orig]` and the Spanish translation in
`text[spa]`. Where available, the dictionary headword that the example illustrates is given in the
`headword` comment.

The sentences were annotated in Arborator-Grew. Annotations exported from Arborator are then
corrected with rule-based postprocessing (feature fixes agreed by the annotation team and
`SpaceAfter` corrections), and only sentences that pass validation are included. Lemmas and
morphological features are not yet annotated for the whole corpus.

# Citation

If you use this treebank in your research, please cite:

@inproceedings{pugh-etal-2026-mesotree,
title = "{M}eso{T}ree: Annotated Linguistic Resources for Quantitative Comparative Linguistic Analysis and {NLP} in Mesoamerica",
author = "Pugh, Robert and
Tyers, Francis and
Henderson, Robert",
editor = {{\c{C}}{\"o}ltekin, {\c{C}}a{\u{g}}r{\i} and
Dobrovoljc, Kaja},
booktitle = "Proceedings of the Ninth Workshop on {U}niversal {D}ependencies ({UDW} 2026)",
month = may,
year = "2026",
address = "Palma de Mallorca, Spain",
publisher = "ELRA Language Resources Association (ELRA)",
url = "https://aclanthology.org/2026.udw-1.17/",
doi = "10.63317/2xvtti733shi",
pages = "197--207"
}

# Acknowledgments

We would like to thank the Huave speakers and annotators who worked on these sentences, and the
authors and Huave collaborators of the _Diccionario huave de San Mateo del Mar_ (Proceso Olivares
Oviedo, Tereso Ponce Villanueva and Lorenzo Comonfort Llave). This work was supported by NSF grant
2319246/2319247, "Collaborative Research: Syntactically-annotated corpora for endangered languages
in areal contact".

## References

- Pugh, R., Tyers, F., & Henderson, R. (2026, May). MesoTree: Annotated Linguistic Resources for Quantitative Comparative Linguistic Analysis and NLP in Mesoamerica. In The Ninth Workshop on Universal Dependencies (UDW 2026), (pp. 197–207).
- Stairs Kreger, G. A., & Scharfe de Stairs, E. F. (1981). Diccionario huave de San Mateo del Mar. Serie de Vocabularios y Diccionarios Indígenas "Mariano Silva y Aceves" 24. México, D.F.: Instituto Lingüístico de Verano.

# Changelog

- 2027-05-15 v2.20
  - Initial release in Universal Dependencies: 189 validated example sentences (1,528 tokens)
    from the _Diccionario huave de San Mateo del Mar_.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.20
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: grammar-examples
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Tyers, Francis
Contributing: elsewhere
Contact: ftyers@iu.edu
===============================================================================
</pre>
