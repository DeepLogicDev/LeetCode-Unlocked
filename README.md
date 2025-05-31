<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Leetcode Unlocked</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f6f8;
      color: #2d3436;
      line-height: 1.6;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #0984e3;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }

    h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 2rem;
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      margin-top: -50px;
    }

    h2 {
      color: #0984e3;
      margin-top: 2rem;
    }

    ul {
      list-style-type: none;
      padding-left: 0;
    }

    ul li::before {
      content: "✅ ";
      color: #00b894;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 1rem;
    }

    th, td {
      border: 1px solid #ccc;
      padding: 8px;
      text-align: left;
    }

    code {
      background-color: #f1f2f6;
      padding: 2px 6px;
      border-radius: 4px;
      font-family: monospace;
    }
  </style>
</head>
<body>

<header>
  <h1>🚀 Leetcode Unlocked</h1>
  <p>A curated collection of well-explained LeetCode problems with step-by-step solutions and clean code.</p>
</header>

<div class="container">

  <h2>🎯 Goal</h2>
  <p>To understand <strong>how</strong> to approach each problem, not just memorize the solution.</p>

  <h2>📁 Structure</h2>
  <p>Each problem is organized into its own folder with:</p>
  <ul>
    <li>Problem Description</li>
    <li>Step-by-step Explanation</li>
    <li>Intuition & Approach</li>
    <li>Time and Space Complexity Analysis</li>
    <li>Example Test Cases</li>
    <li>Clean Code Implementation (Python, C++, and sometimes Java)</li>
  </ul>

  <p><strong>Example structure:</strong></p>
  <pre><code>/problems/
  └── 0001_two_sum/
      ├── README.md
      ├── solution.py
      ├── solution.cpp
      └── solution.java</code></pre>

  <h2>🔍 How to Use This Repo</h2>
  <ol>
    <li>Navigate to the problem folder.</li>
    <li>Read the detailed explanation in the <code>README.md</code>.</li>
    <li>Review or run the solution in your preferred language file (<code>.py</code>, <code>.cpp</code>, or <code>.java</code>).</li>
    <li>Try modifying test cases and see how the solution behaves.</li>
    <li>Repeat. Learn. Master.</li>
  </ol>

  <h2>🧩 Featured Topics</h2>
  <table>
    <thead>
      <tr>
        <th>Category</th>
        <th>Examples</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Arrays</td>
        <td>Two Sum, Container With Most Water</td>
      </tr>
      <tr>
        <td>Strings</td>
        <td>Longest Substring Without Repeats, Palindrome Checker</td>
      </tr>
      <tr>
        <td>Hashing</td>
        <td>Valid Anagram, Group Anagrams</td>
      </tr>
      <tr>
        <td>Sliding Window</td>
        <td>Minimum Window Substring</td>
      </tr>
      <tr>
        <td>Two Pointers</td>
        <td>Remove Duplicates from Sorted Array</td>
      </tr>
      <tr>
        <td>Binary Search</td>
        <td>Find First and Last Position, Peak Element</td>
      </tr>
      <tr>
        <td>Linked Lists</td>
        <td>Reverse List, Middle of the List</td>
      </tr>
      <tr>
        <td>Stacks / Queues</td>
        <td>Valid Parentheses, Min Stack</td>
      </tr>
      <tr>
        <td>Trees</td>
        <td>Inorder Traversal, Level Order Traversal</td>
      </tr>
      <tr>
        <td>DFS / BFS</td>
        <td>Number of Islands, Word Ladder</td>
      </tr>
      <tr>
        <td>Dynamic Programming</td>
        <td>Climbing Stairs, House Robber</td>
      </tr>
      <tr>
        <td>Greedy</td>
        <td>Jump Game, Assign Cookies</td>
      </tr>
      <tr>
        <td>Graphs</td>
        <td>Course Schedule, Clone Graph</td>
      </tr>
      <tr>
        <td>Backtracking</td>
        <td>Subsets, Permutations</td>
      </tr>
      <tr>
        <td>Heap / Priority Queue</td>
        <td>Kth Largest Element, Merge k Sorted Lists</td>
      </tr>
    </tbody>
  </table>

  <h2>🛠️ Tech Stack</h2>
  <ul>
    <li>🐍 Python (Primary)</li>
    <li>CppClass 🟠 C++</li>
    <li>☕ Java (Optional)</li>
    <li>🌐 Markdown for documentation</li>
    <li>📊 GitHub for version control</li>
  </ul>

  <h2>🌟 Why This Repo?</h2>
  <p>This isn't just another LeetCode dump. Each solution is carefully explained so you can learn <strong>why</strong> we do what we do. Whether you're preparing for FAANG interviews or brushing up on algorithms, this repo will help you think like a problem solver.</p>

  <h2>🙌 Contributions</h2>
  <p>Contributions are welcome! If you'd like to add a new problem or improve an existing one, feel free to open a PR or issue.</p>

  <h3>Contribution Guidelines:</h3>
  <ul>
    <li>Follow the folder structure.</li>
    <li>Write clear explanations.</li>
    <li>Include time and space complexity.</li>
    <li>Provide example test cases.</li>
    <li>Keep code readable and well-commented.</li>
  </ul>

  <h2>📢 Shoutouts</h2>
  <p>Special thanks to <a href="https://leetcode.com/"  target="_blank">LeetCode</a> for providing such an amazing platform for practice.</p>

  <h2>📬 Feedback</h2>
  <p>If you have any suggestions or find something that needs improvement, please reach out via email or LinkedIn.</p>

  <h2>📝 License</h2>
  <p>MIT License – see <code>LICENSE</code> for details.</p>

  <p>Let's unlock every problem together. 💪<br/>
  Happy coding!</p>

</div>

</body>
</html>
