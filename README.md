# GPU-Powered Image Processing and Performance Analyzer

## Project Overview

This project demonstrates the use of GPU computing to accelerate image processing operations using NVIDIA CUDA. It implements grayscale conversion and Sobel edge detection using custom CUDA kernels and compares their performance with CPU-based processing.

The project was developed as part of the GPU Specialization Capstone Project to explore parallel computing, GPU acceleration, and performance analysis.

## Objectives

* Understand how GPU computing accelerates image processing.
* Implement custom CUDA kernels using CuPy.
* Perform grayscale conversion and Sobel edge detection.
* Compare CPU and GPU execution times.
* Analyze performance across different batch sizes.
* Generate performance graphs and CSV reports.

## Technologies Used

* Python
* NVIDIA CUDA
* CuPy
* NumPy
* OpenCV
* Pandas
* Matplotlib
* Google Colab

## Hardware

* GPU: NVIDIA Tesla T4
* Environment: Google Colab

## Project Workflow

1. Generate a dataset containing 100 test images.
2. Process images using CPU-based functions.
3. Implement custom CUDA kernels for GPU processing.
4. Perform grayscale conversion and Sobel edge detection.
5. Benchmark CPU and GPU execution times.
6. Compare results across batches of 10, 25, 50, and 100 images.
7. Generate CSV reports, graphs, and processed image outputs.

## Project Structure

```text
GPU-Capstone-Image-Processing/
│
├── GPU_Capstone_Final.zip
├── GPU_Capstone_Image_Processing.ipynb
└── README.md
```

The ZIP archive contains the execution results, dataset, performance reports, graphs, and output images.

## Results and Performance Analysis

The project measures:

* Total CPU execution time
* Total GPU execution time
* Average processing time per image
* GPU speedup relative to CPU
* Output differences between CPU and GPU processing

The benchmark results are available in `results/performance_results.csv`.

Performance graphs are saved in the results folder for visual comparison.

**Note:** Execution times include data transfer and processing overhead. Performance may vary depending on batch size and runtime conditions.

## How to Run

1. Open the Jupyter Notebook in Google Colab.
2. Select a GPU runtime.
3. Install the required Python libraries.
4. Execute the notebook cells sequentially.
5. Review the generated output images, CSV report, and performance graphs.

## Conclusion

This project provides practical experience with CUDA programming and parallel image processing. It demonstrates how GPU kernels can be used to perform image operations and how performance measurements can help evaluate GPU acceleration.

The project also highlights the importance of output validation and fair benchmarking when comparing CPU and GPU implementations.

## Author

**Mayank Pande**

GPU Specialization Capstone Project
