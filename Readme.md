# Learning Azure Cloud 

## Cloud Computing
>Cloud computing is the on-demand availability of computer system resources, especially data storage and computing power. 

### Benefits
 - Fast access to resources
 - Pay for what we use
 - No capex/opex costs

## Deployment Models
- Private cloud
- Community Cloud
- Public Cloud
- Hybrid Cloud
>![enter image description here](images/pvtCloudPublic.png)

### Virtualization
> Virtualization refers to the act of creating a virtual (rather than actual) version of something, including virtual computer hardware platforms, storage devices, and computer network resources.
>
> Virtualization is the logical division of physical computing resources
>
> ![enter image description here](images/cloud-os.png)

### Hypervisor
> A hypervisor or virtual machine monitor (VMM) is computer software, firmware or hardware that creates and runs virtual machines. 
>
> ![enter image description here](images/hypervisor-2.jpg)

>### Popular hypervisors available in the current market
> - ESXi -*VMWare*
> - Hyper-V - *Microsoft*
> - XenServer - *Citrix*

### Containers
>A container is operating system level virtualization, where the OS kernel provides isolated user spaces to run specific application 
>
>Its a standard unit of software that packages up code and all its dependencies 
>![enter image description here](images/Container.png)

>### Popular container technology in the current market
> - Docker - *Docker Inc*

## Service Models
- IaaS  - *Infrastructure as service*
- PaaS - *platform as service*
- SaaS - *software as service*

>![enter image description here](images/CloudAzureTypes.png)

>[Albert Barron's pizaa as service example](https://www.linkedin.com/pulse/20140730172610-9679881-pizza-as-a-service)

### IaaS  - *Infrastructure as service*
> Giving provision for the consumer to access storage, networks, and other fundamental computing resources 

> Consumer can able to deploy and run arbitrary software, which can include operating systems and applications. The consumer does not manage or control the underlying cloud infrastructure but has control over operating systems, storage, and deployed applications

> Infrastructure as a service (IaaS) is a form of cloud computing that provides virtualized computing resources over the internet

> Azure offerings Virtual Machines, Containers

#### Virtual Machines 
- Linux or Windows 
- Prebuilt images (pre installed tools like visual studio , Sql Server)
- Varying sizes (CPU Size)
- Premium Storage like SSD
- Consumers need to take care of OS, and other activities like Sofware installation, Patches update
  Networking, load balancing, fail over etc.
  
#### Containers
- Chain images together
- light weight 
- Sharing single os and physical server resources
- resource utilization is more when compare to VM

### Paas  - *Platform as service*
> platform-based service is a category of cloud computing services that provides a platform allowing customers to develop, run, and manage applications without the complexity of building and maintaining the infrastructure typically associated with developing and launching an app

### Some of the Paas services in azure
- Web Apps
- Mobile Apps
- Logic Apps
- Azure Functions
- Azure Web Jobs
- Azure Storage (Blob/Table/Queue/File)

### SaaS  - *Software as service*
SaaS is the highest abstraction level and allows you to just use the application, you don’t even have to build it. You just configure it. No need to worry about the OS or even scaling the app. This allows you to work on business value, but offers you little control over your application.

Example:  Azure IoT Suite & Office 365




