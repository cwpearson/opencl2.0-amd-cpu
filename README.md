# Readme

A Docker container with the AMD OpenCL 2.0 runtime and Khronos group OpenCL 2.0 header files.

# Building Locally

    docker build . -t cwpearson/opencl2.0-amd-cpu

# Testing

    docker run -it cwpearson/opencl2.0-amd-cpu bash -c clinfo
