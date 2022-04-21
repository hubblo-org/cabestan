<h1 align="center">
  Cabestan
</h1>

---
## 🎯 Objective

Cabestan helps you inventories your IT assets from different sources. It has been designed to be part of an approach to measure, monitor and reduce the environmental impacts of digital systems and services.

## 🏗️ Architecture

Cabestan is a modular tool based on several gathering and exporting strategy

<img src="https://github.com/hubblo-org/cabestan/blob/main/CABESTAN - MACRO VUE.jpg">

### 🏷️ Sources

Sources are places where assets can be gathered

* **Network :** Identify assets throught a network
* **Device :** Identify assets config and usage inside a device
* **Assest managment :** Identify assets config and usage throught existing assets managment system (like CMDB)
* **SaaS-PaaS-IaaS :** Identify SaaS-PaaS-IaaS assets config and usage throught API providers
* **Flows and stock managment :** Identify assets config and usage as a flow or a stock throught non-IT tools

### 🔬 Scanners

| Name                       | Source         | issue |
|----------------------------|----------------|-------|
| nmap                       | Network        | https://github.com/hubblo-org/cabestan/issues/1 |
| scaphandre                 | Device         |       |
| boagent                    | Device         |       |
| netbox                     | Assets manager |       |
| Ralph                      | Assets manager |       |
| CMDBuild                   | Assets manager |       |
| GLPI                       | Assets manager |       |
| iTop                       | Assets manager |       |
| ServiceNow                 | Assets manager |       |
| CloudQuerry                | PaaS-IaaS-FaaS |  https://github.com/hubblo-org/cabestan/issues/2   |
| Google Workplace usage API | SaaS           |  https://github.com/hubblo-org/cabestan/issues/3   |
| Microsoft Graph API        | SaaS           |  https://github.com/hubblo-org/cabestan/issues/4     |

### 📤 Exporters

* **CMDB exporter :** Use CMD API to export your assets
* **Database exporter :** Write your assets in a dedicated database 

## 📅 Roadmap

## ⚖️  Footprint
