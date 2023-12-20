# Awesome AI System

This repo is motivated by [awesome tensor compilers](https://github.com/merrymercy/awesome-tensor-compilers.git).
## Contents

- [Papers-Code](#paper-code)
  - [LLM Serving Framework](#llm-serving-framework)
  - [LLM Serving](#LLM-Serving)
  - [LLM Platform](#LLM-Platform)
  - [LLM FineTune](#LLM-FineTune)
  - [Fancy LLM](#Fancy-LLM)
  - [Framework](#framework)
  - [Parallellism Training](#parallellism-training)
  - [Training](#training)
  - [Communication](#communication)
  - [Serving-Inference](#Serving-Inference)
  - [MoE](#MoE)
  - [GPU Cluster Management](#gpu-cluster-management)
  - [Schedule and Resource Management](#schedule)
  - [Optimization](#optimzation)
  - [GNN](#GNN)
  - [Fine-Tune](#Fine-Tune)
  - [Energy](#energy)
  - [Misc](#Misc)
- [Contribute](#contribute)

## Papers-Code

### LLM Serving Framework
- [xFasterTransformer(CPU Side)](https://github.com/intel/xFasterTransformer)
- [TensorRT-LLM by nvidia ](https://github.com/NVIDIA/TensorRT-LLM.git)
- [CTranslate2(low latency)](https://github.com/OpenNMT/CTranslate2.git)

### LLM Serving

- [Flash-LLM: Enabling Cost-Effective and Highly-Efficient Large Generative Model Inference with Unstructured Sparsity vldb'24](https://github.com/MachineLearningSystem/24vldb-flash-llm)

- [PowerInfer: Fast Large Language Model Serving with a Consumer-grade GPU](https://github.com/MachineLearningSystem/PowerInfer.git)

- [vLLM System(Efficient Memory Management for Large Language Model Serving with PagedAttention SOSP'23)](https://github.com/vllm-project/vllm)

- [LLMCompiler: An LLM Compiler for Parallel Function Calling](https://github.com/MachineLearningSystem/LLMCompiler)


- [SpecInfer: Accelerating Generative Large Language Model Serving with Speculative Inference and Token Tree Verification 23arxiv](https://github.com/flexflow/FlexFlow/tree/inference)

### LLM Platform
- [FastChat](https://github.com/lm-sys/FastChat.git)

### LLM FineTune
- [S-LoRA: Serving Thousands of Concurrent LoRA Adapters ](https://github.com/S-LoRA/S-LoRA.git)
- [Punica: Serving multiple LoRA finetuned LLM as one](https://github.com/punica-ai/punica.git)

### Fancy LLM
- [Mamba: Linear-Time Sequence Modeling with Selective State Spaces](Mamba: Linear-Time Sequence Modeling with Selective State Spaces)
- [Teaching LLMs memory management for unbounded context arxiv](https://github.com/MachineLearningSystem/23arxiv-MemGPT)

- [Break the Sequential Dependency of LLM Inference Using Lookahead Decoding](https://github.com/hao-ai-lab/LookaheadDecoding.git)

- [EAGLE: Lossless Acceleration of LLM Decoding by Feature Extrapolation](https://github.com/SafeAILab/EAGLE.git)

### Framework
-  [Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning OSDI'22](https://github.com/alpa-projects/alpa.git) 

- [Unity: Accelerating DNN Training Through Joint Optimization of Algebraic Transformations and Parallelization OSDI'22 ](https://github.com/flexflow/FlexFlow) OSDI'22 

- [Megatron-LM SC21 ](https://github.com/NVIDIA/Megatron-LM.git) 

- [A Unified Architecture for Accelerating Distributed DNN Training in Heterogeneous GPU/CPU Clusters OSDI'20](https://github.com/bytedance/byteps) 

- [Colossal-AI: A Unified Deep Learning System For Large-Scale Parallel Training](https://github.com/hpcaitech/ColossalAI)

- [HET: Scaling out Huge Embedding Model Training via Cache-enabled Distributed Framework VLDB'22](https://github.com/MachineLearningSystem/Hetu) 

### Parallellism Training
- [ DynaPipe: Optimizing Multi-task Training through Dynamic Pipelines Eurosys'24](https://github.com/MachineLearningSystem/24Eurosys-optimizing-multitask-training-through-dynamic-pipelines)
- [Aceso: Efficient Parallel DNN Training through Iterative Bottleneck Alleviation Eurosys'24](https://github.com/MachineLearningSystem/24Eurosys-Aceso)
- [HAP: SPMD DNN Training on Heterogeneous GPU Clusters with Automated Program Synthesis Eurosys'24](https://github.com/MachineLearningSystem/24Eurosys-hap)
- [Calculon: A Methodology and Tool for High-Level Co-Design of Systems and Large Language Models SC'23](https://github.com/MachineLearningSystem/23sc-calculon)
- [Artifact for DynaPipe: Optimizing Multi-task Training through Dynamic Pipelines Eurosys'24](https://github.com/MachineLearningSystem/24Eurosys-DynaPipe-Megatron-LM)
- [PipeFisher: Efficient Training of Large Language Models Using Pipelining and Fisher Information Matrices  MLSYS'23](https://github.com/MachineLearningSystem/23MLSYS-pipe-fisher)
- [Bamboo: Making Preemptible Instances Resilient for Affordable Training of Large DNNs](https://github.com/MachineLearningSystem/bamboo) NSDI'23 

- [MPress: Democratizing Billion-Scale Model Training on Multi-GPU Servers via Memory-Saving Inter-Operator Parallelism](https://github.com/MachineLearningSystem/HPCA23-mpress) HPCA'23 

- [Optimus-CC: Efficient Large NLP Model Training with 3D Parallelism Aware Communication Compression](https://github.com/MachineLearningSystem/Optimus-CC) ASPLOS'23

- [Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning](https://github.com/alpa-projects/alpa.git) OSDI'22


- [AMP: Automatically Finding Model Parallel Strategies with Heterogeneity Awareness](https://github.com/MachineLearningSystem/AMP) NeurIPS '22

- [Unity: Accelerating DNN Training Through Joint Optimization of Algebraic Transformations and Parallelization](https://github.com/flexflow/FlexFlow) OSDI'22 

- [NASPipe: High Performance and Reproducible Pipeline Parallel Supernet Training via Causal Synchronous Parallelism](https://github.com/MachineLearningSystem/naspipe) ASPLOS'22

- [Varuna: Scalable, Low-cost Training of Massive Deep Learning Models](https://github.com/MachineLearningSystem/varuna) Eurosys'22 

- [Megatron-LM](https://github.com/NVIDIA/Megatron-LM.git) SC'21

- [Chimera: efficiently training large-scale neural networks with bidirectional pipelines](https://github.com/MachineLearningSystem/Chimera) SC'21 

- [Piper: Multidimensional Planner for DNN Parallelization](https://github.com/MachineLearningSystem/piper) NeurIPS'21

- [PipeTransformer: Automated Elastic Pipelining for Distributed Training of Large-scale Models](https://github.com/MachineLearningSystem/PipeTransformer.git) ICML'21

- [DAPPLE: An Efficient Pipelined Data Parallel Approach for Large Models Training](https://github.com/MachineLearningSystem/DAPPLE) PPOPP'21

- [TeraPipe:Large-Scale Language Modeling with Pipeline Parallelism](https://github.com/MachineLearningSystem/terapipe) ICML'21 

- [PipeDream: Pipeline Parallelism for DNN Training](https://github.com/MachineLearningSystem/pipedream.git) SOSP'19

- [SWARM Parallelism: Training Large Models Can Be Surprisingly Communication-Efficient](https://github.com/MachineLearningSystem/swarm)

- [Merak: An Efficient Distributed DNN Training Framework with Automated 3D Parallelism for Giant Foundation Models](https://github.com/MachineLearningSystem/Merak) 

- [awesome distributed deep learning](https://github.com/MachineLearningSystem/Awesome-Distributed-Deep-Learning.git)
- [awsome parallelism](https://github.com/MachineLearningSystem/awesome-Auto-Parallelism)

### Training 

- [ModelKeeper: Accelerating DNN Training via Automated Training Warmup](https://github.com/MachineLearningSystem/ModelKeeper) NSDI'23


- [STRONGHOLD: Fast and Affordable Billion-scale Deep Learning Model Training SC'22](https://github.com/MachineLearningSystem/sc22-ae-big_model) 

- [Whale: Efficient Giant Model Training over Heterogeneous {GPUs}](https://github.com/MachineLearningSystem/EasyParallelLibrary) ATC'22

- [GeePS: Scalable Deep Learning on Distributed GPUs with a GPU-Specialized Parameter Server](https://github.com/MachineLearningSystem/geeps) Eurosys'16


### Communication
- [ARK: GPU-driven Code Execution for Distributed Deep Learning NSDI'23](https://github.com/MachineLearningSystem/23NSDI-arkwo)
- [TopoOpt: Optimizing the Network Topology for Distributed DNN Training](https://github.com/MachineLearningSystem/TopoOpt) NSDI'23 

- [Breaking the Computation and Communication Abstraction Barrier in Distributed Machine Learning Workloads](https://github.com/parasailteam/coconet.git) ASPLOS'22 

- [Efficient Sparse Collective Communication and its application to Accelerate Distributed Deep Learning SIGCOMM'21 ](https://github.com/MachineLearningSystem/omnireduce.git) 

### Serving-Inference

- [Paella: Low-latency Model Serving with Virtualized GPU Scheduling SOSP'23](https://github.com/MachineLearningSystem/23sosp-paella)

- [Beta: Statistical Multiplexing with Model Parallelism for Deep Learning Serving OSDI'23](https://github.com/MachineLearningSystem/OSDI23-mms)

- [Optimizing Dynamic Neural Networks with Brainstorm OSDI'23](https://github.com/MachineLearningSystem/23OSDI-brainstorm)

- [Fast and Efficient Model Serving Using Multi-GPUs with Direct-Host-Access](https://github.com/MachineLearningSystem/DeepPlan.git) Eurosys'23

- [Hidet: Task-Mapping Programming Paradigm for Deep Learning Tensor Programs.](https://github.com/MachineLearningSystem/hidet)

- [MPCFormer: fast, performant, and private transformer inference with MPC](https://github.com/DachengLi1/MPCFormer) ICLR'23 

- [High-throughput Generative Inference of Large Language Modelwith a Single GPU](https://github.com/MachineLearningSystem/FlexGen) 

- [VELTAIR: Towards High-Performance Multi-Tenant Deep Learning Serving via Adaptive Compilation and Scheduling](https://github.com/MachineLearningSystem/VELTAIR_ASPLOS22) ASPLOS'22

- [DVABatch: Diversity-aware Multi-Entry Multi-Exit Batching for Efficient Processing of DNN Services on GPUs](https://github.com/MachineLearningSystem/DVABatch)  ATC'22 

- [Cocktail: A Multidimensional Optimization for Model Serving in Cloud](https://github.com/MachineLearningSystem/cocktail) NSDI'22

- [Serving Heterogeneous Machine Learning Models on Multi-GPU Servers with Spatio-Temporal Sharing](https://github.com/MachineLearningSystem/glet) ATC'22

- [RIBBON: cost-effective and qos-aware deep learning model inference using a diverse pool of cloud computing instances](https://github.com/MachineLearningSystem/SC21_Ribbon) SC'21

- [ INFaaS: Automated Model-less Inference Serving](https://github.com/MachineLearningSystem/INFaaS.git) ATC'21

- [Abacus](https://github.com/MachineLearningSystem/Abacus) SC'21

- [Serving DNNs like Clockwork: Performance Predictability from the Bottom Up](https://github.com/MachineLearningSystem/clockwork) OSDI'20

- [Exploiting Cloud Services for Cost-Effective, SLO-Aware Machine Learning Inference Serving](https://github.com/MachineLearningSystem/MArk-Project) ATC'19 

- [Nexus: a GPU cluster engine for accelerating DNN-based video analysis](https://github.com/MachineLearningSystem/nexus) SOSP'19 

- [Clipper:A low-latency prediction-serving system](https://github.com/ucbrise/clipper) NSDI'17


### MoE
- [SmartMoE: Efficiently Training Sparsely-Activated Models through Combining Static and Dynamic Parallelization ATC'23](https://github.com/MachineLearningSystem/23ATC-SmartMoE-AE)
- [MegaBlocks: Efficient Sparse Training with Mixture-of-Experts](https://github.com/stanford-futuredata/megablocks) MLSYS'23 
- [Tutel: Adaptive Mixture-of-Experts at Scale](https://github.com/MachineLearningSystem/tutel-MOE) MLSYS'23

- [FastMoE: A Fast Mixture-of-Expert Training System](https://github.com/MachineLearningSystem/fastmoe-thu) PPOPP'22

- [awesome MoE](https://github.com/MachineLearningSystem/awesome-mixture-of-experts)

- [MoE Paper](https://github.com/MachineLearningSystem/Awesome-Mixture-of-Experts-Papers)

- [AutoMoE: Neural Architecture Search for Efficient Sparsely Activated Transformers](https://github.com/MachineLearningSystem/AutoMoE) 

### GPU Cluster Management
- [Lucid: A Non-Intrusive, Scalable and Interpretable Scheduler for Deep Learning Training Jobs](https://github.com/MachineLearningSystem/Lucid) ASPLOS'23

- [Shockwave: Fair and Efficient Cluster Scheduling for Dynamic Adaptation in Machine Learning](https://github.com/MachineLearningSystem/shockwave) NSDI'23

- [Synergy : Looking Beyond GPUs for DNN Scheduling on Multi-Tenant Clusters](https://github.com/MachineLearningSystem/synergy.git) OSDI'22

- [Pollux: Co-adaptive Cluster Scheduling for Goodput-Optimized Deep Learning](https://github.com/MachineLearningSystem/adaptdl) OSDI'21

- [Heterogeneity-Aware Cluster Scheduling Policies for Deep Learning Workloads](https://github.com/MachineLearningSystem/gavel) OSDI'20

- [Tiresias -- A GPU Cluster Manager for Distributed Deep Learning Training without complete job information](https://github.com/MachineLearningSystem/Tiresias) NSDI'19

- [Chronus: A Novel Deadline-aware Scheduler for Deep Learning Training Jobs](https://github.com/MachineLearningSystem/ChronusArtifact) SOCC'21 


- [awesome DL scheduler](https://github.com/MachineLearningSystem/Awesome-DL-Scheduling-Papers.git)

### Schedule and Resource Management
- [An interference-aware scheduler for fine-grained GPU sharing Resources Eurosys'24](https://github.com/MachineLearningSystem/24Eurosys-orion.git)
- [ElasticFlow: An Elastic Serverless Training Platform for Distributed Deep Learning](https://github.com/MachineLearningSystem/ElasticFlow-ASPLOS23) ASPLOS'23 

- [Multi-Resource Interleaving for Deep Learning Training](https://github.com/MachineLearningSystem/Muri) SIGCOMM'22

- [Slapo: A Schedule Language for Progressive Optimization of Large Deep Learning Model Training ](https://github.com/MachineLearningSystem/slapo)  arxiv 

- [Out-of-order backprop: an effective scheduling technique for deep learning](https://github.com/MachineLearningSystem/ooo-backprop) Eurosys'22 

- [ KungFu: Making Training in Distributed Machine Learning Adaptive](https://github.com/MachineLearningSystem/KungFu) OSDI'20

- [PipeSwitch: Fast Pipelined Context Switching for Deep Learning Applications](https://github.com/MachineLearningSystem/PipeSwitch) OSDI'20 


### Optimization
- [GLake: optimizing GPU memory management and IO transmission ASPLOS'24](https://github.com/MachineLearningSystem/24ASPLOS-glake)
- [Spada: Accelerating Sparse Matrix Multiplication with Adaptive Dataflow](https://github.com/MachineLearningSystem/spada-sim) ASPLOS'23 

- [MISO: Exploiting Multi-Instance GPU Capability on Multi-Tenant GPU Clusters](https://github.com/MachineLearningSystem/socc22-miso) SOCC'22 

- [Accpar: Tensor partitioning for heterogeneous deep learning accelerators](https://github.com/MachineLearningSystem/AccPar) HPCA'20 


- [Hidet: Task Mapping Programming Paradigm for Deep Learning Tensor Programs](https://github.com/MachineLearningSystem/hidet) ASPLOS'23

- [iGniter: Interference-Aware GPU Resource Provisioning for Predictable DNN Inference in the Cloud](https://github.com/MachineLearningSystem/igniter) TPDS'22 

- [CheckFreq: Frequent, Fine-Grained DNN Checkpointing](https://github.com/MachineLearningSystem/CheckFreq) FAST'22

- [Efficient Quantized Sparse Matrix Operations on Tensor Cores](https://github.com/MachineLearningSystem/Magicube) SC'22

- [Harmony: Overcoming the hurdles of GPU memory capacity to train massive DNN models on commodity servers](https://github.com/MachineLearningSystem/harmony) VLDB'22

- [Pets](https://github.com/MachineLearningSystem/PetS-ATC-2022) ATC'22 

- [PET: Optimizing Tensor Programs with Partially Equivalent Transformations and Automated Corrections](https://github.com/MachineLearningSystem/pet-osdi21-ae) OSDI'21

- [APNN-TC: Accelerating Arbitrary Precision Neural Networks on Ampere GPU Tensor Cores](https://github.com/MachineLearningSystem/APNN-TC) SC'21

- [iGUARD](https://github.com/MachineLearningSystem/iGUARD.git) SOSP'21

- [Fluid: Resource-Aware Hyperparameter Tuning Engine](https://github.com/MachineLearningSystem/Fluid) MLSYS'21
- [Baechi: Fast Device Placement on Machine Learning Graphs ](https://github.com/MachineLearningSystem/baechi) SOCC'20 

- [Dynamic Parameter Allocation in Parameter Servers](https://github.com/MachineLearningSystem/AdaPS) VLDB'20 

- [Data Movement Is All You Need: A Case Study on Optimizing Transformers](https://github.com/MachineLearningSystem/substation) 

### GNN
- [gSampler: Efficient GPU-Based Graph Sampling for Graph Learning SOSP'23](https://github.com/MachineLearningSystem/23SOSP-gSampler)
- [Legion: Automatically Pushing the Envelope of Multi-GPU System for Billion-Scale GNN Training ATC'23](https://github.com/MachineLearningSystem/ATC23-Legion)
- [TC-GNN: Accelerating Sparse Graph Neural Network Computation Via Dense Tensor Core on GPUs ATC'23](https://github.com/MachineLearningSystem/ATC23-TCGNN-Pytorch)
- [Accelerating Graph Neural Networks with Fine-grained intra-kernel Communication-Computation Pipelining on Multi-GPU Platforms](https://github.com/MachineLearningSystem/MGG-OSDI23-AE) OSDI'23
- [COGNN](https://github.com/MachineLearningSystem/CoGNN_info_for_SC22.git) SC'22
- [TC-GNN: Accelerating Sparse Graph Neural Network Computation Via Dense Tensor Core on GPUs](https://github.com/MachineLearningSystem/TCGNN-Pytorch)
- [GNNAdvisor: An Efficient Runtime System for GNN Acceleration on GPUs](https://github.com/MachineLearningSystem/OSDI21_AE-GNN) OSDI'21

- [Marius: Learning Massive Graph Embeddings on a Single Machine](https://github.com/MachineLearningSystem/marius) OSDI'21

- [Dorylus: Affordable, Scalable, and Accurate GNN Training with Distributed CPU Servers and Serverless Threads](https://github.com/MachineLearningSystem/dorylus) OSDI'21 

- [BNS-GCN: Efficient Full-Graph Training of Graph Convolutional Networks with Partition-Parallelism and Random Boundary Node Sampling](https://github.com/MachineLearningSystem/BNS-GCN) MLSYS'22 

- [Accelerating Large Scale Real-Time GNN Inference Using Channel Pruning](https://github.com/MachineLearningSystem/GCNP) VLDB'21 
- [Reducing Communication in Graph Neural Network Training](https://github.com/MachineLearningSystem/CAGNET) SC'20 

- [awesome GNN](https://github.com/chwan1016/awesome-gnn-systems)

### Fine-Tune
-  [Fine-tuning giant neural networks on commodity hardware with automatic pipeline model parallelism](https://github.com/MachineLearningSystem/FTPipe-ATC21-Finetune.git) ATC'21

### Energy

- [Zeus: Understanding and Optimizing {GPU} Energy Consumption of {DNN} Training NSDI'23](https://github.com/MachineLearningSystem/Zeus) 

- [EnvPipe: Performance-preserving DNN Training Framework for Saving Energy ATC'23](https://github.com/MachineLearningSystem/23ATC-EnvPipe)

### Misc 
- [Characterizing Variability in Large-Scale, Accelerator-Rich Systems](https://github.com/MachineLearningSystem/gpu_variability_sc22_artifact) SC'22 

- [Prediction of the Resource Consumption of Distributed Deep Learning Systems](https://github.com/MachineLearningSystem/Driple) SIGMETRICS'22 

- [AI-Enabling Workloads on Large-Scale GPU-Accelerated System: Characterization, Opportunities, and Implications](https://github.com/MachineLearningSystem/HPCA22_SuperCloud) HPCA'22



## Contribute
We encourage all contributions to this repository. Open an [issue](https://github.com/lambda7xx/awesome-AI-system/issues) or send a [pull request](https://github.com/lambda7xx/awesome-AI-system/pulls).
