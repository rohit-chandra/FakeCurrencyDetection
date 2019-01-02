# FakeCurrencyDetection
 Build an artificial neural network that detects fake banknotes using Tensorflow

The dataset is a CSV file that contains information extracted from (wavelet transformed) images of banknotes. There are 1,372 banknotes, each with the following attributes:

1. Image.Var (Variance of Wavelet Transformed image (WTI))
2. Image.Skew (Skewness of WTI)
3. Image.Curt (Curtosis of WTI)
4. Entropy (Entropy of image)
5. Class (Whether or not the banknote was authentic)

# References
Links to the Dataset: [UCI Banknote Authentication] (https://archive.ics.uci.edu/ml/datasets/banknote+authentication)
