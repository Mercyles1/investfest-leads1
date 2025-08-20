# investfest-leads1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Invest Fest Lead Form</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 40px; background: #f7f7f7; }
    form { background: #fff; padding: 20px; border-radius: 8px; max-width: 400px; margin: auto; }
    label { display: block; margin-top: 10px; }
    input, button { width: 100%; padding: 10px; margin-top: 5px; }
    button { background: #2b6cb0; color: white; border: none; border-radius: 5px; cursor: pointer; }
    button:hover { background: #2c5282; }
  </style>
</head>
<body>
  <h2>Invest Fest AI Business Card</h2>
  <form method="POST" action="https://YOUR-N8N-DOMAIN/webhook/investfest/lead">
    <label for="name">First Name</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Email Address</label>
    <input type="email" id="email" name="email" required>

    <label for="phone">Phone Number</label>
    <input type="text" id="phone" name="phone" placeholder="+15551234567">

    <label for="business_type">Business Type</label>
    <input type="text" id="business_type" name="business_type" placeholder="Real Estate, Coaching, etc." required>

    <button type="submit">Make My AI Business Card</button>
  </form>
</body>
</html>
