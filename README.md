<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Elements Implementation</title>
    <meta name="description" content="A webpage demonstrating HTML5 images, lists, tables, and forms.">
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to HTML5 Elements</h1>
    </header>
    
    <!-- Navigation Menu -->
    <nav>
        <ul>
            <li><a href="#list">Ordered List</a></li>
            <li><a href="#image">Image</a></li>
            <li><a href="#table">Contacts Table</a></li>
            <li><a href="#form">Registration Form</a></li>
        </ul>
    </nav>
    
    <!-- Ordered List Section -->
    <section id="list">
        <h2>Ordered List with Roman Numerals</h2>
        <ol type="I">
            <li>First Item</li>
            <li>Second Item</li>
            <li>Third Item</li>
            <li>Fourth Item</li>
            <li>Fifth Item</li>
        </ol>
    </section>
    
    <!-- Image Section -->
    <section id="image">
        <h2>External Image</h2>
        <img src="https://www.pexels.com/photo/nature-landscape-123456/" alt="Beautiful Nature Scene" width="600">
    </section>
    
    <!-- Table Section -->
    <section id="table">
        <h2>Contacts Table</h2>
        <table border="1">
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
                    <td>123 Main St</td>
                    <td>+1234567890</td>
                    <td>john@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Elm St</td>
                    <td>+0987654321</td>
                    <td>jane@example.com</td>
                </tr>
                <tr>
                    <td>Mike Johnson</td>
                    <td>789 Oak St</td>
                    <td>+1122334455</td>
                    <td>mike@example.com</td>
                </tr>
                <tr>
                    <td>Emily Davis</td>
                    <td>101 Pine St</td>
                    <td>+6677889900</td>
                    <td>emily@example.com</td>
                </tr>
                <tr>
                    <td>Chris Brown</td>
                    <td>202 Maple St</td>
                    <td>+5566778899</td>
                    <td>chris@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>
    
    <!-- Registration Form Section -->
    <section id="form">
        <h2>Registration Form</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required minlength="6">
            
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female" required>
            <label for="female">Female</label>
            
            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">Select a country</option>
                <option value="usa">USA</option>
                <option value="uk">UK</option>
                <option value="canada">Canada</option>
            </select>
            
            <label>Interests:</label>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label>
            <input type="checkbox" id="reading" name="interests" value="reading">
            <label for="reading">Reading</label>
            
            <button type="submit">Register</button>
        </form>
    </section>
    
    <!-- Footer Section -->
    <footer>
        <p>Contact us at: <a href="mailto:info@example.com">info@example.com</a></p>
    </footer>
</body>
</html>


