Tools for Recon on IoT Devices, IPs, Domains, and Subdomains
This repository contains a list of four open-source tools used for reconnaissance and information gathering on exposed IoT devices, IP addresses, domains, and subdomains. These tools assist in the early stages of cybersecurity assessments by identifying potential attack surfaces.

Overview
Reconnaissance is a critical phase in penetration testing, red teaming, and vulnerability assessments. It provides insights into exposed infrastructure, misconfigurations, and assets that could be leveraged during an attack. The tools listed here streamline the process of collecting data from public and semi-public sources.

1. OWASP Amass
OWASP Amass is a comprehensive tool for DNS enumeration and attack surface mapping. It supports passive, active, and brute-force methods to identify subdomains and associated IP addresses.

Key Features:

Subdomain enumeration (passive, active, brute)

ASN and IP range discovery

Supports integration with other tools

Produces graph visualizations for mapping infrastructure

Installation:


<pre>$ go install -v github.com/owasp-amass/amass/v4/...@latest  </pre>
Repository:
https://github.com/owasp-amass/amass

2. Automater
Automater is an OSINT tool designed to automate the collection of intelligence on IPs, URLs, and domains. It queries multiple public data sources and aggregates the findings into a report.

Key Features:

Queries VirusTotal, Robtex, Shodan, and others

Supports batch processing of targets

Useful for digital forensics and threat analysis

Installation:

<pre>$ git clone https://github.com/1aN0rmus/TekDefense-Automater.git  </pre>
Repository:
https://github.com/1aN0rmus/TekDefense-Automater

3. Raccoon
Raccoon is a reconnaissance tool that performs subdomain enumeration, port scanning, and directory brute-forcing. It is lightweight and designed for quick recon workflows.

Key Features:

Performs DNS lookups and scans

Detects open ports and services

Brute-forces directories using wordlists

Installation:


<pre> $ git clone https://github.com/evyatarmeged/Raccoon </pre>
Repository:
https://github.com/evyatarmeged/Raccoon

4. Photon
Photon is a web crawler focused on collecting useful data from websites. It extracts URLs, emails, files, JavaScript endpoints, and form elements.

Key Features:

Recursive crawling with customizable depth

Extracts sensitive artifacts from HTML and JavaScript

Supports multiple export formats for integration

Installation:

<pre>$ git clone https://github.com/s0md3v/Photon  </pre>
Repository:
https://github.com/s0md3v/Photon
