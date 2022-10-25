# yolov7-object-cropping

### Steps to run Code

```
- Clone the repository.
```
git clone https://github.com/noorkhokhar99/yolov7-object-cropping.git
```
- Goto the cloned folder.
```
cd yolov7-object-cropping
```

```
- Upgrade pip with mentioned command below.
```
pip install --upgrade pip
```
- Install requirements with mentioned command below.
```
pip install -r requirements.txt
```
- Download [yolov7](https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7.pt) object detection weights from link and move them to the working directory {yolov7-object-cropping}
- Run the code with mentioned command below.
```
#if you want to change source file
python detect_and_crop.py --weights yolov7.pt --source "your video.mp4"

#for specific class (person)
python detect_and_crop.py --weights yolov7.pt --source "your video.mp4" -classes 0
```
- Cropped Objects will be stored in "working-dir/crop" folder.

### Results


<img src="https://github.com/noorkhokhar99/yolov7-object-cropping/blob/main/Screen%20Shot%201444-03-29%20at%201.34.23%20PM.png">

