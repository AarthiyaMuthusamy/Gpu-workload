# Gpu-workload 
One of the projects I worked on is focused on optimizing time-series data processing within a GPU cluster environment, specifically for workload analysis in GPU clusters. Time-series forecasting, especially in multivariate datasets with complex dynamics, is a crucial problem in various real-world applications. This project aims to enhance the performance and efficiency of GPU-based computations for time-series data.

In this project, we proposed a novel architecture called TSMixer, which uses multi-layer perceptrons (MLPs) for efficiently processing time-series data. The key idea behind TSMixer is to apply mixing operations along both time and feature dimensions, allowing for better information extraction from the data. This approach helps us process time-series data more efficiently within a GPU cluster environment.

The objective of the project was to understand the characteristics of time-series data and how to effectively transform and process it. We also focused on ensuring load balancing within the GPU cluster to maximize resource utilization and overall performance. Additionally, we evaluated how the solution scales with increasing volumes of data and ensured the GPU cluster could handle growing workloads effectively.

For the implementation, we used Google Colab and Python, leveraging LSTM variants for time-series forecasting. Our results highlighted the importance of optimizing workload distribution and resource utilization to improve the forecasting performance, particularly in a distributed GPU environment.

This project gave me valuable experience in time-series forecasting, GPU clustering, and distributed computing, along with hands-on experience with advanced architectures like TSMixer.
