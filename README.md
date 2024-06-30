# Pooling

Pooling layers, serve the dual purposes of mitigating the sensitivity of convolutional layers to location and of spatially downsampling representations.
### Maximum Pooling and Average pooling
Pooling operators consist of a fixed-shape window that is slid over all regions in the input according to its stride, computing a single output for each location traversed by the fixed-shape window (sometimes known as the pooling window). Pooling operators are deterministic, typically calculating either the maximum or the average value of the elements in the pooling window. 

E.g of a pooling window starting from the upper-left of the input tensor and sliding across it from left to right and top to bottom. At each location that the pooling window hits, it computes the maximum or average value of the input subtensor in the window, depending on whether max or average pooling is employed.
![image](https://github.com/MutshidziPhaswana/Pooling/assets/53537195/ec14c46b-19a6-4fd5-9203-43f884f5b446)

https://d2l.ai/chapter_convolutional-neural-networks/pooling.html#pooling

