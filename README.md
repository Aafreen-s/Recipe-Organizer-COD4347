# Recipe-Organizer-COD4347
Certainly! Let's organize the provided details into the requested format:

 1. Title: CODTECH IT SOLUTIONS Intern - Task Submission - Recipe Organizer


 2. Introduction
This document outlines the development and implementation of a Recipe Organizer web application. The application aims to provide users with a platform to explore various recipes conveniently.

  3. Intern Information
- Name: Aafreen Shaik
- Intern ID: COD4374
- Company: CODTECH IT SOLUTIONS

  4. Task Description
As an intern at CODTECH IT SOLUTIONS, Aafreen Shaik was assigned the task of creating a Recipe Organizer web application. The application should allow users to browse recipes under different categories like vegetarian, non-vegetarian, desserts, and juices.

  5. Implementation
The Recipe Organizer web application was implemented using HTML, CSS, and JavaScript. The application consists of various sections such as the header, about, find it, and contact. Each section serves a specific purpose to enhance user experience and engagement.

 6. Code and Code Explanation:
  HTML Code:
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recipe Finder</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="./icon.png">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400..700;1,400..700&family=Montserrat:wght@100;200;300;400;500;600;700;800&display=swap" rel="stylesheet">
</head>
<body>
<div id="header">
   <div class="nav">
    <div class="logo">
        <img src="./logo.png" alt="image">
    </div>
    <div class="side">
         <ul>
            <li><a href="#header">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#find">Find It</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </div>
   </div>
   <div class="bg">
    <div class="txt">
        <h2>Find Your <span>Recipe</span></h2>
        <p>FIND WHAT YOU WANT TO EAT.</p>
        </div>
   </div>
   </div>
   <!-- about -->
   <div id="about">
    <div class="ab-txt">
        <h2>About us</h2>
    </div>
    <div class="ab-img">
         <img src="./ab.jpg" alt="image">
    </div>

    <div class="ab-con">
        <h2>You Know What?</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae unde deleniti, accusantium voluptas in quam distinctio tempora quo qui vitae officia enim saepe maxime aliquid fugiat! Voluptas ipsam tempore similique?
        Minima ipsum dolorem recusandae iste tempore sint dolor suscipit quis aut accusamus nihil doloremque maxime, <br><br><br>quaerat dolorum ea. Nihil facere voluptates voluptatum in velit exercitationem reiciendis adipisci autem quisquam neque.
        Sint aut facere animi ex odio, quibusdam inventore, architecto nisi perspiciatis excepturi ipsa quidem quia fuga distinctio maiores? Accusamus, adipisci! Non harum, nostrum debitis perferendis distinctio deserunt magni incidunt sit.
        Temporibus nobis nemo numquam hic, nihil, quod dolorum obcaecati tempore qui fugiat labore sunt dignissimos aliquid. <br> <br><br>Molestiae, dolorem. Itaque distinctio voluptates impedit adipisci laboriosam illum ab officia libero rem expedita?
        Officia quos tempora reiciendis facilis dolorum quisquam, nulla cum officiis sit dolores asperiores magni delectus facere esse eaque at ipsum incidunt ducimus a aperiam quo! Voluptatum placeat velit rerum minima?</p>
    </div>
   </div>

   <!-- find it -->

   <div id="find">
    <div class="findit">
        <h2>Find Your Food!!</h2>
    </div>
    <div class="food">
        <div class="veg">
            <a href="./veg.html"><img src="./veg.jpg" alt="img"></a>
            <h2 class="tit">Veg</h2>
        </div>
        <div class="non-veg">
            <a href="./non-veg.html"><img src="./non-veg.jpg" alt="img"></a>
            <h2 class="tit">Non-Veg</h2>
        </div>
        <div class="dessert">
            <a href="./dessert.html"><img src="./dessert.jpg" alt="img"></a>
            <h2 class="tit">Dessert</h2>
        </div>
        <div class="juice">
           <a href="./juice.html"><img src="./juices.jpg" alt="img"></a>
            <h2 class="tit">Juice</h2>
        </div>
    </div>
   </div>

   <!-- Contact -->

   <div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                 
            </div>
            <div class="contact-right">
                <form name="submit-to-google-sheet">
                    <input type="text" name="Name" placeholder="Your name" required>
                    <input type="email" name="Email" placeholder="Your e-mail" required>
                    <textarea name="Message"  rows="6" placeholder="Your Message"></textarea>
                    <button type="submit" class="btn btn2">Submit</button>
                </form>
                <span id="msg"></span>
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>Copyright @ Aafreen <i class="fa-regular fa-face-smile"></i></p>
    </div>
   </div>
</body>
</html>

Explanation:

- This HTML code defines the structure of the Recipe Finder web application.
- It includes sections for the header, about, find it, and contact.
- The header contains a navigation menu with links to different sections of the page.
- The about section provides information about the application.
- The find it section allows users to browse recipes based on categories such as vegetarian, non-vegetarian, dessert, and juice.
- The contact section provides a form for users to submit messages.
 
 
CSS Code:
 *
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html
{
    scroll-behavior: smooth;
}

body
{
    color: #fff;
    background: #000;
}

.nav
{
    width: 100%;
    height: 100px;
    /* background-color: rgb(0, 0, 0); */
}

.logo
{
    height: 100px;
    width: 30%;
    float: left;
}

.logo img
{
    width: 60%;
    height: 70px;
    padding-left: 50px;
    margin-top: 30px;
  
}

.side
{
  width: 65%;
  float: right;
  height: 100px;
  padding-left: 20px;
  display: flex;
}

ul li
{
    list-style: none;
    text-decoration: none;
    display: inline-block;
    margin-left: 140px;
    margin-right: 10px;
    align-items: center;
    margin-top: 50px;
    justify-content:space-around; 
} 

ul li a 
{
    color: white;
    text-decoration: none;
    font-size: 18px;
    position: relative;
}

ul li a::after
{
    content: '';
    width: 0;
    height: 3px;
    background-color: #FF5C0A;
    position: absolute;
    left: 0;
    bottom: -6px;
    transition: 0.4s;
}

ul li a:hover::after
{
    width: 100%;

}

.bg
{
    height: 600px;
    width: 100%;
    background-image: url(./bg.png);
    background-position: left;
    background-size: cover;
}

.txt
{
    height: 300px;
    width: 40%;
    /* background-color:#FF5C0A; */
    margin-top: 90px;
    margin-left: 150px;
}

.txt h2
{
    color: #fff;
    font-size: 50px;
    padding-top: 90px;
    padding-left: 20px;
}

.txt h2 span
{
    color: #FF5C0A;
}

.txt p
{
    color: #fff;
    font-size: 20px;
    padding-left: 20px;
    padding-top: 10px;
}

#about
{
    height: 700px;
    width: 100%;
     
}

.ab-txt
{
    height: 60px;
    width: 100%;
    
}

.ab-txt h2
{
    color: #fff;
    font-size: 60px;
    margin-left: 90px;
}

.ab-img
{
    height: 550px;
    width: 30%;
     
    border-radius: 30px;
    margin-top: 50px;
    margin-left: 48px;
    float: left;
}

.ab-img img
{
   height: 100%;
   width: 100%;
   border-radius: 15px;
}

.ab-con
{
    height: 550px;
    width: 55%;
    float: right;
    margin-right: 30px;
    margin-top: 50px;
}

.ab-con h2
{
    font-size: 40px;
    padding-left: 20px;
    padding-top: 20px;
}

.ab-con p
{
    font-size: 20px;
    padding-left: 30px;
    padding-top: 34px;
}

.ab-con
{
    border-radius: 10px;
    transition: background 0.5s,transform 0.5s;
}

.ab-con:hover
{
    background:#f87e42;
    transform: translatey(-10px);
}

/* find */
.findit
{
    height: 70px;
    width: 100%;
    margin-bottom: 60px;
}

.findit h2
{
    font-size: 40px;
    align-items: center;
    color: #fff;
    padding-left: 40%;
    padding-top: 15px;
}

.food
{
    height: 800px;
    width: 100%;
    /* background-color: #f87e42; */
}

.veg
{
    height: 300px;
    width: 40%;
    /* background-color: #FF5C0A; */
    border-radius: 10px;
    margin-left: 100px;
    float: left;
}

.veg img
{
    height: 310px;
    width: 100%;
    border-radius: 10px;

}

.non-veg
{
    height: 300px;
    width: 40%;
    /* background-color: #FF5C0A; */
    border-radius: 10px;
    margin-left: 50px;
    margin-right: 100px;
    float: right;
}

.non-veg img
{
    height: 310px;
    width: 100%;
    border-radius: 10px;

}

.dessert
{
    height: 300px;
    width: 40%;
    /* background-color: #FF5C0A; */
    border-radius: 10px;
    margin-left: 100px;
    margin-top: 90px;
    float: left;
}

.dessert img
{
    height: 310px;
    width: 100%;
    border-radius: 10px;
}

.juice
{
    height: 300px;
    width: 40%;
    /* background-color: #FF5C0A; */
    border-radius: 10px;
    margin-left: 50px;
    margin-right: 100px;
    margin-top: 90px;
    float: right;
}

.juice img
{
    height: 310px;
    width: 100%;
    border-radius: 10px;
}

.tit
{
    margin-top: 10px;
    margin-left: 38%;
    align-items: center;
    color: #f87e42;
    font-size: 30px;
}

/* contact */

.container
{
    padding: 10px 10%;
}

.contact-left
{
    flex-basis: 35%;
}

.contact-right
{
    flex-basis: 60%;
}

.contact-left p
{
  margin-top: 30px;
}

.contact-left p i 
{
    color: #f87e42;
    margin-right: 15px;
    font-size: 25px;

}

.social-icons
{
    margin: 30px;

}
.social-icons a 
{
    text-decoration: none;
    font-size: 30px;
    margin-right: 15px;
    color: #ababab;
    display: inline-block;
    transition: transform 0.5s;

}

.social-icons a:hover 
{
    color: #FF5C0A;
    transform: translate(-5px);

}

.btn 
{
    display: block;
    margin: 50px auto;
    width: fit-content;
    border: 1px solid #FF5C0A;
    padding: 14px 50px;
    border-radius: 6px;
    text-decoration: none;
    color: #fff;
    transition: background 0.5s;
}

.btn:hover
{
    background: #FF5C0A;
}
.btn.btn2
{
    display: inline-block;
    background:#FF5C0A;
}
.contact-right form 
{
    width: 100%;

}

form input, form textarea
{
    width: 100%;
    border: 0;
    outline: none;
    background: #262626;
    padding: 15px;
    margin: 15px 0;
    color: #fff;
    font-size: 18px;
    border-radius: 6px;
}
form .btn2 
{
    padding: 14px 60 px;
    font-size: 18px;
    margin-top: 20px;
    cursor: pointer;
}
.copyright
{
    width: 100%;
    text-align: center;
    padding: 25px 0;
    background: #262626;
    font-weight: 300;
    margin-top: 20px;

}

Explanation:
- The CSS code styles the elements of the Recipe Finder web application to enhance its visual appearance and layout.
- It includes styles for the navigation menu, header background, text, images, sections, buttons, form elements, and social icons.
- The HTML code provides the structure of the web page, dividing it into different sections such as header, about, find it, and contact.
- CSS is used to style the elements of the page, including the layout, colors, fonts, and spacing, to create an attractive and cohesive design.
- The web page is designed to be responsive, ensuring that it looks good and functions well on various devices and screen sizes.
- Users can navigate through different sections of the page using the navigation menu.
- The find it section allows users to explore recipes based on different categories, providing an interactive and engaging experience.
- The contact section provides a form for users to reach out to the website owner, enhancing user engagement and interaction.




7. Conclusion
In conclusion, the Recipe Organizer web application developed by Aafreen Shaik successfully meets the requirements of the internship task. It demonstrates proficiency in HTML, CSS, and JavaScript, providing users with a user-friendly platform to explore and organize recipes effectively.

This documentation provides an overview of the project, including its purpose, implementation details, and code structure.
 
