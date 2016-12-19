# Readme

A Docker image with the AMD OpenCL 2.0 runtime and Khronos group OpenCL 2.0 header files.

# Using from Docker Hub

    docker run -it cwpearson/opencl2.0-amd-cpu bash -c clinfo

You should see a dump of information about the OpenCL capabilities of your system.

# Building Locally

    docker build . -t cwpearson/opencl2.0-amd-cpu