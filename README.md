<!DOCTYPE html>
<html>
<head>
    <title>Simple Registration Form</title>
    <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700" rel="stylesheet">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.4.1/css/all.css" integrity="sha384-5sAR7xN1Nv6T6+dT2mhtzEpVJvfS3NScPQTrOxhwjIuvcA67KV2R5Jz6kr4abQsz" crossorigin="anonymous">
    <style>
        /* Basic styling for the form */
        html, body {
            display: flex;
            justify-content: center;
            height: 100%;
        }
        body, div, h1, form, input, p {
            padding: 0;
            margin: 0;
            outline: none;
            font-family: Roboto, Arial, sans-serif;
            font-size: 16px;
            color: #666;
        }
        /* Other styles go here (see below) */
        /* ... */
    </style>
</head>
<body>
    <div class="main-block">
        <h1>Registration</h1>
        <form action="/">
            <!-- Account type (Personal/Company) -->
            <div class="account-type">
                <input type="radio" value="none" id="radioOne" name="account" checked>
                <label for="radioOne" class="radio">Personal</label>
                <input type="radio" value="none" id="radioTwo" name="account">
                <label for="radioTwo" class="radio">Company</label>
            </div>
            <!-- Email, Name, Password fields -->
            <label id="icon" for="email"><i class="fas fa-envelope"></i></label>
            <input type="text" name="email" id="email" placeholder="Email" required>
            <label id="icon" for="name"><i class="fas fa-user"></i></label>
            <input type="text" name="name" id="name" placeholder="Name" required>
            <label id="icon" for="password"><i class="fas fa-unlock-alt"></i></label>
            <input type="password" name="password" id="password" placeholder="Password" required>
            <!-- Gender selection -->
            <div class="gender">
                <input type="radio" value="none" id="male" name="gender" checked>
                <label for="male" class="radio">Male</label>
                <input type="radio" value="none" id="female" name="gender">
                <label for="female" class="radio">Female</label>
            </div>
            <!-- Privacy policy and submit button -->
            <div class="btn-block">
                <p>By clicking Register, you agree to our <a href="https://www.w3docs.com/privacy-policy">Privacy Policy</a>.</p>
                <button type="submit">Submit</button>
            </div>
        </form>
    </div>
</body>
</html>
