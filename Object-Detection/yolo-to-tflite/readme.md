### Download the pretrained weight file or use your custom train weight


  python save_model.py --weights ./data/yolov4-obj_last.weights --output ./checkpoints2/yolov4-416 --input_size 416 --model yolov4
  
  python detect_video.py --weights ./checkpoints/yolov4-416 --size 416 --model yolov4 --video ./data/video/road.mp4 --output ./detections/results.avi
