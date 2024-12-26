# Star Siraj Academy 🚀

Welcome to the **Star Siraj Academy** project! This repository contains a basic website built using HTML. It features two pages:

1. **Home Page**: Provides an introduction to the academy and its offerings.
2. **Registration Page**: Includes a form for users to register for courses.

---

## Features

### Home Page
The home page showcases:
- A welcoming header with the academy's name and tagline.
- An embedded YouTube video.
- An overview of full-stack web development.
- A table listing technologies used for front-end, back-end, and database development.
- Navigation links to the registration page and the academy's Instagram page.

### Registration Page
The registration page includes:
- A form to collect user details such as:
  - Name
  - Age
  - Gender
  - Email
  - Selected course
  - Resume upload
- Reset and submit buttons for easy interaction.
- Links to navigate back to the home page and the Instagram page.

---

## Project Files

### `index.html` (Home Page)

```html
<!DOCTYPE html>
<html>
<head>
    <title>Star Siraj Academy</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body bgcolor="black" style="color: white;">
    <center>
        <h1>Star Siraj Academy🚀</h1>
        <h5>Training | Tech News | Freshers Guides</h5>
        <p>Empowering young developers to level up their skills through training in software development technologies.</p>
    </center>
    <hr>
    <center>
        <iframe width="560" height="315" 
            src="https://www.youtube.com/embed/BB49x_uMlGA?si=uSBd-zrZbbcQlild" 
            title="YouTube video player" 
            frameborder="0" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
            referrerpolicy="strict-origin-when-cross-origin" 
            allowfullscreen>
        </iframe>
    </center>
    <p>A 10-sec test animation from my short film for my University BA Animation course, due in January.</p>
    <h2>Let's Divide Full Stack into 3 Parts</h2>
    <ul>
        <li>Front End</li>
        <li>Back End</li>
        <li>Database</li>
    </ul>
    <h2>Technologies Used for Full Stack Web Development</h2>
    <table border="1">
        <tr>
            <td>Front End</td> <td>Back End</td> <td>Database</td>
        </tr>
        <tr>
            <td>HTML</td> <td>Java</td> <td>MongoDB</td>
        </tr>
        <tr>
            <td>CSS</td> <td>Python</td> <td>MySQL</td>
        </tr>
    </table>
    <hr>
    <center>
        <a href="register.html">Register for a Course</a> | 
        <a href="https://www.instagram.com/google/">Instagram</a>
    </center>
</body>
</html>

### `register.html`  (Registration Page)

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Register</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body bgcolor="black" style="color: white;">
    <center>
        <h1>Star Siraj Academy🚀</h1>
        <h5>Training | Tech News | Freshers Guides</h5>
        <p>Empowering young developers to level up their skills through training in software development technologies.</p>
    </center>
    <hr>
    <center>
        <h1>Registration Form</h1>
        <form>
            <table>
                <tr>
                    <td>Name:</td> 
                    <td><input type="text" placeholder="Enter Your Name"></td>
                </tr>
                <tr>
                    <td>Age:</td> 
                    <td><input type="number" placeholder="Enter Your Age"></td>
                </tr>
                <tr>
                    <td>Gender:</td>
                    <td>
                        <input type="radio" name="Gender" value="Male"> Male 
                        <input type="radio" name="Gender" value="Female"> Female
                    </td>
                </tr>
                <tr>
                    <td>Email:</td> 
                    <td><input type="email" placeholder="Enter Your Email"></td>
                </tr>
                <tr>
                    <td>Course:</td>
                    <td>
                        <select>
                            <option>Python Programming</option>
                            <option>Java</option>
                            <option>C++</option>
                        </select>
                    </td>
                </tr>
                <tr>
                    <td>Upload Resume:</td>
                    <td><input type="file" accept=".pdf,.doc,.docx"></td>
                </tr>
                <tr>
                    <td><input type="reset" value="Reset"></td>
                    <td><input type="submit" value="Submit"></td>
                </tr>
            </table>
        </form>
    </center>
    <hr>
    <center>
        <a href="index.html">Home</a> | 
        <a href="https://www.instagram.com/google/">Instagram</a>
    </center>
</body>
</html>
