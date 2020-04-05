# Data repository for correlation functions of Yang-Mills theory

This repository contains data for the ghost and gluon propagators and the ghost-gluon, three-gluon and four-gluon vertices of Landau gauge Yang-Mills theory.
All data is given in physical units of GeV.
The content of the files should be understandable from the comments that can be found there.
Details can be found in [[1]](#YM).
Subdirectories contain data for different ghost renormalization values.
For any questions, please contact [Markus Huber](mailto:markus.huber@physik.jlug.de).
The contained datasets are only a subset of the available data and correspond to the data shown in [[1]](#YM).
Data for more decoupling solutions is available upon request.

## Data and figures in [[1]](#YM)
Correlation function | Figure |Data file
:--------------------|:-------|:--------
Ghost                | 9      | ghost.dat
Gluon 				       | 8  	  | gluon.dat
Ghost-gluon vertex   | 11     | ghost-gluon2.dat
Three-gluon vertex   | 12     | three-gluon2.dat
Four-gluon vertex    | 13     | four-gluon2_SD.dat

### Notes
* For the plots in [[1]](#YM), the dressing functions were rescaled to compare with other results.
* For the vertices two datasets exist: One contains the interpolation points (in case one wants to use the same interpolation as described in [[1]](#YM)), the other contains interpolated data.

## Reference
Data is published in [[1]](#YM).

## Terms of use
This GitHub repository and its contents are provided for free use. Whenever it is used for calculations or plots shown in presentations, publications or something similar, reference [[1]](#YM) should be acknowledged.

---

## References
<a name="YM">[1]</a> Markus Q. Huber, Correlation functions of Landau gauge Yang-Mills theory, [arXiv:2003.13703](https://arxiv.org/abs/2003.13703)
