# 背景知识

语音的声波通过空气传播，并被麦克风捕获，从而将压力波转换为可以捕获的电信号。通过对电信号进行采样，可以创建能对该信号进行描述的一系列波形信号。通常情况下，音乐信号的采样频率一般是44,100 Hz，根据奈奎斯特采样定理，这意味着可以通过采样准确地捕获频率高达22,050 Hz的音频。而语音信号的高频信息较少（仅高达8000 Hz），因此通常使用16,000 Hz的采样率。传统有线电话的语音和大多数移动电话的语音带宽被限制为大约3400 Hz，因此电话语音通常使用8000 Hz的采样率。

下图绘制了一个典型的语音波形图，相应的语音内容为“speech recognition is cool stuff”.

<div align=center><img src="https://github.com/xinshengwang/edx-SRS/blob/master/figures/m2i1.png" style="zoom:40%" /> </div>

