# Inseclab Project
This is my group's project for Inseclab training course.
# Member
| Index | Full name | ID Card | Role |
|-------|-------|-------|
| 1 | Pham Hoang Le Nguyen | 22520982 | Leader |
| 2 | Phan Quoc Dat | 22520233 | Member |
# Dataset
<br/>[Download phishing](https://uithcm-my.sharepoint.com/:f:/g/personal/22520982_ms_uit_edu_vn/ElC2kZcK6RdNkYmsPNBwl8AB_eqFH19IbFq0z7Ov9ej6cQ?e=w4JEgl). Code include the download of 3 csv file: train, valid and test. The dataset include testcases about the content of emails and their labels.
# Model
<br/>[Download model](https://uithcm-my.sharepoint.com/:u:/g/personal/22520982_ms_uit_edu_vn/ES75jFI1ZOpGpuFfnEscqmoBnP1JAOHYD-yp9HTXTamB1g?e=uvqx3d). There is the model which we use for our demo.
## Usage
# Preparation
Install the neccessary libraries in `requirement.txt`(please change the path of the file if necessary):
~~~
pip install -r requirement.txt
~~~
# Demo:
Run the file `demo.ipynb`. Please change the path in the line `model = pickle.load(open("/content/fakenewsdetection/fakenews.sav", 'rb'))` to the actual path of the file `fakenews.sav`. After running, enter the link provided in the file to access the website.
