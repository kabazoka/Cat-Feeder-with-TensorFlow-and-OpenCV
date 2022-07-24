# Cat-Feeder-with-TensorFlow-and-OpenCV
Final project of class 2021 embedded systems.

藉由整合 OpenCV, TensorFlow Object Detection API, Protobuf, SSD Lite Model
以及 RaspberryPi 和 Webcam 辨識貓咪。以貓咪待在飼料碗前的時長判斷貓咪是否想要進食。
並以 RPi.GPIO, PWM, ChangeDutyCycle 控制 Servo Motor 開啟及關閉飼料碗的蓋子。
在一日內限制貓進食的次數(預設為五次，可調整)，
每次進食時間預設為 60 秒(依據家中貓咪習慣調整)。
