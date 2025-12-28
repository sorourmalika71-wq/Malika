<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Contact Form</title>
    <style>
        body { font-family: Arial, sans-serif; max-width: 500px; margin: 50px auto; padding: 20px; background: #f0f8ff; }
        label { display: block; margin: 10px 0 5px; font-weight: bold; color: #4682b4; }
        input { width: 100%; padding: 10px; margin-bottom: 15px; box-sizing: border-box; border: 1px solid #add8e6; border-radius: 4px; }
    </style>
</head>
<body>
    <h1>Contact Information</h1>
    
    <label for="idnumber">ID number:</label>
    <input type="text" id="idnumber" name="idnumber" value="LA7132400" readonly>

    <label for="name">Name:</label>
    <input type="text" id="name" name="name" value="Malika Hany Ahmed Saadallah Sorour" readonly>

    <label for="address">Address:</label>
    <input type="text" id="address" name="address" value="14 Al-Marwa Buildings - in front of the girls' college" readonly>

    <label for="phone">Phone number:</label>
    <input type="tel" id="phone" name="phone" value="+20 100 6697655" readonly>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" value="Sorourmalika71@gmail.com" readonly>
</body>
</html>
