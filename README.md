# Reading-Order-using-Language-Properties

- run this script in a virtual environment with python3.10.2 (recommended), requirements.txt has all the required packages.
- save this file using some name, here it is updatedLatest_readOrder.py
- MODEL_FILE_PATH is the path to the model file, ./db_resnet50.pt. Change as required.
- PATH_TO_IMAGE is the path to the image file, ./test_images/{}.jpg. Change as required.

- run this script from command line using the command:
$ python3 updatedLatest_readOrder.py --ImageFile <PATH_TO_IMAGE> --resume <MODEL_FILE_PATH>

- Output9.jpg is the final output image with reading order

- by default col_only and para_only are set to False, so both column order and paragraph order will not be visualized.
- currently the column order and paragraph order are under development, so might not work well for all kinds of documents.

- to visualize paragraph order, use the command:
$ python3 updatedLatest_readOrder.py --ImageFile <path to image> --resume <MODEL_FILE_PATH> --para_only True

- to visualize column order, use the command:
$ python3 updatedLatest_readOrder.py --ImageFile <path to image> --resume <MODEL_FILE_PATH> --col_only True


