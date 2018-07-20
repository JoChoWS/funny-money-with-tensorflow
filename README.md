## Tensorflow Currency Image Recognition
This project uses Google's Tensorflow library to construct a DNN that can recognize and classify images of banknotes as legal or counterfeit. The data comes from the UCI Machine Learning Repository's Bank Authentication Data Set which contains data regarding 1,372 "images that were taken for the evaluation of an authentication procedure for banknotes." Typically, the term banknote refers to paper money, but can also include a central bank's promissory note to pay a stated sum to the bearer on demand.

Rather than pixel data, the dataset provides numerical information about the images produced via Wavelet transformation.

The data consists of 5 columns:

variance of Wavelet Transformed image (continuous)
skewness of Wavelet Transformed image (continuous)
curtosis of Wavelet Transformed image (continuous)
entropy of image (continuous)
class (integer - indicates whether or not a Bank Note was authentic (1) or counterfeit (0))
