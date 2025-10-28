# Sentinel SIEM Implementation in Azure

This project demonstrates how to deploy a **cloud-based Security Information and Event Management (SIEM)** solution using **Microsoft Sentinel** on **Microsoft Azure**. It provides real-time threat detection, automated incident response, and centralized visibility across cloud resources through analytics rules, watchlists, and user behavior analytics.

---

## Table of Contents

* [Sentinel SIEM Implementation in Azure](#sentinel-siem-implementation-in-azure)
  * [Table of Contents](#table-of-contents)
  * [Overview](#overview)
  * [Tools & Environment](#tools--environment)
  * [Medium Article](#medium-article)

---

## Overview

In today’s cloud-driven world, organizations need real-time visibility into security events to detect threats and respond quickly. This project implements a complete **SIEM solution in Microsoft Azure** using **Microsoft Sentinel**, a cloud-native SIEM and SOAR platform. The deployment was performed using the **Microsoft Sentinel All-in-One GitHub repository**, which streamlines setup while allowing hands-on configuration for deeper understanding.

This project focuses on:

* Deploying and configuring Microsoft Sentinel in Azure
* Enabling data connectors, analytics rules, and diagnostic logging
* Creating custom KQL detection logic for suspicious Tor-based sign-ins
* Simulating an attacker scenario to generate incidents
* Investigating, classifying, and remediating detected threats

---

## Tools & Environment

* **[Microsoft Azure](https://azure.microsoft.com)** — Cloud platform hosting the SIEM and connected resources.
* **Microsoft Sentinel** — Cloud-native SIEM and SOAR solution for security monitoring and response.
* **Kusto Query Language (KQL)** — Query language used to create custom detection and analytics rules.
* **Azure Active Directory** — Used for identity management and UEBA (User Entity Behavior Analytics).
* **Windows / Linux** — Environments used for deployment, configuration, and simulation of attack scenarios.

---

## Medium Article

A complete step-by-step deployment and incident investigation guide for this project is available here:
https://medium.com/@wazeen.tech/building-a-siem-in-azure-cloud-using-microsoft-sentinel-84541c3650c3
