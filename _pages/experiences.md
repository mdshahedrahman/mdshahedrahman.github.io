---
layout: archive
title: ""
permalink: /experiences/
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
            font-size: 15.5px; /* Ensures consistent font size for all text */
            font-family: 'Georgia', serif; /* Ensure the same font family */
            line-height: 1.6;
            color: #333;
            text-align: justify;
            margin-bottom: 13px; /* Consistent spacing */
        }

        /* Bullet point formatting */
        ul {
            list-style: disc;
            margin-left: 1px;
        }

        ul li {
            text-align: justify;
            margin-bottom: 5px;
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
            font-weight: normal;
            margin-bottom: 8px;
            color: #666;
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
            font-family: 'Georgia', serif; /* Ensure this is consistent */
            line-height: 1.6;
            color: #333;
            text-align: justify;
            margin-bottom: 13px; /* Moderate gap between list items */
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
    <h2>Building a Strong Foundation with 12+ Years of Professional Expertise</h2>
    <div class="separator"></div>

    <!-- Experience cards -->
    <div class="experience-container">

        <!-- Role 1: Graduate Student Researcher -->
        <div class="experience-card">
            <h3>Graduate Student Researcher</h3>
            <h4><a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/" target="_blank">The University of Texas at Arlington (UTA)</a> · Aug 2023 – Present</h4>
            <h5>Texas, USA</h5>
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/da/UTA_logomark.png" alt="UTA Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Optimized resource allocation and scaling strategies for microservice-based cloud applications, enhancing computational efficiency and overall system performance.</li>
                <li>Designed and implemented a Kubernetes-based Resource Manager to orchestrate microservices, dynamically improving deployment scalability and operational resilience.</li>
                <li>Identified and mitigated critical resource bottlenecks in microservices architecture, ensuring peak performance across distributed cloud environments.</li>
            </ul>
            <div class="section-header">Contributions</div>
            <ul class="section-content">
                <li>Implemented early SLO violation detection to streamline CPU utilization, driving greater resource efficiency, reducing unnecessary CPU overhead, and saving costs.</li>
            </ul>
        </div>

        <!-- Role 2: Chief Information Security Officer (CISO) -->
        <div class="experience-card">
            <h3>Chief Information Security Officer (CISO)</h3>
            <h4><a href="https://www.bracbank.com/en" target="_blank">BRAC Bank PLC</a> · Nov 2022 – Aug 2023</h4> 
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://play-lh.googleusercontent.com/alpY0C3iFPpBBULGdBBnR0i3mdMEk3M8GR35o7sWcg_OzVakagI11yxqokIGOYrbmcA" alt="BRAC Bank Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
               <li>Directed enterprise-wide cybersecurity strategy, aligning initiatives with business goals and regulatory standards.</li>
               <li>Led a 30-member Security Operations Center (SOC), ensuring 24/7 threat detection, rapid breach containment, and operational resilience.</li>
               <li>Architected advanced security frameworks to protect data, counter emerging threats, and ensure compliance.</li>
               <li>Authored and enforced policies for risk governance, vendor security, SLA oversight, and GABV-aligned audits.</li>
               <li>Delivered board-level risk reports and fostered stakeholder collaboration to drive organization-wide cybersecurity awareness.</li>
            </ul>
            <div class="section-header">Contributions</div>
            <ul class="section-content">
                <li>Deployed advanced ransomware defenses, XDR, EDR, and SIEM/SOAR solutions, mitigating 99.9% of threats and ensuring business continuity.</li>
                <li>Fortified cybersecurity across 187 branches, 33 sub-branches, and 1,041 agent-banking outlets, ensuring uninterrupted banking services.</li>
                <li>Drove security-focused digital transformation, saving $1.5M annually, improving efficiency by 25%, and reducing manual processes by 40%.</li>
                <li>Strengthened BRAC Bank’s alignment with the Global Alliance for Banking on Values (GABV), reinforcing its leadership in secure, sustainable finance.</li>
            </ul>
        </div>

        <!-- Role 3: National IT Security Consultant -->
        <div class="experience-card">
            <h3>National IT Security Consultant</h3>
            <h4><a href="https://bcc.gov.bd/" target="_blank">Bangladesh Computer Council</a> Funded Projects by <a href="https://www.worldbank.org/" target="_blank">World Bank Group</a> · Jan 2019 – Sep 2022</h4> 
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Bangladesh_Computer_Council_Logo.svg" alt="Bangladesh Computer Council Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Served as a key strategist in strengthening Bangladesh's cybersecurity landscape through comprehensive initiatives addressing technical and strategic challenges.</li>
                <li>Demonstrated expertise in cyber threats, risk management, infrastructure development, and policy formulation, which is critical in advancing the nation's cybersecurity posture.</li>
                <li>Contributed to building a resilient cybersecurity defense ecosystem for the Government of Bangladesh, enhancing technical capabilities and fostering security awareness across various sectors.</li>
                <li>Acted as a pivotal force in shaping national cybersecurity policies and awareness efforts, collaborating with government agencies, financial institutions, law enforcement agencies (LEAs), critical infrastructures, academia, and civil societies.</li>
                <li>Supervised audit teams by creating detailed plans, guiding them through the process, and preparing blueprints for prevention, detection, correction, and deterrent controls for the 
Government.</li>
            </ul>
            <div class="section-header">Contributions</div>
            <ul class="section-content">
                <li>Significantly imparted in developing Bangladesh's National Cybersecurity Strategy, IT Audit Framework, and Cloud Computing Framework policy, reinforcing the nation's digital security posture.</li>
                <li>Oversaw auditing efforts for the <a href="https://ndc.bcc.gov.bd/" target="_blank">National Data Center (NDC)</a>, <a href="https://www.cirt.gov.bd/" target="_blank">BGD e-GOV CIRT</a>, <a href="https://bdccl.gov.bd/" target="_blank">Tier IV National Data Center</a>, and Critical Information Infrastructures (CIIs) by ensuring compliance with stringent security standards.</li>
            </ul> 
        </div>

        <!-- Role 4: Assistant Vice President -->
        <div class="experience-card">
            <h3>Assistant Vice President</h3>
            <h4><a href="https://www.ebl.com.bd/" target="_blank">Eastern Bank PLC</a> · Nov 2016 – Dec 2018</h4> 
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://play-lh.googleusercontent.com/cEk_c4aNXPvN5SdT8IdDdSfHgFrtxhBx__0PGWafT6Y81Jv4I6nwBElLgdzkIQS7d868" alt="Eastern Bank PLC Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Headed the IT Security team, setting strategic direction and overseeing the development and implementation of the bank’s comprehensive information security strategy and architecture.</li>
                <li>Formulated and enforced stringent security policies and standards, ensuring strict compliance with regulations and cybersecurity laws.</li>
                <li>Steered bank-wide threat detection and response initiatives, conducting thorough risk assessments and driving proactive vulnerability management across critical systems.</li>
                <li>Pioneered integrating innovative security technologies, strengthening the bank's infrastructure against evolving threats, and successfully leading high-impact IT security projects to completion.</li>
            </ul>
            <div class="section-header">Contributions</div>
            <ul class="section-content">
                <li>Secured PCI-DSS compliance, the gold standard for protecting sensitive client data, mitigating breaches, and safeguarding customers from financial and identity theft risks.</li>
                <li>Instrumental in Eastern Bank PLC’s trailblazing PCI-DSS implementation, solidifying its position as a frontrunner in data security within Bangladesh’s banking sector.</li>
                <li>Activated 24/7 cyber defenses using SIEM and SOAR systems, fending off major threats like ransomware and DDoS attacks and protecting assets.</li>
            </ul>
        </div>

        <!-- Role 5: Assistant Manager (Cybersecurity) -->
        <div class="experience-card">
            <h3>Assistant Manager (Cybersecurity)</h3>
            <h4><a href="https://kpmg.com/bd/en/home.html" target="_blank">KPMG Bangladesh "Big Four"</a> · Feb 2015 – Nov 2016</h4> 
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://1000logos.net/wp-content/uploads/2023/03/KPMG-logo.png" alt="KPMG Bangladesh Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Analyzed security incidents and conducted vulnerability assessments.</li>
                <li>Orchestrated project execution, preparing RFPs and technical proposals for security audits and developing IT policies aligned with international standards (ISO 27001, ITIL, COBIT) and regulatory guidelines.</li>
                <li>Coordinated as a critical liaison between IT and business units, managing SLAs, resolving security-related breaches, and driving service improvements.</li>
                <li>Conducted risk management assessments, utilizing CRAMM methodologies to pinpoint and mitigate IT risks while streamlining business processes through gap analysis and workflow redesign using MS Visio.</li>
            </ul>
            <div class="section-header">Contributions</div>
            <ul class="section-content">
                <li>Strengthened the resilience of Payment and Settlement Systems of the Central Bank (Bangladesh Bank) by conducting thorough IT security audits, ensuring the stability and security of critical financial operations.</li>
                <li>Fortified the IT infrastructure and bolstered the credibility of Dhaka Bank PLC, NCC Bank PLC, Prime Bank PLC, BRAC Bank PLC, and Al-Arafah Islami Bank PLC, holding 15% of the market share through comprehensive security audits.</li>
            </ul>
        </div>

        <!-- Role 6: Senior Programmer (ERP Security) -->
        <div class="experience-card">
            <h3>Senior Programmer (ERP Security)</h3>
            <h4><a href="https://www.ibcs-primax.com/" target="_blank">IBCS-PRIMAX Software(Bangladesh) Limited</a> · Jan 2014 – Feb 2015</h4> 
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://iconape.com/wp-content/files/sl/341486/svg/341486.svg" alt="IBCS-PRIMAX Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Ensured robust database security through proactive maintenance, backups, and monitoring while securely integrating ERP systems to minimize risks.</li>
                <li>Identified and mitigated security vulnerabilities via regular scans, testing, and role-based access control (RBAC) implementation.</li>
                <li>Secured sensitive data through encryption, masking, and compliance with data privacy regulations (GDPR, CCPA), with frequent backups and recovery tests.</li>
                <li>Managed secure ERP configurations and applied timely patches to address vulnerabilities and maintain system integrity.</li>
            </ul>
            <div class="section-header">Contributions</div>
            <ul class="section-content">
                <li>Securely implemented ERP solutions such as Oracle E-Business Suite and JD Edwards in multiple organizations, enabling seamless, efficient service delivery to a large customer base, enhancing operational smoothness and reliability.</li>
            </ul>
        </div>

        <!-- Role 7: IT Specialist (Security) -->
        <div class="experience-card">
            <h3>IT Specialist (Security)</h3>
            <h4><a href="https://www.ibm.com/us-en/" target="_blank">IBM Bangladesh</a> · Oct 2012 – Dec 2013</h4> 
            <h5>Dhaka, Bangladesh</h5>
            <img src="https://purepng.com/public/uploads/large/purepng.com-ibm-logologobrand-logoiconslogos-251519939113t2tuw.png" alt="IBM Bangladesh Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Facilitated security analysis, collaborating with stakeholders to align advanced solutions with business goals.</li>
                <li>Organized security integration across projects, ensuring compliance with standards and monitoring SLAs.</li>
                <li>Enhanced database security through proactive monitoring, secure backups, and strategic capacity planning while maintaining detailed documentation for optimization.</li>
            </ul>
            <div class="section-header">Contributions</div>
            <ul class="section-content">
                <li>Actively ensured seamless operations for Airtel Bangladesh, the second-largest mobile operator, by delivering critical IT and security services through IBM, supporting their customer experience with precision and reliability.</li>
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
