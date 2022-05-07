<h1 align="center">
  Cabestan
</h1>

---

[![Join the chat at https://gitter.im/hubblo-org/cabestan](https://badges.gitter.im/hubblo-org/cabestan.svg)](https://gitter.im/hubblo-org/cabestan?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

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
* **Monitoring :** Identify assets config and usage throught monitoring services


### 🔬 Scanners

| Name                       | Source         | issue |
|----------------------------|----------------|-------|
| nmap                       | Network        | https://github.com/hubblo-org/cabestan/issues/1 |
| snmp                       | Network        | https://github.com/hubblo-org/cabestan/issues/7 |
| scaphandre                 | Device         |       |
| boagent                    | Device         |       |
| netbox                     | Assets manager | https://github.com/hubblo-org/cabestan/issues/8 |
| Ralph                      | Assets manager |       |
| CMDBuild                   | Assets manager |       |
| GLPI                       | Assets manager |       |
| iTop                       | Assets manager |       |
| ServiceNow                 | Assets manager |       |
| Observium                  | Monitoring     |       |
| Librenms                   | Monitoring     |       |
| Nagios                     | Monitoring     |       |
| M onit                     | Monitoring     |       |
| Munin                      | Monitoring     |       |
| Icing                      | Monitoring     |       |
| Zabbix                     | Monitoring     |       |
| Centreon                   | Monitoring     |       |
| Centreon                   | Monitoring     |       |
| Microsoft Intune           | MDM            |       |
| CloudQuerry                | PaaS-IaaS-FaaS |  https://github.com/hubblo-org/cabestan/issues/2   |
| Google Workplace usage API | SaaS           |  https://github.com/hubblo-org/cabestan/issues/3   |
| Microsoft Graph API        | SaaS           |  https://github.com/hubblo-org/cabestan/issues/4   |

### 📤 Exporters

| Name               | Target type         | issue |
|--------------------|----------------|-------|
| JSON-LD            | LCA softaware  | https://github.com/hubblo-org/cabestan/issues/6 |
| netbox             | CMDB           | https://github.com/hubblo-org/cabestan/issues/5      |
| SQL                | Database       |       |

## 📅 Roadmap

## ⚖️  Footprint
