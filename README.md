# 👋 Hi there, I'm Rashed

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=2F81F7&background=FFFFFF00&center=true&vCenter=true&width=440&lines=Backend+Developer;Problem+Solver;Tech+Enthusiast;Competitive+Programmer" alt="Typing SVG" />
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=rashed112&label=Profile%20views&color=2F81F7&style=for-the-badge" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/rashed112?label=Followers&style=for-the-badge&color=2F81F7" alt="GitHub Followers" />
</div>

---

## 🚀 About Me

```golang
package main

import "fmt"

type StatusProvider interface {
    Status() string
}

type Developer struct {
    Name         string            `json:"name"`
    Role         string            `json:"role"`
    Location     string            `json:"location"`
    Stack        []string          `json:"stack"`
    Interests    map[string]bool   `json:"interests"`
    CurrentGoals []string          `json:"current_goals"`
    Contact      string            `json:"contact"`
}

func NewBackendDev() *Developer {
    return &Developer{
        Name:     "Rashed",
        Role:     "Backend Developer & Problem Solver",
        Location: "Dhaka, Bangladesh 🇧🇩",
        Stack:    []string{"Go", "Node.js", "C++", "PostgreSQL", "Docker"},
        Interests: map[string]bool{
            "Microservices": true,
            "Open Source":   true,
            "Football":      true,
            "Anime":         true,
        },
        CurrentGoals: []string{
            "Mastering System Design & Microservices",
            "Building Scalable Backend Systems",
            "Excelling in Competitive Programming",
            "Contributing to Open Source",
        },
        Contact: "rashedzaman319@gmail.com",
    }
}

func (d *Developer) Status() string {
    return "🟢 Available for collaboration"
}

func main() {
    me := NewBackendDev()
    var provider StatusProvider = me
    fmt.Printf("Hi! I'm %s - %s\n", me.Name, provider.Status())
}
```

---

## 🛠️ Tech Stack

### Languages
<div align="left">
  <img src="https://skillicons.dev/icons?i=cpp,c,go,js,java,ts,python" alt="Languages" />
</div>

### Backend Ecosystem & Databases
<div align="left">
  <img src="https://skillicons.dev/icons?i=spring,nodejs,express,mongodb,mysql,postgresql,graphql,redis" alt="Backend Ecosystem & Databases" />
</div>

### DevOps & Tools
<div align="left">
  <img src="https://skillicons.dev/icons?i=git,github,arch,postman,docker" alt="DevOps & Tools" />
</div>

<!--### Frontend (Bonus Skills)
<div align="left">
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,bootstrap" alt="Frontend" />
</div>-->

---

## 🏆 Competitive Programming

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://codeforces.com/profile/mrashedz" target="_blank">
          <img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"/>
        </a>
      </td>
      <td align="center">
        <a href="https://www.leetcode.com/mrashedz" target="_blank">
          <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/>
        </a>
      </td>
      <td align="center">
        <a href="https://www.codechef.com/users/rashed112" target="_blank">
          <img src="https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef"/>
        </a>
      </td>
      <td align="center">
        <a href="https://www.hackerrank.com/mrashed" target="_blank">
          <img src="https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white" alt="HackerRank"/>
        </a>
      </td>
    </tr>
  </table>
</div>

---

## 🤝 Connect With Me

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://linkedin.com/in/md-rashed" target="_blank">
          <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
        </a>
      </td>
      <td align="center">
        <a href="mailto:rashedzaman319@gmail.com">
          <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/rashed112" target="_blank">
          <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
        </a>
      </td>
    </tr>
  </table>
</div>

---

## 📊 GitHub Analytics

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=rashed112&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rashed112&layout=compact&langs_count=8&theme=tokyonight"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rashed112&theme=tokyonight" alt="GitHub Streak"/>
</div>

<!--<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=rashed112&theme=tokyo-night&hide_border=true" alt="Contribution Graph"/>
</div>-->

---
<!--
## 🎯 Current Goals

- 🔍 **Learning**: Advanced System Design & Microservices Architecture
- 🚀 **Building**: Scalable APIs and Backend Systems
- 🏆 **Competing**: Regular participation in competitive programming contests
- 🌟 **Contributing**: More open-source projects
- 📚 **Sharing**: Technical knowledge through blog posts and tutorials

---
-->
<!--
<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random Dev Quote"/>
</div>

---
-->
<!--<div align="center">
  <h3>Thanks for visiting! 😊</h3>
  <p>Feel free to connect with me and let's build something amazing together!</p>
  
  ⭐️ From [rashed112](https://github.com/rashed112)
</div>-->
