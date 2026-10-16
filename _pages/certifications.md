---
layout: archive
title: ""
permalink: /certifications/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Accreditations & Credentials</title>
    <style>
        /* General Body Style */
        body {
            font-family: 'Georgia', serif;
            background-color: #f0f7fa;
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
            margin: 20px auto;
            padding: 15px;
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
        }

        .content h2 {
            font-size: 28px;
            color: #1e3d8f;
            font-weight: bold;
            margin-bottom: 15px;
            position: relative;
        }

        .content h2::after {
            content: '';
            display: block;
            width: 100%;
            height: 1px;
            background-color: #cccccc;
            margin-top: 8px;
        }

        .content p {
            font-size: 17px;
            line-height: 1.6;
            color: #333;
            margin-bottom: 15px;
            text-align: justify;
        }

        /* Certifications Grid Layout */
        .certification-layout {
            display: grid;
            grid-template-columns: repeat(2, 1fr); /* Two cards per row */
            gap: 15px;
            margin-top: 15px;
        }

        /* Certification card styling */
        .certification-card {
            display: flex;
            align-items: center;
            padding: 10px;
            background-color: #f9f9f9;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .certification-card img {
            width: 40px;
            height: 40px;
            object-fit: contain;
            flex: 0 0 40px;
            margin-right: 15px;
        }

        .certification-card h6 {
            font-size: 14px;
            font-weight: normal;
            margin: 0;
        }

        .certification-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }

        /* Section Separator */
        .separator {
            grid-column: 1 / -1;
            text-align: center;
            font-size: 18px;
            font-weight: bold;
            color: #1e3d8f;
            margin-top: 10px;
            margin-bottom: 10px;
        }

        .separator::after {
            content: '';
            display: block;
            width: 50%;
            height: 1px;
            background-color: #cccccc;
            margin: 5px auto;
        }

        @media (max-width: 768px) {
            .certification-layout {
                grid-template-columns: 1fr;
            }
        }

        /* Footer styles */
        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 14px;
            color: #333;
            font-family: 'Georgia', serif;
            background-color: #f0f7fa;
            padding: 20px 0;
            border-top: 1px solid #cccccc;
        }

        footer .separator {
            font-size: 20px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 15px;
        }

        footer .separator::after {
            content: '';
            display: block;
            width: 50px;
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

<!-- Accreditations & Credentials Section -->
<div class="content">
    <div class="separator">Project Management</div>

    <!-- Two-Column Layout for Cards -->
    <div class="certification-layout">
        <div class="certification-card">
            <img src="{{ '/images/verified-icons/pmp.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>Project Management Professional (PMP)</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/lean-six-sigma-black-belt-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>Lean Six Sigma Black Belt</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/prince2-practitioner-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>PRINCE2 Practitioner</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/prince2-foundation-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>PRINCE2 Foundation</h6>
        </div>
    </div>
</div>

<!-- Governance, Risk & Compliance Section -->
<div class="content">
    <div class="separator">Governance, Risk & Compliance</div>

    <!-- Two-Column Layout for Cards -->
    <div class="certification-layout">
        <div class="certification-card">
            <img src="{{ '/images/verified-icons/crisc.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>Certified in Risk and Information Systems Control (CRISC)</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/iso-iec-27001-lead-implementer-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>ISO/IEC 27001:2013 ISMS: Lead Implementer</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/verified-icons/iso27701.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>ISO/IEC 27701:2019 Privacy Information Management and GDPR: Lead Implementer</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/itil-foundation-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>ITIL Foundation</h6>
        </div>
    </div>
</div>

<!-- IT Audit Section -->
<div class="content">
    <div class="separator">IT Audit</div>

    <!-- Two-Column Layout for Cards -->
    <div class="certification-layout">
        <div class="certification-card">
            <img src="{{ '/images/certifications/cisa-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>Certified Information Systems Auditor (CISA)</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/csa-star-certification-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>Advanced Auditing for CSA STAR Certification</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/iso-iec-27001-lead-auditor-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>ISO/IEC 27001 ISMS: Lead Auditor</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/pci-dss-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>PCI DSS V3.2.1 Implementation</h6>
        </div>
    </div>
</div>

<!-- Information & Cyber Security Section -->
<div class="content">
    <div class="separator">Information & Cyber Security</div>

    <!-- Two-Column Layout for Cards -->
    <div class="certification-layout">
        <div class="certification-card">
            <img src="{{ '/images/certifications/certified-in-cybersecurity-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>Certified in Cybersecurity (CC)</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/certified-threat-intelligence-analyst-icon.jpg' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>Certified Threat Intelligence Analyst</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/verified-icons/cei.webp' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>Certified EC-Council Instructor v10</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/certified-lead-pen-test-professional-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>Certified Lead Pen Test Professional</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/iso-iec-27032-lead-cybersecurity-manager-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>ISO/IEC 27032 Lead Cybersecurity Manager</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/verified-icons/ceh.webp' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>Certified Ethical Hacker (CEH)</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/certified-blockchain-professional-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>Certified Blockchain Professional</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/certified-secure-computer-user-v2-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>Certified Secure Computer User v2</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/certified-cybercrime-first-responder-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>Certified Cybercrime First Responder</h6>
        </div>

        <div class="certification-card">
            <img src="{{ '/images/certifications/cyber-security-foundation-professional-certificate-icon.png' | relative_url }}" alt="" width="40" height="40" decoding="async">
            <h6>Cyber Security Foundation Professional Certificate (CSFPC)</h6>
        </div>
    </div>
</div>

<footer>
    <div class="separator"></div>
    <div class="links">
        <a href="https://www.linkedin.com/in/m-shahed/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
        <a href="https://github.com/mdshahedrahman" target="_blank" rel="noopener noreferrer">GitHub</a>
        <a href="#">Twitter</a>
    </div>
    <div class="footer-note">
        &copy; 2024 Your Name. All rights reserved.
    </div>
</footer>

</body>
</html>
