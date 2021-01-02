**# CS867-Assignment3**

**Introduction:**
This repository contains the notebook file and the necessary image files to reproduce the results of the assignment code. The weights are already trained and the link is provided. 

**Reproducing the results:**

#1  Pre-requisites:

1) The code is run using colab so for most similar results it is advised to run this code on colab with teh gpu available from google. 

2) After that you are required to download to dataset to your google drive for ease of access. The google drive link for the dataset is given below. The first link contains the dataset which is used for training and validating. The second link contains the dataset for testing. 

Training and Validating Dataset:
https://drive.google.com/drive/folders/1AD1qeSb1OnafPxIR9fE79d0mkIuD0I5i?usp=sharing

Testing Dataset:
https://drive.google.com/drive/folders/1LPsZ8Pi8Qd8NTN2hgSZu7pC2pNZpO73f?usp=sharing

3) For the visual results you must upload the images given in this repository to your google drive and create subfolders so that each image is in a folder named by its class. or for ease you can directly download the folder from the link i have provided below. 

Visualizing Classification:
https://drive.google.com/drive/folders/1l4eC_LsTr9wqZVZGYjs42uoiEPtpuy_A?usp=sharing

**#2  Running the Code:**

1) Once the dataset is loaded into your google drive you can run the code. However remember that the code allows for training your own weights along with loading the pre-trained weights. If you wish to train the weights yourself than you can simply run the code. 

2) However if you wish to reproduce my results then you will have to skip the training and weights-saving cells in the code and directly run the load weights cell. The link for the pre-trained weights is given below.

Pre-Trained Weights for Reproducing My Results:
https://drive.google.com/file/d/13cvP_sN7lytz3aNlBKUDSScPADclf8rC/view?usp=sharing

3) If you wish to see the visual results then you can load the images given in the repository and run the last cell. You will see the confusion matrix where each image will be classified into one category and you can judge whether the images have been classified correctly. For reference the classes are in order as below:
Buildings, Forest, Glacier , Mountain, Sea and Street.

**#3  Results:**
The results are given as:

Accuracy Graph:

![Screenshot from 2021-01-02 18-48-07](https://user-images.githubusercontent.com/74458556/103462910-6c033400-4d4a-11eb-8a07-125176870b7d.png)

Loss Graph: 

![Screenshot from 2021-01-02 18-48-16](https://user-images.githubusercontent.com/74458556/103462921-78878c80-4d4a-11eb-8903-5b0ddfa3304c.png)

Confusion Matrix:

![Screenshot from 2021-01-02 18-48-40](https://user-images.githubusercontent.com/74458556/103462930-89d09900-4d4a-11eb-814f-2facad89498b.png)

Classification Report:

![Screenshot from 2021-01-02 19-36-29](https://user-images.githubusercontent.com/74458556/103462894-4fff9280-4d4a-11eb-82bf-211a522f537b.png)

Confusion Matrix for Visual Data:

![Screenshot from 2021-01-02 18-48-51](https://user-images.githubusercontent.com/74458556/103462941-9bb23c00-4d4a-11eb-8308-0ac8135f4729.png)


