# AWS : Amazon Web Service : 200+ services

## Benefits of AWS Cloud

### Criteria of Cloud Computing
1. On-Demand Services
2. Access to networks
3. Resource Pooling
4. Elasticity
5. Resource usage and monitored and billing

### High Availability
	A system with a minimal downtime.
	Have extra instance ready to serve if acitve instance failed.
### Fault Tolerance
	A system designed with zero downtime. 
	Have more than one active instances to serve at all time. 

### Disaster Recovery
	A system designed to operate through a disaster
	Plan to execute in a disaster.

Fault tolerance : More Expensive
High Availability : Less Expensive 

## Elasticity

Automating along with Horizontal Scaling instances to match capacity of changing demands. 
### Vertical Scaling
**Increase the size of an instance. i.e. t2.micro -> t2.medium -> t2.large**
###### Pros: 
	No application modification needed 
###### Cons: 
	Small Disruption, when scaling. 
	More Expensive. 
### Horizontal Scaling
**Add similar size instances i.e. 3 x t2.micro -> 5 x t2.micro -> 10 x t2.micro**
###### Pros:
	Session loss, Can be handle with sticky sessions feature. 
	Less Expensive
###### Cons:
	Application Design must support this scaling before hand.


## Design principles of AWS well architect framework
### What is of AWS well architect framework
	It is a aws best practices and core strategies for architecting systems in cloud. Helping you design, build and operate reliable, secure and efficient and cost-effective systems. 
### Based on 6 pillars

#### Operational Excellency
**Ability to support development and run work-load effectively. Gain insight into their operation and continuous improve supporting processes and procedures to deliver business values** 
###### 5 Design principles of Operational Excellency 
1. Perform operations as code
2. Make frequent, small, reversible changes
3. Refine operations procedure frequently
4. Anticipate failures
5. Learn from all operational failures.
#### Security 
**Ability to protect data, systems and assets to take advantage of cloud technologies to improve security**
###### 7 Design Principle of Security 
1. Implement a Strong identity foundation
2. Maintain Traceability
3. Apply Security at all layers
4. Automate security best practices
5. Protect Data in transit and at rest
6. Keep people away from data
7. Prepare for security events
#### Reliability 
**Ability of a workload to perform its intended function correctly and consistently when its expected to. Ability to test and operate through its lifecycle.**  
###### 5 Design Principle of Reliability
1. Automatically recover from failure
2. Test recovery procedures
3. Scale Horizontally to increase aggregated workload availability 
4. Stop guessing capacity
5. Manage change in automation
#### Performance Efficiency 
**Ability to use computer resources efficiently to meet system requirements. And Maintain that efficiency after system changes and technologies evolve**
###### 5 Design Principle of Performance Efficiency
1. Democratize advance technologies
2. Go global in minutes
3. Use Serverless architecture
4. Experiment Often
5. Consider Mechanical Sympathy
#### Cost Optimization 
**Ability to run system to deliver business values at the lowest price point possible.** 
#### Sustainability 
**Focus on environment effects, especially energy consumption and efficiency.** 
###### 6 Design Principle of Sustainability
1. Understand your impact
2. Establish Sustainability goals
3. Maximize utilization
4. Anticipate and adopt or new hardware and software offering
5. Use manage services
6. Reduce downstream impact of your cloud workloads

## Benefits and Strategies for migrating to AWS cloud using AWS cloud adoption framework

### What is AWS cloud adoption framework?
	AWS CAF provides a comprehensive approach to cloud and identify organizational capabilities for sucessful cloud transformations. It provides best practice guidance and improve your cloud readiness. 
### Benefits of using AWS CAF
	1. Reduce Business Risk, improve reliability, increase performance and enhance security.
	2. Increase operational effeciency by reducing cost and increasing productivity
	3. Grow by creating new products or services to reach new market and improve performance. 

### 6 Perspective of AWS CAF

#### Business

#### People

#### Governance

#### Platform

#### Security 

#### Operations
### Cloud Adoption Strategies
Depends on different stage of adoption. Different adoption stages are as below

#### Different adoption stages

##### Project Stage
	Evaluating if migration will meet your specific requirements and need
##### Foundation Stage
	Migration to AWS begins here. Move few production application to AWS or an initial framework for landing zone for non-production enviorment
##### Migration Stage
	Define roles for cloud operations. Establish Cloud Centered of Excellence (CCOE) and prepare for long-term cloud operations. 
##### Reinvention stage
	All new project start in AWS. 

### 7 Migration Strategies 
1. Retire : Service you no longer need and decommission. 
2. Retain : Service you need in source environment or not ready to migrate
3. Rehost : Service needed to migrate without changing applications
4. Relocate : Large number of servers made up of one or more application
5. Repurchase : Service with different version or product and provide more value than existing
6. Replatform : Service need some optimization in-order to operate efficiently 
7. Refactor or Re-Architect: Service that need to changed from ground-up to take advantage of AWS services. 

## Concepts of Cloud Economics

### Total Cost of Ownership (TCO)
**Cost needed to providing services by owning different services**
1. Operational Cost : Day-to-Day Expenses
2. Capital Expenses : Purchasing Server
3. Labor Cost : Hires for installing, managing those Servers
4. Software Licensing Cost : Currently used softwares and re-purchasing them is required or not


## Security and Compliance

### AWS Shared responsibility model

![Pasted image 20231118145234](https://github.com/samarthpatel1289/Cloud-Practitioner-Certificate-Notes/assets/57533166/47f79f59-8bc4-4b2a-9f93-9ac2326044dd)


### AWS Cloud security, Governance and Compliance 

### AWS Access Management Capabilities

### Component and Resource for Security

