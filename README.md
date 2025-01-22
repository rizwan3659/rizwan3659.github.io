<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Rizwan Alam</title>
    <style>
        /* General body styling */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f7f7f7;
            color: #333;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        /* Header Styling */
        header {
            background-color: #007BFF; /* Blue background */
            color: #fff;
            padding: 30px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.2rem;
            font-weight: 300;
        }

        /* Section Styling */
        section {
            padding: 25px;
            margin: 20px auto;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            max-width: 900px;
        }

        section h2 {
            color: #333;
            font-size: 2rem;
            text-align: center;
            margin-bottom: 20px;
        }

        section p {
            font-size: 1.1rem;
            text-align: justify;
            color: #555;
        }

        /* Courses list styling */
        .courses ul {
            list-style-type: none;
            padding: 0;
            text-align: center;
        }
        .courses li {
            display: inline-block;
            background-color: #6c757d;
            color: #fff;
            padding: 12px 25px;
            margin: 10px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: background-color 0.3s, transform 0.3s;
        }

        .courses li a {
            color: white;
            text-decoration: none;
            font-size: 1.1rem;
        }

        .courses li:hover {
            background-color: #28a745; /* Green hover */
            transform: translateY(-5px);
        }

        .courses li:hover a {
            color: #f8f9fa;
            text-decoration: underline;
        }

        /* Footer Styling */
        footer {
            background-color: #343a40;
            color: #fff;
            text-align: center;
            padding: 15px;
            position: fixed;
            width: 100%;
            bottom: 0;
            box-shadow: 0 -4px 10px rgba(0, 0, 0, 0.1);
        }

        footer p {
            margin: 0;
        }

        /* Link Hover effect */
        a:hover {
            color: #007BFF;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Rizwan Alam</h1>
        <p>Computer Science Educator | Mentor | Innovator</p>
    </header>

    <section>
        <h2>About Me</h2>
        <p>
            With 13 years of expertise in System Design, Data Structures, Algorithms, Distributed Systems, Cloud Computing, and Telecom solutions, I have contributed to flagship programs like 5G, BharatNet, Digital India, and Smart Cities, enhancing public life. As a Computer Science graduate from NITK Surathkal and Scientist D at C-DOT, I focus on advancing 4G/5G mobile packet core performance and exploring next-gen NFV and SDN-based designs. I tutor topics like Operating Systems, Networking, DSA, C++, C, Java, Python, and System Design, helping students and professionals excel in coding and system design interviews.
        </p>
    </section>

    <section class="courses">
        <h2>Courses</h2>
        <ul>
            <li><a href="/operating-systems.html">Operating Systems</a></li>
            <li><a href="data_analysis_using_python/data-analysis.html">Data Analysis and Machine Learning using Python</a></li>
            <li><a href="/cpp.html">C++</a></li>
             <li><a href="/cpp.html">C</a></li>
            <li><a href="/system-design.html">System Design</a></li>
            <li><a href="/data-structures-algorithms.html">Data Structures and Algorithms</a></li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 Rizwan Alam. All rights reserved.</p>
    </footer>
</body>
</html>
