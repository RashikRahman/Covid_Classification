# Pneumonia classification from covid patient chest xray


Developed a CNN model to recognize pneumonia from chest xray of covid patients. Also the model is implemented in web-end for ease of use. Dependencies to run the web-edn are the followings:

```ini
Flask==1.1.2
joblib==1.0.1
Keras==2.4.3
numpy
scipy==1.5.4
opencv-python==4.5.1.48
pywebio==1.2.3
scikit-image
tensorflow==2.4.1
argparse

```

# How to use?

Clone the repo(link attached below), then goto the server subdirectory. Open anaconda dir and type in the following commands.

```ini

cd 'path_to_repo/Server'

pip install -r requirements.txt

```

After installation of the dependencies now you need to run the following command.

```ini 

python app.py
```

Then the web will start at port **http://localhost:8080/**. Then you can just upload a chest xray given in data subdirectory and see predictions. Some evaluation metrics and usage are given below.

![Imgur](https://i.imgur.com/lQZZ5Zc.png)

![Imgur](https://i.imgur.com/QQnHNhX.png)

![Imgur](https://i.imgur.com/IiClzuf.png)


 
