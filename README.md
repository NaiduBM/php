<form method="post" action="reservation.php">
  <label for="date">Date:</label>
  <input type="date" id="date" name="date" required>
  <br>

  <label for="time">Time:</label>
  <input type="time" id="time" name="time" required>
  <br>

  <label for="guests">Number of guests:</label>
  <input type="number" id="guests" name="guests" min="1" max="10" required>
  <br>

  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>
  <br>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>
  <br>

  <label for="phone">Phone:</label>
  <input type="tel" id="phone" name="phone" pattern="[0-9]{10}" required>
  <br>

  <input type="submit" value="Submit">
</form>
