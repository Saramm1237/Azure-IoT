## 👀 First Look at Azure

> **⚠️ Already familiar with Azure?**
> This section introduces the Azure Portal and covers how to create and remove resources.
> If you're comfortable with that already, feel free to **skip to the next section**.
> That said, a quick refresh never hurts. 😉

---
## 🖥️ Azure Portal — First Look

The Azure Portal (portal.azure.com) is the main web interface to manage 
all Azure resources. It provides a visual, point-and-click experience for 
creating, configuring, and monitoring cloud services.

### 📌 Key Elements of the Portal

| Element | Description |
|---|---|
| **+ Create a resource** | Entry point to provision any Azure service |
| **Home** | Dashboard with quick access and recommendations |
| **All resources** | Complete list of everything deployed in your subscription |
| **Resource groups** | Logical containers to organize related resources |
| **Monitor** | Centralized observability — metrics, logs, alerts |
| **Microsoft Entra ID** | Identity and access management (users, roles, permissions) |

> 📸 *Screenshot: Azure Portal Home view*
> ![Azure Portal Home](../assets/portal-home1.png)

## 🆓 Azure Free Account

Azure offers a **free trial** with $200 USD in credits (valid for 30 days),
giving full access to all Azure services to explore and build.

> 📸 *Screenshot: Azure Portal Home view*
> ![Azure Portal Home](../assets/portal-home2.png)

### Quick Actions available from the start

| Action | Description |
|---|---|
| **Start with a template** | Deploy pre-made solutions in minutes |
| **Create a resource** | Manually provision any Azure service |
| **Build an AI agent** | Create AI-powered apps using Azure AI models |
| **Import code from GitHub** | Connect a repo and deploy directly to Azure |

> 💡 **Tip:** For this course, **"Create a resource"** will be the most used 
> option — it's where you provision IoT Hub and all related services.

## 📦 Resource Groups

A **Resource Group** is a logical container that holds related Azure resources 
for a solution. It helps you organize, manage, and delete resources together.

> Think of it as a **project folder** in the cloud — everything related to 
> one solution lives inside the same group.

### Key concepts

| Field | Description |
|---|---|
| **Subscription** | The billing account associated with the resources |
| **Resource group name** | A unique identifier for the container |
| **Region** | Where the metadata of the group is stored |

> ⚠️ The region of the resource group doesn't force resources inside it 
> to be in the same region — each resource can be deployed independently.

---

### 🥇 First resource created: `myresourcegroup`

| Setting | Value |
|---|---|
| Subscription | Azure subscription 1 |
| Region | (South America) Brazil South |

> 💡 **Why Brazil South?** It's the closest Azure region to Colombia, 
> which means lower latency for local projects.

> ![Azure Portal Home](../assets/first-resource-group.png)

---

### ✅ Best practices for naming resource groups

- Use descriptive names: `rg-iot-livestock-dev`, `rg-iot-course-labs`
- Include the environment: `-dev`, `-prod`, `-test`
- One resource group per lab or project — makes cleanup easy

> 🗑️ **Tip:** When you finish a lab, deleting the resource group 
> deletes **everything inside it** in one click — saving credits.