# APEXPLANET_wd01
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ApexPlanetTask1 </title>
    <style>
      /* Styling for body section */
    body {
      margin: 0;
      padding: 0;
    }
    /* Style for head section */
    .header {
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 20px;
      background-color: #ffffff;
      border-bottom: 2px solid sandybrown;
      position: relative;
    }
/* style for logo section */
    .logo {
      position: absolute;
      left: 20px;
    }

    .logo img {
      max-height: 74px;
    }
/* style for company name section */
    .company-name {
      font-size: 28px;
      font-weight: bold;
      color: orange;
    }
/* style for nav links */
    nav{
        background-color:skyblue;
        text-align: center;
        padding: 9px 0;
    }
    nav a{
        color: black;
        text-decoration: none;
        margin: 0 20px;
        font-weight: 600;
        font-size: 1.1rem;
        letter-spacing: 0.5px;
    }
    /* appplying hover effect for nav links */
    nav a:hover {
        color: #ff6347;
        text-decoration: underline;
    }
    section {
        padding: 25px;
        margin: 20px auto;
        max-width: 900px;
        box-shadow: 0 2px 10px rgba(161, 11, 215, 0.737);
        transition: box-shadow 0.3s ease;
        }
    section:hover {
        box-shadow: 0 6px 18px rgb(212, 8, 8);
    }
    /* style for about section */ 
    #About {
        background-color: #5a44ea;
        padding: 28px;
        color:white;
    }
    /* style for StudentLogin section */
    #StudentLogin{
      background-color: #5a44ea;
      color: white;
    }
    /* style for footer section */
    .footer {
      background-color: #f1f1f1;
      text-align: center;
      padding: 15px;
      font-size: 14px;
      color: #333;
    }
    </style>
  </head>
<body>
  <!-- This is logo section -->
    <div class="header">
        <div class="logo">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRdn3YltXeO1Bt0psUkaJWgjlDZ-A_Qp6Njrg&s">
        </div>
        <div class="company-name">
          ADITYA UNIVERSITY
        </div>
      </div>
      <!-- This is nav section -->
    <nav>
        <a href="#Home">Home</a> |
        <a href="#About">About</a> |
        <a href="#Internships">Internships</a> |
        <a href="#StudentLogin">StudentLogin</a>
    </nav>
    <!-- this is home section -->
    <section id="Home">
        <h4>WELCOME TO ADITYA UNIVERSITY</h4>
        <p>Embark on a transformative journey towards academic excellence and personal growth. At Aditya University, education is more than a degree it's a pathway to unlocking your full potential and making a meaningful impact. The campus, set in a vibrant environment, attracts students from more than 20 countries, creating a diverse and enriching academic experience. This multicultural atmosphere fosters collaboration and innovation, preparing students for a global workforce.</p>
    </section>
    <!-- this is about section -->
    <section id="About">
        <h2>About</h2>
        <p>Aditya University is a State Private University formed under the Andhra Pradesh Private Universities Act, 2016. It has evolved from the well-established Aditya Engineering College in Surampalem, Kakinada District, Andhra Pradesh. Aditya University is committed to provide quality higher education with global standards. Programs are well crafted to blend academic rigor with practical relevance, equipping students to effectively address both societal and industrial challenges. </p>
    </section>
    <!-- this is internships section -->
    <section id="Internships">
        <h2>Internships</h2>
        <p>Join To Our Internship Program. With Provide ADITYA UNIVERSITY Approved Certificate. Digital Marketing Services.</p>
        <h5>Web Development (HTML, CSS & JAVASCRIPT) Internship:<input type="button" onclick="showAlert1()" value="Apply now"></h5>
        <h5>Web Development (PHP & MySQL) Internship:<input type="button" onclick="showAlert1()" value="Apply now"></h5>
        <h5>App Development Internship:<input type="button" onclick="showAlert1()" value="Apply now"></h5>
          
        <input type="button" onclick="showAlert2()" value="View more Info">
    </section>
    <!-- this is StudentLogin section -->
    <section id="StudentLogin">
      <h2>StudentLogin</h2>
      <center> 
        <form>
        Enter your Rollno:<input type="text"><br><br>
        Enter ur Password: <input type="text"><br><br>
       <input type="button" onclick="showAlert()" value="login">
      </form>
    </center>
    </section>
    <!-- this is footer section -->
    <footer class="footer">
      &copy; © 2024 Aditya University. All Rights Reserved
    </footer>
    <script>
      // js code for submit button
      function showAlert() {
      alert("Succesfully login..!!");
    }
    // js code for apply button
    function showAlert1() {
      alert("Successfully applied for an internship..!!");
    }
    // js code for view more button
    function showAlert2() {
      alert("To know more about the internships,visit our official page..!!");
    }
    </script>
</body>
</html>
