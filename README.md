
https://github.com/user-attachments/assets/00b82efe-5cbc-4a61-8177-250550832c26


sycl-gs3d demo application

The release `sycl-gs3d-xpu.zip` is a demo for Intel GPUs. It was tested on an Intel Arc A370m. It was tested on Ubuntu 22.04 with Intel Base SDK 2025.0 installed. In the `colmap` directory is a colmap dataset from a set of images I dumped from a video of an art installation in a local park. The `run.sh` runs the `sycl-gs3d` with the appropriate `LD_LIBRARY_PATH` for the Intel XPU. `point_cloud_1000.ply` is an example of what the gaussian splats should look like after 1000 iterations.

The release `sycl-gs3d-cuda.zip` is a demo for Nvidia GPUs. It was tested on Windows 11 WSL2 (Ubuntu 22.04) with CUDA 12.6 and OneAPI 2023.2. It uses the same image set as the XPU version. 
