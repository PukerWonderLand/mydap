# git_dsp
- 频率响应：对采样的音频使用fft函数实现fft变换，并绘制图像。（或者使用freqz函数）

- 瀑布频谱图：频谱瀑布图又叫谱阵图，它是将振动信号的功率谱或幅值谱随转速变化而叠置而成的三维谱图，显示振动信号中各谐波成分随转速变化的情况。即x轴为频率，y轴为时间，z轴为幅度用不同颜色表示，随着时间的的变化，整个频谱由上到下移动。

- 相位响应曲线：使用angle函数将频谱幅值转换为角度即可

- 音压曲线：音压即声压（SPL）即将幅度转换为分贝，x轴为时间，y轴为20*log10(y)

- 其它功能待实现
