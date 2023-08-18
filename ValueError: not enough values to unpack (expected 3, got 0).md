Traceback (most recent call last):
  File "C:\Users\dmstj\OneDrive\바탕 화면\yolov7\test.py", line 319, in <module>
    test(opt.data,
  File "C:\Users\dmstj\OneDrive\바탕 화면\yolov7\test.py", line 90, in test
    dataloader = create_dataloader(data[task], imgsz, batch_size, gs, opt, pad=0.5, rect=True,
  File "C:\Users\dmstj\OneDrive\바탕 화면\yolov7\utils\datasets.py", line 73, in create_dataloader
    dataset = LoadImagesAndLabels(path, imgsz, batch_size,
  File "C:\Users\dmstj\OneDrive\바탕 화면\yolov7\utils\datasets.py", line 426, in __init__
    labels, shapes, self.segments = zip(*cache.values())    # 여기서 오류
ValueError: not enough values to unpack (expected 3, got 0)


if egd_dataset: 함수 위에 아래 구문 추가

egd_dataset = True
               
