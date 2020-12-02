# Table of Contents

- [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Automation Host Prerequisites](#automation-host-prerequisites)
  - [PowerVS Prerequisites](#powervs-prerequisites)
  - [OCP Install](#ocp-install)
  - [Contributing](#contributing)


## Introduction

The `ocp4-upi-powervs` [project](https://github.com/ocp-power-automation/ocp4-upi-powervs) provides Terraform based automation code to help the deployment of OpenShift Container Platform (OCP) 4.x on [IBM® Power Systems™ Virtual Server on IBM Cloud](https://www.ibm.com/cloud/power-virtual-server).

This project leverages the helpernode [ansible playbook](https://github.com/RedHatOfficial/ocp4-helpernode) internally for OCP deployment on IBM Power Systems Virtual Servers (PowerVS).

!!! Note
	For bugs/enhancement requests etc. please open a GitHub [issue](https://github.com/ocp-power-automation/ocp4-upi-powervs/issues)

For general PowerVS usage instructions please refer to the following links:

- [Power Systems Virtual Servers(IBM Cloud Docs)](https://cloud.ibm.com/docs/power-iaas?topic=power-iaas-getting-started)
- [IBM Power Systems in the Multicloud(Youtube video)](https://www.youtube.com/watch?v=RywSfXT_LLs)
- [PowerVS (Youtube video)](https://www.youtube.com/playlist?list=PLVrJaTKVPbKM_9HU8fm4QsklgzLGUwFpv)

!!! Warning
	**This branch must be used with OCP 4.6.x versions only.**


## Automation Host Prerequisites

The automation needs to run from a system with internet access. This could be your laptop or a VM with public internet connectivity. This automation code have been tested on the following Operating Systems:
- Mac OSX (Darwin)
- Linux (x86_64)
- Windows 10

Follow the [guide](docs/automation_host_prereqs.md) to complete the prerequisites.

## PowerVS Prerequisites

Follow the [guide](docs/ocp_prereqs_powervs.md) to complete the PowerVS prerequisites.

## OCP Install

Follow the [quickstart](docs/quickstart.md) guide for OCP installation on PowerVS.


## Contributing
Please see the [contributing doc](CONTRIBUTING.md) for more details.
PRs are most welcome !!
