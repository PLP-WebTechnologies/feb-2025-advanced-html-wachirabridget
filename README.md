# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f4f4f4;
        }
    </style>
</head>
<body>
    <header>
        <h1>Advanced HTML5 Elements and Forms</h1>
    </header>

   <section>
        <h2>Ordered List</h2>
        <ol type="I">
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>Python</li>
            <li>SQL</li>
        </ol>
    </section>

   <section>
        <h2>External Image</h2>
        <img src="https://images.pexels.com/photos/1108099/pexels-photo-1108099.jpeg" alt="Sample Image from Pexels" width="500">
    </section>
    <section>
        <h2>Contacts</h2>
        <table>
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>John Doe</td>
                    <td>123 Street, City</td>
                    <td>+1234567890</td>
                    <td>johndoe@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Avenue, Town</td>
                    <td>+9876543210</td>
                    <td>janesmith@example.com</td>
                </tr>
                <tr>
                    <td>Mike Johnson</td>
                    <td>789 Boulevard, Village</td>
                    <td>+1928374650</td>
                    <td>mikej@example.com</td>
                </tr>
                <tr>
                    <td>Emily Davis</td>
                    <td>321 Road, Metro</td>
                    <td>+5678901234</td>
                    <td>emilyd@example.com</td>
                </tr>
                <tr>
                    <td>Chris Brown</td>
                    <td>654 Lane, City</td>
                    <td>+3456789012</td>
                    <td>chrisb@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="POST">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            <br>   
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter a password" required>
            <br>
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br>
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female" required>
            <label for="female">Female</label>
            <br>
            <label for="course">Select Course:</label>
            <select id="course" name="course" required>
                <option value="">--Select--</option>
                <option value="web">Web Development</option>
                <option value="data">Data Science</option>
                <option value="cyber">Cybersecurity</option>
            </select>
            <br>
            <label>Interests:</label>
            <input type="checkbox" id="coding" name="interests" value="coding">
            <label for="coding">Coding</label>
            <input type="checkbox" id="design" name="interests" value="design">
            <label for="design">Design</label>
            <input type="checkbox" id="gaming" name="interests" value="gaming">
            <label for="gaming">Gaming</label>
            <br>
            <button type="submit">Register</button>
        </form>
    </section>
</body>
</html>


