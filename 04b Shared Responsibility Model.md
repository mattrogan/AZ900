# Part 4b: Shared Responsibility Model

## Objectives:
* Describe the shared responsibility model

---

Having looked at the consumption-based model, we now also need to consider a shared-responsibility model for applications in the cloud.

## What is the Shared Responsibility model?
> In simple terms, the shared responsibility model is a framework that explains who is responsible for what when it comes to security and compliance in the cloud.

The main keyword here is **responsibility** - who is responsible? In the context of Microsoft Azure:
* Microsoft is responsible for the security of infrastructure. This includes the physical datacentres, the network, and the hardware
However, the responsibility is **shared**. Hence:
* You are responsible for the security of your data and application(s) being hosted on Azure. This includes access management, network security, application security, and data encryption.

Another way of viewing this is that:
* Microsoft provides a secure and compliant infrastructure
* You are ensuring that your applications and data are secure and compliant
...so, the security & compliance of the application is *shared* between you and Microsoft.

## Based on your Cloud Deployment Model...
...the exact responsibilities will differ.

This is natural:
* If you are using IaaS, then of course Microsoft will handle only the IS and you are responsible for everything else
* However, PaaS offerings mean that Microsoft will take on more than just the underlying infrastucture; it is responsible for the platform too.

---

In summary, however, Microsoft and you as the customer work together to create a secure and compliant cloud environment that meets the needs of your business.