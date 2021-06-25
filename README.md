# Virtual-Self 
A Text to Video Animator

The system creates your virtual self what is does is make an image come alive. It takes only a close-up image of you and a text input and a gender choice for the voice that you want and once done. The system will create a video of your image speaking the text that you provided and email it to you on your given email id.

### Pre-trained checkpoint
Checkpoints can be found under following link: [google-drive](https://drive.google.com/open?id=1PyQJmkdCsAkOYwUyaj_l-l0as-iLDgeH) or [yandex-disk](https://yadi.sk/d/lEw8uRm140L_eQ).
Place the checkpoint in the checkpoint folder

### Downloading the models
The models were hosted on git LFS. However the demand was so high that I reached the quota for free gitLFS storage. I have moved the models to GoogleDrive. Models can be found [google-drive](https://drive.google.com/open?id=1pJdsnknLmMLvA8RQIAV3AQH8vU0FeK16).
Place the model file(s) under sda/data/

### Installation (Preferrably Windows)

We support ```python3```. To install the dependencies run:
```
pip install -r requirements.txt
```
### Demo
Run the Final Code.py (Check default parameters) 
This takes 3 inputs 
1. Image
2. Text 
(Both should be present in inputs folder. Text has to be edited in the inputs folder)
3. Gender 
(For voice type -  male or female)

``` python FinalCode.py --source_image pathtoimage --voice male/female ``` 

### Look of WebApp 
