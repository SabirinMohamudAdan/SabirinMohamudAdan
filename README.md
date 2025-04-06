# 👋 Hi, I'm Sabirin Mohamud Adan

🚀 **About Me**  
I'm a Full-Stack Developer with expertise in the MERN (MongoDB, Express, React, Node.js) Stack. Passionate about web development,  
I enjoy crafting scalable, efficient, and user-friendly solutions. Always eager to explore new technologies,  
I strive to improve my skills and stay ahead in the ever-evolving tech landscape.

💻 **Currently working on:** Full-stack applications using React, Node.js, PHP  

🔍 **Ask me about:** JavaScript, React, Node.js, PHP, Spring Boot, and MERN Stack.  

📬 **Reach out at:** sabrinmohamud247@gmail.com  

---

🛠 **Tech Stack & Tools**
<p align="left">
   <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white"/>
   <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white"/>
   <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black"/>
   <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black"/>
   <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white"/>
   <img src="https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white"/>
   <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white"/>
   <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white"/>
   <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white"/>
   <img src="https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white"/>
   <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white"/>
</p>

---




<!DOCTYPE html>
<html>
<head>
  <title>My Repo Collaborators</title>
  <style>
    .collab { display: flex; align-items: center; margin: 10px; }
    img { width: 50px; border-radius: 50%; margin-right: 10px; }
  </style>
</head>
<body>
  <h1>🛠️ My GitHub Collaborators</h1>
  <div id="collabs"></div>
  <script>
    fetch("https://api.github.com/repos/YOUR_USERNAME/REPO_NAME/collaborators", {
      headers: { "Authorization": "token YOUR_TOKEN" }
    })
      .then(res => res.json())
      .then(data => {
        let html = "";
        data.forEach(user => {
          html += `
            <div class="collab">
              <img src="${user.avatar_url}" alt="${user.login}">
              <a href="${user.html_url}" target="_blank">${user.login}</a>
            </div>
          `;
        });
        document.getElementById("collabs").innerHTML = html;
      })
      .catch(err => console.error("Error:", err));
  </script>
</body>
</html>
https://gist.githubusercontent.com/YOUR_GIST_USERNAME/GIST_ID/raw/collaborators.html

## 📊 GitHub Stats  


[![Sabirin's GitHub Summary](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=SabirinMohamudAdan&theme=radical)](https://github.com/vn7n24fzkq/github-profile-summary-cards)


 

## 🏆 GitHub Contributions & Streak  





[![GitHub Contributions](https://github-readme-stats.vercel.app/api?username=SabirinMohamudAdan&show_icons=true&count_private=true&include_all_commits=true&theme=radical)](https://github.com/SabirinMohamudAdan)


## 📌 Most Used Languages  
 
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=SabirinMohamudAdan&layout=compact&theme=radical)](https://github.com/anuraghazra/github-readme-stats)




### 🚀 Most Technologies I Use  
<p align="left">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white"/>
</p>
