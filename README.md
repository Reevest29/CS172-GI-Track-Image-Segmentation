# CS172-GI-Track-Image-Segmentation


### Baseline notebook
Formatted for colab. 

##### Getting started
```
!mkdir ~/.kaggle
!touch ~/.kaggle/kaggle.json

api_token = {"username":"username","key":"key"}

import json

with open('/root/.kaggle/kaggle.json', 'w') as file:
    json.dump(api_token, file)

!chmod 600 ~/.kaggle/kaggle.json
!kaggle competitions download -c uw-madison-gi-tract-image-segmentation
!unzip uw-madison-gi-tract-image-segmentation.zip
```
replace api_token with your kaggle credentials.  
  Kaggle website > account > 5th section "API" > "create New API Token"  
    this should download a file, just copy and paste into api_token =   
