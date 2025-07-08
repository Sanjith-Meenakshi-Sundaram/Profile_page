# Profile Page
## Date:7/7/2025
## Objective:

To design a simple Profile Page using HTML that displays a user's profile image, name, headings, and a short bio, suitable for personal or academic purposes.

## Tasks:

#### 1. Set Up the HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the basic structure.

Add an appropriate <title> such as "My Profile".

#### 2. Add Page Headings:

Insert a main heading using ```<h1>``` for the user's name.

Include subheadings such as ```<h2>``` or ```<h3>``` for titles or roles (e.g., "Student", "Web Developer").

#### 3. Insert a Profile Image:

Use the ```<img>``` tag to display the user’s profile picture.

Add alt text and set basic attributes like width and height.

#### 4. Include a Short Bio Section:

Add a paragraph using <p> to provide a short introduction or biography.

The content may include education, interests, or a personal statement.

#### 5. Organize Content Using HTML Elements:

Use ```<section>```, ```<div>```, or ```<article>``` for logical grouping.

Add a horizontal line (```<hr>```) to separate sections.

#### 6. Keep the Design HTML-Only:

Do not use CSS or JavaScript.

Focus on semantic HTML and readability.
## HTML Code:

<!DOCTYPE html>
<html>
<head>
  <title>My Profile</title>
</head>
<body>

  <h1>Meenakshi Sundaram D</h1>
  <h2>Student</h2>
  <h3>Web Developer</h3>

  <img src="212222060145.jpg" alt="Profile Picture" width="200" height="200">

  <hr>

  <section>
    <h2>About Me</h2>
    <p>
      I'm currently pursuing my degree in engineering. I enjoy building web applications and exploring how software can solve real-world problems. I like to keep learning and work on interesting side projects in my free time.
    </p>
  </section>

  <section>
    <h2>Skills</h2>
    <p>
      HTML, CSS, JavaScript, React, Node.js, MongoDB, Git, GitHub
    </p>
  </section>

  <section>
    <h2>Areas of Interest</h2>
    <p>
      Full Stack Development, Open Source Contributions, Competitive Programming
    </p>
  </section>

</body>
</html>


## Output:
![image](https://github.com/user-attachments/assets/9e38d50f-ddc7-464a-8e78-bb0108a9b94d)

## CSS Code:
body {
  background-color: beige;
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}
.profile-card {
  max-width: 600px;
  background-color: white;
  margin: 40px auto;
  padding: 30px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
  border-radius: 10px;
}
h1, h2, h3 {
  text-align: center;
  margin: 10px 0;
}
h1 {
  color: #2c3e50;
  font-size: 32px;
}
h2 {
  color: #34495e;
  font-size: 24px;
}
h3 {
  color: #666;
  font-size: 18px;
}
img {
  display: block;
  margin: 20px auto;
  width: 180px;
  height: 180px;
  border-radius: 50%;
}
section {
  margin-top: 30px;
  padding: 20px;
  background-color: #fafafa;
  border: 1px solid #ddd;
  border-radius: 12px;
}
p {
  line-height: 1.6;
  font-size: 16px;
  color: #333;
  margin: 0;
}
hr {
  margin: 30px 0;
  border: none;
  border-top: 1px solid #ccc;
}

## Output:
![image](https://github.com/user-attachments/assets/3cd9ccaa-a25e-46ac-8fd1-0a1b656f0777)



## Result:
A simple Profile Page using HTML that displays a user's profile image, name, headings, and a short bio, suitable for personal or academic purposes is designed successfully.
