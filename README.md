# iodraw
A cross-platform drawing library for C++

这个是一个设想，目标是在各个平台都能抽出统一的绘制接口，包括一些微控制器，比如stm32

# 关键概念
## Surface
可以通过不同的函数来创建surface，我们的绘制都是基于这个surface

ex:CreateSurfaceOnGDI()
## Brush
