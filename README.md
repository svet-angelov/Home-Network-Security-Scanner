# Home Network Security Scanner

## Overview
This project is a Python and Flask-based web application designed to help non-technical users discover and assess the security of Internet of Things (IoT) devices on their home network. The proliferation of IoT devices has fundamentally reshaped the modern home, but it has also introduced significant, often invisible, security risks. This tool aims to bridge that knowledge gap by providing clear, simple, and actionable security insights.

## Problem Statement
Many homeowners are unaware of the risks posed by insecure IoT devices, often using weak default passwords or neglecting firmware updates. While professional scanning tools exist, they are overly complex for the average user. This project addresses this challenge by creating an intuitive tool that empowers everyday users to proactively improve their smart home's cybersecurity posture.

## Key Features (Design)
The application is designed around a modular architecture with the following core features:
* **Automated Device Discovery:** Uses Nmap to accurately scan the local network and identify all connected devices.
* **Multi-Factor Fingerprinting:** Employs a combination of MAC address vendor lookups and service banner analysis to intelligently distinguish IoT devices from regular computers or phones.
* **Vulnerability Assessment:** Integrates with the official NIST National Vulnerability Database (NVD) via its API to retrieve known Common Vulnerabilities and Exposures (CVEs) for discovered devices.
* **User-Friendly Web Dashboard:** Presents complex scan data in a simple, intuitive interface, featuring a quantitative 'Home Security Score' to simplify risk communication.

## System Architecture

![System Architecture Diagram](architecture.png)

## Technologies Used
* **Backend:** Python, Flask
* **Scanning Engine:** python-nmap
* **External Data:** NIST NVD API for CVE data
* **Frontend:** HTML, CSS, JavaScript

## Project Status
This project was initially conceived and documented as part of my final year BSc (Honours) Cyber Security project at The Open University. The comprehensive research, system architecture, and project management plan are complete.

I am **currently in the process of developing this design into a fully functional, open-source application.** The goal is to build a working MVP (Minimum Viable Product) that demonstrates the core features outlined above.

## Next Steps & Future Development
* [ ] Implement the core Nmap scanning script.
* [ ] Develop the basic Flask web interface and routing.
* [ ] Display initial scan results on the webpage.
* [ ] Integrate the NIST NVD API call.
