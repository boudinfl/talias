# Abstract

Information retrieval in scientific digital libraries is a time consuming and tedious task, because of an often incomplete indexing scientific articles. Accelerated by the uptake of open access to scientific publications, full-text indexing has not yet led to the expected improvement. Rather, exploiting full-text articles requires the use of complex and error-prone Natural Language Processing techniques which may degrade indexing. In previous work, these techniques are often unstated and their impact on the retrieval effectiveness remains unclear. The purpose of the TALIAS project is to re-assess and compare state-of-the-art keyphrase extraction models at increasingly sophisticated levels of document preprocessing. In doing so, we determine to what extend performance variation across keyphrase extraction systems is a function of the effectiveness of document preprocessing, and study their robustness over noisy text.

# Results

- We showed that performance variation across keyphrase extraction systems is, at least in part, a function of the (often unstated) effectiveness of document preprocessing.

- We empirically showed that supervised models are more resilient to noise, and pointed out that the performance gap between baselines and top performing systems is narrowing with the increase in preprocessing effort.

- We compared the previously reported results of several keyphrase extraction models with that of our re-implementation, and observed that baseline performance is underestimated because of the inconsistence in document preprocessing.

- We released both a new version of the [SemEval-2010 dataset](https://github.com/boudinfl/semeval-2010-pre) with preprocessed documents and our [implementation of the state-of-the-art keyphrase extraction models](https://github.com/boudinfl/pke) using the ``pke`` toolkit for use by the community.

# Participants

- [Florian Boudin](http://florianboudin.org/) - Principal investigator
- [Béatrice Daille](http://bdaille.com/)
- [Nicolas Hernandez](https://sites.google.com/site/nicolashernandez/)
- [Adrien Bougouin](http://adrien-bougouin.github.io/)
- [Hugo Mougard](https://github.com/m09)
- [Damien Cram](http://www.univ-nantes.fr/cram-d)


# Publications

- **[How Document Pre-processing affects Keyphrase Extraction Performance](http://aclweb.org/anthology/W16-3917.pdf).** \\
  [[arXiv](https://arxiv.org/abs/1610.07809), [bib](http://aclweb.org/anthology/W16-3917.bib), [code](https://github.com/boudinfl/pke), [dataset](https://github.com/boudinfl/semeval-2010-pre)]\\
  Florian Boudin, Hugo Mougard and Damien Cram.\\
  *COLING 2016 Workshop on Noisy User-generated Text (WNUT).* 

- **[pke: an open source python-based keyphrase extraction toolkit](http://aclweb.org/anthology/C16-2015.pdf).** \\
  [[bib](http://aclweb.org/anthology/C16-2015.bib), [code](https://github.com/boudinfl/pke)]\\
  Florian Boudin.\\
  *International Conference on Computational Linguistics (COLING), demonstration papers, 2016.*

- **[Keyphrase Annotation with Graph Co-Ranking](http://aclweb.org/anthology/C16-1277.pdf).** \\
  [[bib](http://aclweb.org/anthology/C16-1277.bib)]\\
  Adrien Bougouin, Florian Boudin, Béatrice Daille.\\
  *International Conference on Computational Linguistics (COLING), 2016.*
