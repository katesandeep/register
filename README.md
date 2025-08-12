<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Event Registration</title>
  <link rel="stylesheet" href="styles.css" />
<style>
</head>
<body>
  <div class="form-container">
    <h2>Register for the Event</h2>
    <form action="#" method="post">
      <div class="form-group">
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" required />
      </div>

      <div class="form-group">
        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email" required />
      </div>

      <div class="form-group">
        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" />
      </div>

      <div class="form-group">
        <label for="tickets">Number of Tickets:</label>
        <select id="tickets" name="tickets">
          <option value="1">1</option>
          <option value="2">2</option>
          <option value="3">3</option>
          <option value="4+">4+</option>
        </select>
      </div>

      <div class="form-group">
        <label for="comments">Additional Comments:</label>
        <textarea id="comments" name="comments" rows="4"></textarea>
      </div>

      <button type="submit">Submit Registration</button>
    </form>
  </div>
</body>
</html>
</style>
/* Simple reset */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  background: #f9f9f9;
  padding: 20px;
}

.form-container {
  max-width: 400px;
  margin: 0 auto;
  background: #fff;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

h2 {
  margin-bottom: 20px;
  text-align: center;
}

.form-group {
  margin-bottom: 15px;
}

label {
  display: block;
  font-weight: bold;
  margin-bottom: 6px;
}

input[type="text"],
input[type="email"],
input[type="tel"],
select,
textarea {
  width: 100%;
  padding: 8px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

input:focus,
select:focus,
textarea:focus {
  border-color: #007BFF;
  outline: none;
}

button[type="submit"] {
  width: 100%;
  padding: 10px;
  background: #007BFF;
  border: none;
  color: white;
  font-size: 16px;
  border-radius: 4px;
  cursor: pointer;
}

button[type="submit"]:hover {
  background: #0056b3;
}


