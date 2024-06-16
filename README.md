# [Mean-Field Multi-Agent Contextual Bandit for Energy-Efficient Resource Allocation in vRANs](#description)

## Abstract
The paper addresses the high energy consumption of hardware accelerators (HAs) in virtualized RANs (vRANs). It proposes ECORAN, a multi-agent contextual bandit algorithm that uses mean field theory for scalable and energy-efficient resource allocation. Experiments show ECORAN can achieve up to 40% energy savings while maintaining reliability.

## Aim
The aim is to develop an energy-efficient strategy for resource allocation in vRANs by optimizing the use of HAs and CPUs, thereby reducing energy consumption and maintaining reliability.

## Shortcomings
The primary shortcoming is the complexity and unpredictability of balancing workloads between HAs and CPUs in real-time, especially with varying traffic loads and the need for scalability with a large number of base stations.

## [Description](#)
This paper discusses Radio Access Network (RAN) virtualization, key for new-generation mobile networks, which requires hardware accelerators (HAs) to process wireless signals from base stations (BSs) to meet stringent reliability targets. However, HAs are expensive and energy-hungry. To address this problem, data from an experimental platform is gathered, comparing the performance and energy consumption of a HA (NVIDIA GPU V100) versus a CPU (Intel Xeon Gold 6240R, 16 cores) for energy-friendly software processing. Based on these insights, a strategy to offload workloads to HAs opportunistically is devised, aiming to save energy while preserving reliability. This strategy must be configured in near-real-time for every BS sharing common computational resources, presenting a challenging multi-agent collaborative problem with a potentially large and variable number of agents (BSs). Therefore, an efficient multi-agent contextual bandit algorithm called ECORAN is proposed, applying concepts from mean field theory to ensure scalability. Using a real platform and traces from a production mobile network, ECORAN is shown to provide up to 40% energy savings compared to current industry approaches.
