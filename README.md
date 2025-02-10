[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/LHOh9PUe)
# INST377-Lab

# Name: Asad Khan 

# Comments: 

#Index Page 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>INST377 - Lab 2 - Contact Me</title>
  <style>
    body {
      background-color: #e6d0d0; /* Light maroon background */
      font-family: Arial, sans-serif;
    }
    .form-container {
      margin: 20px;
    }
    label {
      font-size: 1.2rem;
      display: block;
      margin-bottom: 5px;
    }
    input[type="text"], input[type="email"] {
      margin: 10px 0;
      padding: 8px;
      width: 100%;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      background-color: #800000; /* Maroon color */
      color: white;
      border: none;
      padding: 10px 20px;
      margin-top: 10px;
      font-size: 1rem;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover {
      background-color: #660000; /* Darker maroon */
    }
  </style>
</head>
<body>
  <h1>INST377 - Lab 2 - Contact Me</h1>
  <form action="thank-you.html" method="GET">
    <div class="form-container">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
    </div>
    <button type="submit">Submit</button>
  </form>
</body>
</html>


# Thank-you Page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Thank You</title>
  <style>
    body {
      background-color: #e6d0d0; /* Light maroon background */
      text-align: center;
      font-family: Arial, sans-serif;
    }
    img {
      width: 50%;
      margin-top: 20px;
    }
    h1 {
      font-size: 2rem;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <h1>Thank You for Contacting Us!</h1>
  <img src="c9d8d1832194e7097faa4058ea0f2053.jpg" alt="Cute Kitten">
</body>
</html>




