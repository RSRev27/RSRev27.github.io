---
permalink: /
redirect_from: 
  - /about/
  - /about.html
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Venkata Ravi Teja Sandram</title>
    <style>
        /* General Body Style */
        body {
            font-family: 'Georgia', serif;
            background-color: #f0f7fa;
            margin: 0;
            padding: 0;
            color: #333;
        }

        /* Main content container */
        .content {
            max-width: 900px;
            margin: 30px auto;
            background-color: #ffffff;
            border-radius: 10px;
            padding: 40px;
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
            text-align: justify;
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

        /* Card-like Layout for Interests and Education */
        .certification-layout {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .certification-card {
            display: flex;
            align-items: center;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .certification-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
        }

        .certification-card img {
            width: 40px;
            height: 40px;
            margin-right: 20px;
        }

        .certification-card h4 {
            font-size: 20px;
            margin: 0;
            color: #333;
        }

        .certification-card p {
            margin: 5px 0 0;
            font-size: 16px;
            color: #666;
        }

        /* Separator for Education Section */
        .separator {
            grid-column: 1 / -1;
            text-align: center;
            font-size: 22px;
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

        /* Footer */
        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 14px;
            color: #aaa;
        }

        /* Aesthetic Enhancements */
        .content .cv-link {
            display: inline-block;
            background-color: #007acc;
            color: #fff;
            padding: 12px 24px;
            border-radius: 5px;
            margin-top: 20px;
            text-decoration: none;
        }

        .content .cv-link:hover {
            background-color: #0056b3;
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

<div class="content">
    <!-- Biography Section -->
    <h2>Biography</h2>
    <p>I’m a Master student in the Computer Science department at The University of Texas at Arlington. </p>
    
    <p>Before starting my masters, I accrued over 1 years of professional experience in India in numerous critical roles, including Data Engineer at <a href="https://www.bracbank.com/en/">ADP</a> and Analyst and testing expert for several Oracle Clients (<a href="https://www.cirt.gov.bd/">BGD e-GOV CIRT</a>) funded by companies like Deliotte and ADP. Additionally, I gained significant expertise in React js and Django, Machine Learning , and Large language models through my work with <a href="https://www.ibm.com/us-en/">Twist Lab and ciruculum</a> and <a href="https://kpmg.com/bd/en/home.html/">KPMG Bangladesh</a>, one of the Big Four accounting firms.</p>
    
    <a href="#" class="cv-link">Download my resumé / CV</a>

    <!-- Card Layout for Interests and Education -->
    <div class="certification-layout">
    <!-- Education Section Separator -->
        <div class="separator">Interests</div>
        <!-- Interests Card -->
        <div class="certification-card">
            <img src="https://img.icons8.com/ios-filled/50/000000/learning.png" alt="Interests Icon">
            <div>
                <h4>Interests</h4>
                <p>Cloud Computing, Information and Cyber Security, Microservices, High Performance Computing (HPC), HPC in the Cloud, Machine Learning for Systems, Distributed Systems</p>
            </div>
        </div>

        <!-- Education Section Separator -->
        <div class="separator">Education</div>

        <!-- Education Card 1 -->
        <div class="certification-card">
            <img src="https://img.icons8.com/ios-filled/50/000000/graduation-cap.png" alt="Graduation Cap">
            <div>
                <h4>Masters in Computer Science and Engineering</h4>
                <p>August 2028 (Expected)<br><small><a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/">The University of Texas at Arlington (UTA)</a></small></p>
            </div>
        </div>

        <!-- Education Card 2 -->
        <div class="certification-card">
            <img src="https://img.icons8.com/ios-filled/50/000000/graduation-cap.png" alt="Graduation Cap">
            <div>
                <h4>MSc in Information Systems Security (MISS)</h4>
                <p>2018<br><small><a href="https://bup.edu.bd/academics/academic_details/464">Bangladesh University of Professionals (BUP)</a></small></p>
            </div>
        </div>

        <!-- Education Card 3 -->
        <div class="certification-card">
            <img src="https://img.icons8.com/ios-filled/50/000000/graduation-cap.png" alt="Graduation Cap">
            <div>
                <h4>MBA in Management Information Systems</h4>
                <p>2016<br><small><a href="https://www.fbs-du.com/mis.php">University of Dhaka (DU)</a></small></p>
            </div>
        </div>

        <!-- Education Card 4 -->
        <div class="certification-card">
            <img src="https://img.icons8.com/ios-filled/50/000000/graduation-cap.png" alt="Graduation Cap">
            <div>
                <h4>BSc in Computer Science and Engineering</h4>
                <p>2011<br><small><a href="https://cse.buet.ac.bd/">Bangladesh University of Engineering and Technology (BUET)</a></small></p>
            </div>
        </div>
    </div>
</div>

<footer>
    © 2024 by Mohammad Shahedur Rahman. All rights reserved.
</footer>

</body>
</html>
