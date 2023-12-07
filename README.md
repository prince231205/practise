<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login to get your daily dose of News</title>
    <style>
        body{
            background-color: gray;
        }
        .container {
            max-width: 800px;
            border: 20px dashed;
            padding: 100px;
            margin:  auto;
            text-align: center;
            background-image: url(appointment.jpg);
            background-size: cover;
        }
        .form-group {
            margin-bottom: 15px;
            text-align: center;
        }
        .form-control {
            height: 40px;
            margin: 5%;
            border-radius: 15px;
        }
        .form-check-label {
            margin-left: 10px;
        }
        .btn {
            width: 100%;
            height: 50px;
            font-size: 18px;
        }
        .error {
            color: red;
            font-size: 14px;
        }
        body{
            align-self: center;
            background-image: url(form.jpg);
            background-size: cover;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="text-center">Login to get your daily dose of News</h1>
        <p class="text-center">Please fill out the form below to get daily news .</p>
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" class="form-control" placeholder="Enter your name">
                <span id="name-error" class="error"></span>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" class="form-control" placeholder="Enter your email">
                <span id="email-error" class="error"></span>
            </div>
            <div class="form-group">
                <label for="phone">Phone:</label>
                <input type="tel" id="phone" name="phone"  class="form-control" placeholder="Enter your phone number">
                <span id="phone-error" class="error"></span>
            </div>
            <div class="form-group">
                <label for="service">Membership</label>
                <select id="service" name="service" class="form-control">
                    <option value="Select a Service">Select a Membership</option>
                    <option value="Facial">Golden</option>
                    <option value="Manicure">Silver</option>
                    <option value="Pedicure">Normal</option>
                </select>
                <div class="form-group"><button type="button"class="form-control"><a href="index.html">Login Now</button></a></div>
            </div>
             </div>
            </body>
                </html>
