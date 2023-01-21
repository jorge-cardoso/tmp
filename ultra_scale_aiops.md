# Overview

+ Project name
	+  AI for Project Management 
+ Stakeholders
	+ Jane Osborn @j00000001
+ Team
	+ Lilly Koch @l00000002, Gillian Petty @g00000002, Abigayle Moran @a00000003
	+ Frederick Martin @f00000004, Anton Chambers @a00000005, Byron Compton @b00000006 
+ Chat rooms
	+ AI4PM: Local Berlin 
	+ AI4PM: Global Team
+ Cloud storage: 
	+ https://dropbox.com/b/52f3a0a66a90992b62d4aa643a74e2f1
+ Duration
	+ `15.03.2023` -- `15.03.2024`
+ Deliverables
	+ D1. Tool/Library to predict the failure of hardrives 
	+ D2. Powerpoint report with tool design and evaluation in production   

# Description

+ **Goal**
	+ Develop a PoC which demonstrated the benefits of Quantum computing w.r.t. latency, response time and bandwidth
+ **Background**
	+ In recent years, cloud computing has become a central part of the AI evolution. To better address requirements, businesses are becoming aware of the need to bring the technology closer to customers. Thus, Edge AI is emerging as a solution that uses ML to process data generated at the local level. 
+ **Problem**
	+ While the edge model considerably reduces transmission costs and latency requirements, it raises questions with respect to system architectures, AI pipelines and privacy and reliability concerns. An example of this technology is Amazon Alexa which learns and stores phrases locally using AI.
	+ When a user gives a verbal command, the device sends the voice recording to an edge network where it is transformed to text using AI algorithms. Without an edge network the response time would be seconds, with edge the latency is reduced to <400 ms. 
+ **Approach**
	+ As a starting point, this project will use two use cases involving video recognition, security cameras, OCR, real-time device tracking, as well as cloud gaming and video compression.
	+ In one use case, cameras will monitor containers in a transportation chain, while the ML will recompile data in real time for the container tracking process.
	+ The two use cases will be used to derive requirements and implement a prototype to demonstrate how edge platforms can be exploited to steer AI-driven applications. 
+ **Results**
	+ The prototype to be developed will serve to experiment with various architecture configurations, derive latency and bandwidth constraints, and explore how high levels of reliability and security can be achieved.
+ **KPI**
	+ Response time < 100ms.


# Results

+ Algorithm
	+ Hard drive failure prediction
+ Performance
	+ Precision improved from 63% to 92%  
+ Impact
	+ Reduction on 5% of HUAWEI CLOUD failures impacting colleagues
+ Report
	+ https://dropbox.com/b/52f3a0a66a90992b62d4aa643a74e2f1


# Execution
## Tasks

+ &Literature_Review: [&Research] Review literature of log management systems
+ &Competitor_analysis: [&Research] Analyse commercial log management systems
+ &PoC: [&Prototyping] Build MVP system with log anomaly detection
+ &Demo: [&Prototyping] Show running system with HUAWEI CLOUD data
+ &System_Design: [&Design] Make system design for HUAWEI CLOUD CLS
+ &Dev: [&Development] Implement system in Python
+ &Staging: [&Preproduction] Integrated into CLS preproduction platform
+ &Production: [&Production] Move system to CLS to production region
+ &Evaluation: [&Evaluation] Prepare final report

## Sprints
### $Jan 2023

+ $23.01.2023
    + *Status*
        + [&System_Design, @j00760260, %75] Design the system to be integrated into the CAD system
        + [&Demo, @j00760260, %90] PoC showing observability analytics
    + *Risks* 
        + No risk
 
+ $16.01.2023
   + *Status*
       + [&PoC, @j00760260, %90] PoC showing observability analytics
       + [&Demo, @j00760260, %90] PoC showing observability analytics
   + *Risks* 
       + No risk


