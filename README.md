# Traffic Light Detector

### Data preprocessing:

1. Assuming that the starting dataset has a form of videos, run

```
python split_video.py --pathIn *the path to a video*
```

to split videos into frames.

2. Rename resulting images

```
python rename_pics.py
```

3. In order to change images' contrast, run 

```
python change_contrast.py
```

### Making predictions:

1. Put your images to test_images folder
2. Run
```
python main.py
```

### Result:

![alt text](https://github.com/imciflam/traffic-lights-detector/blob/main/example/example.png)



