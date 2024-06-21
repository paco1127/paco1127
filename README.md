<h1 align="center">Hi 👋, I'm Paco</h1>
<h3 align="center">A passionate software developer from Hong Kong</h3>


# 💫 Currently:
🔭 I’m currently working on <a href="https://github.com/paco1127/Pure-Blur" target="_blank">Pure Blur</a></h3>
<p align="center">
  <a href="http://www.youtube.com/watch?v=w-lueXyo7WE">
    <img src="http://img.youtube.com/vi/w-lueXyo7WE/0.jpg" alt="Pure Blur Intro">
  </a><br>
</p>

# About Paco Chung

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Paco Chung</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace;
            background-color: #2d2d2d;
            color: #f8f8f2;
            padding: 20px;
        }
        .code-container {
            white-space: pre;
            overflow: hidden;
            border-right: .15em solid orange;
            width: 30ch;
            animation: caret 1s steps(1) infinite;
        }
        @keyframes caret {
            50% {
                border-color: transparent;
            }
        }
    </style>
</head>
<body>

<div class="code-container" id="codeDisplay"></div>

<script>
    const pythonCode = `
def personal_info():
    info = {
        "name": "Paco Chung",
        "linkedin": "https://www.linkedin.com/in/paco-chung-11719827b/",
        "profession": "Software Developer",
        "skills": ["Python", "Java", "JavaScript", "C++", "SQL"],
        "achievements": ["Developed multiple high-traffic web applications", "Led a team in successful project completions", "Published articles on software development best practices"]
    }
    return info

print(personal_info())
`;

    const javaCode = `
import java.util.ArrayList;
import java.util.HashMap;

public class PersonalInfo {
    public static HashMap<String, Object> getPersonalInfo() {
        HashMap<String, Object> info = new HashMap<>();

        info.put("name", "Paco Chung");
        info.put("linkedin", "https://www.linkedin.com/in/paco-chung-11719827b/");
        info.put("profession", "Software Developer");

        ArrayList<String> skills = new ArrayList<>();
        skills.add("Python");
        skills.add("Java");
        skills.add("JavaScript");
        skills.add("C++");
        skills.add("SQL");
        info.put("skills", skills);

        ArrayList<String> achievements = new ArrayList<>();
        achievements.add("Developed multiple high-traffic web applications");
        achievements.add("Led a team in successful project completions");
        achievements.add("Published articles on software development best practices");
        info.put("achievements", achievements);

        return info;
    }

    public static void main(String[] args) {
        System.out.println(getPersonalInfo());
    }
}
`;

    const jsCode = `
function getPersonalInfo() {
    return {
        name: "Paco Chung",
        linkedin: "https://www.linkedin.com/in/paco-chung-11719827b/",
        profession: "Software Developer",
        skills: ["Python", "Java", "JavaScript", "C++", "SQL"],
        achievements: ["Developed multiple high-traffic web applications", "Led a team in successful project completions", "Published articles on software development best practices"]
    };
}

console.log(getPersonalInfo());
`;

    const codes = [pythonCode, javaCode, jsCode];
    let codeIndex = 0;
    let charIndex = 0;
    const speed = 50; // typing speed in milliseconds

    function typeCode() {
        if (charIndex < codes[codeIndex].length) {
            document.getElementById("codeDisplay").innerText += codes[codeIndex].charAt(charIndex);
            charIndex++;
            setTimeout(typeCode, speed);
        } else {
            setTimeout(deleteCode, 1000); // wait 1 second before deleting
        }
    }

    function deleteCode() {
        if (charIndex > 0) {
            document.getElementById("codeDisplay").innerText = codes[codeIndex].substring(0, charIndex - 1);
            charIndex--;
            setTimeout(deleteCode, speed);
        } else {
            codeIndex = (codeIndex + 1) % codes.length;
            setTimeout(typeCode, 500); // wait 0.5 second before typing next code
        }
    }

    typeCode(); // start the typewriter effect
</script>

</body>
</html>
```




## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/paco-chung-11719827b) 

# 💻 Tech Stack:
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white) ![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300000f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-streak-stats.herokuapp.com/?user=paco1127&theme=gotham&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=paco1127&theme=gotham&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=paco1127&theme=radical&rank=SSS,SS,S,A&no-frame=true&no-bg=false&margin-w=4)


### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=merko)

---
![](https://komarev.com/ghpvc/?username=paco1127&label=Views&color=ff69b4)

  ## 💰 You can help me by Donating
  [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/paco1127) 

  
<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
