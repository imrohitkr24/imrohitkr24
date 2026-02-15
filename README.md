# Hi 👋, I'm Rohit Kumar
💻 Full Stack Developer | ⚙️ Backend & System Design Learner | 🎓 B.Tech CSE (2027) | 🚀 Turning Ideas into Production-Ready Applications

---

## 🧑‍💻 About Me
- 🌱 Currently Focused on enhancing problem solving skills by practicing  Data Structures & Algorithms using Java.
- 🔥 Building real-world projects using MERN Stack
- 🎯 Goal: Software Developer at Product-Based Company
- 📫 How to reach me: imrohitkr24@gmail.com

---

## 🚀 Tech Stack

### 💻 Programming
- Java
- DSA
- Java Script

### 🌐 Web Development
- HTML
- CSS
- Tailwind CSS
- Node.js
- Express.js
- MongoDB

---

## 📌 Featured Projects
🔹 Environment Pollution Management System  
🔹 Sachi-Ghani Musturd oil   
🔹 Real-Time Process Monitoring Dashboard  

---

## 🧠 Competitive Programming & Coding Profiles

<p align="center">
  <a href="https://leetcode.com/u/imrohitkr24/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-Rohit240803-orange?style=for-the-badge&logo=leetcode&logoColor=white" />
  </a>

  <a href="https://www.hackerrank.com/profile/imrohitkr24" target="_blank">
    <img src="https://img.shields.io/badge/HackerRank-rks9835070230-green?style=for-the-badge&logo=hackerrank&logoColor=white" />
  </a>
</p>



# 🎮 AlgoWar – Mini DSA Battle Game ⚔️🧠

> Choose the correct algorithm to defeat the enemy!

<div align="center">

<h3 id="enemy">🐉 Enemy: Dynamic Programming Dragon</h3>
<p id="health">Enemy Health: 100 ❤️</p>

<button onclick="attack('Binary Search')">⚡ Binary Search</button>
<button onclick="attack('DFS')">🌳 DFS</button>
<button onclick="attack('Dynamic Programming')">🧠 Dynamic Programming</button>
<button onclick="attack('Greedy')">🎯 Greedy</button>

<p id="result"></p>

</div>

<script>
let health = 100;
const correctAlgorithm = "Dynamic Programming";

function attack(choice) {
    if (health <= 0) return;

    if (choice === correctAlgorithm) {
        health -= 40;
        document.getElementById("result").innerHTML =
            "🔥 Correct! Super Effective Attack!";
    } else {
        health -= 10;
        document.getElementById("result").innerHTML =
            "❌ Weak Attack! Wrong Algorithm!";
    }

    if (health <= 0) {
        document.getElementById("enemy").innerHTML =
            "🏆 Enemy Defeated! You Mastered DP!";
        document.getElementById("health").innerHTML = "Enemy Health: 0 ❤️";
    } else {
        document.getElementById("health").innerHTML =
            "Enemy Health: " + health + " ❤️";
    }
}
</script>

---

### 🚀 About This Game
AlgoWar is a fun DSA battle simulation where algorithms act as weapons.
Choosing the correct algorithm defeats the enemy faster.

⚡ Focus: Algorithm Selection  
🧠 Skill: Logical Thinking  
🎯 Goal: Master Problem Patterns  

---

💻 Built with HTML + JavaScript  
🔥 Created by Rohit Kumar
