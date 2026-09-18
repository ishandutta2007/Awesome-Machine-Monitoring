# Awesome-Machine-Monitoring

## Top Machine Monitoring Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Industrial Machine Monitoring, Predictive Maintenance, OEE, Condition Monitoring, IIoT Analytics & Manufacturing Intelligence*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Machine Monitoring**. These systems collect real-time data from CNC machines, rotating equipment, and industrial assets, calculate OEE, detect anomalies, predict failures, and help manufacturers reduce downtime and optimize production.



**Examples** include MachineMetrics, SymphonyAI Industrial, Augury, Senseye, Litmus, Braincube, Seeq, HighByte, Prediktor, and Infinite Uptime (the category leaders).



**Open-source emphasis**: Full commercial machine-health platforms with proprietary sensors, physics-informed AI, and multi-site OEE analytics remain dominant. Open-source activity centers on IIoT data pipelines, edge analytics, predictive-maintenance research code, and composable stacks (Node-RED, InfluxDB, Grafana, MQTT, OPC-UA). This section lists every significant relevant project and building block found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[MachineMetrics](https://www.machinemetrics.com/)**  

  Leading CNC and discrete manufacturing machine monitoring platform focused on real-time OEE, utilization, cycle-time analytics, and shop-floor visibility with broad protocol support (MTConnect, Fanuc, OPC-UA, etc.).



- **[Augury](https://www.augury.com/)**  

  AI-powered machine health platform using vibration, ultrasonic, and other high-fidelity signals to deliver prescriptive diagnostics and predictive maintenance for critical rotating assets.



- **[Senseye (Siemens)](https://www.senseye.io/)**  

  Predictive maintenance and condition-monitoring platform, often integrated with Siemens industrial ecosystems, focused on automated health insights and remaining useful life.



- **[Litmus](https://litmus.io/)**  

  Industrial edge and data platform that connects machines, normalizes OT data, and enables real-time analytics, OEE, and AI/ML use cases across multi-site manufacturing environments.



- **[SymphonyAI Industrial, Braincube, Seeq](https://www.symphonyai.com/)**  

  Platforms providing industrial AI, process manufacturing analytics, advanced time-series analysis, and manufacturing intelligence for continuous and discrete operations.



- **[HighByte, Prediktor, Infinite Uptime](https://www.highbyte.com/)**  

  Solutions covering industrial dataops / contextualization, historian and analytics capabilities, and specialized machine-health or uptime monitoring offerings.



- **[Other machine monitoring & PdM platforms](https://www.machinemetrics.com/)**  

  Additional commercial tools for vibration analysis, energy monitoring, tool-life tracking, and multi-protocol industrial connectivity.



## Open-Source GitHub Projects



- **[EsoCore](https://www.esocore.com/)**  

  Open-source industrial IoT platform aimed at equipment monitoring and predictive maintenance. Combines edge computing, modular sensors (vibration, temperature, acoustic), and analytics for manufacturing environments under an Apache 2.0 license.



- **[Node-RED + InfluxDB + Grafana IIoT stacks](https://github.com/node-red/node-red)**  

  Widely used open-source combination for industrial data acquisition, flow-based processing, time-series storage, and real-time dashboards. Frequently deployed for machine monitoring and basic predictive workflows.



- **[Predictive Maintenance research & end-to-end projects](https://github.com/search?q=predictive+maintenance+OR+machine+health+OR+RUL+industrial)**  

  Numerous open repositories implementing anomaly detection, remaining useful life (RUL) estimation, digital twins, and vibration analysis on public industrial datasets (e.g., PHM, NASA turbofan, CNC).



- **[MQTT / OPC-UA / Modbus open tooling](https://github.com/search?q=OPC-UA+OR+MQTT+industrial+OR+Modbus+open+source)**  

  Open brokers, clients, and protocol stacks that form the connectivity backbone of most self-hosted machine monitoring systems.



- **[ThingsBoard and open IoT platforms](https://github.com/thingsboard/thingsboard)**  

  Open-source IoT platforms that support device management, telemetry ingestion, rule engines, and dashboards—commonly adapted for industrial asset monitoring.



- **[Edge analytics & anomaly detection notebooks](https://github.com/search?q=industrial+anomaly+detection+OR+vibration+analysis+open+source)**  

  Python/ML projects focused on edge or cloud-based anomaly detection, feature extraction from vibration/current signals, and failure prognosis.



- **[CMMS / maintenance open tools with monitoring hooks](https://github.com/search?q=CMMS+OR+maintenance+management+open+source)**  

  Open maintenance systems that can be integrated with sensor data pipelines for condition-based work-order generation.



- **[Other IIoT & SCADA modernization projects](https://github.com/search?q=IIoT+OR+industrial+monitoring+OR+SCADA+open+source)**  

  Community efforts combining Arduino/Raspberry Pi edge devices, MQTT, historians, and visualization for factory-floor monitoring.



### Additional Strong Open-Source Options



- **Time-series databases**: InfluxDB, TimescaleDB, QuestDB for high-frequency machine telemetry.

- **Visualization**: Grafana and specialized industrial dashboard templates for OEE and asset health.

- **Protocol gateways**: Open OPC-UA servers/clients, MTConnect agents, and Modbus-to-MQTT bridges.

- **MLOps for PdM**: Open pipelines for training, versioning, and deploying anomaly or RUL models.

- **Digital twin frameworks**: Research and lightweight open digital-twin implementations for specific asset classes.

- Composable stacks: Edge (MQTT/OPC-UA) → Node-RED or custom collectors → InfluxDB/Timescale → Grafana + optional ML services.



**Frameworks for building custom systems**:  

There is no single open-source product that fully replicates the depth of MachineMetrics (CNC OEE) or Augury (physics-informed machine health).  

Practical building blocks include **EsoCore** (where available), **Node-RED + InfluxDB + Grafana**, **ThingsBoard**, open protocol stacks, and the large body of predictive-maintenance research code.  

These can be assembled into capable monitoring and early-warning systems.  

Commercial platforms (MachineMetrics, Augury, Senseye, Litmus, SymphonyAI, Braincube, Seeq, etc.) provide hardened connectors, domain-specific AI models, multi-site governance, support, and faster time-to-value.  

Many manufacturers start with open IIoT stacks for visibility and later adopt specialized commercial PdM or OEE platforms for critical assets or enterprise roll-outs.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Machine monitoring and predictive maintenance systems influence production decisions and safety. Incorrect models or missed alerts can have operational and safety consequences. Validate models against real asset behavior and maintain human oversight.

- Open-source IIoT and analytics stacks offer flexibility and no per-machine licensing but require expertise in OT networking, data quality, model maintenance, and cybersecurity. Evaluate total cost of ownership, integration effort, and reliability requirements carefully.



---



**Made for manufacturing engineers, reliability teams, OT/IT architects, and industrial data scientists.**  

Let's expand open, interoperable tools for machine health and production visibility while recognizing the specialized value that mature commercial monitoring and predictive-maintenance platforms deliver.
