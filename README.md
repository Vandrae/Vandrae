<h1 align="center">Hi, I'm Gabe 👋</h1>

<p align="center">
  <b>Entry-level Java backend developer</b> · Dallas, TX<br>
  I build REST APIs with Spring Boot and MySQL, and I put them on the internet.
</p>

<p align="center">
  <a href="https://patchnoteaggregator.com"><b>▶ Live project</b></a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/gabriel-carroll/">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:Carrollgbusiness@gmail.com">Email</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
</p>

---

## About me

I came to software from retail and warehouse work, through [Year Up](https://www.yearup.org/)'s Application Development program, and
I've been building in public since April 2026: from Java basics and SQL to Spring Boot APIs and a site that is live on AWS.

I use AI coding assistants to learn, debug and review. I read, test and can explain every change I ship.

**Looking for:** an entry-level Java / backend developer role where I can keep growing on a team.

---

## ⭐ Featured: Game Patch Notes Aggregator

<a href="https://github.com/Vandrae/patch-notes-aggregator/actions/workflows/ci.yml"><img src="https://github.com/Vandrae/patch-notes-aggregator/actions/workflows/ci.yml/badge.svg" alt="CI status"></a>

**Follow the games you play and read their official patch notes in one feed.** Search about 190,000 Steam games, plus Roblox,
Minecraft, League of Legends and VALORANT, sign in with Steam, or just browse as a guest.

**[patchnoteaggregator.com](https://patchnoteaggregator.com)** · [Source code](https://github.com/Vandrae/patch-notes-aggregator) · [How it works](https://github.com/Vandrae/patch-notes-aggregator/tree/main/docs)

<table>
  <tr>
    <td width="50%"><img src="assets/discover.jpg" alt="Discover: a grid of game covers; pointing at one shows its rating, genres and a Watch button"></td>
    <td width="50%"><img src="assets/feed.jpg" alt="The feed: patch notes from every game you follow, newest first"></td>
  </tr>
</table>

- **Backend:** Java 21, Spring Boot, Spring Security, JPA, Flyway, MySQL. Steam OpenID sign-in, JWT sessions in HttpOnly cookies, CSRF protection and rate limiting.
- **Background jobs:** fetches and normalizes patch notes from five different sources into one format, polling only the games someone follows, on an adaptive schedule.
- **Quality:** 350+ automated tests, including tests against a real MySQL database. Four required checks run in GitHub Actions on every pull request, and `main` is protected.
- **Shipping:** Docker Compose with Caddy for automatic HTTPS, running on an AWS EC2 server with nightly backups. Dependabot and secret scanning are on.

---

## 🛠️ More projects

| Project | What it is | Built with |
|---|---|---|
| [**Helix Bioworks API**](https://github.com/Vandrae/helix-bioworks-api) | REST API for a fictional bioengineering company's orders: layered controller → service → repository design, JPA relationships, and full create / read / update / delete endpoints. 80 commits. | Java · Spring Boot · MySQL · JPA |
| [**E-Commerce REST API**](https://github.com/Vandrae/e-commerce-api) | Added JWT authentication and role-based admin access to an existing storefront backend, plus CRUD for products, categories and cart; fixed search and inventory bugs in the inherited code. | Java · Spring Security · MySQL |
| [**Accounting Ledger**](https://github.com/Vandrae/accounting-ledger) | Team project: a console finance tracker with CSV storage and date-based reports, built with feature branches and pull requests. | Java · File I/O · Git |
| [**ThreatDiff**](https://github.com/Vandrae/threat-diff) | A World of Warcraft addon that shows how much threat you have on each enemy and how close you are to pulling aggro. [On CurseForge](https://www.curseforge.com/wow/addons/threatdiff). | Lua |

---

## 📈 How I got here

My public repositories tell the story:

`Apr` Java fundamentals → `May` object-oriented design, file I/O and Git → `Jun` SQL and first Spring Boot APIs →
`Jul–Sep` larger REST APIs → `Oct` a live AWS deployment

---

<p align="center">
  <a href="https://www.linkedin.com/in/gabriel-carroll/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:Carrollgbusiness@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>
