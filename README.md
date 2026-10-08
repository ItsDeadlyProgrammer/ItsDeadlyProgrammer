<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f6feb&height=170&section=header&text=Harshvardhan%20Singh&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Software%20Engineer%20%C2%B7%20Kotlin%20%C2%B7%20Android%20%C2%B7%20Competitive%20Programmer&descSize=16&descAlignY=60" width="100%" alt="Harshvardhan Singh" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=620&lines=I+build+systems+where+the+code+proves+the+result.;Android+%26+Kotlin+Multiplatform+apps+with+Jetpack+Compose;C%2B%2B+competitive+programmer+%C2%B7+2000%2B+problems+solved;Ktor+backends+%C2%B7+Redis+%C2%B7+Docker+sandboxes" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/harshvardhan-singh-49969b242/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:hvsr29march2004@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/CodeChef-4★%201805-5B4638?style=flat-square&logo=codechef&logoColor=white" alt="CodeChef 4 star">
  <img src="https://img.shields.io/badge/LeetCode-Knight%201935-FFA116?style=flat-square&logo=leetcode&logoColor=black" alt="LeetCode Knight">
  <img src="https://img.shields.io/badge/Codeforces-Specialist%201412-03A89E?style=flat-square&logo=codeforces&logoColor=white" alt="Codeforces Specialist">
</p>

<br>

```kotlin
object Harshvardhan {
    val education  = "B.Tech CSE @ IIIT Bhopal  ·  CGPA 9.29"
    val role       = "Software Engineer  ·  Android & Kotlin"
    val building   = listOf("LLM-powered developer tools", "Online judges", "Kotlin Multiplatform apps")
    val principle  = "The LLM proposes. The sandbox proves."
    val strengths  = setOf("Kotlin", "C++", "Android", "Data Structures & Algorithms")
    val openTo     = "SDE internships & full-time roles"
    val reachMe    = "hvsr29march2004@gmail.com"
}
```

<br>

## Featured Work

<table>
  <tr>
    <td width="52%" valign="middle">
      <a href="https://stressbugger.netlify.app"><img src="https://raw.githubusercontent.com/ItsDeadlyProgrammer/stressbugger-portfolio/main/screenshots/session-dashboard.png" alt="StressBugger dashboard" /></a>
    </td>
    <td width="48%" valign="top">
      <sub>01 &nbsp;·&nbsp; AI DEVELOPER TOOL</sub>
      <h3>StressBugger</h3>
      <i>Finds the exact input that breaks your competitive-programming solution.</i>
      <ul>
        <li>An LLM writes test generators, checkers and brute forces; each must compile, pass samples and agree with the others before it is trusted</li>
        <li>Stress-tests <b>~1,000 inputs per minute</b> in a hardened Docker sandbox (C++, Java, Python)</li>
        <li>Shrinks failures to a minimal counterexample and only marks a fix <b>verified</b> after re-running it</li>
      </ul>
      <p><code>Java 21</code> <code>Spring Boot</code> <code>Spring AI</code> <code>React</code> <code>PostgreSQL</code> <code>Redis</code> <code>Docker</code></p>
      <a href="https://stressbugger.netlify.app"><img src="https://img.shields.io/badge/Live_Demo-1f6feb?style=for-the-badge" alt="Live demo" /></a>
      <a href="https://github.com/ItsDeadlyProgrammer/stressbugger-portfolio"><img src="https://img.shields.io/badge/Case_Study-21262d?style=for-the-badge&logo=github" alt="Case study" /></a>
    </td>
  </tr>
  <tr>
    <td width="48%" valign="top">
      <sub>02 &nbsp;·&nbsp; ONLINE JUDGE</sub>
      <h3>CodeForge</h3>
      <i>An online judge built from scratch: Codeforces problems in, sandboxed verdicts out.</i>
      <ul>
        <li>Compiles once, then runs every test with <b>CPU, memory and output limits</b>, reporting the program's real peak memory</li>
        <li><b>Crash-safe queue:</b> PostgreSQL leases with a reaper; Redis only wakes the workers</li>
        <li>A <b>Docker container per submission</b> when self-hosted; <b>one Kotlin codebase</b> ships Web (Wasm), Android and Desktop</li>
      </ul>
      <p><code>Kotlin</code> <code>Ktor</code> <code>Compose Multiplatform</code> <code>PostgreSQL</code> <code>Redis</code> <code>Docker</code></p>
      <a href="https://super-lolly-fd22a7.netlify.app/"><img src="https://img.shields.io/badge/Live_Demo-1f6feb?style=for-the-badge" alt="Live demo" /></a>
      <a href="https://github.com/ItsDeadlyProgrammer/Codeforge-Portfolio"><img src="https://img.shields.io/badge/Case_Study-21262d?style=for-the-badge&logo=github" alt="Case study" /></a>
    </td>
    <td width="52%" valign="middle">
      <a href="https://super-lolly-fd22a7.netlify.app/"><img src="https://raw.githubusercontent.com/ItsDeadlyProgrammer/Codeforge-Portfolio/main/screenshots/dashboard.png" alt="CodeForge: an accepted C++ submission with three passed test cases" /></a>
    </td>
  </tr>
  <tr>
    <td width="52%" valign="middle">
      <a href="https://verdant-cat-fac52f.netlify.app/"><img src="https://raw.githubusercontent.com/ItsDeadlyProgrammer/OperatingSystem-Portfolio/main/screenshots/process_scheduling.png" alt="OS Simulator process scheduling" /></a>
    </td>
    <td width="48%" valign="top">
      <sub>03 &nbsp;·&nbsp; SYSTEMS VISUALIZER</sub>
      <h3>OS Simulator</h3>
      <i>Operating systems concepts you can watch run.</i>
      <ul>
        <li>CPU scheduling (FCFS, SJF, SRTF, Round Robin, Priority) with live <b>Gantt charts</b> and waiting/turnaround metrics</li>
        <li>Deadlock detection on resource allocation graphs with <b>Banker's algorithm</b> safe sequences</li>
        <li>Memory allocation (First, Best, Worst, Next Fit) with fragmentation analysis</li>
      </ul>
      <p><code>Kotlin Multiplatform</code> <code>Compose</code> <code>Wasm</code> <code>MVVM</code></p>
      <a href="https://verdant-cat-fac52f.netlify.app/"><img src="https://img.shields.io/badge/Live_Demo-1f6feb?style=for-the-badge" alt="Live demo" /></a>
      <a href="https://github.com/ItsDeadlyProgrammer/OperatingSystem-Portfolio"><img src="https://img.shields.io/badge/Case_Study-21262d?style=for-the-badge&logo=github" alt="Case study" /></a>
    </td>
  </tr>
</table>

<p align="center"><sub>Source code for these projects is private. Recruiters and reviewers can <a href="mailto:hvsr29march2004@gmail.com">email me</a> for access.</sub></p>

<br>

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=kotlin,cpp,c,androidstudio,flutter,ktor,java,py,spring,postgres,redis,docker,git,githubactions,linux&perline=15" alt="Tech stack" />
</p>

<table>
  <tr>
    <td width="22%"><b>Languages</b></td>
    <td><code>Kotlin</code> <code>C++</code> <code>C</code> <code>Java</code> <code>Python</code> <code>TypeScript</code> <code>JavaScript</code> <code>Dart</code> <code>SQL</code></td>
  </tr>
  <tr>
    <td><b>CS Core</b></td>
    <td><code>Data Structures</code> <code>Algorithms</code> <code>Competitive Programming</code> <code>Operating Systems</code> <code>DBMS</code> <code>OOP</code></td>
  </tr>
  <tr>
    <td><b>Mobile &amp; Frontend</b></td>
    <td><code>Jetpack Compose</code> <code>Compose Multiplatform</code> <code>Android</code> <code>Flutter</code> <code>React</code></td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td><code>Ktor</code> <code>Spring Boot</code> <code>Spring AI</code> <code>Spring Security</code> <code>JPA / Hibernate</code> <code>Node.js</code> <code>REST</code> <code>WebSockets</code> <code>SSE</code></td>
  </tr>
  <tr>
    <td><b>Data</b></td>
    <td><code>PostgreSQL</code> <code>pgvector</code> <code>MySQL</code> <code>Redis</code> <code>Firebase</code> <code>Cypher</code></td>
  </tr>
  <tr>
    <td><b>DevOps</b></td>
    <td><code>Docker</code> <code>GitHub Actions</code> <code>Gradle</code> <code>Git</code> <code>Linux</code> <code>Netlify</code> <code>Render</code></td>
  </tr>
  <tr>
    <td><b>AI / ML</b></td>
    <td><code>PyTorch</code> <code>Transformers</code> <code>scikit-learn</code> <code>LLM integration</code> <code>Ollama</code> <code>Gemini</code></td>
  </tr>
  <tr>
    <td><b>Testing</b></td>
    <td><code>JUnit 5</code> <code>MockK</code> <code>JaCoCo</code> <code>OpenAPI / Swagger</code></td>
  </tr>
</table>

<br>

## GitHub Activity

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=ItsDeadlyProgrammer&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" alt="GitHub stats" />
  <img height="160" src="https://streak-stats.demolab.com?user=ItsDeadlyProgrammer&theme=github-dark-blue&hide_border=true" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:0d1117&height=100&section=footer" width="100%" alt="" />
</p>
