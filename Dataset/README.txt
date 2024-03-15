******************************************
******************************************
************** MCE CORPUS ****************
******************************************
******************************************


MCE Corpus is the English translated version of the corpus Spanish Movie Reviews (http://www.lsi.us.es/~fermin/index.php/Datasets), which was presented in the paper Clasificación de documentos basada en la opinión: experimentos con un corpus de críticas de cine en español (issue 41 of the journal Procesamiento del Lenguaje Natural).

The MCE Corpus has 3,878 English movie reviews, which are ranked in a scale from 1 (negattive) to 5 (positive). The number of documents per each class is:

1 --> 351
2 --> 923
3 --> 1,253
4 --> 890
5 --> 461


The MCE-corpus.tar.gz contains 3,875 xml files, one per each review. The name of the file is the identification number of each review. Each file has three fields:

1.- Review: It has information about the review. The field has 5 properties:
	1.1 Author:	The author of the review
	1.2 Title:	The title of the movie
	1.3 Rank:	The polarity rank (1-5)
	1.4 MaxRank:	The posible maximum rank. Always is 5.
	1.5 Source:	The webpage Muchocine
2.- Summary: In this field the author of the review expresses with few words his opinion about the film
3.- Body: It is the movie review.

If you use this corpus for your experiments, please, cite the following paper:

Martín-Valdivia, M. T., Martínez-Cámara, E., Perea-Ortega, J. M., & Alfonso Ureña-López, L. (2012). Sentiment polarity detection in Spanish reviews combining supervised and unsupervised approaches. Expert Systems with Applications.
http://dx.doi.org/10.1016/j.eswa.2012.12.084

If you need more information about the corpus you can contact with:
Jose M. Perea Ortega: jose-manuel.perea-ortega@jrc.ec.europa.eu
Eugenio Martínez Cámara: emcamara@ujaen.es
