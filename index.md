Here is the complete code and structure for your assignment (Assignment 4.1 — Student Registration Form).

Save the code below into a file named registration.html. It includes all the required fields (Full Name, Email, Password, Phone Number, Age), proper semantic <label> tags, correct input types, unique id and name attributes, required validation attributes, and a submit button, styled cleanly for your screenshot.

File: registration.html
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f6f9;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .form-container {
            background: #ffffff;
            padding: 2.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08);
            width: 100%;
            max-width: 450px;
        }
        h2 {
            text-align: center;
            color: #2c3e50;
            margin-top: 0;
            margin-bottom: 1.5rem;
        }
        .form-group {
            margin-bottom: 1.25rem;
        }
        label {
            display: block;
            font-weight: bold;
            margin-bottom: 0.5rem;
            color: #34495e;
        }
        input[type="text"],
        input[type="email"],
        input[type="password"],
        input[type="tel"],
        input[type="number"] {
            width: 100%;
            padding: 0.75rem;
            border: 1px solid #cbd5e1;
            border-radius: 4px;
            box-sizing: border-box;
            font-size: 1rem;
            transition: border-color 0.2s;
        }
        input:focus {
            border-color: #2563eb;
            outline: none;
            box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.1);
        }
        button[type="submit"] {
            width: 100%;
            background-color: #2563eb;
            color: white;
            padding: 0.75rem;
            border: none;
            border-radius: 4px;
            font-size: 1rem;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.2s;
            margin-top: 0.5rem;
        }
        button[type="submit"]:hover {
            background-color: #1d4ed8;
        }
    </style>
</head>
<body>

    <div class="form-container">
        <h2>Student Registration</h2>
        
        <!-- Form Tag -->
        <form action="#" method="POST">
            
            <!-- Full Name Field -->
            <div class="form-group">
                <label for="fullname">Full Name:</label>
                <input type="text" id="fullname" name="fullname" placeholder="Enter your full name" required>
            </div>

            <!-- Email Field -->
            <div class="form-group">
                <label for="email">Email Address:</label>
                <input type="email" id="email" name="email" placeholder="student@example.com" required>
            </div>

            <!-- Password Field -->
            <div class="form-group">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" placeholder="Create a secure password" required>
            </div>

            <!-- Phone Number Field -->
            <div class="form-group">
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" placeholder="123-456-7890" required>
            </div>

            <!-- Age Field -->
            <div class="form-group">
                <label for="age">Age:</label>
                <input type="number" id="age" name="age" min="1" max="120" placeholder="Enter your age" required>
            </div>

            <!-- Submit Button -->
            <button type="submit">Register</button>

        </form>
    </div>

</body>
</html>
How to Complete Your Submission:
Save the File: Save the code above as registration.html on your computer.

Test the Form: Double-click the file to open it in your web browser.

Try clicking the Register button without filling anything out to test browser validation (required fields will trigger alerts).

Test typing into the fields to make sure inputs respond correctly (e.g., number field limiting characters or email checking for @).

Take a Screenshot: Capture a clean browser screenshot of the rendered registration form.

Submit: Turn in your registration.html source file and the browser screenshot as required by your assignment!