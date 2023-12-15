<H1 align="center">
YOLOv8 Object Detection with DeepSORT Tracking(ID + Trails) </H1>


[`Github Repo Link`](https://github.com/AyushPadvekar05/Vehicle_Detection_and_Counting_System)

## Steps to run Code

- Clone the repository
```
git clone https://github.com/AyushPadvekar05/Vehicle_Detection_and_Counting_System.git
```
- Goto the cloned folder.
```
cd YOLOv8-DeepSORT-Object-Tracking
```
- Install the dependecies
```
pip install -e '.[dev]'

```

- Setting the Directory.
```
cd ultralytics/yolo/v8/detect

```

- Run the code with mentioned command below.

```
- For yolov8 object detection + Tracking + Vehicle Counting
```
python predict.py model=yolov8l.pt source="test3.mp4" show=True
```

### RESULTS

#### Vehicles Detection, Tracking and Counting 
![](./figure/figure1.png)

#### Vehicles Detection, Tracking and Counting

![](./figure/figure3.png)

