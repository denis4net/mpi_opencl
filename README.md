
## Archlinux dependencies:

opencl-nvidia: execute on your NVidia GPU (official NVidia runtime)
opencl-mesa: execute on AMD GPU's using the mesa drivers (currently under development, your mileage may vary)
intel-opencl-runtime: execute on your CPU (official Intel runtime, must not be an Intel CPU)
ocl-icd: OpenCL ICD loader implementation, up to date with the latest OpenCL specification.
opencl-headers: OpenCL C/C++ API headers.

```
# packer -S ocl-icd opencl-headers intel-opencl-runtime
```