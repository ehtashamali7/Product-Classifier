The current repository includes a Jupyter Notebook file downloaded from Google Colab, where the dataset was created using images obtained from the provided link for the app. Initially, screenshots were taken of the targeted categories, followed by organizing them into respective folders. Additionally, cropping of the images was performed to remove unnecessary areas captured during screenshots.

Subsequently, a zip file containing the dataset folder was created and uploaded to Google Drive to streamline the process, avoiding multiple uploads on Google Colab. To expedite the training process, the images were converted into numpy arrays. Training directly with images would have consumed considerably more time and computation power.

Data management was then carried out according to requirements, with only five categories collected initially due to some being missing. Augmentation techniques were applied to impart product characteristics from different angles and perspectives. The dataset was split into three parts, allocating 80% for training and the remaining divided between validation and testing.

Sequential layers were employed for model training, with early stopping implemented to mitigate computation costs. Additionally, transfer learning was experimented with using a pre-trained model to assess its impact. Results revealed model instability throughout training, possibly due to class imbalance or other factors.

Efforts were made to address this instability by adjusting parameters, altering layers, and modifying learning rates. The presented outcome represents the best result achieved amid this iterative process. While acknowledging its room for improvement, I remain committed to refining the model over time.


  Dataset link :
https://drive.google.com/file/d/1pI1uJmdb6HXfut5QMNr67jKZgo_II2lV/view?usp=drive_link

Vedio Link: https://vimeo.com/925821813/36b2f224b7?share=copy

