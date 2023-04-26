# Part 7: Geographies, Regions & Availability Zones

## Objectives:
* Describe Data Center
* Describe Regions and Region Pairs
* Describe Geographies
* Describe Availability Zones
* Describe benefits and usage of core architectural components

---

## Data Center
If you purchase services in Azure (SQL, Web hosting, VM) - all of these run on **physical infrastructure** underneath, on some sort of a server. A facility hosting these servers is a data center.

Hence:
> A data centre is a physical facility hosting a group of networked servers, each having their own power, cooling, and networking infrastructure

## Regions and Region Pairs
Data centres are building blocks for the Microsoft Azure infrastructure. As such, Microsoft will often group various data centres together. These are known as **regions**, with many across the globe of different sizes.
> A region is a group of data centres, distributed globally (e.g. one in East US, West US)

Choosing which region to use is important - the closer the server is to your clients, the lower the latency (delay in getting data to/from them). Some things to consider:
* Regions are just geographical areas on the planet
* However, it is the location for your services
* These regions need to be connected with low latency (<2ms) networking

Important things to remember:
* Some services not available in all regions.
* Some services are global services - no specific region/location assigned e.g. traffic managers for DNS routing
* Azure is currently globally available with 50+ regions
* Some regions are special:
  * There are government regions (e.g. for US DoD central)
  * There are also partnered regions (e.g. China East, China North)

## Availability Zones
Remembering our data centre-region infrastructure, these are interconnected with super fast Internet. However, the stuff you can do with these regions differs.
> An availability zone is a grouping of physically separate facilities which is designed to protect clients from data centre failures. I.e: if one zone goes down, others will continue working (because they're physically separate!)

You can have either:
1. Zonal services: VMs, disks, &c.
2. Zone-redundant services: SQL, storage, &c.