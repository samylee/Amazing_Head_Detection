# Amazing_Head_Detection
CPU Real-time Amazing Head Detection
# Test steps
## step1
Download opencv_dll and put it to current directory [BaiDu Cloud](https://pan.baidu.com/s/14VIsF6PD6ktU7ctUh301wA)
## step2
Set parameters:
`Amazing_Head_Detection.exe test_type img_path`
```cpp
like:  Amazing_Head_Detection.exe image test.jpg  (for image)
or:    Amazing_Head_Detection.exe imgdir /img/path/test_imgs  (for imgdir)
or:    Amazing_Head_Detection.exe video test.avi  (for video)
or:    Amazing_Head_Detection.exe video 0  (for usbcam)
```
# Algorithm efficiency
| Image Size | Speed | FPS | CPU | min_size |
|:------:|:------:|:------:|:------:|:------:|
| 320x240  | 6ms |166.7| i7-9700K | 16x16 |
| 640x480  | 23ms |43.5| i7-9700K | 16x16 |
| 800x600  | 42ms |23.8| i7-9700K | 16x16 |
# Test experience
If the image size is larger than `720p`, it is recommended to scale the image `below 720p`!
# Example result
![image](https://github.com/samylee/Amazing_Head_Detection/blob/master/result.jpg)
# Reference
https://blog.csdn.net/samylee
