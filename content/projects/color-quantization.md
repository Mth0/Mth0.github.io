+++
date = 2025-01-11
title = "Color Quantization 🐈☕"

[extra]
authors = "Matheus do Ó"
where = "Final project for subject Non-Linear Optimization"
link = "https://github.com/Mth0/Color-Quantization"
#pdf =
+++

One of the mostly used image format in computers and other devices is the RGB format. In this format there are three channels which values can vary between 0 and 255. The pixels, therefore, are represented by three values, one for each channel. So we have $256^{3}$ possible colors! That's a lot more than the number of colors a human can recognizes. In fact, this huge number of possible colors can enlarge the image file size. So what if we delimit the number of colors of our image? Is it possible to reduce drastically this number and maintain a good image quality? Yes!

Color quantization looks to solve this problem: To find a good color palette that reduce the number of colors of the image and preserve its quality. There are a lot of ways to define this problem more precisely and a lot of algorithms to solve it. I'll define it in a specific way, but remind that it's not the unique way to do that. First let's remind that in the RGB format images with m pixels by n pixels can be represented as 3 matrices with m × n dimension, one matrix for each channel containing the values of the pixels in that channel.

In this project, I try to solve it approximately with the meta-heuristics GRASP.
