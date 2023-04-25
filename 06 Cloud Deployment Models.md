# Part 6: Cloud Deployment Models

## Objectives:
* Describe Public cloud
* Describe Private cloud
* Describe Hybrid cloud
* Compare and contrast the three different deployment models

-----

There's a clear separation of _where_ we deploy our applications to:
- either in a cloud service provider,
- or in our own datacenter
- ...or both?

There are various advantages and disadvantages to deploying to a cloud service provider or your own datacenter - even (dis)advantages to using both! - that will affect which one you choose.

## Public
All our resources runs on public cloud provided hardware; we don't own the hardware! <br><br>
Public provides the **greatest degree of high availability, agility, and consumption**

### Advantages
 -  It's simple to understand: you host everything in the public cloud! Not much technical know-how is needed this way.
 -  It uses the consumption-based model: you only pay for what you use (with granular costs)
 -  No CapEx, hence no initial investment - this makes it highly available and agile!
 -  Pay as you go pricing means you only pay for what you use; Microsoft manages all hardware.
 -  Furthermore... no maintenance or deep tech skills required

### Disadvantages
 - Security & compliance: the cloud is secure by default, but if you have any specific security requirements/policies/legal requirements, it's unlikely that a public cloud will always be able to meet them.
 - Another problem arises with ownership: changes to hardware aren't possible, since it belongs to Microsoft within their own datacenters, so this is bad for unique business requirements
  - Finally - Some services will require you to share hardware with other customers (but this is usually solved when choosing pricing tier)


## Private
With private, you host everything in your own datacenter. You need a self-service to be provided for this deployment model.
<br><br>
Private provides you with the **greatest degree of control** over deployment, which is natural since all of the hardware is your own.

### Advantages
 - Private provides you with total access to your own (private) servers & infrastructure; you have total control of every aspect
 - This means you can support any scenario!
 - ...and, you have total control over security and can meet any security/compliance requirements

### Disadvantages
 - There is big initial CapEx - you have to pay upfront all of the costs for your hardware
 - You also have limited based on the amount of hardware you have
 - Team skills is also a factor: you need expertise in your team! There will be a lot of maintenance.

---

## Hybrid

This approach takes advantage of the benefits of both public and private deployment models. <br><br>
Hybrid, as its name suggests, gives you the **greatest degree of flexibility** with your deployment. You can choose to use a mixture of public and private, hence you can delegate control wherever you'd like.
<br><br>
Additionally - consider the use case for hybrid. You might want to publicise part of it for the reliance on Microsoft-owned infrastructure, or you might privatise part of it to have more control. It depends!
 - Flexibility is the _main advantage_ here! Very flexible, very good.
 - With hybrid, you can run legacy apps in private cloud
 - You can utilise existing infrastructure, whilst meeting security requirements
 
### Disadvantages
- Of course, it's expensive: you're still renting resources on public whilst having to pay for/maintain your own hardware.
 - It's also complicated to manage - you will rely a lot on the skills of your management team to control the private server.