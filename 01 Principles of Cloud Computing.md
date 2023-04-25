# Part 1: Principles of Cloud Computing

## Objectives
* Describe what is Cloud Computing
* Describe terms such as:
  * High Availability, 
  * Scalability, 
  * Elasticity, 
  * Agility, 
  * Fault Tolerance, 
  * Disaster Recovery

---

## What is Cloud Computing?
Cloud computing is a _service delivery model_ over the Internet (the Cloud).
<br><br>
Typically, you need to sort your own resources out...

* Servers
* Storage
* Databases
* Networks
* Software
* Analytics
* Intelligence

...with cloud computing, you typically only pay for whichever services you require. There are, of course, great benefits to this!

☑ Your operating costs are lowered

☑ Your infrastructure can be run efficiently

☑ Your scale as a business can grow

## Ideal benefits of cloud computing
There are key characteristics of cloud computing:

### Scalability
> The ability to scale the system. This can either be **vertical scaling** (increasing the size/capacity of your resources) or **horizontal scaling** (increasing how many resources you have).

* If you 'scale up', you're increasing the size of your allocated resources; if you 'scale down', you're decreasing instead.
* Analogously... if you 'scale out', you're allocating more resources; if you 'scale in' you're deallocating.

### Elasticity
If scaling is how we (de)allocate more/increase the amount of resources, then we need to consider how/when we do that.
> Elasticity is the ability to scale dynamically. This means (de)allocating resources to users as they're needed. For example, if we only have one user using the system, only allocate one user's worth of resources... if we have five users, allocate five users' worth.

### Agility
To be 'agile' is to react quickly. Hence,
> Agility is defined as the ability to (de)allocate resources as quickly as they're (not) needed.

Systems should have high agility, and be able to react to the demand for resources. 

### Fault Tolerance
> The ability to maintain uptime while physical or service component failures happen in a system.

For a system, we want high fault tolerance. This shows the system can react to and handle faults well.

### Disaster Recovery
> A disaster is a natural or human induced incident that causes the system to go offline.

Disasters can occur within systems - they happen! What's important is how we bounce back from them.

> Disaster recovery is the ability to recover from disaster.

### High Availability
This is more of a metric than a 'definition'.
> High availability is the agreed level of operational uptime for a system.

We calculate the 'availability' of a system using:

$ {Availability} = \frac{Uptime}{Uptime + Downtime} $

We want to maximise this availability by having more uptime through the system lifetime.