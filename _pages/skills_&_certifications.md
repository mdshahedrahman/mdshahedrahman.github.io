---
layout: archive
title: ""
permalink: /skills_&_certifications/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Georgia', serif;
            background-color: #f7f7f7;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        /* Ensure content has enough padding at the bottom */
        .content {
            flex: 1;
            padding-bottom: 50px; /* Added bottom padding */
        }
        /* Footer */
        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 14px;
            color: #aaa;
            position: relative; /* Ensure the footer is positioned relative to the content */
            clear: both; /* Clear any floating elements */
            padding: 20px 0; /* Add padding to the footer */
        }

        .separator {
            grid-column: 1 / -1;
            text-align: center;
            font-size: 24px;
            font-family: 'Georgia', serif;
            font-weight: bold;
            color: #1e3d8f;
            margin-top: 20px;
            margin-bottom: 20px;
            position: relative;
        }

        .separator::after {
            content: '';
            display: block;
            width: 60%;
            height: 1px;
            background-color: #cccccc;
            margin: 10px auto;
        }

        .skills-section {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-template-rows: repeat(4, auto);
            gap: 20px;
            padding: 30px 20px;
            max-width: 1200px;
            margin: auto;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .item {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 15px;
            border-radius: 10px;
            background-color: #f9f9f9;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .item:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);
        }

        .item img {
            width: 60px;
            margin-bottom: 15px;
        }

        .item p {
            font-size: 16px;
            margin: 5px 0;
            color: #333;
        }

        .subtext {
            font-size: 14px;
            color: #888;
        }

        /* Footer styling */
        footer {
            text-align: center;
            padding: 20px 0;
            background-color: #f1f1f1;
            color: #666;
            width: 100%;
            margin-top: auto;
        }

        footer a {
            text-decoration: none;
            color: #1e3d8f;
            font-weight: bold;
        }

        footer a:hover {
            color: #333;
        }

    </style>

<div class="content">
   <!-- Skills Section -->
<div class="separator">Skills</div>
<div class="skills-section">
    <div class="item">
        <img src="{{ '/images/verified-icons/legacy-8a663500f6.png' | relative_url }}" alt="Project Management">
        <p>Waterfall, Agile, Scrum</p>
        <p class="subtext">Large Scale Project Management</p>
    </div>

    <div class="item">
        <img src="{{ '/images/verified-icons/legacy-b0ee9a105e.jpg' | relative_url }}" alt="Soft Skills">
        <p>Inclusive Leadership, Business Communication</p>
        <p class="subtext">Soft Skills</p>
    </div>

    <div class="item">
        <span>
        <img src="{{ '/images/verified-icons/legacy-f8df636fc3.png' | relative_url }}" alt="Python Icon">
        <img src="{{ '/images/verified-icons/legacy-1ef1f55cae.png' | relative_url }}" alt="Python Icon">
        </span>       
        <p>Python, C, SQL, Bash</p>
        <p class="subtext">Programming Languages</p>
    </div>

    <div class="item">
        <img src="{{ '/images/verified-icons/legacy-03b6b94555.png' | relative_url }}" alt="Web Development">
        <p>HTML, CSS, Bootstrap, MERN, MEAN</p>
        <p class="subtext">Web Development</p>
    </div>
    
    <div class="item">
        <img src="{{ '/images/verified-icons/legacy-57d303ae0d.jpg' | relative_url }}" alt="Docker Icon">
        <p>Docker, Kubernetes</p>
        <p class="subtext">Container Orchestration</p>
    </div>

    <div class="item">
        <img src="{{ '/images/verified-icons/legacy-f07806eb9b.png' | relative_url }}" alt="Cloud Icon">
        <p>AWS, GCP</p>
        <p class="subtext">Cloud Computing</p>
    </div>

    <div class="item">
        <span>
        <img src="{{ '/images/verified-icons/legacy-662902e9a0.png' | relative_url }}" alt="Linux Icon">
        <img src="{{ '/images/verified-icons/kali.svg' | relative_url }}" alt="Linux Icon">
        </span>
        <p>Linux, Kali Linux</p>
        <p class="subtext">Operating Systems</p>
    </div>

    <div class="item">
        <span>
        <img src="{{ '/images/verified-icons/legacy-2622d1351d.png' | relative_url }}" alt="Grafana Icon">
        <img src="{{ '/images/verified-icons/legacy-128b404783.png' | relative_url }}" alt="Grafana Icon">
        </span>        
        <p>Prometheus, Grafana, Jaeger</p>
        <p class="subtext">Monitoring and Metrics</p>
    </div>

    <div class="item">
        <img src="{{ '/images/verified-icons/legacy-695cbda1ce.jpg' | relative_url }}" alt="Database Icon">
        <p>MySQL, MongoDB</p>
        <p class="subtext">Databases</p>
    </div>

    <div class="item">
        <img src="{{ '/images/verified-icons/legacy-1450854de5.png' | relative_url }}" alt="IT Audit">
        <p>ISO, ITAF</p>
        <p class="subtext">IT Audit</p>
    </div>

    <div class="item">
        <img src="{{ '/images/verified-icons/legacy-a9bafefc1c.png' | relative_url }}" alt="SIEM">
        <p>SIEM, XDR, EDR</p>
        <p class="subtext">Threat Detection and Defense Tools</p>
    </div>

    <div class="item">
        <img src="{{ '/images/verified-icons/legacy-9c009a722b.png' | relative_url }}" alt="SOAR">
        <p>SOAR, Threat Intel</p>
        <p class="subtext">Threat Intelligence and Incident Response Platform</p>
    </div>

    <div class="item">
        <img src="{{ '/images/verified-icons/legacy-b931301504.jpg' | relative_url }}" alt="DLP">
        <p>DLP, MDM</p>
        <p class="subtext">Data Privacy Tools</p>
    </div>

    <div class="item">
        <span>
        <img src="{{ '/images/verified-icons/nmap.png' | relative_url }}" alt="VAPT Tools">
        <img src="{{ '/images/verified-icons/legacy-0ef2f2f858.png' | relative_url }}" alt="VAPT Tools">
        </span>        
        <p>NMAP, Nessus, Burpsuite</p>
        <p class="subtext">VAPT Tools</p>
    </div>

    <div class="item">
        <img src="{{ '/images/verified-icons/grc.png' | relative_url }}" alt="GRC">
        <p>GRC, ISO, COBIT</p>
        <p class="subtext">GRC</p>
    </div>

    <div class="item">
        <img src="{{ '/images/verified-icons/legacy-1816e4b630.jpg' | relative_url }}" alt="ITIL">
        <p>ITIL, ISO</p>
        <p class="subtext">IT Incident Management</p>
    </div>
</div>
<footer>
</footer>

