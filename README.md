# SkillBox
## 2. Computer Vision <br>
### 2.1 Бинарный классификатор <br>
https://github.com/GermanYanchenko/ImageClass_binary <br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/IC_history.png?raw=true)<br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/IC_predict.png?raw=true)<br>
### 2.2 Transfer Learning and Fine Tuning <br>
Для задачи 2.1 в качестве базовой модели выбрана MobileNet, заморозив модель и дополнив выходным полносвязным слоем реализовано обучение, после разморозив слои было выполнено дообучение.<br>
https://github.com/GermanYanchenko/TransferLearn_FineTun<br>
Значения потерь и качества при Transfer Learning: <br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/hist_trans_learn.png?raw=true)<br>
Значения потерь и качества при Fine Tuning: <br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/hist_fine_tun.png?raw=true)<br>
Предсказание модели: <br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/predict_tl_ft.png?raw=true)<br>
### 2.3 Модель предсказания пола, расы и вовзраста лиц людей.
https://github.com/GermanYanchenko/VGGFace <br>
Датасет - https://susanqq.github.io/UTKFace/. Базовая модель - VGGFace https://github.com/rcmalli/keras-vggface.<br>
Пример изображения из датасета:<br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/vgg_img.png?raw=true)<br>
История обучения:<br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/vgg_hist1.png?raw=true)<br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/vgg_hist2.png?raw=true)<br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/vgg_hist3.png?raw=true)<br>
Предсказание модели для тестового датасета: <br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/vgg_predict.png?raw=true)<br>
