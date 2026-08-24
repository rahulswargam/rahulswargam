<div align="center">

```
██████╗  █████╗ ██╗  ██╗██╗   ██╗██╗         ██████╗ ███████╗██╗   ██╗ ██████╗ ██████╗ ███████╗
██╔══██╗██╔══██╗██║  ██║██║   ██║██║         ██╔══██╗██╔════╝██║   ██║██╔═══██╗██╔══██╗██╔════╝
██████╔╝███████║███████║██║   ██║██║         ██║  ██║█████╗  ██║   ██║██║   ██║██████╔╝███████╗
██╔══██╗██╔══██║██╔══██║██║   ██║██║         ██║  ██║██╔══╝  ╚██╗ ██╔╝██║   ██║██╔═══╝ ╚════██║
██║  ██║██║  ██║██║  ██║╚██████╔╝███████╗    ██████╔╝███████╗ ╚████╔╝ ╚██████╔╝██║     ███████║
╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚══════╝    ╚═════╝ ╚══════╝  ╚═══╝   ╚═════╝ ╚═╝     ╚══════╝
```

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=2800&pause=900&color=00C853&center=true&vCenter=true&multiline=true&repeat=true&width=780&height=100&lines=%24+whoami;rahul-swargam+%E2%80%94+devops+engineer;%24+kubectl+apply+-f+career.yaml;deployment.apps%2Frahul+configured+%E2%9C%94" alt="Typing SVG" />

</div>

<div align="center">

![Build](https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge&logo=githubactions&logoColor=white)
![Uptime](https://img.shields.io/badge/uptime-5%2B%20years-blue?style=for-the-badge&logo=statuspage&logoColor=white)
![Env](https://img.shields.io/badge/environment-production-critical?style=for-the-badge&logo=kubernetes&logoColor=white)
![Status](https://img.shields.io/badge/status-works%20on%20my%20machine-yellow?style=for-the-badge&logo=docker&logoColor=white)
![Coffee](https://img.shields.io/badge/fuel-coffee-6F4E37?style=for-the-badge&logo=buymeacoffee&logoColor=white)

</div>

---

### `Jenkinsfile` — pipeline: rahul-swargam

```groovy
pipeline {
    agent { label 'hyderabad-in' }

    stages {
        stage('Build') {
            steps { echo 'Learned infra automation the hard way: 2 AM pages.' }
        }
        stage('Test') {
            steps { sh 'validate --experience "5+ years" --domain "AWS, CI/CD, K8s"' }
        }
        stage('Deploy') {
            steps { echo 'Ships infrastructure so teams can ship product.' }
        }
        stage('Monitor') {
            steps { echo 'Dashboards open. Alerts on. Always watching.' }
        }
    }

    post {
        success { echo '✅ Available for interesting problems & new opportunities.' }
    }
}
```

---

## 🔀 The Pipeline (a.k.a. how I got here)

```mermaid
flowchart LR
    A[Learn] --> B[Build]
    B --> C[Break Prod]
    C --> D[3AM Page]
    D --> E[Fix]
    E --> F[Automate It<br/>So It Never Pages Again]
    F --> G[Ship]
    G --> H([Monitor])
    H -->|feedback loop| A

    style D fill:#e05252,stroke:#e05252,color:#fff
    style F fill:#00C853,stroke:#00C853,color:#fff
    style G fill:#2088FF,stroke:#2088FF,color:#fff
```

---

## 🧭 `kubectl get profile rahul -o yaml`

```yaml
apiVersion: devops/v1
kind: Engineer
metadata:
  name: rahul-swargam
  location: Hyderabad, India
  labels:
    role: devops-engineer
    experience: 5-plus-years
spec:
  focus:
    - automation
    - reliability
    - cloud-native-deployments
  currentGoal: ship-faster-break-less
status:
  phase: Running
  conditions:
    - type: Available
      status: "True"
      reason: OpenToOpportunities
```

---

## 🛠 Tech Stack — CI/CD View

<table>
<tr>
<td valign="top" width="50%">

**☁️ Infra as Code**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)

**🔄 CI/CD**

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</td>
<td valign="top" width="50%">

**🐳 Containers & Orchestration**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

**📊 Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![ELK](https://img.shields.io/badge/ELK-005571?style=for-the-badge&logo=elastic&logoColor=white)

**💻 Scripting & OS**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</td>
</tr>
</table>

---

## 📈 Live Metrics Dashboard

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=rahulswargam&show_icons=true&theme=react&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=rahulswargam&theme=react&hide_border=true" alt="GitHub Streak" height="165"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rahulswargam&layout=compact&theme=react&hide_border=true" alt="Top Languages" height="165"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=rahulswargam&theme=react-dark&hide_border=true" alt="Activity Graph" width="100%"/>

</div>

### 🐍 Deploying a snake to eat my own contribution graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rahulswargam/rahulswargam/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/rahulswargam/rahulswargam/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/rahulswargam/rahulswargam/output/github-contribution-grid-snake.svg" width="100%"/>
</picture>

<sub>generated nightly by <a href=".github/workflows/snake.yml">.github/workflows/snake.yml</a> — real CI/CD, eating real commit history</sub>

</div>

---

<details>
<summary>📜 <code>cat /etc/motd</code></summary>
<br/>

```
Last login: today from 127.0.0.1
Welcome to rahul-swargam-prod, an on-call human.

  * "It's not a bug, it's an undocumented feature of the rollback."
  * Uptime is a personality trait.
  * Terraform plan reviewed twice. Applied once. Prayed always.
  * Friday deploys require: passing tests, a rollback plan, and courage.
  * # this incident is now a runbook
```

</details>

---

## 🌐 Connect With Me

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-Website-0A1AFF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.rahulswargam.online)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rahul%20Swargam-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rahulswargam)
[![Email](https://img.shields.io/badge/Email-swargamrahul%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:swargamrahul@gmail.com)

</div>

---

<div align="center">

```bash
$ echo "Thanks for stopping by. Now go check my repos before the build breaks."
```

⭐ *Explore my repositories for real-world DevOps, cloud automation, and CI/CD implementations.*

<img src="https://komarev.com/ghpvc/?username=rahulswargam&style=for-the-badge&color=00C853&label=PROFILE+VIEWS" alt="Profile Views"/>

</div>
