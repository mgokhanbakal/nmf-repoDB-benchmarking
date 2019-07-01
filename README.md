# Benchmarking Files Used in NMF Experiments with repoDB Dataset


This repository contains the validation and test set splits of repoDB drug–disease pairs used in the study of "Non-Negative Matrix Factorization for Drug Repositioning: Experiments with the repoDB Dataset".


## For the test set, there are two files under the [benchmark/test/](https://github.com/mgokhanbakal/testRepo/tree/master/benchmark/test) directory:

* *Approved_treatments_test.txt* - Each line represents an approved treatment CUI pair from repoDB in the format of (subject CUI, object CUI).
							  
* *Failed_indications_test.txt* - Each line shows a failed indication CUI pair from repoDB in the format of (subject CUI, object CUI).

							  
## For the validation set, there are two files under the [benchmark/validation/](https://github.com/mgokhanbakal/testRepo/tree/master/benchmark/validation) directory:

* *Approved_treatments_validation.txt* - Each line represents an approved treatment CUI pair from repoDB in the format of (subject CUI, object CUI).
									
* *Failed_indications_validation.txt* - Each line shows a failed indication CUI pair from repoDB in the format of (subject CUI, object CUI).
