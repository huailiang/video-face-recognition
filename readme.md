<p align="center">
     <a href="https://huailiang.github.io/" target="_blank">
    	<img src="https://huailiang.github.io/img/avatar-Alex.jpg" width="160" height="140">
    </a>
</p>


<b>视频中人物提取人脸特征进行识别</b>

对应的博客地址：https://huailiang.github.io/2018/04/06/videoreg/

Keras

如果说 Tensorflow 或者 Theano 神经网络方面的巨人. 那 Keras 就是站在巨人肩膀上的人. Keras 是一个兼容 Theano 和 Tensorflow 的神经网络高级包, 用他来组件一个神经网络更加快速, 几条语句就搞定了. 而且广泛的兼容性能使 Keras 在 Windows 和 MacOS 或者 Linux 上运行无阻碍.Keras 是建立在 Tensorflow 和 Theano 之上的更高级的神经网络模块, 所以它可以兼容 Windows, Linux 和 MacOS 系统。

鉴于keras极简的api,本次我们使用keras来搭建一个CNN网络模型，基于tensorflow。之前有一篇文章专门介绍CNN，不懂cnn的同学可以去看看。
<p align="center">
 <a href="https://keras.io" target="_blank">
    	<img src="https://keras.io/img/keras-logo-small-2018.jpg" width="160" height="150">
</a>
</p>

OpenCV

OpenCV是一个基于BSD许可（开源）发行的跨平台计算机视觉库，可以运行在Linux、Windows、Android和Mac OS操作系统上。它轻量级而且高效——由一系列 C 函数和少量 C++ 类构成，同时提供了Python、Ruby、MATLAB等语言的接口，实现了图像处理和计算机视觉方面的很多通用算法。
<p align="center">
<a href="https://opencv.org" target="_blank">
    	<img src="https://opencv.org/assets/theme/logo.png" width="160" height="150">
</a>
</p>


素材获取

因为需要训练需要大量的人脸素材，此次项目中所有使用的素材都是来源于UMASS（马萨诸塞大学）的一个对外的网站，这里你可以获取大量的预处理好的关于人脸素材，下载地址：http://vis-www.cs.umass.edu/lfw/

<p align="center">
<a href="https://opencv.org" target="_blank">
    	<img src="https://huailiang.github.io/img/in-post/post-tf/face.jpg" width="240" height="150">
</a>
</p>
