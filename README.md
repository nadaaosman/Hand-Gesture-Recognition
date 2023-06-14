# README

How to run the code:

1.  singlePipline file is the file contain the whole pipline from preprocessing to training models and there accuricies
2.  model file load all pickle classifiers of most heigh accuricies , read data from test folder image by image and it also contains read_test_labels function you con use it to read true labels and it will put it in array for you to use it to compare true labels with the predicted one u can modify in the function the path of the text file (Actual labels)
3.  put test images in test folder (test) in project folder
4.  run all model file
5.  if you want to run the model more than one time please delete time.txt and result.txt manually at each run

NOTE : there is folder named classifiers (which contain the trained classifiers as pickle file to load them in the model file)

the model file will give you 2 files one contain label prediction and the other contain execution time (time.txt,result.txt)

Packages and libraries used:

- cv2: OpenCV library for computer vision tasks
- numpy: Numerical computing library for Python
- os: Operating system interface for Python
- glob: Unix-style pathname pattern expansion for Python
- PIL: Python Imaging Library for image processing tasks
- time: Time-related functions in Python
- re: Regular expression operations in Python
- skimage.feature: Feature extraction algorithms from scikit-image library
- sklearn.model_selection: Model selection and evaluation tools from scikit-learn library
- sklearn.linear_model: Linear models from scikit-learn library
- sklearn.tree: Decision tree algorithms from scikit-learn library
- sklearn.neighbors: Nearest neighbors algorithms from scikit-learn library
- sklearn.naive_bayes: Naive Bayes algorithms from scikit-learn library
- sklearn.svm: Support vector machines algorithms from scikit-learn library
- sklearn.ensemble: Ensemble methods (AdaBoost, Random Forest, Gradient Boosting) from scikit-learn library
- sklearn.metrics: Metrics to evaluate model performance
  from scikit learn library
  from scipy.stats import randint, uniform : Probability distributions and statistical functions from SciPy
  import warnings : Warning control in python
  from sklearn.decomposition : PCA - Principal component analysis implementation in python
  from sklearn.feature_selection : Feature selection algorithms implementation in python
  from skimage.feature : Feature extraction algorithms implementation in python
  from skimage import exposure : Image processing functions implementation in python
  from sklearn.preprocessing import StandardScaler : Data normalization function implementation in python
  from skimage.feature import greycomatrix, greycoprops : Texture feature extraction functions implementation in python  
  from skimage.measure import moments_central, moments_hu : Shape feature extraction functions implementation in python
