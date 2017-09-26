# wordnet-prolog

https://github.com/ekaf/wordnet-prolog

*Wordnet-prolog* includes new versions of the _WNprolog_ databases,
generated by Eric Kafe, and bundled with a copy of the original
WNprolog-3.0 documentation (c) 2012 Princeton University.

_WNprolog-3.0BF.tar.gz_ is a bugfix release of _WNprolog-3.0_.
It fixes some known problems, including the transitive hyponym bug.

_WNprolog-3.1.tar.gz_ is a _Prolog_ version of _WordNet 3.1_.

The accompanying _wnprolog.pl_ file is a SWI-prolog program 
implementing some common WordNet use cases, and a few formal checks, 
like symmetry and transitive loop detection.

## Other formats

For convenient inter-operation with other projects, the included  _pl2csv_ and _csv2tab_ scripts
convert the Prolog databases to repectively comma- and tab-separated CSV files, which can be
easily imported into most database systems.
The resulting output constitutes full WordNet versions, and is available in the following packages:

* _WNcsv-3.0BF.tar.gz_
* _WNtab-3.0BF.tar.gz_
* _WNcsv-3.1.tar.gz_
* _WNtab-3.1.tar.gz_
