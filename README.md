# Smart-India-Hackathon-23
Cloud-Burst prediction

The uploaded data includes several files that are used for model training, testing, and validation. The files and their descriptions are as follows:

**Training.ipynb**: This file contains the code used for model training.

**Testing.ipynb**: This file contains the code used for model evaluation.

**API.ipynb**: This file contains the code for an API that can be used for continuous monitoring and predicting cloudburst on the latest data retrieved from IMD using a pre-trained model.

**CB12.npy**: This file contains Cloudburst Training-Testing Data for 12-Hour Early Prediction.

**CB6.npy**: This file contains Cloudburst Training-Testing Data for 6-Hour Early Prediction.

**Model12.h5**: This file contains the pre-trained 12-Hour Early Prediction model.

**Model6.h5**: This file contains the pre-trained 6-Hour Early Prediction model.

| Model-Feature  | 6H Value | 12H Value |
| ------------- | ------------- | ------------- |
| Optimizer | Adam | rmsprop  |
| Kernel Size  | 2,2  | 1,1  |
| Pooling Size  | 3,3  | 3,3  |
| Learning rate | 0.0005  | 0.0005  |
| Epoch | 50  | 50  |

**NB.npy**: This file contains Non-Cloudburst Training-Testing data.

**TEST12.npy**: This file contains Cloudburst Validation Data for 12-Hour Early Prediction.

**TEST6.npy**: This file contains Cloudburst Validation Data for 6-Hour Early Prediction.
