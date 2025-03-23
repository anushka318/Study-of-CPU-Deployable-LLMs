# Study-of-CPU-Deployable-LLMs

This project investigates the feasibility of running open-source LLMs efficiently on CPUs under varying hardware constraints. Students will simulate different CPU and RAM configurations using virtual machines, deploy various model architectures, and systematically measure latency. The goal is to analyze the relationship between compute resources (CPU, RAM) and model performance, identifying trade-offs and best practices for running LLMs on edge devices and resource-limited environments.


**Folder Structure:**

Since we were running multiple experiments on the same model, we have uploaded python notebooks for experiments performed and one final Analysis notebook to view all the visualizations.

GPT2Med: Has the GPT2 Medium python notebook, which was modified as required to perform # CPU cores vs Latency and throughput.

GPT2Quant : Has the GPT2 and GPT2Quant python notebook, which was modified as required to perform effect of quantization on # CPU cores vs Latency and throughput.

T5Base: Has the T5Base python notebook, which was modified as required to perform # CPU cores vs Latency and throughput.

GPT2_CoreCount: Has the GPT2 python notebooks, which were modified as required to perform # CPU cores vs Latency and throughput. 

GPT2Large_Pruning: Contains the codes use to run inference and benchmark the models with varying sparisty levels. Model pruning was performed using the code present in "GPT2_large_pruning.ipynb". The pruned models couldn't be included due to size restriction. Please modify the path in the inference code to match the location of pruned model. 

Analysis_visualization: Final notebook with all the analysis performed
