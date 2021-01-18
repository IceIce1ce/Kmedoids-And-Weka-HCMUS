- hawks.csv: dataset file
- preprocsss.py: because our dataset have some column NaN and a few empty cell which 
  decrease percentage of classification, so we have to preprocess our dataset before using weka
- preprocess.csv: dataset file exported after preprocessing successfully
- preprocess_default.arff: dataset file converted from preprocess.csv
- preprocess_reduce_noise.csv: dataset file exported after preprocessing and removing BandNumber column
- preprocess_reduce_noise.arff: dataset file converted from preprocess_reduce_noise.csv
- Result.xlsx and RawResult.csv: include all features mentioned in 1.1 and 1.2 but we work in two 
  dataset preprocess_default.arff and preprocess_reduce_noise.arff to know which datasets after
  preprocessing help us attain percentage of classification better

