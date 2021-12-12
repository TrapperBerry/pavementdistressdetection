# pavementdistressdetection
This is a senior design project completed by two civil engineering undergraduate students Berry & McHugh at University of Tennessee at Chattanooga (UTC) in December 2021.
The senior design project is titled as "Computer Vision & Civil Engineering: Pavement Distress Object Detection" 

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

Acknowledgement:
The authors greatly appreciate the pavement images received from FHWA LTPP InfoPave.
A good amount of the images were retrieved by the sponsor of this projrect Dr. Weidong Wu at UTC from LTPP InfoPave website.

Note: please cite the work following:
J. Berry, & S. McHugh, (2021), GitHub repository, https://github.com/TrapperBerry/pavementdistressdetection

BibTeX entry:

@misc{Cite,
  author = {Berry, J., McHugh,S.},
  title = {Computer Vision & Civil Engineering: Pavement Distress Object Detectio},
  year = {2021},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/TrapperBerry/pavementdistressdetection}}}
}

