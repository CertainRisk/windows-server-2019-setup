# Windows Server 2019 Installation Guide

## Introduction

Welcome to the Windows Server 2019 Installation Guide repository! In this comprehensive guide, we document the step-by-step process of installing Windows Server 2019 and configuring two workstations. Whether you're an aspiring IT professional or a seasoned expert, this guide provides valuable insights into the intricacies of the installation process.

## Table of Contents

1. [Setting the Stage](#setting-the-stage)
2. [Installing Windows Server 2019 (DC01) and Initial Configuration](#installing-windows-server-2019-dc01-and-initial-configuration)
3. [Configuring Active Directory Domain Services (ADDSForest)](#configuring-active-directory-domain-services-addsforest)
4. [Promoting, Creating, and Configuring](#promoting-creating-and-configuring)
5. [Setting Up Workstations 01 and 02](#setting-up-workstations-01-and-02)
6. [Verification and Access](#verification-and-access)
7. [Conclusion](#conclusion)

## Setting the Stage

Before diving into the installation, understand the significance of a well-configured Windows Server environment. Explore preparations and initial steps that set the foundation for a seamless installation.

## Installing Windows Server 2019 (DC01) and Initial Configuration

The journey begins with a script that installs Windows Active Directory, domain services, and tools, generating a forest where the domain controller (DC01) will reside. Address the complexity of passwords, navigate DNS errors, and troubleshoot login issues.


## Configuring Active Directory Domain Services (ADDSForest)

Execute the Invoked Forest Deployed script to generate AD domain service tools and set up the initial domain controller. Dive into editing ADGenerator, creating a snapshot, and executing post-snapshot tasks, including renaming the domain controller.

![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/9a3327b1-0835-425d-bd4e-ec4e8ae67f1b)
![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/07c4505f-c38e-4354-9e51-24880af2bf8a)


## Promoting, Creating, and Configuring

With the domain controller in place, move on to promoting the mayor to domain and enterprise administrator, creating file shares, and working on user groups and ServicePrincipalName for SQL service.

![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/9cd80155-931c-4f0c-95a8-b1738494dd78)

![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/b31db5fe-dbe5-47dd-925f-30b6422bb016)


## Setting Up Workstations 01 and 02

Connect workstations to the domain by modifying network adapters, overcoming challenges with Windows 10 Home editions, and joining devices to the active local directory domain. Explore the process step by step, ensuring a smooth integration.

![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/d7734440-eb72-43c4-b3f8-cb0d2a353af7)
![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/675dd94d-4410-4736-a5a6-c220e551e27f)


## Verification and Access

Once Workstations 01 and 02 are connected, return to DC01 to verify their successful addition using Active Directory Users and Computers. Navigate to the setup shared folder, demonstrating the seamless connection between the domain controller and workstations.

![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/6b6ff417-f64d-428c-b1aa-a4d8d4aeec1d)

![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/43e2365a-7672-49ec-aa50-8ff183d303c8)

![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/39ac5ebf-1506-4f57-84b6-52f003eaa03f)

![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/877abf3a-c539-499c-acfb-e3f0a4aff2a0)

![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/7fef8ff3-77cf-4524-9c96-fc72a1ff92f4)

![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/4f4649b3-38b9-4d6d-b95c-9347117eb623)

![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/aab0da8f-40ae-497c-a563-815525190d15)

![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/4c0d6371-0cbe-4708-a625-d5dd01c7e85f)

![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/42da6995-92f1-4213-a0b6-d7fa2522ed82)

![image](https://github.com/CertainRisk/windows-server-2019-setup/assets/141761181/da85699b-4a8a-457e-9352-d82f4b4979f2)




## Conclusion

The installation journey of Windows Server 2019 is a multifaceted process that demands attention to detail and creative problem-solving. As we've explored each step, from installation scripts to workstation integration, I hope this guide provides valuable insights for both aspiring IT professionals and seasoned experts. In the dynamic world of IT, continuous learning and adaptability are the keys to success.

