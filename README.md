# Research Papers Overview

## Table of Contents
1. **[Mean-Field Multi-Agent Contextual Bandit for Energy-Efficient Resource Allocation in vRANs](#mean-field-multi-agent-contextual-bandit-for-energy-efficient-resource-allocation-in-vrans)**
2. **[Intent-Aware Radio Resource Scheduling in a RAN Slicing Scenario Using Reinforcement Learning](#intent-aware-radio-resource-scheduling-in-a-ran-slicing-scenario-using-reinforcement-learning)**
3. **[DRL-based Latency-Aware Network Slicing in O-RAN with Time-Varying SLAs](#drl-based-latency-aware-network-slicing-in-o-ran-with-time-varying-slas)**
4. **[Machine Learning-based xApp for Dynamic Resource Allocation in O-RAN Networks](#machine-learning-based-xapp-for-dynamic-resource-allocation-in-o-ran-networks)**
5. **[Programmable and Customized Intelligence for Traffic Steering in 5G Networks Using Open RAN Architectures](#programmable-and-customized-intelligence-for-traffic-steering-in-5g-networks-using-open-ran-architectures)**
6. **[Conflict Mitigation Framework and Conflict Detection in O-RAN Near-RT RIC](#conflict-mitigation-framework-and-conflict-detection-in-o-ran-near-rt-ric)**
7. **[Digital Twin for Open RAN Toward Intelligent and Resilient 6G Radio Access Networks](#digital-twin-for-open-ran-toward-intelligent-and-resilient-6g-radio-access-networks)**
8. **[Open Radio Access Networks (O-RAN) Experimentation Platform Design and Datasets](#open-radio-access-networks-o-ran-experimentation-platform-design-and-datasets)**
9. **[OREO: O-RAN Intelligence Orchestration of xApp-based network services](#oreo-o-ran-intelligence-orchestration-of-xapp-based-network-services)**
10. **[Efficient Service Allocation Scheduling Algorithms for 5G User Equipments in Slice-in-Slice Networks](#efficient-service-allocation-scheduling-algorithms-for-5g-user-equipments-in-slice-in-slice-networks)**
11. **[Open RAN LSTM Traffic Prediction and Slice Management using Deep Reinforcement Learning](#open-ran-lstm-traffic-prediction-and-slice-management-using-deep-reinforcement-learning)**
12. **[Slice-aware Open Radio Access Network Planning and Dimensioning](#slice-aware-open-radio-access-network-planning-and-dimensioning)**
13. **[Intelligent QoS-aware Slice Resource Allocation with User Association Parameterization for Beyond 5G ORAN Based Architecture Using DRL](#intelligent-qos-aware-slice-resource-allocation-with-user-association-parameterization-for-beyond-5g-oran-based-architecture-using-drl)**
14. **[Elastic O-RAN Slicing for Industrial Monitoring and Control: A Distributed Matching Game and Deep Reinforcement Learning Approach](#elastic-o-ran-slicing-for-industrial-monitoring-and-control-a-distributed-matching-game-and-deep-reinforcement-learning-approach)**
15. **[Dynamic MAC Scheduling in O-RAN Using Federated Deep Reinforcement Learning](#dynamic-mac-scheduling-in-o-ran-using-federated-deep-reinforcement-learning)**
16. **[Policy-controlled QoS-based Resource Allocation xApp (QRA-xApp) from Rimedo Labs with ONF's SD-RAN RIC](#policy-controlled-qos-based-resource-allocation-xapp-qra-xapp-from-rimedo-labs-with-onfs-sd-ran-ric)**
17. **[Energy Saving and Traffic Steering Cooperate in O-RAN](#energy-saving-and-traffic-steering-cooperate-in-o-ran)**
18. **[Hierarchical Traffic Management in O-RAN – A Vehicular Scenario](#hierarchical-traffic-management-in-o-ran-a-vehicular-scenario)**
19. **[Traffic Management for V2X Use Cases in O-RAN](#traffic-management-for-v2x-use-cases-in-o-ran)**

## Details

### Mean-Field Multi-Agent Contextual Bandit for Energy-Efficient Resource Allocation in vRANs
**Abstract:**
The paper presents a mean-field multi-agent contextual bandit approach for energy-efficient resource allocation in virtualized Radio Access Networks (vRANs). By leveraging mean-field theory and multi-agent systems, the proposed method aims to optimize energy usage while ensuring efficient resource distribution among multiple agents in a vRAN environment.

**Aim:**
The primary aim is to develop a scalable and efficient resource allocation algorithm that reduces energy consumption in vRANs, enhancing overall network performance and sustainability.

**[⬆ Back to Top](#table-of-contents)**

### Intent-Aware Radio Resource Scheduling in a RAN Slicing Scenario Using Reinforcement Learning
**Abstract:**
Network slicing in the radio access network (RAN) domain, known as RAN slicing, demands elasticity, efficient resource sharing, and customization. This paper introduces an intent-aware reinforcement learning method for radio resource scheduling (RRS) in a RAN slicing scenario. The proposed method aims to prevent intent faults by managing radio resources among slices, ensuring fulfillment of slice quality of service (QoS) intents.

**Aim:**
The goal is to enhance the RRS function in RAN slicing by using reinforcement learning to fulfill QoS intents described in service-level agreements (SLAs). The method is evaluated under various network conditions to ensure it outperforms existing baselines.

**Shortcomings:**
- The approach may encounter difficulties in scenarios with highly dynamic network conditions and varying QoS requirements.
- The reinforcement learning method might have high sample complexity and sensitivity to hyperparameters.
- Stability and convergence issues could arise when dealing with continuous state and action spaces.

**[⬆ Back to Top](#table-of-contents)**

### DRL-based Latency-Aware Network Slicing in O-RAN with Time-Varying SLAs
**Abstract:**
In the paper, a novel Deep Reinforcement Learning (DRL) agent design is proposed for O-RAN applications to learn control policies under varying Service Level Agreements (SLAs) with heterogeneous minimum performance requirements. The focus is on RAN slicing and SLAs specifying maximum tolerable end-to-end latency levels. The OpenRAN Gym open-source environment is utilized to train a DRL agent capable of adapting to diverse SLAs. A comparison is made against the state-of-the-art methods, demonstrating that the agent maintains a low SLA violation rate, which is 8.3× and 14.4× lower than approaches based on Deep Q-Learning (DQN) and Q-Learning, respectively, while consuming 0.3× and 0.6× fewer resources without necessitating re-training.

**[⬆ Back to Top](#table-of-contents)**

### Machine Learning-based xApp for Dynamic Resource Allocation in O-RAN Networks
**Abstract:**
The issue of dynamic resource allocation was tackled using a data-driven approach through the employment of Machine Learning (ML). An xApp-based implementation for the proposed ML algorithm was presented, with the core aim of optimizing resource allocation and fulfilling Service Level Specifications (SLS). This was accomplished by dynamically adjusting the allocation of Physical Resource Blocks (PRBs) based on traffic demand and Quality of Service (QoS) requirements. The proposed ML model effectively selected the best allocation policy for each base station and enhanced the performance of scheduler functionality in the O-RAN - Distributed Unit (O-DU). It was demonstrated that an xApp implementing the Random Forest Classifier could yield high performance accuracy (85%) for optimal policy selection, achieved using the O-RAN instance state input parameters over a short training duration.

**[⬆ Back to Top](#table-of-contents)**

### Programmable and Customized Intelligence for Traffic Steering in 5G Networks Using Open RAN Architectures
**Abstract:**
The issue of dynamic resource allocation is addressed through the introduction of ns-O-RAN, a software framework that integrates a real-world, production-grade near-RT RIC with a 3GPP-based simulated environment on ns-3. This integration enables the development of xApps and the automated large-scale data collection and testing of Deep Reinforcement Learning-driven control policies for user-level optimization. Additionally, the first user-specific O-RAN Traffic Steering (TS) intelligent handover framework is proposed. This framework employs Random Ensemble Mixture combined with a state-of-the-art Convolutional Neural Network architecture to optimally assign a serving base station to each user in the network. The TS xApp, trained with more than 40 million data points collected by ns-O-RAN, runs on the near-RT RIC and controls its base stations. Performance evaluation on a large-scale deployment shows that the xApp-based handover improves throughput and spectral efficiency by an average of 50% over traditional handover heuristics, with less mobility overhead.

**[⬆ Back to Top](#table-of-contents)**

### Conflict Mitigation Framework and Conflict Detection in O-RAN Near-RT RIC
**Abstract:**
A conflict mitigation framework (CMF) built into the existing O-RAN architecture is defined, enabling the Conflict Mitigation component in O-RAN's Near-Real-Time RAN Intelligent Controller (Near-RT RIC) to detect and resolve all conflict types as specified by the O-RAN Alliance's technical specifications. Methods for detecting each type of conflict are outlined, including message flows between Near-RT RIC components. The suitability of the proposed CMF is demonstrated through a simulation of an O-RAN network. Simulation results show that enabling the CMF allows for the balancing of network control capabilities of conflicting xApps, significantly improving network performance with only a small increase in control signaling overhead.

**[⬆ Back to Top](#table-of-contents)**

### Digital Twin for Open RAN Toward Intelligent and Resilient 6G Radio Access Networks
**Abstract:**
A comprehensive examination of a Digital Twin (DT) system in the context of 6G is presented, leveraging recent advancements in O-RAN and DTs. The focus is on dynamic service scheduling, resource allocation, and RAN optimization, tailored to the anticipated 6G landscape. Additionally, a novel intelligent conflict avoidance framework is discussed. The DT system achieves significant improvement in key performance indicators (KPIs) for networks equipped with the system, demonstrating its efficacy in service orchestration, dynamic scheduling, and efficient resource allocation. 

**[⬆ Back to Top](#table-of-contents)**

### Open Radio Access Networks (O-RAN) Experimentation Platform Design and Datasets
**Abstract:**
The paper describes the development of an O-RAN experimentation platform integrated with standardized data sets and testbeds to enhance the research and development of future wireless networks. A comprehensive overview of the architecture, components, and functionalities of the platform is provided, with an emphasis on its ability to facilitate real-world experiments and benchmarking. The availability of open data sets and standardized testing scenarios aims to streamline the validation of new algorithms and technologies in the O-RAN ecosystem, promoting collaboration and innovation.

**[⬆ Back to Top](#table-of-contents)**

### OREO: O-RAN Intelligence Orchestration of xApp-based Network Services
**Abstract:**
The paper introduces OREO, a scalable orchestration framework that dynamically manages xApp-based network services in O-RAN. OREO ensures optimal resource utilization and SLA compliance by leveraging machine learning models to predict network conditions and orchestrate xApps accordingly. The proposed framework demonstrates significant improvements in network performance, scalability, and adaptability to changing network environments.

**[⬆ Back to Top](#table-of-contents)**

### Efficient Service Allocation Scheduling Algorithms for 5G User Equipments in Slice-in-Slice Networks
**Abstract:**
The paper presents advanced scheduling algorithms designed for efficient service allocation in 5G slice-in-slice network environments. By prioritizing user equipments based on real-time network conditions and service requirements, the proposed algorithms aim to enhance network resource utilization and QoS delivery. Simulation results indicate significant improvements in service latency and throughput.

**[⬆ Back to Top](#table-of-contents)**

### Open RAN LSTM Traffic Prediction and Slice Management using Deep Reinforcement Learning
**Abstract:**
This research focuses on integrating LSTM-based traffic prediction models with deep reinforcement learning (DRL) for efficient slice management in Open RAN. By predicting traffic patterns and dynamically adjusting resource allocations, the proposed system enhances network performance and reduces SLA violations. Experimental results highlight the effectiveness of the approach in managing network slices under varying traffic conditions.

**[⬆ Back to Top](#table-of-contents)**

### Slice-aware Open Radio Access Network Planning and Dimensioning
**Abstract:**
A slice-aware planning and dimensioning approach for Open RAN is proposed, aimed at optimizing resource allocation across multiple network slices. By considering slice-specific requirements and network constraints, the method enhances overall network efficiency and QoS. The paper provides detailed modeling and simulation results, demonstrating the benefits of the proposed approach.

**[⬆ Back to Top](#table-of-contents)**

### Intelligent QoS-aware Slice Resource Allocation with User Association Parameterization for Beyond 5G ORAN Based Architecture Using DRL
**Abstract:**
This paper addresses the challenge of resource allocation in beyond 5G O-RAN architectures by proposing a DRL-based method that intelligently manages slice resources while considering user association parameters. The approach ensures QoS adherence and optimizes resource usage, leading to improved network performance and user satisfaction. Experimental evaluations show significant enhancements over traditional methods.

**[⬆ Back to Top](#table-of-contents)**

### Elastic O-RAN Slicing for Industrial Monitoring and Control: A Distributed Matching Game and Deep Reinforcement Learning Approach
**Abstract:**
The paper introduces an elastic O-RAN slicing framework designed for industrial monitoring and control applications. By combining a distributed matching game with deep reinforcement learning, the proposed method dynamically allocates resources to meet the stringent requirements of industrial IoT systems. Simulation results demonstrate the framework's ability to maintain low latency and high reliability.

**[⬆ Back to Top](#table-of-contents)**

### Dynamic MAC Scheduling in O-RAN Using Federated Deep Reinforcement Learning
**Abstract:**
This research presents a novel approach to MAC scheduling in O-RAN using federated deep reinforcement learning (FDRL). By enabling distributed learning across multiple network nodes, the proposed method improves scheduling efficiency and adapts to changing network conditions. The paper includes detailed experimental results, highlighting the benefits of FDRL in terms of throughput and latency.

**[⬆ Back to Top](#table-of-contents)**

### Policy-controlled QoS-based Resource Allocation xApp (QRA-xApp) from Rimedo Labs with ONF's SD-RAN RIC
**Abstract:**
Rimedo Labs presents the QRA-xApp, designed to provide policy-controlled QoS-based resource allocation in O-RAN environments. Leveraging the ONF's SD-RAN RIC, the xApp dynamically allocates resources based on QoS policies, ensuring SLA compliance and efficient network operation. The paper discusses the xApp's architecture, implementation, and performance in various scenarios.

**[⬆ Back to Top](#table-of-contents)**

### Energy Saving and Traffic Steering Cooperate in O-RAN
**Abstract:**
This paper explores the synergy between energy-saving mechanisms and traffic steering strategies in O-RAN. By integrating energy-efficient algorithms with intelligent traffic steering, the proposed approach reduces energy consumption while maintaining network performance. The paper includes comprehensive evaluations, demonstrating the approach's effectiveness in various network conditions.

**[⬆ Back to Top](#table-of-contents)**

### Hierarchical Traffic Management in O-RAN – A Vehicular Scenario
**Abstract:**
The paper introduces a hierarchical traffic management framework for O-RAN, specifically designed for vehicular scenarios. By leveraging hierarchical control and optimization techniques, the framework aims to enhance traffic management and QoS for connected vehicles. Simulation results show significant improvements in latency and throughput.

**[⬆ Back to Top](#table-of-contents)**

### Traffic Management for V2X Use Cases in O-RAN
**Abstract:**
Focused on vehicle-to-everything (V2X) use cases, this paper presents traffic management strategies for O-RAN. By addressing the unique requirements of V2X communication, the proposed methods aim to improve network performance and reliability. The paper includes detailed analyses and simulation results, highlighting the benefits of the proposed strategies.

**[⬆ Back to Top](#table-of-contents)**
