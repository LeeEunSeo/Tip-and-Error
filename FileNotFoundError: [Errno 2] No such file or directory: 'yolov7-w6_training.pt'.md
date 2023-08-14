Traceback (most recent call last):
  File "C:\Users\dmstj\OneDrive\바탕 화면\yolov7\train_aux.py", line 614, in <module>
    train(hyp, opt, device, tb_writer)
  File "C:\Users\dmstj\OneDrive\바탕 화면\yolov7\train_aux.py", line 89, in train
    ckpt = torch.load(weights, map_location=device)  # load checkpoint
  File "C:\Users\dmstj\anaconda3\lib\site-packages\torch\serialization.py", line 581, in load
    with _open_file_like(f, 'rb') as opened_file:
  File "C:\Users\dmstj\anaconda3\lib\site-packages\torch\serialization.py", line 230, in _open_file_like
    return _open_file(name_or_buffer, mode)
  File "C:\Users\dmstj\anaconda3\lib\site-packages\torch\serialization.py", line 211, in __init__
    super(_open_file, self).__init__(open(name, mode))
FileNotFoundError: [Errno 2] No such file or directory: 'yolov7-w6_training.pt'

어느순간 가중치 파일이 삭제된건지 내가 소스코드를 옮긴건지 쨋든 없다고 뜨는 가중치 파일을 다운받아서 소스코드 파일안에 넣어주면 해결 !
