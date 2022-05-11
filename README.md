# object_detection_JH


<h3> file info </h3>

- best.pt - best fit model
- export.zip - 파일 데이터셋 (일단 갈치만)
- Untitled1.ipynb - 모델 + detect.py로 감지 test, source code


모델 test :

command : </br>

!python detect.py --weights /content/mnt/MyDrive/yolov5/runs/train/food_yolov5s_results3/weights/best.pt --img 416 --conf 0.5 --source "{val_img_path}" </br>

.
.
.


data.yaml - export.zip 안에 있음
Untitled1.ipynb 마지막 라인에 command가 있어용.

but 경로 알맞게 수정 필요..! 

source뒤에는 img file 경로.