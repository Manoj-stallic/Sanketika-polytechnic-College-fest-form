# Sanketika-polytechnic-College-fest-form
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>College Fest Registration - Sanketika Polytechnic</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f0f8ff;
    }
    .form-container {
      max-width: 800px;
      margin: 30px auto;
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    }
    .form-container h1 {
      text-align: center;
      color: #333;
      margin-bottom: 20px;
    }
    .form-group {
      margin-bottom: 15px;
    }
    .form-group label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }
    .form-group input,
    .form-group select,
    .form-group textarea {
      width: 100%;
      padding: 10px;
      font-size: 16px;
      border: 1px solid #ccc;
      border-radius: 5px;
      box-sizing: border-box;
    }
    .form-group textarea {
      resize: vertical;
    }
    .form-group input[type="checkbox"] {
      width: auto;
      margin-right: 10px;
    }
    .submit-btn {
      display: block;
      width: 100%;
      padding: 12px;
      font-size: 18px;
      color: #fff;
      background-color: #007bff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      text-align: center;
    }
    .submit-btn:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
  <div class="form-container">
    <h1>Sanketika Polytechnic College Fest Registration</h1>
    <form action="#" method="POST">
      <!-- Participant Name -->
      <div class="form-group">
        <label for="name">Participant Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>
      </div>

      <!-- Pin Number -->
      <div class="form-group">
        <label for="pin">Pin Number (e.g., 24221-AIM-30):</label>
        <input type="text" id="pin" name="pin" placeholder="Enter your pin number" pattern="^\d{5}-[A-Z]{3}-\d{2}$" required>
      </div>

      <!-- Email -->
      <div class="form-group">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
      </div>

      <!-- Phone Number -->
      <div class="form-group">
        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required>
      </div>

      <!-- Department -->
      <div class="form-group">
        <label for="department">Department:</label>
        <select id="department" name="department" required>
          <option value="" disabled selected>Select your department</option>
          <option value="AIML">Artificial Intelligence & Machine Learning</option>
          <option value="CME">CME</option>
          <option value="CSE">Computer Science</option>
          <option value="MECH">Mechanical Engineering</option>
          <option value="CIVIL">Civil Engineering</option>
          <option value="EEE">Electrical Engineering</option>
          <option value="ECE">Electronics & Communication Engineering</option>
          <option value="AUTO">Automobile Engineering</option>
          <option value="YARD">Yard Engineering</option>
        </select>
      </div>

      <!-- Events -->
      <div class="form-group">
        <label for="events">Select Events:</label>
        <div>
          <input type="checkbox" id="catwalk" name="events" value="Catwalk">
          <label for="catwalk">Catwalk</label>
        </div>
        <div>
          <input type="checkbox" id="moonwalk" name="events" value="Moonwalk">
          <label for="moonwalk">Moonwalk</label>
        </div>
        <div>
          <input type="checkbox" id="cricket" name="events" value="Cricket">
          <label for="cricket">Cricket</label>
        </div>
        <div>
          <input type="checkbox" id="volleyball" name="events" value="Volleyball">
          <label for="volleyball">Volleyball</label>
        </div>
        <div>
          <input type="checkbox" id="dance" name="events" value="Dance">
          <label for="dance">Dance</label>
        </div>
        <div>
          <input type="checkbox" id="singing" name="events" value="Singing">
          <label for="singing">Singing</label>
        </div>
        <div>
          <input type="checkbox" id="mimicry" name="events" value="Mimicry">
          <label for="mimicry">Mimicry</label>
        </div>
      </div>

      <!-- Additional Comments -->
      <div class="form-group">
        <label for="comments">Any Additional Comments:</label>
        <textarea id="comments" name="comments" rows="4" placeholder="Enter any additional comments or preferences"></textarea>
      </div>

      <!-- Submit Button -->
      <button type="submit" class="submit-btn">Register</button>
    </form>
  </div>
</body>
</html>