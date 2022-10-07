#### ICASSP2021[10] SINGING MELODY EXTRACTION FROM POLYPHONIC MUSIC BASED ON SPECTRAL CORRELATION MODELING<br>
- 动机：对于旋律提取来说，歌唱旋律的频率范围通常很广，然而普通的CNN只可提取到局部的信息，可见域较小，很难提取出相距较远的频率的相关性。<br>
- 特征：STFT幅度谱图。<br>
- 方法：遵循crnn框架，卷积部分由频谱相关模块SCM组成。<br>
  ![image](https://user-images.githubusercontent.com/41570758/194511955-3639d23b-ecf8-40a4-80d8-6d1dfa5cceb8.png)
- 优点：MedleyDB测试集得到了很好的提升※<br>
