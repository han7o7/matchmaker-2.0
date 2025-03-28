# matchmaker-2.0
LAB4
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>True Love Compatibility</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>💘 True Love Compatibility Test 💘</h1>
    <p>Answer the five statements below using numbers from 1 (Strongly Disagree) to 5 (Strongly Agree). We'll calculate your compatibility score!</p>
    <form id="loveForm">
      <div class="question">
        <label>1. I love going on spontaneous road trips.</label>
        <input type="number" name="q1" min="1" max="5" required />
      </div>
      <div class="question">
        <label>2. Dogs are better than cats.</label>
        <input type="number" name="q2" min="1" max="5" required />
      </div>
      <div class="question">
        <label>3. Broccoli is delicious.</label>
        <input type="number" name="q3" min="1" max="5" required />
      </div>
      <div class="question">
        <label>4. I enjoy staying up late and watching movies.</label>
        <input type="number" name="q4" min="1" max="5" required />
      </div>
      <div class="question">
        <label>5. I prefer mountains over beaches.</label>
        <input type="number" name="q5" min="1" max="5" required />
      </div>
      <button type="submit">Check Compatibility</button>
    </form>
    <div id="results"></div>
  </div>

  <script src="script.js"></script>
</body>
</html>
