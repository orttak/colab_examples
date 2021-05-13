# Google Colab Examples


#### Moung Google drive
from google.colab import drive
drive.mount('/content/drive/')

import os
os.chdir("target path under drive mount point")
