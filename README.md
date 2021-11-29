# pavementdistressdetection
Repository for Google Colab notebooks for use in pavement distress detection on images and videos
To access our data set use the following instructions

To download our data set from Roboflow use the following code in the Colab Notebook under the Data Download section:
>!pip install roboflow
>
>from roboflow 
>import Roboflow
>
>rf = Roboflow(api_key="pkoPigON328wDd7jwy4E")
>
>project = rf.workspace().project("pavement-distresses")
>
>dataset = project.version(12).download("yolov5")

You may also download the dataset directly through your terminal using the following code:
>curl -L "https://app.roboflow.com/ds/qETIYGFoiw?key=l5JFaEUH1c" >
>
> roboflow.zip; unzip roboflow.zip; rm roboflow.zip

You may also download the zip file directly through your browser using the following link:
>https://app.roboflow.com/ds/qETIYGFoiw?key=l5JFaEUH1c
