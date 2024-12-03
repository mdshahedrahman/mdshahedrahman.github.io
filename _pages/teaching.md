---
layout: archive
title: ""
permalink: /teaching/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biography</title>
    <style>
        /* General Body Style */
        body {
            font-family: 'Georgia', serif;
            background-color: #f0f7fa;
            margin: 0;
            padding: 0;
            color: #333;
        }

        /* Bullet Style for Course Titles */
        .bullet {
            display: inline-block;
            width: 12px;
            height: 12px;
            background-color: #1e3d8f;
            clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
            margin-right: 10px;
        }

        /* Main content container */
        .content {
            width: 128%;
            margin: 0;
            padding: 10px;
            padding-bottom: 20px; /* Added padding at the bottom */
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        .content h2 {
            font-size: 28px;
            color: #1e3d8f;
            font-weight: bold;
            margin-bottom: 20px;
            position: relative;
        }

        .content h2::after {
            content: '';
            display: block;
            width: 100%;
            height: 1px;
            background-color: #cccccc;
            margin-top: 10px;
        }

        .content p {
            font-size: 18px;
            line-height: 1.8;
            color: #333;
            margin-bottom: 20px;
            text-align: justify; /* Justify the paragraph text */
        }

        .content a {
            color: #1e3d8f;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .content a:hover {
            color: #003399;
        }

        /* Style for Biography and Interests (Unchanged) */
        .certification-layout {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .certification-card {
            padding: 10px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            font-family: 'Georgia', serif;
        }

        .certification-card h5,
        .certification-card p,
        .certification-card small {
            font-family: 'Georgia', serif;
            color: #333;
        }

        .certification-card h5 {
            font-size: 18px; /* Font size for headings */
            font-weight: bold; /* Keeping the heading bold */
        }

        .certification-card p {
            font-size: 17px; /* Font size for regular text */
        }

        .certification-card small {
            font-size: 15px; /* Font size for small text */
        }

        .certification-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
        }

        .separator {
            grid-column: 1 / -1;
            text-align: center;
            font-size: 22px;
            font-weight: bold;
            color: #1e3d8f;
            margin-top: 0px;
            margin-bottom: 0px;
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

        /* New Style for Education Section (as per your uploaded image) */
        .education-layout {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
            margin-top: 20px;
        }

        .education-card {
            padding: 15px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            display: flex;
            align-items: center;
        }

        .education-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }

        .education-card h5 {
            font-family: 'Georgia', serif;
            font-size: 16px; /* Matching font size to Interests section */
            font-weight: bold;
            color: #333;
            margin: 0;
        }

        .education-card small {
            font-size: 14px;
            color: #666;
        }

        .education-card img {
            width: 40px;
            height: 40px;
            margin-right: 20px;
        }

        .education-card p {
            font-size: 14px;
            color: #333;
            margin: 0;
            text-align: justify; /* Ensuring the text is justified */
        }

        /* Styling for Download CV link */
        .cv-link-wrapper {
            display: flex;
            align-items: center;
            margin-top: 20px;
        }

        .cv-link-wrapper img {
            width: 20px;
            height: 20px;
            margin-right: 10px;
        }

        .cv-link-wrapper a {
            font-size: 18px;
            font-family: 'Georgia', serif;
            color: #333;
            text-decoration: none;
        }

        .cv-link-wrapper a:hover {
            color: #1e3d8f;
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

        /* Responsive Design */
        @media (max-width: 768px) {
            .certification-layout {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <!-- New Style for Education Section -->
    <div class="education-layout">
        <!-- Education Section Separator -->
        <div class="separator">
            <span>Teaching Assistantships</span>
        </div>
        
       <!-- Education Card 4 -->
        <div class="education-card">
            <div>
                <span class="bullet"></span><h5 style="display: inline-block;">CSE 5380. INFORMATION SECURITY 1</h5>
                <p><h5 style="display: inline-block;">Spring 2025</h5></p>
                <p>Hands-on introduction to the basics of security. Includes system security, buffer overflows, a high-level overview of cryptography, firewalls and IDS/IPS, malware, penetration testing, forensics, and system administration. Prerequisite: CSE 3320 (OPERATING SYSTEMS).<br>
                </p>
            </div>
        </div>
        
       <!-- Education Card 4 -->
        <div class="education-card">
            <div>
                <span class="bullet"></span><h5 style="display: inline-block;">CSE 2312. Computer Organization & Assembly Language Programming</h5>
                <p><h5 style="display: inline-block;">Fall 2024</h5></p>
                <p>Computer organization from the software viewpoint, including instruction set architectures, memory addressing, integer and floating-point representation and arithmetic, instruction pipelining, cache, memory virtualization, and I/O. The relationship of higher-level programming languages to assembly language and instruction set architecture is also explored. Prerequisite: C<br>
                </p>
            </div>
        </div>
        
               <!-- Education Card 3 -->
        <div class="education-card">
            <div>
                <span class="bullet"></span><h5 style="display: inline-block;">CSE 5307. Programming Language Concepts</h5>
                <p><h5 style="display: inline-block; font-size: 16px;">Summer 2024</h5></p> <!-- Reduced the font size for Summer 2024 -->
                <p>Study and evaluation of concepts in programming language for modern computer systems. Programming projects are selected from string-based, symbolic, algorithmic, and object-oriented languages.<br>
                </p>
            </div>
        </div>
 


        <!-- Education Card 2 -->
        <div class="education-card">
            <div>
                <span class="bullet"></span><h5 style="display: inline-block;">CSE 1106. Introduction To Computer Science And Engineering</h5>
                <p><h5 style="display: inline-block;">Spring 2024</h5></p>
                <p>A practical approach to hands-on computer hardware and software systems in a laboratory environment. Students will be exposed to basic engineering concepts such as simple circuits, digital logic, embedded controllers, computer networking, software design, and Linux operating systems. Prerequisite: C<br>
                </p>
            </div>
        </div>



                <!-- Education Card 1 -->
        <div class="education-card">
            <div>
                <span class="bullet"></span><h5 style="display: inline-block;">CSE 1310. Introduction To Computers & Programming</h5>
                <p><h5 style="display: inline-block;">Fall 2023</h5></p>
                <p>An introduction to the computer, algorithmic process, and programming using basic control and data structures, using a procedural language. Prerequisite: C<br>
                </p>
            </div>
        </div>

        
    </div>

<footer>

</footer>
</body>
</html>
