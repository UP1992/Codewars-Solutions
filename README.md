<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6;">

  <h1>📘 Codewars-Solutions</h1>
  <p>
    A collection of <strong>JavaScript solutions</strong> for various 
    <a href="https://www.codewars.com/" target="_blank">Codewars</a> kata challenges.  
    This repository serves as a personal practice log and reference for improving 
    problem-solving, algorithms, and clean coding skills.
  </p>

  <hr>

  <h2>📂 Repository Structure</h2>
  <p>Each kata solution is implemented in its own file for clarity and organization.</p>

  <ul>
    <li>✅ <strong>Is a number prime?</strong></li>
    <li>✅ <strong>Complementary DNA</strong></li>
    <li>✅ <strong>Is it triangle?</strong></li>
    <li>✅ <strong>Multiples of 3 or 5</strong></li>
    <li>✅ <strong>Shortest Word</strong></li>
    <li>✅ <strong>Your order, please.</strong></li>
    <li>✅ <strong>Bit Counting</strong></li>
    <li>✅ <strong>Decode the Morse Code</strong></li>
    <li>✅ <strong>Tribonacci Sequence</strong></li>
    <li>✅ <strong>Find the unique number</strong></li>
  </ul>

  <hr>

  <h2>🚀 Example: <em>Is a number prime?</em></h2>
  <pre style="background:#f4f4f4; padding:10px; border-radius:5px;">
<code>function isPrime(num) {
  if (num <= 1) return false;   // negatives, 0, 1 are not prime
  if (num === 2) return true;   // 2 is prime
  if (num % 2 === 0) return false; // even numbers > 2 are not prime

  let sqrt = Math.sqrt(num);
  for (let i = 3; i <= sqrt; i += 2) {
    if (num % i === 0) {
      return false;
    }
  }
  return true;
}
</code>
  </pre>

  <h3>✅ Tests</h3>
  <pre style="background:#f4f4f4; padding:10px; border-radius:5px;">
<code>console.log(isPrime(1));   // false
console.log(isPrime(2));   // true
console.log(isPrime(29));  // true
console.log(isPrime(-5));  // false
</code>
  </pre>

  <hr>

  <h2>🛠️ How to Use</h2>
  <ol>
    <li>Clone the repo:
      <pre><code>git clone https://github.com/UP1992/Codewars-Solutions.git</code></pre>
    </li>
    <li>Navigate to the folder:
      <pre><code>cd Codewars-Solutions</code></pre>
    </li>
    <li>Run a solution with Node.js:
      <pre><code>node isPrime.js</code></pre>
    </li>
  </ol>

  <hr>

  <h2>📖 Goals</h2>
  <ul>
    <li>Practice <strong>JavaScript algorithms</strong> and problem-solving.</li>
    <li>Write <strong>clean, efficient, and optimized</strong> code.</li>
    <li>Document solutions for future reference.</li>
  </ul>

  <hr>

  <h2>📜 License</h2>
  <p>
    This repository is licensed under the 
    <a href="LICENSE">MIT License</a>.  
    You’re free to use and share the solutions with attribution.
  </p>

</body>
</html>
