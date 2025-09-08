# Bachelor and Master Thesis Topics in AaltoSEA
>TBD

## AaltoSEA Thesis Principles and Procedure

### Principles for Bachelor Theses

- We define each topic in a way that it is big enough to allow 2-3 students carried out the thesis work. Usually a topic is defined in a subarea, which is our thesis focus for the current academic year. 
- Within a topic, individuals can do a specific threat of work, each topic will be advised by an advisor and mostly aligned with the advisor research direction 
- The head of AaltoSEA - Linh Truong - will oversee the quality but not act as the advisor for postdocs/PhD students offering the topic 
- All students are required to meet and report the progress of the work in Aalto thesis meetings
   - If a student does not commit to the schedule due to the lack of time or other reasons, we suggest the student should not take the topic from our group.
  
In the first meeting, we will clarify the protocol. 

### Quality control in writing

We suggest students to write a story like what could be found in seminar/conference/journal paper. Students should also try to do some qualitative/quantitative 
work to have better understanding and discussion (avoid just reading the papers, although the thesis does not require design or implementation work) 

The course of a bachelor thesis is 10 credits = 270 hours. Estimated around 50 hours for other assignments, the rest shall be dedicated for scoping, working on the thesis content, and writing the thesis. Thus, we suggest:

- 40 hours to really scope and understand the scope of the work
- 40 hours to identify all relevant documents/sources (initial)

We ask students to outline how many hours they plan per week for us to make two checkpoints: scoping and initial sources. Without passing that two checkpoints, the change the thesis fails is quite high.


## List of Available Topics for Bachelor Theses

**Once selecting the topic, the students have to join the first meeting on 11 Sep 2025 (at 11am, B322 CS building)**

### Bachelor Thesis Meetings

**All students who take the thesis topics from AaltoSEA will have to join regular thesis meetings**

> Thu, 11am-12pm, Konemiehentie 2, B322
> The first meeting: 11.09.2025. Then we will design the follow ups.

### Fall, 2025

#### Topic: Quality of Analytics for Data/AI-intensive Applications and Systems 

>**Background**:  

The concept of QoA recommends to characterize, monitor and optimize cloud applications, data pipelines, ML training/inferences, etc based on multiple dimensional metrics associated with data, performance, AI/ML, etc.  

As data- and AI-intensive services and systems evolve due to complex workloads and requirements, as the same time, new hardware and infrastructures emerge, metrics and techniques must be evolved.  

The work is to review/survey QoA metrics, techniques and tools. Within this topic, specific areas can be studied, such as (i) emerging metrics and measurements for AI Agents/Agentic AI, (ii) optimization based on QoA, (iii) tools for new metrics and infrastructures, e.g., related to the memory and low-latency communications with RDMA, and CXL fabrics. 

>**Some references**: 
- https://github.com/rdsea/QoA4ML 
- https://arxiv.org/pdf/2409.14317 
- https://dl.acm.org/doi/abs/10.1145/3630106.3658948 
- https://arxiv.org/abs/2501.10114 
- https://dl.acm.org/doi/pdf/10.1145/3555803 
- https://arize.com/ml-observability/ 
- https://dl.acm.org/doi/10.1145/3644815.3644964 
 

>**Prerequisite:** Programming models, system software, performance tool, observability, operating systems, cloud computing, AI infrastructures 

>**Advisor/Topic presented by**: Hong-Linh Truong (https://users.aalto.fi/~truongh4/)

>**Language**: English 

>**Topic Area**: Big Data and Large-scale Computing

#### Topic: Opportunistic Data Operation Platforms 
 
>**Background**: 
 Advanced applications leverage heterogeneous computing resources for diverse types of tasks. To date computing resources can be complex sets of GPU and CPU, whereas underlying communications and memory fabrics are also heterogenous, such as hardware acceleration for communications, RDMA, CLX, multi-endpoint smart NIC nodes, etc. At the same time, applications have different types of tasks with different workloads. Applications have services and tasks deployed in multi facilities of edge, cloud and HPC. Even a small fraction of unused allocated resources could be useful for some opportunistic operations. The topic will examine possible solutions to support opportunistic data operations, in terms of monitoring, scheduling, or profiling applications. The topic will also examine concrete techniques for specific infrastructures, such as multi-tenant environments in clouds and HPC with intra- and inter-node opportunistic operations.  Students will focus only on one specific aspect of the topic.
 
> **Some references**: 
 - https://github.com/rdsea/odop/ 
 - https://research.aalto.fi/en/publications/supporting-opportunistic-data-operations-for-data-intensive-compu-2 
 - https://dl.acm.org/doi/full/10.1145/3669900?af=R 
  
>**Prerequisite**: operating systems, virtualization, programming models, computing architecture, HPC, edge cloud computing 

>**Advisor/Topic presented by**: Hong-Linh Truong (https://users.aalto.fi/~truongh4/)

>**Topic Area**: Big Data and Large-scale Computing

#### Topic: Zero-Trust Networks for Edge-Cloud Computing 

>**Background**: 

As edge-cloud computing becomes increasingly prevalent, securing communication and operations across dynamic and distributed environments is critical. Traditional perimeter-based security models fall short in addressing the unique challenges of edge-cloud systems, such as distributed resources, scalability, and low-latency requirements. Zero-trust architecture, operating on the principle of "never trust, always verify," continuously validates every device, user, and application within the network to minimize security risks from both internal and external threats. Theses focus on exploring the advantages and disadvantages of zero-trust networks in edge-cloud computing, emphasizing best practices to secure data and communication channels, authenticate and authorize entities, and monitor threats in real time. 

>**Some references**: 

- [1] Stafford, V. "Zero trust architecture." NIST special publication 800 (2020): 207. 
- [2] Syed, Naeem Firdous, et al. "Zero trust architecture (ZTA): A comprehensive survey." IEEE Access 10 (2022): 57143-57179. 

>**Prerequisite**: Basic knowledge of network security and cloud computing 

>**Advisor/Topic presented by**: Hong-Tri Nguyen (hong-tri.Nguyen@aalto.fi) 

>**Language**: English 

>**Topic Area**: Software Systems and Technologies

#### Topics: A Survey of Observability Frameworks for LLMs

>**Background**: 

Despite rapid advances in large language models (LLMs), current observability frameworks remain limited in their ability to provide rigorous, transparent, and trustworthy evaluation. The complexity of heterogeneous data and interactions complicates traceability, benchmarking, and fairness assessment, while existing tools often prioritize either safety or performance without adequately balancing both. Moreover, mechanisms for integrating human oversight into observability are underdeveloped, leaving gaps in accountability, trust, and transparency. Without addressing these shortcomings, LLM-integrated systems risk propagating errors, biases, and failures that undermine their reliability and practical utility.

a student can choose to do a board topic (the title topic) or more precise from sub-topics for examples:
- **A Survey of Observability Frameworks for LLMs**: Compare existing frameworks (e.g., LangSmith, Arize, DeepEval, OpenTelemetry-based setups) in terms of their coverage of tracing, evaluation, fairness, and robustness.

   - **Comparing Safety-Oriented vs. Performance-Oriented Observability Frameworks**: Explore differences in frameworks that prioritize security/safety versus those focused on system performance and cost efficiency.

   - **Human-in-the-Loop Observability: Challenges and Approach**; Review how observability frameworks account for human feedback, trust, and transparency in LLM systems.

>**Some references**: 

- [TrustLLM: Trustworthiness in Large Language Models ](https://arxiv.org/abs/2401.05561)
- [Design Principles and Guidelines for LLM Observability: Insights from Developers ](https://dl.acm.org/doi/full/10.1145/3706599.3719914)
- [A.I. Robustness: a Human-Centered Perspective on Technological Challenges and Opportunities](https://dl.acm.org/doi/10.1145/3665926)
>**Prerequisite**: basic skills w.r.t. software and service engineering or AI/ML systems

>**Advisor/Topic presented by**: Korawit Rupanya (korawit.rupanya@aalto.fi) 

>**Language**: English 

>**Topic Area**: Software and Service Engineering

#### Topic: Systematic Review of Quantum Computing Integration with High-Performance Computing Systems

> **Background**:  

With the rise of distributed systems and edge computing, computational tasks are increasingly being distributed across clusters of edge devices to reduce latency, improve scalability, and bring processing closer to data sources. In parallel, quantum computing has emerged as a disruptive technology for solving problems in optimisation, machine learning, and cryptography. Recently, researchers have begun exploring how quantum algorithms could be integrated with distributed systems, leveraging clusters of heterogeneous devices for hybrid classical–quantum computation.  

The topic will review:
- Existing research on integrating quantum computing with distributed systems.
- Interaction models between edge clusters, cloud/HPC systems, and quantum backends.

Students will focus only on the review aspect, producing classification tables, taxonomies, and conceptual models summarising current research directions and challenges in quantum–HPC integration.  

> **Some references**:  
- [https://arxiv.org/abs/2508.04974](https://arxiv.org/abs/2508.04974)
- [https://arxiv.org/abs/2503.04905](https://arxiv.org/abs/2503.04905) 
- [https://ieeexplore.ieee.org/document/10989577](https://ieeexplore.ieee.org/document/10989577) 
- [https://dl.acm.org/doi/full/10.1145/3743149](https://dl.acm.org/doi/full/10.1145/3743149)  

> **Prerequisite**: Basic understanding of quantum computing concepts, basic understanding of HPC.  

> **Advisor/Topic presented by**: Debayan Bhattacharya  (debayan.bhattacharya@aalto.fi)

> **Language**: English  

> **Topic Area**: Software and Service Engineering 
