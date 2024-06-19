# Detection and information of poisonous mushrooms using machine learning
Team Projects for Embedded Systems and IOT<br/>
YOUTUBE about our team project: 

## 프로젝트 소개
A machine learning project with the theme of "Detecting Poison Mushrooms Using Raspberry Pi". The purpose is to inform the presence or absence of toxicity of mushrooms detected in real time and to provide approximate information on the mushrooms.<br/>
The core of project is machine learning using Yolov8 and raspberry pie, which informs the presence or absence of toxicity of mushrooms detected by cameras connected to raspberry pie with LED signals and provides information on the mushrooms on a web page.

## 개발 기간
 - 2024.5.5 ~ 2024.6.17
 - Writing Project Plan
 - dataset Collect & Labeling(labelme)
 - Machine Learning Programming with YOLOv8
 - Web page programming
 - Raspberry Pi Programming(Python) & Implementation(LED, Camera ..)

## 개발 환경
- Language: Python
- Machine Learning: YOLOv8
- Development environment(IDE): Raspberry Pi, VScode, SSH, VNC
- Labeling tool: Labelme
- Language of web programming: HTML, CSS

## Data set
- Number of data:
- kind of labes(kind of mushroom data):
  - poisonous - Hypholoma fasciculare, Ramaria formosa, Galerina marginata, Amanita virosa<br/>
  - eible - Hypholoma lateritium, agaricus arvensis, Oyster mushroom, Sparassis crispa, Volvariella volvacea, Apioperdon pyriforme
- how to gather data: Using kaggle site - Mushroom Classification Dataset(updated by ZAIN UL ABDIN, https://www.kaggle.com/datasets/zedsden/mushroom-classification-dataset)

## 아키텍쳐


## 주요 기능
1. Reading the Toxicity of Mushrooms
After detecting mushrooms using a camera connected to a raspberry pie designed based on a pre-trained model, it is possible to determine the toxicity of mushrooms based on the learned data.
A total of 10 mushrooms can be detected, four of which are poisonous mushrooms and the remaining six are edible mushrooms. To show the presence or absence of toxicity visually, LEDs are implemented with raspberry pie. If it is a poisonous mushroom, the red LED glows, and if it is an edible mushroom, the green LED glows.
2. Provide approximate information on mushrooms
It provides approximate information on detected mushrooms through a web page.
-> Connect the link to the pre-made web page to the corresponding mushroom and show it to the user.(information based on the appearance and risk of mushrooms.)

