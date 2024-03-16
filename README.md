<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mohith Pulavarthi - Business Analyst</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      background-color: #ffcc00;
      color: #333;
      text-align: center;
      padding: 20px;
      position: relative;
    }

    .profile-img {
      border-radius: 50%;
      width: 150px;
      height: 150px;
      float: left top; /* Align profile picture to the left */
    }

    .logo-img {
      width: 100px;
      height: 50px;
      margin: 0 5px;
    }

    h1 {
      font-size: 36px;
      margin: 0;
    }

    h2 {
      font-size: 24px;
      color: #ff6666;
    }

    .container {
      max-width: 1200px;
      margin: auto;
      padding: 20px;
    }

    .section {
      background-color: #fff;
      margin-bottom: 30px;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 20px;
    }

    .skill {
      background-color: #66cccc;
      border-radius: 8px;
      padding: 10px 20px;
      margin: 5px;
      text-align: center;
      color: #fff;
      font-weight: bold;
    }

    .projects {
      list-style: none;
      padding: 0;
      display: flex;
      flex-direction: column;
    }

    .project {
      margin-bottom: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      display: flex;
      animation: fade-in 0.5s forwards;
    }

    .project img {
      width: 200px;
      height: auto;
    }

    .project-info {
      padding: 20px;
      background-color: #f9f9f9;
      flex: 1;
    }

    .education {
      margin-top: 30px;
      font-family: Arial, sans-serif;
    }

    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 10px 0;
    }

    @keyframes fade-in {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .pdf-download {
      margin-top: 10px;
    }

    .pdf-download a {
      text-decoration: none;
      color: #333;
      background-color: #ffcc00;
      padding: 5px 10px;
      border-radius: 5px;
    }

    .pdf-download a:hover {
      background-color: #ff9933;
    }

    .certificates {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      margin-top: 20px;
    }

    .certificate {
      margin: 10px;
      text-align: center;
    }

    .certificate img {
      width: 200px;
      height: auto;
      opacity: 0.5; /* Light opacity for certificate image */
    }

    .certificates-heading {
      text-align: left;
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <img src="myimage.jpg" alt="Profile Picture" class="profile-img">
      <div style="position: absolute; top: 20px; right: 20px; text-align: right;">
        <div style="display: flex; align-items: center;">
          <img src="purdue university.png" alt="Purdue University" class="logo-img">
          <span style="font-size: 18px; font-family: Arial, sans-serif; color: black; font-weight: bold;">Purdue University</span>
        </div>
        <br>
        <div style="display: flex; align-items: center;">
          <img src="Simplilearn.jpg" alt="Simplilearn.jpg" class="logo-img">
          <span style="font-size: 18px; font-family: Arial, sans-serif; color: black; font-weight: bold;">Simplilearn</span>
        </div>
      </div>
      <h1 style="color: #333;">Mohith Pulavarthi</h1>
      <p>Business Analyst</p>
    </div>
  </header>
  <div class="container">
    <div class="section">
      <h2>Summary</h2>
      <p>I am a versatile Business Analyst specialized in data analytics. With certifications in business analytics, SQL, and data visualization, I have successfully developed projects such as implementing canteen ordering systems for Unilever and developing digital payment features for WhatsApp Pay. With a bachelor's degree in commerce and hands-on experience, I can drive strategic insights. I’m ready to grow and provide effective solutions.</p>
    </div>
    <div class="section">
      <h2>Skills</h2>
      <div class="skills">
        <div class="skill">Power BI</div>
        <div class="skill">Tableau</div>
        <div class="skill">Jira</div>
        <div class="skill">MS Excel</div>
        <div class="skill">SQL</div>
        <div class="skill">Data Visualization</div>
        <div class="skill">Agile</div>
        <div class="skill">Report Making</div>
        <div class="skill">Requirement LCM</div>
        <div class="skill">Business Acumen</div>
        <div class="skill">Collaboration</div>
        <div class="skill">Critical Thinking</div>
        <div class="skill">Project Management</div>
        <div class="skill">Stakeholder Management</div>
        <div class="skill">Adaptability</div>
        <div class="skill">Problem Solving</div>
        <div class="skill">Customer Feedback Handling</div>
      </div>
    </div>
    <div class="section">
      <h2>Projects</h2>
      <ul class="projects">
        <li class="project">
          <img src="zomato.png" alt="Zomato Data Analysis">
          <div class="project-info">
            <h3>Zomato Data Analysis with Power BI</h3>
            <p>Completed a comprehensive Power BI project for Zomato, a global restaurant aggregation and meal delivery service. The objective was to examine and assess business performance by consolidating data from multiple Excel files. Key project tasks included data import, transformation, and visualization for easy accessibility and assessment.</p>
            <div class="pdf-download">
              <a href="4965784_5183_7699_1_1700808734_zomato project.pdf" target="_blank">Download PDF</a>
            </div>
          </div>
        </li>
        <!-- Add remaining projects here -->
        <li class="project">
          <img src="whatsapp pay.png" alt="WhatsApp Pay Feature Implementation">
          <div class="project-info">
            <h3>WhatsApp Pay Feature Implementation</h3>
            <p>Had the unique opportunity to collaborate with Facebook as a Business Analyst on a groundbreaking project, WhatsApp Pay, designed to revolutionize digital payments. This feature seamlessly integrated secure payment functionality into WhatsApp, serving a global user base of 2 billion.</p>
            <div class="pdf-download">
              <a href="4965784_3988_3899_1_1689364103_Whatsapp Pay Project by mohith_pdf.pdf" target="_blank">Download PDF</a>
            </div>
          </div>
        </li>
        <li class="project">
          <img src="uniliver.png" alt="Canteen Ordering System for Unilever">
          <div class="project-info">
            <h3>Canteen Ordering System for Unilever</h3>
            <p>Led the requirements capture process for the Canteen Ordering System at Unilever, a project aimed at streamlining food ordering and reducing inefficiencies in their UK offices. Achieved a 30% reduction in canteen food wastage within six months following the initial release, exceeding the target of 15%.</p>
            <div class="pdf-download">
              <a href="4965784_3988_3897_4_1689364082_uniliver canteen ordering system.pdf" target="_blank">Download PDF</a>
            </div>
          </div>
        </li>
        <li class="project">
          <img src="airline.jpg" alt="Airline Database Management Project">
          <div class="project-info">
            <h3>Airline Database Management Project</h3>
            <p>As a Database Administrator (DBA) expert, led a critical project at Air Cargo, an aviation company, aimed at optimizing database management to enhance operational efficiency. The project focused on identifying regular customers, analyzing busiest routes, and generating detailed ticket sales reports to improve the customer experience and operational effectiveness.</p>
            <div class="pdf-download">
              <a href="AIR CARGO ANALYSIS by mohith.pdf" target="_blank">Download PDF</a>
            </div>
          </div>
        </li>
        <li class="project">
          <img src="restaurent managment.jpg" alt="Restaurant Management System">
          <div class="project-info">
            <h3>Restaurant Management System</h3>
            <p>Collaborated with a celebrity chef to develop a Restaurant Management System, streamlining day-to-day operations, including menu management, table reservations, and sales reporting. Implemented features such as menu categorization, table reservation system, and comprehensive sales reporting.</p>
            <div class="pdf-download">
              <a href="restaurant_management_system.pdf" target="_blank">Download PDF</a>
            </div>
          </div>
        </li>
        <li class="project">
          <img src="sales dashboard excel.png" alt="Sales Dashboard in Excel">
          <div class="project-info">
            <h3>Designing a Sales Dashboard in Excel</h3>
            <p>Created a sales dashboard in Excel for analyzing sales based on various product categories. The dashboard allowed users to visualize sales trends, compare regions, and track performance metrics. Implemented features such as monthly sales tables, region-wise sales analysis, and user-controlled product category filters.</p>
            <div class="pdf-download">
              <a href="4965784_3992_6434_4_1691830140_ecommerce sales dashboard project.pdf" target="_blank">Download PDF</a>
            </div>
          </div>
        </li>
        <li class="project">
          <img src="sales comparision.jpg" alt="Comparison of Region Based on Sales">
          <div class="project-info">
            <h3>Comparison of Region Based on Sales</h3>
            <p>Developed a dashboard to compare sales between two regions for a leading organization. Utilized data visualization techniques to analyze sales performance, identify trends, and suggest improvements. Implemented features such as parameterized region selection, sales summary by region, and comparative analysis charts.</p>
            <div class="pdf-download">
              <a href="4965784_3991_6437_1_1707973671_Comparison of Region Based on Sales.pdf" target="_blank">Download PDF</a>
            </div>
          </div>
        </li>
      </ul>
    </div>
    <div class="section education">
      <h2>Education</h2>
      <p style="font-family: Arial, sans-serif; font-size: 16px; color: #333;">Purdue University, Business Analyst Program (June 2023 - Feb 2024)</p>
      <p style="font-family: Arial, sans-serif; font-size: 16px; color: #333;">Bachelor of Commerce in Computer Science and Accounting - Andhra University<br>
      CGPA: 7/10</p>
      <p style="font-family: Arial, sans-serif; font-size: 16px; color: #333;">12th Grade: Major in Mathematics, Physics, and Chemistry (MPC) - Adhitya<br>
      CGPA: 6.89/10</p>
      <p style="font-family: Arial, sans-serif; font-size: 16px; color: #333;">10th Grade - St.Augustine.E.M. High School<br>
      CGPA: 8.3/10</p>
    </div>
    <div class="section">
      <h2 class="certificates-heading">Certifications</h2>
      <div class="certificates">
        <div class="certificate">
          <img src="pg.png" alt="Certification 1">
          <div class="pdf-download">
            <a href="pg of purdue university.pdf" target="_blank">Download PDF</a>
          </div>
        </div>
        <div class="certificate">
          <img src="cbap.png" alt="Certification 2">
          <div class="pdf-download">
            <a href="cbap.pdf" target="_blank">Download PDF</a>
          </div>
        </div>
        <div class="certificate">
          <img src="excel.png" alt="Certification 3">
          <div class="pdf-download">
            <a href="excel.pdf" target="_blank">Download PDF</a>
          </div>
        </div>
        <div class="certificate">
          <img src="sql.png" alt="Certification 4">
          <div class="pdf-download">
            <a href="sql.pdf" target="_blank">Download PDF</a>
          </div>
        </div>
        <div class="certificate">
          <img src="powerbi.png" alt="Certification 5">
          <div class="pdf-download">
            <a href="powerbi.pdf" target="_blank">Download PDF</a>
          </div>
        </div>
        <div class="certificate">
          <img src="tablue.png" alt="Certification 6">
          <div class="pdf-download">
            <a href="tablue.pdf" target="_blank">Download PDF</a>
          </div>
        </div>
        <div class="certificate">
          <img src="capstone.png" alt="Certification 7">
          <div class="pdf-download">
            <a href="capstone.pdf" target="_blank">Download PDF</a>
          </div>
        </div>
      </div>
    </div>
  </div>
  <footer>
    <div class="container">
      <p>+919515629981 | p.mohith79@gmail.com | Hyderabad, IN | <a href="https://www.linkedin.com/in/pulavarthimohith/">LinkedIn</a></p>
    </div>
  </footer>
</body>
</html>
