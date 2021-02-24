###########################################################
The b5 corpus of Text and Personality Information v. 1.7.

R. Ramos, G. Stavracas Neto, B. da Silva, D. Monteiro, V. dos Santos, I. Paraboni, R. Dias

School of Arts, Sciences and Humanities (EACH)
University of São Paulo (USP)

This work is licensed under a Creative Commons Attribution 4.0 International License, and it is free for reuse.

###########################################################

Version 1.0 - 3 January 2017 (initial release)

Version 1.1 - 1 March 2017
	* b5-ref minor attribute and string corrections

Version 1.2 - 8 March 2017
	* allTokens and wordTokens lexical feature names under /post 
	were corrected to allTypes and wordTypes.

Version 1.3. - 29 April 2017
	* Big Five facet information added to subject tables and to XML trials under /ref
	* minor corrections in /ref

Version 1.4. - 03 June 2017
	* Psycholinguistic properties added to lexical features map under /post/
	* Posts with less than 10 items (words etc.) removed.

Version 1.5. - 19 August 2017
	* $FOREIGN$ and $OOV$ symbols are no longer in use. Original words are kept instead.
	* /post now includes all posts over 40 characters-long as a single file with binary Big Five labels 
	* post lexical feature files moved to /post/lexical features/

Version 1.6. - 04 September 2017
	* folder /post moved to /post/text files/
	* (for the non-public version) posts are now available in both ISO and UTF-8 formats
	* posts in lemmatised version are no longer available

Version 1.7. - 14 December 2017
	* publication details updated

###########################################################


===============
1. Overview
===============

The b5 corpus is a collection of text in different genres (Facebook posts, referring expressions, picture long and short descriptions) and Big Five personality inventories.

The corpus makes use of images taken from the Face Place database described in Righi,  Peissig  & Tarr (2012). Recognizing disguised faces. Visual Cognition, 20(2), 143-169. doi:10.1080/13506285.2012.654624

Stimulus images courtesy of Michael J. Tarr, Center for the Neural Basis of Cognition and Department of Psychology, Carnegie Mellon University, http://www.tarrlab.org/. Funding provided by NSF award 0339122. http://wiki.cnbc.cmu.edu/Face_Place


=======
2. Data
=======

The b5 corpus consists of a subjects table (in three versions, on the subjects table folder), and four text corpus: Facebook posts (/post), Referring Expressions (/ref), Text (/text) and Caption (/caption) subsets. All text corpus are linked to the subject table by a unique subject id identifier.

The subjects table is available in three formats (.csv, .csv with Brazilian decimal separator and the full .xlsx table, including the individual answers to every BFI item for every subject). It contains personality information for every subject and additional information (gender, age etc.)

The post subcorpus contains anonymized Facebook posts for over 1000 subjects.

The b5-ref subcorpus is a standard corpus of referring expressions annotated with their semantic attributes and subject id. The corpus has been extensively used in the following paper. If you reuse b5-ref data, please cite this:

@inproceedings{b5-ref,
title={Personality-dependent Referring Expression Generation},
author={Ivandr\'e Paraboni and Danielle Sampaio Monteiro and Alex Gwo Jen Lan},
booktitle={Text, Speech and Dialogue (TSD-2017) Lecture Notes in Artificial Intelligence vol. 10415},
address={Prague, Czech Republic},
publisher={Springer-Verlag},
pages={20--28},
doi={10.1007/978-3-319-64206-2_3},
year={2017}
}

@inproceedings{b5-alex,
  author={Alex Gwo Jen Lan and  Ivandr\'e Paraboni},
  title={Definite Description Lexical Choice: taking speaker's Personality into account},
  booktitle={11th International Conference on Language Resources and Evaluation ({LREC}-2018) (to appear)},
  address={Miyasaki, Japan},
  publisher={{ELRA}},
  year={2018}
}


The text and caption subcorpora contain scene descriptions in long and short versions.



================
3. How to cite 
================

If you wish to use b5 for research purposes, please cite the following articles:

@inproceedings{b5-corpus,
  author={Ricelli Moreira Silva Ramos and Georges Basile Stavracas Neto and Barbara Barbosa Claudino Silva and  Danielle Sampaio Monteiro and  Ivandr\'e Paraboni and Rafael Felipe Sandroni Dias},
  title={Building a Corpus for Personality-dependent Natural Language Understanding and Generation},
  booktitle={11th International Conference on Language Resources and Evaluation ({LREC}-2018) (to appear)},
  address={Miyasaki, Japan},
  publisher={{ELRA}},
  year={2018}
}

@inproceedings{b5-mult,
title={Big Five Personality Recognition from Multiple Text Genres},
author={Vitor Garcia dos Santos and Ivandr\'e Paraboni and B\'arbara Barbosa Claudino Silva},
booktitle={Text, Speech and Dialogue (TSD-2017) Lecture Notes in Artificial Intelligence vol. 10415},
address={Prague, Czech Republic},
publisher={Springer-Verlag},
pages={29--37},
doi={10.1007/978-3-319-64206-2_4},
year={2017}
}




======================
4. Further information
======================

For further information, please feel free to contact the authors:

Ivandré Paraboni
ivandre  @  usp . br
School of Arts, Sciences and Humanities (EACH)
University of São Paulo (USP)
São Paulo, Brazil
