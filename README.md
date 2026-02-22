# SAS2Python

Offline SAS-to-Python converter. Single HTML file, no server needed — open it in a browser and paste your SAS code.

Built for banking and financial services teams migrating legacy SAS codebases to Python (pandas/numpy/scipy).

## What it handles

- **13 PROCs**: SORT, MEANS, FREQ, PRINT, CONTENTS, SQL, TRANSPOSE, RANK, UNIVARIATE, CORR, REG, LOGISTIC, IMPORT/EXPORT
- **DATA steps**: SET, MERGE, IF/THEN/ELSE, DO loops, RETAIN, arrays, OUTPUT
- **Macros**: `%LET`, `%MACRO/%MEND`, `%IF/%THEN`, `%DO` loops, `%INCLUDE`, `%SYSFUNC`
- **55+ function mappings**: `INPUT()`, `PUT()`, `INTCK()`, `INTNX()`, `CATX()`, `COMPRESS()`, and more
- **Format handling**: `PROC FORMAT` value/invalue ranges, date/datetime informats

## Usage

Open `index.html` in any browser. Paste SAS code on the left, get Python on the right.

No installation, no dependencies, no data leaves your machine.

## License

MIT
