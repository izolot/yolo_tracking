# yolo_tracking(test)
This code has been tested CUDA 10.1, OpenCV 4.1, VS 2019, Win10x64.
1. Install CUDA https://developer.nvidia.com/cuda-downloads
2. Install OpenCV https://opencv.org/releases/
3. Add environment variables like this CUDA_PATH = "C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.1" and OPENCV_DIR = "C:\opencv_4.1\opencv\build"
4. git clone https://github.com/izolot/yolo_tracking.git
5. Open yolo_tracking.sln in Visual Studio
6. Build -> Release x64 - yolo_cuda, then  Build -> Release x64 - yolo_tracking
7. Copy file <b>opencv_{opencv_version}\opencv\build\x64\vc15\bin\opencv_world{opencv_version}.dll</b> to folder yolo_tracking\x64
8. Download https://pjreddie.com/media/files/yolov3.weights
9. yolo_tracking.exe cfg/coco.names cfg/yolov3.cfg yolov3.weights path_to_video



