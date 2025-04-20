The dataset is too large for GitHub. You can download it from here:
https://drive.google.com/drive/folders/1m2_UIrBUTkNdJHfOT6hgVu_jDV-pdX9R?usp=drive_link

__"Creator":__

Trains an lstm model to predict time series of EEG data of requested patients ('Healthy', 'AD', 'FTD')

__"Tester":__

Takes a trained model and uses it to predict data, as well as basically evaluate the model's performance.
Afterwards saves the prediction and actual data as NPZ files for later use.
NPZ files are accesible here:
https://drive.google.com/drive/folders/1094D1FgnALBGMZWLiuxGiRBJyQ8VPinq?usp=drive_link

__"Compare":__

Presents the predicted data to visualy compare the different groups.

__"SVM":__

Creates an SVM model to classify predicted data into the three classes of its patients.
