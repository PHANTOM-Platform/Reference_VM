# Reference_VM
This repository provides a links to the Virtual Machine in the PHANTOM Integrated Reference System

You can get the Lite version of the Virtual Machine with the PHANTOM Integrated Reference System [**here**](https://unparallel-my.sharepoint.com/:u:/g/personal/marcio_mateus_unparallel_pt/EbVeVRBEYIlPlhpVwuPkQzIBUvjivvWtxV1gah9T5mHCNg?e=QxQxEr)

## What is included
This version of PHANTOM Integrated Reference System includes the folowing PHANTOM components:
* [Parallelisation Toolset (PT) - **lite version**](https://github.com/PHANTOM-Platform/Parallelisation-Toolset)
* [Generic Multi-Objective Mapper (MOM) - **lite version**](https://github.com/PHANTOM-Platform/GenericMOM)
* [Offline Multi-Objective Mapper (offline-MOM)](https://github.com/PHANTOM-Platform/OfflineMOM)
* [Deployment Manager (DM)](https://github.com/PHANTOM-Platform/Deployment-Manager)
* [Repository](https://github.com/PHANTOM-Platform/Repository) + [Security Framework](https://github.com/PHANTOM-Platform/Monitoring)
* [Application Manager](https://github.com/PHANTOM-Platform/Application-Manager)
* [Execution Manager](https://github.com/PHANTOM-Platform/Execution-Manager)
* [Monitoring Server (and Client)](https://github.com/PHANTOM-Platform/Monitoring)
* [Model-Based Testing](https://github.com/PHANTOM-Platform/MBT-Test-Execution)
* [User-Scripts](https://github.com/PHANTOM-Platform/PHANTOM-User-Scripts) + [PHANTOM-IP-Core-Marketplace](https://github.com/PHANTOM-Platform/PHANTOM-IP-Core-Marketplace) integration

### Lite vs Full
This Virtual Machine includes a lite version of PT and MOM. These versions have the following limitations:

#### Parallelisation Toolset (PT)
The simplified version of the Parallelization Toolset supports all the basic functionalities that are expected, namely:
* The support of the PHANTOM Programming Model.
*	The interaction with all PHANTOM components such as the Repository, the Appli-cation and Execution Managers, the MOM, and the Deployment Manager.
*	The support of library selection according to the selected Deployment Plan.

The features that are only supported by the full version are the following:
*	Automatic generation of parallelized components

#### Generic Multi-Objective Mapper (MOM)
The simplified version of the Multi-Objective Mapper supports all the basic functionalities that are expected, namely:
*	The generation of deployment plans of parallel applications on the CPU-based hardware platforms.
*	The support of the PHANTOM Programming Model.
*	The interaction with all PHANTOM components such as the Repository, the PT, and the Monitoring framework.
*	The support of requirements such as execution time, energy consumption, memory utilization and reliability.  

The features that are only supported by the full version are the following:
*	Mapping of components in GPUs and FPGAs.
*	Multiple MOM iterations to provide improved performance deployment plans.
*	Multiple MOM mutations to support extended design space exploration from the generated deployment plans.

### Demo application
Besides to these tools, it is also included in this Virtual Machine an demo application - `Tutorial`

## What is not included
In this virtual machine is not included the PHANTOM components related with FPGAs:
* [PHANTOM-FPGA-Linux](https://github.com/PHANTOM-Platform/PHANTOM-FPGA-Linux)
* [IP-Core-Generator](https://github.com/PHANTOM-Platform/IP-Core-Generator)



