# Formula-1-Race-winner-and-strategy-prediction

## Authors
##### Atharv Anant Athavale
##### Atharva Anil Chanda
##### Atul Krishnan


## Introduction
This project is done by our above mentioned team as a part of our machine intelligence mini project of Semester 5. In this project, we have striven to create an effective prediction model to find the next race winner in the popular motor sport formula 1 and also predict the life span of the car tyres in order to come up with an effective race strategy. This project has been done completely using python !!

Since we wanted this to be decently accurate , we have considered the data set of the 2022 season of which we have collected and analysed data of 4 races which we found as game changers in order to predict the next couple of races . All the data used in this project is available publically and was extracted by us using the FastF1 api in python . 


## Getting Started
1. Download all the datasets and notebooks provided.
2. Install the library 'FastF1' incase you require to download your own datasets.


## Running the Race Winner Model
1. The dataset that needs to be Pre-Processed is provided as 'PreProcessingDataset.csv'. This can be run on the 'F1_PreProcessing_RaceWinner' notebook to eliminate unwanted information.
2. The 'Test_RaceWinner' and 'Train_RaceWinner' datasets should be loaded on to the 'F1_RaceWinner' notebook.
3. On running the notebook, the predictions of the position each driver is likely to finish appears. This is segregated into 3 classes (0, 1, 2) where 0 implies top 3-4, 1 implies 4-10 and 2 implies anything after that.


## Running the Race Strategy Model
1. Load the 'Test_RaceStrategy.csv' and 'Train_RaceStrategy.csv' files on to the notebook 'F1_RaceStrategy'.
2. Run the notebook. All Pre-Processing is handled in it.
3. The life span of each tyre for each respective driver as well as the average life span will be displayed.
4. Based on this, we will be able to predict what combination of tyres will be most beneficial for each driver.


## License

[MIT](https://choosealicense.com/licenses/mit/)
