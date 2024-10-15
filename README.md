<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SMEDIS</title>
    <style>
        /* SMEDIS Website Theme CSS */

        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        /* Header Styles */
        header {
            background: #007acc;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        header h2 {
            margin: 0;
            font-size: 1.2em;
            margin-top: 5px;
        }

        /* Image Styles */
        .organization-logos {
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 20px 0;
            flex-direction: column; /* Align the logos vertically */
        }

        .organization-logos img {
            max-width: 200px;
            margin: 0 20px;
        }

        .organization-logos p {
            text-align: center;
            margin: 0;
        }

        .main-image {
            text-align: center;
        }

        .main-image img {
            max-width: 300px; /* Adjust this as needed */
            margin-bottom: 20px;
        }

        /* Section Styles */
        section {
            padding: 20px;
            margin: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        section h2 {
            color: #007acc;
        }

        /* Coordinators Section */
        .coordinators {
            background: #e9f5ff;
            padding: 20px;
            margin: 20px;
            border-radius: 8px;
        }

        .coordinators ul {
            list-style: none;
            padding: 0;
        }

        .coordinators ul li {
            margin: 5px 0;
        }

        /* Flexbox for Images */
        .visualizations {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
        }

        .visualizations img {
            max-width: 45%; /* Adjust the size of the images */
            height: auto;
        }

        /* Footer Styles */
        footer {
            background: #007acc;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: relative;
            width: 100%; /* Ensure full-width footer */
            bottom: 0;
        }

        /* Responsive Styles */
        @media (max-width: 768px) {
            .organization-logos {
                flex-direction: column;
            }

            .organization-logos img {
                margin: 10px 0;
            }
            
            .visualizations img {
                max-width: 90%; /* Adjust width for smaller screens */
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>SMEDIS</h1>
        <h2>Social Media Dermatological Intervention Study</h2>
    </header>

    <!-- New main image added -->
    <div class="main-image">
        <img src="https://i.postimg.cc/dtHYyzxq/image-4.png" alt="SMEDIS Main Logo">
    </div>

    <div class="organization-logos">
        <div>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJ2AmVJyrYvpb-XayyiwPFoNZW5iPEdkSE9g&s" alt="NHS Logo">
        </div>
        <div>
            <img src="https://healthinnovationmanchester.com/wp-content/uploads/2018/10/MMU-post.png" alt="Manchester Metropolitan University Logo">
        </div>
    </div>
    
    <section>
        <h2>Research Support for the Social Media Dermatological Intervention Study (SMEDIS)</h2>
        <p>Our team is dedicated to providing comprehensive research support for the Social Media Dermatological Intervention Study (SMEDIS). Our primary focus is on assisting with research data collection and analysis, as well as disseminating our findings to relevant research groups and contacts. Our goal is to enhance understanding and safety of drug interactions through social media platforms.</p>
    </section>
    <section>
        <h2>Collaboration with Leading Medical Experts</h2>
        <p>We work closely with consultant dermatologists at The University of Manchester NHS and the Northern Care Alliance. These experts provide invaluable medical guidance on the use of JAK inhibitors, particularly in their application for dermatological interventions in young adults. Their collaboration ensures our research is both medically accurate and relevant.</p>
    </section>
    <section>
        <h2>Advancing Drug Safety Surveillance</h2>
        <p>Our research data scientists are pioneering new methods in drug safety surveillance on large online platforms such as TikTok and Reddit. By leveraging state-of-the-art techniques in natural language processing (NLP), graph models, large language models (LLM), and retrieval augmented graphs (RAG), we aim to detect and analyze drug safety issues more effectively.</p>
    </section>
    <section>
        <h2>Innovative Techniques in Social Media Analysis</h2>
        <p>The adoption of cutting-edge technologies allows us to explore and understand social media interactions related to drug safety in unprecedented ways. Our innovative approach helps us to identify trends, patterns, and potential safety concerns, contributing to the safer use of dermatological treatments.</p>
    </section>
    <section>
        <h2>Visualizations and Data Insights</h2>
        <p>Below are some of the key visualizations that provide insights into our research findings:</p>
        <div class="visualizations">
            <img src="https://i.postimg.cc/8C5mPX3J/image-1.png" alt="Graph 1 Description">
            <img src="https://i.postimg.cc/SRrn9kYy/Rinvoq.png" alt="Graph 2 Description">
            <img src="https://i.postimg.cc/L6DPYBjz/Upadacitinib.png" alt="Graph 3 Description">
        </div>
    </section>
    <section class="coordinators">
        <h2>Coordinators</h2>
        <h3>From Manchester Metropolitan University:</h3>
        <ul>
            <li>Dr. Seun Ajao</li>
            <li>Tawakalit Omolabake Agboola</li>
            <li>Muhammad Shumyl Akbar</li>
            <li>Oluwatosin Titilayo Akinsuli</li>
        </ul>
        <h3>From NHS/NCA:</h3>
        <ul>
            <li>Dr. Zenas Yiu</li>
        </ul>
    </section>
    <footer>
        <p>&copy; 2024 SMEDIS. All rights reserved.</p>
    </footer>
</body>
</html>
