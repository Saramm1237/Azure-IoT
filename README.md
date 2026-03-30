# ☁️ Azure IoT — Internet of Things on the Cloud

> **Connecting the physical world to the digital — securely, reliably, and at scale.**

---

## 🌐 What is IoT?

**Internet of Things (IoT)** refers to hardware devices connected to the internet that can collect, send, and receive data. The key pillars of any solid IoT solution are:

- 🔒 **Secure** — End-to-end protection for devices and data
- ✅ **Reliable** — Stable connectivity and fault-tolerant architecture
- 🔄 **Bidirectional** — Devices can both send telemetry *and* receive commands
- 📊 **Monitored** — Real-time visibility into device health and data streams

---

## 📘 About This Course

This course is a comprehensive, hands-on journey through IoT development and architecture on **Microsoft Azure**.

| Feature | Detail |
|---|---|
| 🧩 **Coverage** | All major IoT aspects in the Azure ecosystem |
| 🛠️ **Approach** | Extremely practical and hands-on oriented |
| 👨‍💼 **Foundation** | Built on the professor's experience as an Azure Architect & Consultant |

## Introduction to Cloud 

---

### 🕰️ Before the Cloud

If you needed a server, you had to:

- 💸 Buy it, install it, maintain it, and eventually replace it
- 👨‍💻 Have a dedicated IT team
- Handle everything yourself: **Networking, User Management, Storage, and more**

---

### 🌩️ What is the Cloud?

The cloud provides **Compute, Networking, Storage**, and many other services —
all managed by someone else.

#### Cloud Providers
Companies that:
- Build and operate **massive data centers** worldwide
- Handle servers, networking, cooling, and electricity
- Design and expose services publicly over the internet
- Compete fiercely by offering a growing catalog of services:
  `AI` · `IoT` · `Kubernetes` · `Databases` · `Analytics` · and much more

---

### ✅ In the Cloud Era

If you need a server today, you can:

- 🚀 Create it in **minutes**
- 💰 **Pay only for what you use**
- ⏸️ Shut it down when it's no longer needed
- 🔧 Have it automatically **maintained, patched, secured, and monitored**

---

### 📋 5 Characteristics of Cloud Computing

> As defined by NIST — the foundation of every cloud provider.

| # | Characteristic | Description |
|---|---|---|
| 1 | **On-Demand Self Service** | Resources are provisioned with a click, 24/7, with no human interaction required |
| 2 | **Broad Network Access** | Accessible from anywhere via the network — no physical access ever needed |
| 3 | **Resource Pooling** | Physical infrastructure is shared among customers; the cloud allocates resources dynamically |
| 4 | **Rapid Elasticity** | Scale up or down automatically — no need to overprovision for peak scenarios |
| 5 | **Measured Service** | Pay only for what you actually use, measured at high resolution (e.g., per second) |

---

### 🧱 Types of Cloud Services

---

#### 🔩 IaaS — Infrastructure as a Service

The cloud provides the **underlying infrastructure**:
`Compute` · `Networking` · `Storage`

The client is responsible for everything built on top of it.

> **Most common example: Virtual Machines**
> The cloud provides the host machine, networking and disks.
> The client creates the VM, installs software, patches and maintains it.

---

#### 🧩 PaaS — Platform as a Service

The cloud provides a **complete platform** for running apps, including:
`Compute` · `Networking` · `Storage` · `Runtime` · `Scaling` · `Security` · `Patching`

The client only needs to **bring the code**.

> **Most common example: Web Apps**
> The client uploads the code — and it just runs.
> No access to the underlying virtual machines is needed.

---

#### 📦 SaaS — Software as a Service

A **fully managed software** running in the cloud.
No installation required on the client's machine.
The provider handles updates, patches, redundancy and scalability.

---

#### ⚡ Additional Service Types

| Acronym | Full Name |
|---|---|
| FaaS | Functions as a Service |
| DBaaS | Database as a Service |
| DaaS | Desktop as a Service |
| IoTaaS | IoT as a Service |
| AIaaS | AI as a Service |

---

## 🌍 Types of Clouds

| Type | Access | Managed By | Key Trait |
|---|---|---|---|
| **Public Cloud** | Internet (anyone) | Large cloud companies | No access to underlying infra |
| **Private Cloud** | Internal network only | Organization's IT team | Subset of public cloud capabilities |
| **Hybrid Cloud** | Both | Usually the public cloud | Workloads split between on-prem and cloud |

> **Hybrid use case example:** Sensitive data stays on-premises; public-facing data lives in the public cloud.

---

## 🏢 Cloud Providers

Companies that build datacenters and deliver public cloud services — offering IaaS, PaaS, SaaS, and specialized services.

---

## 🔷 Microsoft Azure

| Detail | Info |
|---|---|
| 📅 Announced | October 2008 |
| 🚀 Released | February 2010 |
| 🥈 Market position | 2nd largest public cloud |
| 🎯 Original focus | PaaS (to counter AWS's IaaS focus) |
| 📦 Today | Largest variety of cloud services available |

---

## 🗺️ Azure Global Infrastructure

### 📍 Regions
- A **Region** is the geographic location of an Azure datacenter
- Azure has **~60 regions** — more than any other cloud provider
- Almost every resource must be assigned to a region when created

### 🏗️ Availability Zones
- Some regions contain **multiple physical datacenters**
- Each datacenter = one **Zone**
- Zones provide **high availability** — if one datacenter fails, others take over

### 🔁 Paired Regions
- Some regions have a designated **pair region** for disaster recovery
- If a full region goes down, its pair can take over
- Pairs are **defined by Azure** and cannot be changed

---

## ⚙️ Azure Services

> Everything you can do in the cloud is called a **Cloud Service**.

Examples include:
- Creating and managing **Virtual Machines**
- Building and scaling **Databases**
- Setting up **Virtual Networks**
- Using **AI algorithms**
- Centralized **User Management**
- And hundreds more...
