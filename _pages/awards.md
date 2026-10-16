---
layout: archive
title: ""
permalink: /awards/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Awards</title>
    <style>
        /* General Body Style */
        body {
            font-family: 'Georgia', serif;
            background-color: #f0f7fa;
            margin: 0;
            padding: 0;
            color: #333;
        }

        /* Header styles for better alignment */
        h1, h2, h3, h4, h5, h6 {
            margin: 0em 0 0.5em;
            line-height: 1.2;
            font-family: -apple-system, ".SFNSText-Regular", "San Francisco", "Roboto", "Segoe UI", "Helvetica Neue", "Lucida Grande", Arial, sans-serif;
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

        /* Styling for smaller text in certifications */
        .certification-card p {
            font-size: 16px;
        }

        /* Adjust link behavior to open in a new tab */
        a:link, a:visited, a:hover, a:active {
            color: #1e3d8f;
            text-decoration: none;
        }

        a:hover {
            color: #003399;
        }

        a {
            target-new: tab !important;
        }

        /* Style for Cards */
        .certification-layout {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(340px, 1fr)); /* Adjusted width */
            gap: 10px; /* More compact gap */
            margin-top: 15px;
        }

        .certification-card {
            padding: 8px;
            background-color: #f9f9f9;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .certification-card h5,
        .certification-card p,
        .certification-card small {
            font-family: 'Georgia', serif;
            color: #333;
        }

        .certification-card h5 {
            font-size: 18px;
            font-weight: bold;
            margin-bottom: 5px;
        }

        .certification-card small {
            font-size: 14px;
        }

        .certification-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }

        /* Section Separator */
        .separator {
            grid-column: 1 / -1;
            text-align: center;
            font-size: 22px;
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

        /* Flex layout for icon and text */
        .flex-row {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .flex-row img {
            width: 40px;
            height: 40px;
            vertical-align: middle;
        }

        .flex-row h5 {
            margin: 0;
            line-height: 1.2;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .certification-layout {
                grid-template-columns: 1fr;
            }
        }

        /* Updated footer styling */
        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 14px;
            color: #aaa;
            font-family: 'Georgia', serif;
            background-color: #f9f9f9;
            padding: 20px 0;
            border-top: none;
        }

        footer .links {
            margin-bottom: 10px;
        }

        footer .links a {
            margin: 0 10px;
            color: #333;
        }

        footer .links a:hover {
            text-decoration: underline;
        }

    </style>
</head>
<body>

<!-- Awards Section -->
<div class="content">
    <div class="certification-layout">
        <!-- Awards Section Separator -->
        <div class="separator">Awards Received</div>

        <!-- Awards Cards -->
        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="{{ '/images/verified-icons/legacy-fc2d5714d5.png' | relative_url }}" alt="UTA Logo">
                    <h5>STEM Tuition Support</h5>
                </div>
                <p>Honored with a renowned STEM scholarship covering all tuition and fees, alongside a Graduate Teaching Assistantship offer for academic excellence., Fall 2023 - Present<br><small><a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/" target="_blank">The University of Texas at Arlington (UTA)</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="{{ '/images/verified-icons/bup.svg' | relative_url }}" alt="BUP Logo">
                    <h5>Chancellor's Gold Medal</h5>
                </div>
                <p>Recipient of the prestigious Chancellor's Gold Medal, awarded by the President of the People's Republic of Bangladesh, for achieving top honors at the master's level, 2020<br><small><a href="https://bup.edu.bd/academics/academic_details/464" target="_blank">Bangladesh University of Professionals (BUP)</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="{{ '/images/verified-icons/legacy-bacd229231.png' | relative_url }}" alt="JICA Logo">
                    <h5>IT Engineers Examinations (ITEE)</h5>
                </div>
                <p>Participated in a competitive examination to support the vision of Digital Bangladesh and earned the distinguished ITEE certification, awarded by JICA, 2010<br><small><a href="https://www.jica.go.jp/english/" target="_blank">Japan International Cooperation Agency (JICA)</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="{{ '/images/verified-icons/legacy-2f9e346c48.png' | relative_url }}" alt="Janata Bank Logo">
                    <h5>Gold Medal</h5>
                </div>
                <p>Received a distinguished gold medal for exceptional performance in 12th grade, awarded by the Janata Bank PLC Employees Benevolent Fund Managing Committee, 2007.<br><small><a href="https://www.jb.com.bd/" target="_blank">Janata Bank PLC</a></small></p>
            </div>
        </div>

    </div>
</div>

<!-- Affiliations Section -->
<div class="content">
    <div class="certification-layout">
        <!-- Affiliations Section Separator -->
        <div class="separator">Affiliations</div>

        <!-- Affiliation Cards (Merged Academic and Professional) -->
        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="{{ '/images/verified-icons/legacy-fc2d5714d5.png' | relative_url }}" alt="UTA Logo">
                    <h5>Student Affiliation</h5>
                </div>
                <p>Fall 2023 - Present<br><small><a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/" target="_blank">The University of Texas at Arlington (UTA)</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="{{ '/images/verified-icons/legacy-b977872719.png' | relative_url }}" alt="ISACA Logo">
                    <h5>Silver Member</h5>
                </div>
                <p>2017 - Present<br><small><a href="https://www.isaca.org/" target="_blank">Information Systems Audit and Control Association (ISACA)</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="{{ '/images/verified-icons/legacy-81730908e0.png' | relative_url }}" alt="PMI Logo">
                    <h5>Member</h5>
                </div>
                <p>2020 - Present<br><small><a href="https://my.pmi.org/" target="_blank">Project Management Institute (PMI)</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="{{ '/images/verified-icons/legacy-f4b4f2929f.png' | relative_url }}" alt="EC-Council Logo">
                    <h5>Member</h5>
                </div>
                <p>2016 - Present<br><small><a href="https://www.eccouncil.org/" target="_blank">EC-Council</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="{{ '/images/verified-icons/ieb.png' | relative_url }}" alt="IEB Logo">
                    <h5>Life Member</h5>
                </div>
                <p>2013 - Present<br><small><a href="https://www.iebbd.org/" target="_blank">The Institution of Engineers, Bangladesh (IEB)</a></small></p>
            </div>
        </div>

        <div class="certification-card">
            <div class="education-card">
                <div class="flex-row">
                    <img src="{{ '/images/verified-icons/bcs.png' | relative_url }}" alt="BCS Logo">
                    <h5>Life Member</h5>
                </div>
                <p>2013 - Present<br><small><a href="https://www.bcsbd.org.bd/" target="_blank">Bangladesh Computer Society (BCS)</a></small></p>
            </div>
        </div>
    </div>
</div>

<footer>
    <div class="links">
        <a href="#">Sitemap</a> | <a href="https://github.com/mdshahedrahman" target="_blank" rel="noopener noreferrer">GitHub</a> | <a href="#">RSS</a>
    </div>
    © 2024 Mohammad Shahedur Rahman. Powered by Jekyll & AcademicPages, a fork of Minimal Mistakes.
</footer>

</body>
</html>
