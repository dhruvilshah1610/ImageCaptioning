Image Captioning Based on Deep Neural Networks
This file contains code for generating image captions using a pre-trained image captioning model.
Requirements
* Python 3.x
* Google Colab
* Required Python libraries:
* pycocotools
* keras
* h5py
* Rouge
* pycocoevalcap
* nltk
* gtts
* wordcloud
* matplotlib
The required libraries can be installed using pip.
Usage
* Run the provided Google Colab Notebook ‘Image_CaptioningSubmisson code.ipynb’.
* Download the dataset from https://cocodataset.org/#download and select the 2017 images (Also submitted with this README file).
* Change the path location of the data file in the Google Colab notebook.
* Run all the code segments in the Google Colab notebook to preprocess, visualize, and transform the data. Finally, the code segments will run to train the classification models and evaluate their performance.
* The code can also be modified for future advancements.
Directory Structure
* Image_CaptioningSubmisson code.ipynb contains the code for image captioning.
* models/: Directory to store trained models.
* data/: Directory to store dataset files.
Dataset
The code uses the Microsoft Common Objects in Context (MS COCO) dataset, a freely available resource included within the COCO dataset. We will employ the 2017 train photos. 
Acknowledgments
* The pre-trained model used in this code is based on the Xception architecture.
* This code is based on the research in the field of image captioning.

