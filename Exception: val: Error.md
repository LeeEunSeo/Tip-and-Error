Traceback (most recent call last):
  File "C:\Users\dmstj\OneDrive\바탕 화면\yolov7\train_aux.py", line 614, in <module>
    train(hyp, opt, device, tb_writer)
  File "C:\Users\dmstj\OneDrive\바탕 화면\yolov7\train_aux.py", line 257, in train
    testloader = create_dataloader(test_path, imgsz_test, batch_size * 2, gs, opt,  # testloader
  File "C:\Users\dmstj\OneDrive\바탕 화면\yolov7\utils\datasets.py", line 73, in create_dataloader
    dataset = LoadImagesAndLabels(path, imgsz, batch_size,
  File "C:\Users\dmstj\OneDrive\바탕 화면\yolov7\utils\datasets.py", line 402, in __init__
    raise Exception(f'{prefix}Error loading data from {path}: {e}\nSee {help_url}')
Exception: val: Error loading data from C:/YOLOtenthdata/val.txt: val: No images found
See https://github.com/ultralytics/yolov5/wiki/Train-Custom-Data

val 파일을 안만들어 줬을 때 생기는 에러,,
