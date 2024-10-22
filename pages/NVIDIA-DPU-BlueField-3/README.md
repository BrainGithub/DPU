# NVIDIA DATA CENTER PROCESSING UNIT (DPU) ARCHITECTURE

-- This artical partially translated from Original [link](https://hc33.hotchips.org/assets/program/conference/day1/HC2021.NVIDIA.IdanBurstein.v08.norecording.pdf)

## DATA CENTER IS THE NEW UNIT OF COMPUTING
![dpu-evolution](dpu-evolution.png)

## DPU MUST INCLUDE HARDWARE ACCELERATION
![offload promoted to hardware acceleration](hardware-acceleration.png)

## PROGRAMMABLE ENGINES

![doca ecosystem](doca1.png)
DOCA
- Offload, Accelerate, and Isolate Infrastructure Processing
- Support for Hyperscale, Enterprise, Supercomputing and
Hyperconverged Infrastructure
- DOCA is for DPUs what CUDA is for GPUs  

![doca engin](doca2.png)

## ARCHITECTURE

### High level arch:

![high level arch](high-level-arch.png)
It's subsystems from CPU system.

### ACCELERATED SWITCHING AND PACKET PROCESSING
1. Programmable Data Path
2. Software-Defined Orchestration

![packet-processing](packet-processing.png)

### ACCELERATED STORAGE PROCESSING

![storage-processing](storage-processing.png)

### Offload
- Offload Cloud-Native Supercomputing

![offload-cloud-native-computing](offload-cloud-native-computing.png)

- Offload CLOUD GAMING Supercomputing

![offload-cloud-game-computing](offload-cloud-game-computing.png)

- Offload 5G NETWORK PROCESSING 

  ![offload-cloud-5g-computing](offload-cloud-5g-computing.png)
  - Accelerate 5G or AI – Fully fungible – Fully programmable
  - Support for CUDA, DOCA – Toolchains, SDKs, Libraries
  - Secure, Isolated, Accelerated data processing
  - No need to move data back and forth from accelerators to
host memory
  - Domain specific acceleration for 5G, AI, Network Security
  - Independent DPU time domain (5T for 5G)
  - Fully optimized data path
