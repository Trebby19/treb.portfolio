<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scaled=1.0">
    <title>Self Portfolio</title>
    <link rel="icon" href="treb1.jpg">
    <link rel="stylesheet" href="style2.css">
</head>
<body>
    <div class="self">
        <h1>SELF INTRODUCTION</h1>
        <img src="treb1.jpg" class="character">
        <a href="https://www.facebook.com/"><h2>Kilbert S.<span>Villanueva</span></h2></a>
    </div>

    <div class="social">
        <a href="https://www.youtube.com/channel/UCj9-2kAU0zwcoKs_ubcu1bA" target="_blank"><img src="youtube.png" class="youtube">"</a>
    </div>

    <div class="self_introduction">
        <h3>Self Introduction</h3>
        <p>
            Hi there! I'm Kilbert Villanueva, and I'm a Bachelor of Science in Information Technology (BSIT) student right now.
            <br>I have a strong interest in how technology is affecting our planet.
            <br>The countless opportunities IT presents to resolve difficult issues and enhance people's lives are what drew me to the field.
            <br>I chose this course with the intention of gaining the abilities and information required to succeed in a variety of fields, including data analysis, cybersecurity, and software development.
            <br>I think IT is the ideal fusion of imagination, ingenuity, and reason, and it perfectly fits my ambitions and desires.
            <br>I appreciate you stopping by my webpage!
        </p>

    </div>

    <div class="education_background">
        <h4>Education Background</h4>
        <table>
            <thead>
                <tr>
                    <th>Level</th>
                    <th>Name of School</th>
                    <th>Basic Education/Degree/Course</th>
                    <th>Period of <br>Attendance</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Elementary</td>
                    <td>Taguig Elementary School</td>
                    <td>Primary Education</td>
                    <td>1992-1998</td>
                </tr>
                <tr>
                    <td>Secondary</td>
                    <td>Pateros National High School</td>
                    <td>Secondary Education</td>
                    <td>1998-2002</td>
                </tr>
                <tr>
                    <td>College</td>
                    <td>Marinduque State College</td>
                    <td>Bachelor of Science in Information Technology</td>
                    <td>2022-2026</td>
                </tr>
            </tbody>
        </table>

    <div class="Expertise">
        <h4>Expertise</h4>
        <div class="skills">
            <ul>
                <li>Programming: Familliar with Python, html-css and C#</li>
                <li>Problem-Solving Skills</li>
                <li>Database Management</li>
                <li>Networking Basics</li>
                <li>Teamwork and Communication</li>
            </ul>
        </div>
    </div>

    <div class="background">
        <h4>Background on Information Technology</h4>
        <p>
            I'm a second-year IT student who is presently laying a solid foundation in a number of information technology-related areas. I'm studying database administration with  web development using HTML, CSS, and JavaScript, and programming languages like Python and Java. Additionally, I'm learning more about IT support and networking principles.
            I am honing my practical skills and teamwork qualities through practical projects and group work. My love of technology motivates me to keep up with developments and trends in the field. As I pursue my education, I want to learn more and get involved in more specific IT fields.
        </p>
    </div>

    <div class="application">
        <h3>Applications used in Studying</h3>
        <div class="list">
            <ol>
                <li>Collaboration Tools</li>
                <li>Online Learning Platforms</li>
                <li>Version Control Systems</li>
                <li>Office Applications</li>
                <li>Integrated Development Environments (IDEs)</li>
            </ol>




            *{
    margin: 0;
    padding: 0;
    font-family: Arial;
    box-sizing: border-box;
}

body{
    padding: 20px;
    display: flex;
    min-height: 100vh;
    background-image: url(image.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    background-attachment: fixed;
    justify-content: center;
    align-items: center;
    color: #f2f5ef;
}

.social{
    padding: 20px;
    width: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    gap: 30px;
}
.social img{
    margin-top: auto;
    width: 75px;
    background-color: rgb(131, 154, 211);
    box-shadow: 0 15px 26.5px 0 rgb(2, 245, 225);
    transition: 0.5s ease;
    background: linear-gradient(135deg, rgba(1, 24, 41, 0.889) 0%, rgb(238, 232, 233) 100%);
    border-radius: 45%;
}
.social img:hover{
    transform: scale(1.1,1.1);
}

.container{
    position: relative;
    display: flex;
    padding: 20px;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 3000%;
    height: 100%;
    background-color: rgba(165, 156, 156, 0.15);
    border-radius: 25px;
    box-shadow: 0 15px 30px 0 rgb(34, 26, 26);
    border: 2px solid white;
    box-shadow: 0 15px 26.5px 0 rgb(2, 245, 225);  
}
.head{
    display: flex;
    flex-direction: column;
    position: relative;
    align-items: center;
    border-radius: 20px 20px 0 0;
    margin-bottom: 60px;   
}
.head h1{
    font-size: 30px;
    font-style: inherit;
    font-weight: bolder;
    margin-top: 20px;
    
}

.head img{
    margin:30px 0 0 0;
    width: 150px;
    height: 150px;
    border: 2px solid white;
    padding: 2px;
    border-radius: 100%;
    box-shadow: 0 15px 26.5px 0 rgb(0, 255, 234);
    transition: 0.5s ease;
}
.head a{
    font-size: 30px;
    font-family: arial, sans-serif;
    margin: 30px 0;
    text-decoration: none;
    color: rgb(225, 235, 225);
    font-weight: 600;
    transition: 0.5s ease;
}

p{
    margin: 20px 0 50px 0;
    letter-spacing: 1.5px;
    text-align: justify;
    text-indent: 50px;
    text-align: justify;
    width: 1850px;
}


h3{
    text-transform: uppercase;
    border-radius: 10px;
    padding-left: 20px;
    background: linear-gradient(135deg, rgba(1, 24, 41, 0.889) 0%, rgb(238, 232, 233) 100%);
}
.container .educational h4{
    text-transform: uppercase;
    border-radius: 10px;
    padding-left: 20px;
    background: linear-gradient(135deg, rgba(1, 24, 41, 0.889) 0%, rgb(238, 232, 233) 100%);
}
.container .educational{
    margin-bottom: 50px;
}
.container .educational table{
    margin-top: 20px;
    width: 1850px;
    font-family: Arial;
    border-collapse: collapse border;
    
}
.container .educational table,th,td{
    border: 2px solid rgb(178, 178, 199);
    text-align: center;
    padding: 20px;
}
th{
    background: rgba(188, 207, 200, 0.25);
}

.container .expertise{
    position: relative;
    width: 100%;
    margin-bottom: 60px;
}
.container .expertise ul{
    list-style-type: square;
}
ul{
    margin-top: 20px;
    padding-left: 20px;
}
.container .IT-background{
    letter-spacing: 1.5px;
    text-align: justify;
    text-indent: 50px 0;
}
.container .IT-background h4{
    text-transform: uppercase;
    border-radius: 10px;
    padding-left: 20px;
    background: linear-gradient(135deg, rgba(1, 24, 41, 0.889) 0%, rgb(238, 232, 233) 100%);
}
.container .Applications{
    width: 100%;

}
.container .Applications h4{
    text-transform: uppercase;
    border-radius: 10px;
    padding-left: 20px;
    background: linear-gradient(135deg, rgba(1, 24, 41, 0.889) 0%, rgb(238, 232, 233) 100%);
}
.container .Applications ul{
    list-style: decimal;
    margin-top: 20px;
    padding-left: 20px;
}
h3 h4{
    text-align: left;
    font-family: Arial;
}
 
.head a:hover{
    transform: scale(1.1);
    transition: 0.5s ease;
    color: #050c0c;
    border: 2px solid white;
    background-color: rgb(89, 164, 194);
    border-radius: 8px;
    color: azure;
}
        </div>
    </div>
</body>
</html>
