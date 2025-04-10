<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration Form</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f1f1f1;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        
        .form-container {
            background: linear-gradient(to right, #6a11cb, #2575fc);
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 400px;
            color: #fff;
        }
        
        h2 {
            text-align: center;
            margin-bottom: 20px;
            font-weight: 500;
        }
        
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
        }
        
        input[type="text"],
        input[type="email"],
        input[type="password"],
        input[type="tel"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0 20px;
            border: 2px solid #fff;
            border-radius: 8px;
            background: #fff;
            color: #333;
            font-size: 16px;
        }
        
        input[type="submit"] {
            width: 100%;
            padding: 12px;
            background-color: #2575fc;
            color: #fff;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        
        input[type="submit"]:hover {
            background-color: #6a11cb;
        }
        
        .form-footer {
            text-align: center;
            margin-top: 20px;
            font-size: 14px;
        }
        
        .form-footer a {
            color: #fff;
            text-decoration: none;
        }
        
        .form-footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>

    <div class="form-container">
        <h2>Student Registration Form</h2>
        <form action="#">
            <label for="fname">First Name</label>
            <input type="text" id="fname" placeholder="Enter your first name" required>

            <label for="lname">Last Name</label>
            <input type="text" id="lname" placeholder="Enter your last name" required>

            <label for="email">Email</label>
            <input type="email" id="email" placeholder="Enter your email" required>

            <label for="phone">Phone</label>
            <input type="tel" id="phone" placeholder="Enter your phone number" required>

            <label for="password">Password</label>
            <input type="password" id="password" placeholder="Create a password" required>

            <input type="submit" value="Register">
        </form>

        <div class="form-footer">
            <p>Already have an account? <a href="#">Login here</a></p>
        </div>
    </div>

</body>

</html>
