---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Experiences</title>
    <style>
        /* General Body Style */
        body {
            font-family: 'Georgia', serif;
            background-color: #ffffff;
            margin: 0;
            padding: 0;
            color: #333;
        }

        /* Header styles */
        h1, h2, h3, h4, h5, h6 {
            margin: 0 0 0.5em;
            line-height: 1.2;
            font-family: 'Georgia', serif;
            font-weight: bold;
        }

        /* Main content container */
        .content {
            width: 100%; 
            max-width: 1100px;
            margin: 30px auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        /* Custom separator for the headline */
        .content h1::after {
            content: '';
            display: block;
            width: 60%;
            height: 2px;
            background-color: #1e3d8f;
            margin-top: 8px;
            margin-left: 0;
        }

        .content h2 {
            font-size: 20px;
            color: #1e3d8f;
            font-weight: bold;
            margin-bottom: 15px;
            text-align: center;
            position: relative;
        }

        .content h2::after {
            content: '';
            display: block;
            width: 60%;
            height: 1px;
            background-color: #cccccc;
            margin: 10px auto;
        }

        .content p, .content li {
            font-size: 15.5px;
            font-family: 'Georgia', serif;
            line-height: 1.6;
            color: #333;
            text-align: justify;
            margin-bottom: 13px;
        }

        /* Bullet point formatting */
        ul {
            list-style: disc;
            margin-left: 1px;
        }

        ul li {
            text-align: justify;
            margin-bottom: 10px;
        }

        ul li::marker {
            font-weight: bold;
        }

        /* Experience card container without timeline */
        .experience-container {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
            position: relative;
            padding-left: 0;
        }

        /* Experience card styling */
        .experience-card {
            background-color: #f9f9f9;
            border-radius: 12px;
            padding: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border-left: 5px solid #1e3d8f;
            position: relative;
        }

        .experience-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
        }

        .experience-card h3 {
            font-size: 18px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 8px;
        }

        .experience-card h4 {
            font-size: 16px;
            font-weight: bold;
            margin-bottom: 8px;
            color: #333;
        }

        .experience-card h5 {
            font-size: 14px;
            color: #999;
            margin-bottom: 6px;
        }

        .experience-card img {
            width: 45px;
            height: 45px;
            object-fit: contain;
            float: right;
            margin-left: 15px;
        }

        .section-header {
            font-size: 16px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 6px;
            border-bottom: 2px solid #cccccc;
            padding-bottom: 3px;
        }

        .section-content {
            font-size: 14px;
            font-family: 'Georgia', serif;
            line-height: 1.6;
            color: #333;
            text-align: justify;
            margin-bottom: 13px;
        }

        /* Links styling */
        a {
            color: #1e3d8f;
            text-decoration: none;
        }

        a:link, a:visited {
            color: #1e3d8f;
            text-decoration: none;
        }

        a:hover, a:active {
            color: #003399;
            text-decoration: none;
        }

        /* Footer styles */
        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 14px;
            color: #333;
            font-family: 'Georgia', serif;
            background-color: #ffffff;
            padding: 20px 0;
            border-top: 1px solid #cccccc;
        }

        footer .separator {
            font-size: 18px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 15px;
        }

        footer .separator::after {
            content: '';
            display: block;
            width: 40px;
            height: 2px;
            background-color: #1e3d8f;
            margin: 10px auto;
        }

        footer .links {
            margin-bottom: 15px;
        }

        footer .links a {
            margin: 0 15px;
            color: #1e3d8f;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
        }

        footer .links a:hover {
            text-decoration: underline;
        }

        footer .footer-note {
            color: #777;
            font-size: 14px;
        }

    </style>
</head>
<body>

<!-- Professional Experiences Section -->
<div class="content">
    <h2>Selected Publications</h2>
    <div class="separator"></div>

    <!-- Experience cards -->
    <div class="experience-container">

        <!-- Role 1: Graduate Student Researcher -->
        <div class="experience-card">
            <h3>Graduate Student Researcher</h3>
            <h4>Role: Graduate Student Researcher -<a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/" target="_blank">The University of Texas at Arlington (UTA)</a></h4>
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Optimized resource allocation and scaling strategies for microservice-based cloud applications, enhancing computational efficiency and overall system performance.</li>
                <li>Designed and implemented a Kubernetes-based Resource Manager to orchestrate microservices, dynamically improving deployment scalability and operational resilience.</li>
                <li>Identified and mitigated critical resource bottlenecks in microservices architecture, ensuring peak performance across distributed cloud environments.</li>
            </ul>
        </div>

        <!-- Role 2: Implementation of Extended Detection and Response (XDR) Tools -->
        <div class="experience-card">
            <h3>Implementation of Extended Detection and Response (XDR) Tools</h3>
            <h4>Role: Project Manager - <a href="https://www.bracbank.com/en" target="_blank">BRAC Bank PLC</a></h4> 
            <div class="section-header">Particulars</div>
            <ul class="section-content">
                <li>Strengthened cybersecurity posture by automating detection, fostering collaboration across teams, and driving continuous threat-hunting and system improvements.</li>
                <li>Directed the strategic adoption and deployment of XDR solutions, aligning with business objectives and integrating with existing security tools to enhance threat detection and response.</li>
                <li>Orchestrated vendor selection, contract negotiations, and seamless XDR integration, ensuring efficient data collection, governance, and operational optimization.</li>
            </ul>
        </div>

                <!-- Role 2: Implementation of Extended Detection and Response (XDR) Tools -->
        <div class="experience-card">
            <h3>Real-Time Threat Detection & SIEM Integration Project</h3>
            <h4>Role: Project Manager - <a href="https://www.bracbank.com/en" target="_blank">BRAC Bank PLC</a></h4> 
            <div class="section-header">Particulars</div>
            <ul class="section-content">
                <li>Led the SIEM deployment, overseeing requirements analysis, vendor selection (EOI, RFQ, RFP), and architecture design to align with corporate security and compliance objectives.</li>
                <li>Maximized threat detection by configuring log sources, fine-tuning detection rules, and integrating SIEM with security tools, minimizing false positives and negatives.</li>
                <li>Planned and enhanced real-time monitoring and incident response, improving security event analysis, threat detection, and ensuring ongoing compliance.</li>
            </ul>
        </div>

        <!-- Role 3: Advanced Ransomware Prevention and Early Detection -->
        <div class="experience-card">
            <h3>Advanced Ransomware Prevention and Early Detection</h3>
            <h4>Role: Project Manager - <a href="https://www.bracbank.com/en" target="_blank">BRAC Bank PLC</a></h4> 
            <div class="section-header">Particulars</div>
            <ul class="section-content">
                <li>Proactively secured systems by patching vulnerabilities, leveraging threat intelligence, maintaining offline backups, minimizing ransomware risks, and ensuring swift recovery.</li>
                <li>Implemented a multi-layered security architecture, including firewalls, EDR, and DDoS mitigation, to enhance ransomware defense and ensure early threat detection and response.</li>
                <li>Drove employee training and developed a comprehensive incident response plan, empowering staff to act as the first line of defense and ensuring coordinated responses to ransomware attacks.</li>
            </ul>
        </div>

        
        <!-- Role 3: Advanced Ransomware Prevention and Early Detection -->
        <div class="experience-card">
            <h3>SOAR and Threat Intelligence Integration for Proactive Automated Response</h3>
            <h4>Role: Project Manager - <a href="https://www.bracbank.com/en" target="_blank">BRAC Bank PLC</a></h4> 
            <div class="section-header">Particulars</div>
            <ul class="section-content">
                <li>Initiated automation of incident response workflows, working closely with security analysts to enhance efficiency through SOAR and SIEM integration.</li>
                <li>Designed a comprehensive library of automation scripts and playbooks, enabling swift and efficient incident management.</li>
                <li>Optimized automation performance, tracking key metrics and reporting enhancements in threat intelligence and incident response capabilities.</li>
            </ul>
        </div>

        <!-- Additional roles omitted for brevity -->
 

                <!-- Role 4: National IT Security Consultant -->
        <div class="experience-card">
            <h3>IT Auditing for Secure Digital Operations</h3>
            <h4>Role: Project Manager & Team Member - <a href="https://bcc.gov.bd/" target="_blank">Bangladesh Computer Council</a> Funded Projects by <a href="https://www.worldbank.org/" target="_blank">World Bank Group</a></h4> 
            <div class="section-header">Particulars</div>
            <ul class="section-content">
                <li>Spearheaded the <a href="https://ndc.bcc.gov.bd/">National Data Center (NDC)</a>) IT audit, a Tier-3 facility providing 24x7 IaaS, PaaS, and SaaS, ensuring secure, continuous operations for the government's digitalization initiative.</li>
                <li>Contributed to IT and cybersecurity audits for <a href="https://bdccl.gov.bd/" target="_blank">Tier IV National Data Center</a>, validating 99.995% SLA uptime, safeguarding 2 Petabytes of cloud storage, and assessing security equipment to enhance national data resilience through multi-layered defense and redundancy systems.</li>
                <li>Steered the IT audit of toll plaza systems for the <a href="https://rhd.portal.gov.bd/" target="_blank">Road Transportation Highway Division (RTHD)</a>, evaluating electronic and manual toll collection systems and bolstering the government’s highway maintenance funding strategy through efficient toll collection.</li>
            </ul>
        </div>
        <!-- Role 4: National IT Security Consultant -->
        <div class="experience-card">
            <h3><a href="https://www.cirt.gov.bd/" target="_blank">Bangladesh (BGD) e-GOV CIRT</a></h3>
            <h4>Role: Team Member - <a href="https://bcc.gov.bd/" target="_blank">Bangladesh Computer Council</a> Funded Projects by <a href="https://www.worldbank.org/" target="_blank">World Bank Group</a></h4> 
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Collaborated in establishing a Cybersecurity Research Wing, assisting with incident response policies, infrastructure setup, and partnerships with international CERTs to enhance e-government security.</li>
                <li>Worked alongside in developing the National Cyber Security Strategy and Risk Assessment Framework, supporting efforts to strengthen cyber defenses and aiding implementation across government agencies.</li>
                <li>Facilitated the setup of a Digital Forensic Lab, providing input on tools, assisting in investigator training, and ensuring compliance with legal requirements for cybercrime investigations.</li>
                <li>Participated in Vulnerability Assessments for Bangladesh Bank, helping identify risks, recommending remediation actions, and offering security insights for system improvements.</li>
                <li>Assisted in deploying Cyber Sensors in Critical Infrastructures, contributing to risk assessments and implementing monitoring systems to safeguard vital sectors from cyber threats.</li>
            </ul>
        </div>

                <!-- Role 4: National IT Security Consultant -->
        <div class="experience-card">
            <h3>PCI-DSS Compliance and Security Enhancement Project</h3>
            <h4>Role: Project Manager & Team Member - <a href="https://www.ebl.com.bd/" target="_blank">Eastern Bank PLC</a></h4>  
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Piloted PCI-DSS implementation, managing project planning, risk assessments, and gap analysis to secure payment card data.</li>
                <li>Synchronized cross-functional teams, developed policies, and ensured compliance through testing and continuous monitoring.</li>
                <li>Guided technical enforcement of security controls, including access control and vulnerability management, enhancing payment security and reducing risks.</li>
            </ul>
        </div>

                <!-- Role 4: National IT Security Consultant -->
        <div class="experience-card">
            <h3>Enterprise SIEM Deployment and Incident Response Initiative</h3>
            <h4>Role: Team Member - <a href="https://www.ebl.com.bd/" target="_blank">Eastern Bank PLC</a></h4> 
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Contributed to requirements analysis and vendor selection for SIEM implementation, aligning the solution with organizational security needs.</li>
                <li>Assisted in designing and configuring the SIEM architecture, setting up log sources, and customizing detection rules for real-time monitoring and incident response.</li>
                <li>Supported real-time monitoring by tuning SIEM alerts and assisting the security team in threat analysis, improving incident detection and response.</li>
            </ul>
        </div>


        <!-- Role 4: National IT Security Consultant -->
        <div class="experience-card">
            <h3>Financial Systems Security Assurance Project</h3>
            <h4>Role: Project Manager & Team Member - <a href="https://kpmg.com/bd/en/home.html" target="_blank">KPMG Bangladesh "Big Four"</a></h4> 
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Assisted in IT security audits for the central bank's (Bangladesh Bank) key payment systems, ensuring the robustness of critical financial operations.</li>
                <li>Supported cybersecurity audits for major banks (Dhaka Bank PLC, BRAC Bank, NCC Bank PLC, Prime Bank PLC, Al-Arafah Islami Bank PLC), enhancing IT infrastructure security and credibility.</li>
                <li>Contributed to strengthening IT security for core banking systems and ERP platforms, ensuring compliance and operational resilience across financial institutions.</li>
            </ul>
        </div>

        <!-- Role 4: National IT Security Consultant -->
        <div class="experience-card">
            <h3>Oracle JD Edwards Implementation and Optimization</h3>
            <h4>Role: Team Member - <a href="https://www.ibcs-primax.com/" target="_blank">IBCS-PRIMAX Software(Bangladesh) Limited</a></h4> 
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Supported the first Oracle JD Edwards implementation in Bangladesh, covering Financials, Procurement, Inventory, and Sales modules.</li>
                <li>Conducted business analysis and process optimization, managing client needs, vendor coordination, and automating manual processes.</li>
                <li>Ensured database security and maintenance, handling backups, monitoring, and capacity planning while supporting end-user training and system integration.</li>
            </ul>
        </div>

        <!-- Role 4: National IT Security Consultant -->
        <div class="experience-card">
            <h3>Airtel Bangladesh IT Operations and Security Support Initiative</h3>
            <h4>Role: Team Member - <a href="https://www.ibm.com/us-en/" target="_blank">IBM Bangladesh</a></h4> 
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Assisted in securing Airtel’s key customer-facing applications, such as the Prepaid Top-Up Transfer and E-Self Care platforms, enhancing customer service delivery.</li>
                <li>Contributed to multiple IT support projects for Airtel Bangladesh, including CRM, PreTUPS, and the Pay Via Scratch Card Application, ensuring seamless operational efficiency.</li>
                <li>Supported Airtel’s operational growth as the second-largest mobile operator in Bangladesh by enabling reliable IT and security support through IBM.</li>
            </ul>
        </div>

        
        
     

    </div>
</div>

<footer>
    <div class="separator"></div>
    <div class="links">
    </div>
    <div class="footer-note">
    </div>
</footer>

</body>
</html>
