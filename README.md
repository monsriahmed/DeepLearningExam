This repository contains the code producing Textual Data Sentiment Analysis.
This work is proposed as a deep learning project within the National Engineering School of Tunis(ENIT), supervised by M. Fares El Kahla and Ms. Sabrine Krichen our industry adjunct for the deep learning course.
For this project a GPU is needed to run the simulations in a reasonable time. To set the environment run in your conda main environment(make sure to upload requirements.txt and kaggle.json file):

pip install -r requirements.txt

In order to load the data directly from kaggle use this code lines:
!pip install kaggle
! mkdir ~/.kaggle
! cp kaggle.json ~/.kaggle/
! chmod 600 ~/.kaggle/kaggle.json
!kaggle datasets download -d kazanova/sentiment140
!unzip sentiment140.zip

A kaggle.json file is a configuration file that is used to connect to the Kaggle API. It contains the credentials (username and API key) needed to authenticate and access the API. The file is used by the Kaggle command line tool and the Kaggle Python library to access and interact with the Kaggle platform. It should be placed in the root of the user's local machine's home directory, and should not be shared with others as it contains sensitive information.

For more details, refer to the report.
