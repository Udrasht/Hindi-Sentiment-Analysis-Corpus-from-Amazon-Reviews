# A Hindi Sentiment Analysis Corpus from Amazon Reviews

## Data
Folder contains the train and test data files. This dataset comprises training and test data for sentiment analysis in Hindi, extracted from Amazon reviews. 

## Data Description
- **Training Data:** The training data folder contains 3527 reviews labeled for sentiment analysis. Each review is labeled as positive, negative, or neutral.
  
- **Test Data:** The test data folder contains 884 reviews for evaluating the performance of sentiment analysis models. Similar to the training data, each review is labeled as positive, negative, or neutral.

## Label Distribution
- **Positive:** 36.2% of the training data
- **Negative:** 44.6% of the training data
- **Neutral:** 19.2% of the training data

## How to Use
1. **Training Data:** Utilize the training data to train sentiment analysis models in Hindi.
2. **Test Data:** Evaluate the performance of trained models using the provided test data.

## Models
## Models
Various models for sentiment analysis are available in the code folder, including Support Vector Machine (SVM), Decision Tree, Naive Bayes, Feedforward Neural Network (FFNN), and Long Short-Term Memory (LSTM). The code files contain the implementation of each model, and the file paths are structured according to our Kaggle notebook setup. For LSTM, pre-trained Hindi embeddings from [IndicNLP](https://drive.google.com/file/d/1g5_dJFI3Sevwi-YMPU67x2jnN-_JzZX6/view?usp=sharing) are utilized. Additionally, the Elmo method is employed to create embeddings specific to our dataset, which are then utilized in the LSTM task.

## Additional Information
For more detailed insights into the dataset construction, data preprocessing, experimental setup, and model implementation, please refer to the [report](./A-Hindi-Sentiment-Analysis-Corpus-from-Amazon-Reviews_report.pdf). If you have any further questions or need assistance, feel free to reach out.


## Citation
If you use this dataset in your research or project, please consider citing the dataset as follows:
**Dataset Name:** HSAC  
**Repository Name:** A-Hindi-Sentiment-Analysis-Corpus-from-Amazon-Reviews  
**URL:** [https://github.com/Udrasht/Hindi-Sentiment-Analysis-Corpus-from-Amazon-Reviews](https://github.com/Udrasht/Hindi-Sentiment-Analysis-Corpus-from-Amazon-Reviews)

## Contributors
- Udrasht Pal (udrashtpal@gmail.com or udrasht.pal@students.iiit.ac.in)
- Nikhil Khemchandani (nikhilkhemchandani5@gmail.com or nikhil.khemchandani@students.iiit.ac.in)
- Instructor: Radhika Mamidi (radhika.mamidi@iiit.ac.in)
