# Azure Fundementals
## Cloud computing
### Datacenters in the past
- In the past datacenters were under-utilised as each server had a dedicated purpose where they could do much more

### Virtualisation
- To tackle the issue of underutilsed machines, Virtualisation was introduced.
    - Virtualisation allowed multiple virtual machines to run on a single virtual host
    - This allowed for more usage out of the hardware and cut down on:
        - Space
        - Cooling
        - Cost

### Virtualisation is not enough:
Even with virtualisation, there were still major problems needed to be solved:
- High up-Front cost
    - Powerfull virtual hosts needed
- Space needed to host servers
    - Space in datacenters are needed to host servers
- Electricity/utility costs
- Hardware maintenance still needed

### Cloud computing comes in

Cloud computing enables companies to consume a compute resource, such as a virtual machine, storage, or an application, as a utility -- just like electricity -- rather than having to build and maintain computing infrastructures in-house.

#### Shared Resources
- Cloud providers own datacenters and manages all their hardwarelike servers, networking and virtualisation
- No client has direct access to the hardware
- The resources are pulled together and shared to multiple clients

#### On demand self service
- Client chooses what service they want to use
- Each service has different price per user or per minute of utilisation
- Provision automated
- Delivered instantly

#### Cost
- Services are billed on-demand, by the minute or by the hour
- Allows organisations to create new resources when needed, and shut them off (and stop paying) when they are not needed anymore
- Organisations can be more dynamic and cost-effective
- Reduces up-front cost
    - Cost goes into Operating Expenses(OpEx)
    - Instead of Capital Expenditures(CapEx)

##### Basic understanding of CAPEX vs OPEX
Capital expenditures are depreciated over the useful life of the asset
- You cannot fully deduct the cost from the fisical year the asset was paid for in.

Operating Expenses are deducted in the same year they are made.

#### Reliability
Cloud provider takes care of high availability (HA) and disaster recovery (DR)
- HA: local failure such as a disk, power supply, etc
- DR: natural/human disaster like a fire, flood, earthquake, etc.
#### Fault Tolerance
- Very similar to HA but offers zero downtime

## Types of cloud computing services

Instead managing everything yourself using an on-premis system, you can use some cloud computing services

Here are some of the types of cloud computing services:

### Infrastructure as a service(IaaS)
```
This is where some components are managed by the vendor and you manage the rest
```
Most pupular cloud providers:
- Microsoft Azure
- Amazon Web services
- Google Compute Engine

Cloud computing services by Microsoft:
- Azure Compute(Virtual machines)
- Azure Storage

Scenarios
- Test and development
- Storage and backups
- High performance computing
- Big data analysis

### Platform as a Service(Paas)
```
This is where most components are managed by the vendor and you jsut handle the app and its database.
```

Most pupular cloud providers:
- Azure Logic Apps
- Heroku
- Amazon Elastic Beanstalk

Cloud computing services by Microsoft:
- Azure Logic
- Azure Functions
- Azure Web Jobs
- Azure Automation

Scenarios
- Analytics or business intelligence
- Development framework


### Software as a Sservice(SaaS)
```
This is where everything is handled by the vendor
```

Most pupular cloud providers:
- Office 365
- Google G Suite
- Dropbox

Cloud computing services by Microsoft:
- SharePoint
- Microsoft Teams
- Onedrive
- Power Platform

Scenarios
- Gain access to sophisticated applications
- Mobilize your workforce easily

## Cloud computing deployment models

### Public Cloud
Cloud service provided by a third-party provider, hardware can be shared amongst mul.tipleclients

### Private Cloud
Hardware is only used by a single company which often owns the hardware and datacenter

### Hybrid Cloud
Combination of public and private cloud with automation and orchestration between the two

### Community Cloud
Infrastructure is shared between several orgs from a specific community with common concerns(security complianc, jurisdiction, etc.)

### Private and Hybrid cloud

- Azure Stack allows you to run cloud services on-premises

- Azure Stack can be used for connected or disconnected scenarios

- Consistent tools, experiences, and app models

- Easy transfer workloads to Azure(Public cloud)

### Community cloud

- Azure Government is an Azure offering specific to government entities

- Can handle data that is subject to government regulations and requirements
    - FedRAMP/DOD/CJIS/etc