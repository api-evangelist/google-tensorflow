---
title: "Simpleperf case study: Fast initialization of TFLite’s Memory Arena"
url: "https://blog.tensorflow.org/2023/08/simpleperf-case-study-fast.html"
date: "2023-08-09"
author: "noreply@blogger.com (TensorFlow Blog)"
feed_url: "https://blog.tensorflow.org/feeds/posts/default?alt=rss"
---
Posted by Alan Kelly , Software Engineer One of our previous articles, Optimizing TensorFlow Lite Runtime Memory , discusses how TFLite’s memory arena minimizes memory usage by sharing buffers between tensors. This means we can run models on even smaller edge devices. In today’s article, I will describe the performance optimization of the memory arena initialization so that our users get the benefit of low memory usage with little additional overhead.
