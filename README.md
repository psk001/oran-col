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
A conflict mitigation framework (CMF) built into the existing O-RAN architecture is defined, enabling the Conflict Mitigation component in O-RAN's Near-Real-Time RAN Intelligent Controller (Near-RT RIC) to detect and resolve all conflict types as specified by the O-RAN Alliance's technical specifications. Methods for detecting each type of conflict are outlined, including message flows between Near-RT RIC components. The suitability of the proposed CMF is demonstrated through a simulation of an O-RAN network. Simulation results show that enabling the CMF allows for the balancing of network control capabilities of conflicting xApps, significantly improving network performance with only a small negative impact on reliability. It is concluded that defining a unified CMF in Near-RT RIC is the first step toward providing a standardized method of conflict detection and resolution in O-RAN environments.

**[⬆ Back to Top](#table-of-contents)**

### Digital Twin for Open RAN Toward Intelligent and Resilient 6G Radio Access Networks
**Abstract:**
A comprehensive vision is provided on how Digital Twin (DT) and O-RAN represent two complementary concepts, which when merged will enable the deployment of an intelligent and resilient 6G RAN. DT is identified as playing a crucial role in enhancing the principles of intelligence, autonomy, and openness upon which O-RAN is based. A brief overview of both O-RAN and DT concepts is discussed. Potential use cases and services delivered through a DT-based O-RAN architecture are illustrated. Challenges and future research directions are also highlighted and discussed.

**[⬆ Back to Top](#table-of-contents)**

### Mean-Field Multi-Agent Contextual Bandit for Energy-Efficient Resource Allocation in vRANs (Pre-print)
**Abstract:**
The paper addresses the energy consumption issues in new-generation virtualized Radio Access Networks (vRANs). By conducting experiments on an O-RAN platform, a strategy for opportunistic offloading to Hardware Accelerators (HAs) is proposed to save energy while maintaining reliability. A scalable multi-agent contextual bandit algorithm called ECORAN is introduced, which uses mean field theory concepts. Experimental results demonstrate that ECORAN can achieve up to 40% energy savings compared to current industry standards.

**Aim:**
The paper aims to propose and validate an efficient strategy for energy-efficient resource allocation in vRANs. This strategy involves opportunistic offloading to HAs to balance energy savings and reliability. The aim is to address the collaborative multi-agent problem in vRANs by introducing ECORAN, a scalable algorithm designed to achieve significant energy savings while meeting reliability targets.

**Shortcomings:**
TBD

**[⬆ Back to Top](#table-of-contents)**

### Open Radio Access Networks (O-RAN) Experimentation Platform Design and Datasets
**Abstract:**
The paper discusses the design and implementation of a comprehensive O-RAN compliant testbed, aimed at addressing various challenges posed by the virtualization of Radio Access Networks (vRANs). By decoupling radio software from dedicated hardware, the proposed testbed fosters flexibility and cost-efficiency while maintaining high performance and reliability standards. The paper also presents datasets collected from extensive experiments, made publicly available to support ongoing research in this field.

**Aim:**
aim of the paper is to demonstrate the potential of an O-RAN compliant testbed to tackle key challenges in vRAN deployment, including real-time network configuration, resource sharing among virtualized base stations, energy consumption management, and integration with edge services. The testbed is designed to validate the performance, reliability, and energy efficiency of vRANs in a realistic setting.

**Shortcomings:**
TBD

**[⬆ Back to Top](#table-of-contents)**

### OREO: O-RAN Intelligence Orchestration of xApp-based network services
**Abstract:**
TBD

**Aim:**
TBD

**Shortcomings:**
TBD

**[⬆ Back to Top](#table-of-contents)**

###Efficient Service Allocation Scheduling Algorithms for 5G User Equipments in Slice-in-Slice Networks
**Abstract**

introduces a novel concept aimed at enhancing system performance at a granular level through the formation of multiple optimized User Equipment (UE) service-specific slice-in-slice categories across network slices. The study addresses the lack of state-of-the-art approaches that explore the relationships and supportability of UEs of different services within these categories during service allocation in network slicing. Novel Service Allocation Scheduling (SAS) algorithms for UE services are proposed, along with multimulti-objective, multi-constraint optimization models to achieve improved service level guarantees. Additionally, a graph-theoretical optimum service allocation strategy is developed to maximize network slice capacity, complemented by a probabilistic system resource prediction algorithm for UE services based on historical data. Comparative analysis with existing service scheduling algorithms demonstrates that the proposed SAS achieves throughput gains of 5.12 and 6.22 times over current methods.

###Open RAN LSTM Traffic Prediction and Slice Management using Deep Reinforcement Learning
**Abstract**
leverages the heterogeneous experiences of Distributed Units (DUs) in ORAN systems and introduces a novel approach to ORAN slicing xApp using Distributed Deep Reinforcement Learning (DDRL). Additionally, to enhance the decision-making performance of the RL agent, a prediction rApp based on Long Short-Term Memory (LSTM) is incorporated to provide additional information from the dynamic environment to the xApp. Simulation results demonstrate significant improvements in network performance, particularly in reducing Quality of Service (QoS) violations. This emphasizes the importance of using the prediction rApp and distributed actors' information jointly as part of a dynamic xApp.

###Slice-aware Open Radio Access Network planning and dimensioning
**Abstract**
introduces a novel approach to the planning and design of the ORAN architecture that simultaneously takes into account Quality of Service (QoS), Capital Expenditure (CAPEX), Operational Expenditure (OPEX), and the transport network. The ORAN slice planning and design is formulated as a multi-objective optimization problem with binary variables and is solved using simulated annealing. This paper provides a comprehensive discussion of the results, demonstrating that the proposed approach can be used in designing 5G ORAN network slices. 


###Intelligent QoS aware slice resource allocation with user association parameterization for beyond 5G ORAN based architecture using DRL

**Abstract**
The study proposes a Quality of Service (QoS)-aware intra-slice resource allocation strategy that outperforms baseline and state-of-the-art methods. Slice-dedicated intelligent agents are employed to manage resources at near-real-time Radio Intelligent Controller (RIC) levels, optimizing key performance indicators (KPIs) and ensuring QoS for each end user. Markov's decision process (MDP) and deep reinforcement learning (DRL) techniques, particularly deep Q network (DQN), are discussed for enhancing KPIs and system performance with various reward functions. The algorithm's efficacy is evaluated through simulations under dynamic network conditions and diverse characteristics, demonstrating improved network performance for enhanced mobile broadband (eMBB) and ultra-reliable low latency (URLLC) slice categories.



###Elastic O-RAN Slicing for Industrial Monitoring and Control: A Distributed Matching Game and Deep Reinforcement Learning Approach

**Abstract**

In this work, an elastic Open Radio Access Network (O-RAN) slicing framework is designed specifically for the Industrial Internet of Things (IIoT), addressing challenges like severe communication environments, varying network-slice resource demands, and real-time data updates crucial for industrial production. The primary objective is to minimize the cost of fresh information updates (Age of Information, AoI) from IIoT devices while considering energy consumption constraints and ensuring O-RAN slice isolation.

The proposed solution involves two main components:
1. **Intelligent O-RAN Framework**: Utilizes game theory and machine learning techniques to manage complexity. A two-sided distributed matching game at the O-RAN control layer captures IIoT channel characteristics and service priorities, forming preference lists for IIoT devices and Small Cell Base Stations (SBSs). This game feeds into an actor-critic model employing Deep Deterministic Policy Gradient (DDPG) in the O-RAN service management layer.
   
2. **Actor-Critic with DDPG**: This model optimizes resource allocation by dynamically adjusting network slice configurations based on time-varying slicing demands. It provides long-term policy-based guidance that reflects overall satisfaction levels of IIoT devices and SBSs with their assignments.

Simulation results demonstrate significant performance improvements over baseline approaches, with the proposed solution serving an average of 50% more IIoT devices and achieving a 43.64% increase in service capability. This approach integrates Industrial IoT management, distributed computation strategies, O-RAN slicing principles, Age of Information considerations, game theory frameworks, and deep reinforcement learning techniques to enhance IIoT service efficiency and reliability.

###Dynamic MAC Scheduling in O-RAN using Federated Deep Reinforcement Learning		
**Abstract**
we explore the use of Federated learning-based DRL (FDRL) for MAC scheduling 
in RAN sharing in O-RAN.

###	Policy-controlled QoS-based Resource Allocation xApp (QRA-xApp) from Rimedo Labs with ONF's SD-RAN RIC

**Abstract**
 integrated a new xApp, the QoS-based Resource Allocation xApp (QRA-xApp), into the SD-RAN platform developed by the Open Networking Foundation (ONF). This integration enhances the capabilities of ONF's Near Real-Time RAN Intelligent Controller (Near RT-RIC) by enabling dynamic control over O-DU functionalities, particularly the scheduler. The QRA-xApp optimizes resource allocation across network slices, ensuring Service Level Agreements (SLAs) are met while adapting to varying user demands and network conditions. Leveraging the A1 interface for policy control, this integration marks another step in Rimedo Labs' contribution to the SD-RAN ecosystem, supporting efficient radio resource management in heterogeneous networks.


###Energy Saving and Traffic Steering cooperate in O-RAN
**Abstract**

Energy Efficiency (EE) and Traffic Steering (TS) are pivotal aspects in the evolution of mobile networks, particularly in the context of 5G and beyond. Enhancing EE involves dynamically managing cell states based on traffic conditions, which necessitates efficient user offloading strategies. TS, defined by O-RAN ALLIANCE, plays a crucial role in distributing network traffic among cells to optimize load and Quality of Service (QoS) flows. This blog explores the integration possibilities and synergies between Energy Saving (ES) and TS mechanisms within O-RAN architectures.

**Aim of the Blog**

This blog aims to elucidate the collaborative potential between Energy Saving (ES) and Traffic Steering (TS) functionalities in O-RAN networks. It discusses two approaches for notifying TS-xApps about ES actions: leveraging the A1 interface and the E2SM-CCC model. By examining these methods, the blog highlights practical implementations and their implications for network efficiency and performance. The discussion underscores how these integrated strategies contribute to the broader goals of network optimization and sustainability in modern wireless ecosystems.

###Hierarchical Traffic Management in O-RAN – A Vehicular Scenario

**Abstract:**
Vehicular communication in 5G and future networks introduces significant challenges due to its dynamic spatial and temporal characteristics. This necessitates robust traffic management solutions within O-RAN architecture. This blog explores the deployment of Traffic Management rApp (TM-rApp) and Traffic Steering xApp (TS-xApp) in vehicular scenarios, leveraging Enrichment Information (EI) and real-time RAN statistics to optimize network performance.

**Aim:**
The blog aims to demonstrate how TM-rApp and TS-xApp contribute to hierarchical traffic management in O-RAN networks. It discusses their role in enhancing Quality of Service (QoS) for diverse vehicular services, including autonomous vehicle platoons and emergency response scenarios. Through simulation-based evaluations, the blog showcases the effectiveness of these applications in minimizing handovers, optimizing resource allocation, and ensuring reliable connectivity amidst dynamic traffic conditions.

This summary captures the core objectives and focus of the blog post, highlighting its exploration of advanced network management strategies tailored for vehicular communication within the O-RAN framework.

###Traffic Management for V2X use cases in O-RAN
**Abstract:**
Vehicular communication in 5G networks poses intricate challenges due to its dynamic spatial and temporal characteristics. This blog explores the deployment of Traffic Management rApp (TM-rApp) and Traffic Steering xApp (TS-xApp) within O-RAN architecture to address these challenges. It highlights the utilization of Enrichment Information (EI) and real-time RAN statistics to enhance network performance in scenarios such as car platoon management and emergency response.

**Aim:**
This blog aims to illustrate the implementation and operational synergy of TM-rApp and TS-xApp in vehicular scenarios within O-RAN networks. It discusses their roles in enabling hierarchical traffic management through policy-based control, efficient use of EI for proactive network management, and the exposure of RAN statistics via the Y1 interface. The simulation-based evaluation demonstrates their effectiveness in minimizing handovers, optimizing resource allocation, and ensuring robust connectivity under varying traffic conditions. The findings underscore the significance of these applications in meeting diverse service requirements and enhancing Quality of Service (QoS) in dynamic network environments.

This summary encapsulates the core objectives and thematic focus of the blog post, emphasizing advancements in traffic management solutions tailored for vehicular communications within evolving O-RAN frameworks.

