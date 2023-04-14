## UnicodeDecodeError: 'cp949' codec can't decode byte 0xed in position 41: illegal multibyte sequence

yolo7을 돌려보던 중 데이터셋을 설정하는 .yaml 파일에 대하여 생긴 오류로 생성시 UTF-8로 생성하거나 수정을 하게되면 자동으로 UTF-8로 바뀌면서 생기는 오류였다.
메모장을 이용하여 UTF-8에서 ANSI로 바꾸어주면 해결된다 !
