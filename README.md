# titanic_reproducibility

Version 0.1.0

Writing reproducible code in Python using existing public "titanic" dataset and code published on kaggle by Niklas Donge check out the project at https://www.kaggle.com/niklasdonges/end-to-end-project-with-python . 

This was a machine learning project that I decided to "borrow and butcher" for the reproducibility workshop.

This code was originally written in Jupyter notebook, but shared here after editing in the Spyder IDE. The version of Spyder used is Spyder 3.2.8 using Python 3.6. Both of these from the Anaconda https://docs.anaconda.com/anaconda/navigator/
Note: all of this was done on a Windows 10 not tested on any other platform. 

To run the project, execute the script Titanic_repro_end_to_end_from_kaggle.py
The best way to do this is to clone the repository and then have titanic_reproducibility as the working directory.




## Project organization

```
.
├── .gitignore
├── CITATION.md
├── LICENSE.md
├── README.md
├── requirements.txt
├── bin                <- Compiled and external code, ignored by git (PG)
│   └── external       <- Any external source code, ignored by git (RO)
├── config             <- Configuration files (HW)
├── data               <- All project data, ignored by git
│   ├── processed      <- The final, canonical data sets for modeling. (PG)
│   ├── raw            <- The original, immutable data dump. (RO)
│   └── temp           <- Intermediate data that has been transformed. (PG)
├── docs               <- Documentation notebook for users (HW)
│   ├── manuscript     <- Manuscript source, e.g., LaTeX, Markdown, etc. (HW)
│   └── reports        <- Other project reports and notebooks (e.g. Jupyter, .Rmd) (HW)
├── results
│   ├── figures        <- Figures for the manuscript or reports (PG)
│   └── output         <- Other output for the manuscript or reports (PG)
└── src                <- Source code for this project (HW)

```


## License

This project is licensed under the terms of the [MIT License](/LICENSE.md)

## Citation

Please [cite this project as described here](/CITATION.md).
