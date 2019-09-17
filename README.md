# Right Pose Classification
Developing classification model to distinguish right sitting pose from bad pose.

컴퓨터 앞에서 장시간 일하는 사람은 목 통증과 어깨 결림을 경험하기 쉽습니다. 모니터를 향해 목을 내밀고 상체를 구부리는 자세는 ‘거북목 증후군(Cervical  Hypolordosis syndrome)’으로 이어지기도 합니다. 거북목 증후군은 목뼈의 형태가 변형되어 목, 어깨, 등에 통증을 유발합니다.

최근 많은 연구자, 기업, 일반인들이 한층 대중화된 머신러닝, 딥러닝 프레임워크를 이용하여 데이터 기반으로 당면한 문제를 풀려고 하고 있습니다.

저도 이런 흐름에 맞춰 거북목 자세를 감시하기 위한 토이 프로젝트를 진행하기로 했습니다. 

I define right pose and bad pose like this : 

바른 자세와 나쁜 자세는 다음 이미지를 참고하여 정의했습니다 : 

![pose_example](./posture_example.png)

The left size is bad pose and the right size is good pose.

왼쪽이 나쁜 자세고 오른쪽이 바른 자세입니다.


# Demo
![demo_image](./demo.gif)

# References
1. [Head CT Hemorrhage Kernel](https://www.kaggle.com/felipekitamura/head-ct-hemorrhage-kernel) : Basic pipline of data preprocessing, model configuration, training, and test
2. [How do I send desktop notifications using Python 3?](https://askubuntu.com/questions/616985/how-do-i-send-desktop-notifications-using-python-3)
3. [How to send desktop notifications in Linux.](https://terrameijar.wordpress.com/2017/06/05/how-to-send-desktop-notifications-in-linux/)
4. [How do I use 'notify-send' to immediately replace an existing notification?
](https://askubuntu.com/questions/161851/how-do-i-use-notify-send-to-immediately-replace-an-existing-notification)
5. [Sound alarm when code finishes](https://stackoverflow.com/questions/16573051/sound-alarm-when-code-finishes)
6. [Getting Started with Videos](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_gui/py_video_display/py_video_display.html)
7. [파이썬 파트12. 예외처리](https://wayhome25.github.io/python/2017/02/26/py-12-exception/)
8. [OpenCV 강좌 C++ & Python - 글자(문자열) 출력하는 putText 함수 사용방법](https://webnautes.tistory.com/1212)
9. [Python - Extracting and Saving Video Frames](https://stackoverflow.com/questions/33311153/python-extracting-and-saving-video-frames)
