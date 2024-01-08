# installation :
- clone the repo
- Download 'resnet-34_kinetics.onnx' from internet and place in the source folder 

# how to run :
```
python3 HAR.py --model resnet-34_kinetics.onnx --classes Actions.txt
python3 HAR.py --model resnet-34_kinetics.onnx --classes Actions.txt --input videos/v1.mp4 --gpu 1 --output output.mp4
```

- avoid this if you want to use webcam for input
- --input videos/v1.mp4 --gpu 1 --output output.mp4
  
