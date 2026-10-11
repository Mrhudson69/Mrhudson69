
README.md
README.md
MD
Update my github portfolio - 

design something animations like terminal which is trending nowadays. shows tridng things on my profolion whihc no one ever done till now which looks and amazing also update it according to my exeprcice and work add AWS devops certified as wlell

Choosing reliable image hosting and linking for the SVGs.
I’ll build you a custom animated SVG terminal plus a live packet-flow topology panel — both hand-written, not from the usual readme-generator services — and rewrite the README around your real infrastructure work.

Created 3 files, shared 3 files, read memory
Three files, all hand-written SVG/markdown — no generator services, so nothing looks like the other 10,000 profiles.

Install — repo Mrhudson69/Mrhudson69, branch main:

README.md
assets/terminal.svg
assets/topology.svg
bash
mkdir -p assets
# drop terminal.svg and topology.svg into assets/, README.md at repo root
git add README.md assets/
git commit -m "feat: animated terminal + live topology profile"
git push
What’s new

terminal.svg — a real typewriter effect built from staggered steps() wipes, not a typing-SVG API call. Commands type character-by-character with a cursor riding the line; output lines print instantly, the way a shell actually behaves. Ends on a blinking prompt. 13s loop, ~0 bytes of JS.
topology.svg — this is the part nobody does. SMIL animateMotion packets flowing internet → nginx → Proxmox/GoCD/StarRocks → data layer, with dashed Prometheus scrape lines marching upward and node borders breathing on a 6s cycle. It’s your actual architecture, animated.
README — restructured as shell commands ($ whoami, $ git log --oneline), stack corrected to what you actually run (Proxmox, GoCD, Mimir, ClickHouse/StarRocks, Flink CDC, Greenbone, OpenObserve) instead of the generic AWS/K8s/Jenkins list, and an “Open to” line targeting DevOps/SRE/Platform in NCR + Germany.
One thing to check: I listed the cert as AWS Certified DevOps Engineer – Professional, the official AWS title. If yours is actually a Udemy/Coursera DevOps course rather than the AWS exam, change that line — recruiters verify Professional-level certs against AWS’s registry and a mismatch hurts more than the badge helps.

Both SVGs are referenced by absolute raw.githubusercontent.com URLs rather than relative paths — GitHub’s camo proxy serves those byte-for-byte so the CSS and SMIL animations survive. Relative paths work too but occasionally get sanitized.


Terminal
Image·SVG 

Topology
Image·SVG 

Readme
Document·MD 
1791704338776_image.png
78916631.jpeg
I need somthing like this mathces to my profile on top my github profile. animated render top to boottom make this SVG Use my photo as left side covert my photo into terminal charahter and on side my skills experience etc

Building a neofetch-style SVG with ASCII art and animation.
Building a neofetch-style SVG with ASCII art and animation.
I’ll turn your photo into ASCII art and build a neofetch-style SVG that renders line by line from top to bottom.

Shared 2 files, created a file, and 40 more steps
Your photo is now a colour ASCII portrait inside a neofetch-style kitty window, in your Catppuccin colours.

How it plays:

❯ neofetch types itself in.
Your portrait renders one row at a time from top to bottom, with a green scanline sweeping down ahead of it.
The info panel lines appear as the scan reaches their height.
It ends on a blinking prompt.
It plays once in about 3.5s and stays finished. I removed the background around you so the hood, lamp and beard show clearly, and coloured each character with the real colour from your photo.

Right panel: role, host, uptime (4+ yrs), estate (4 orgs, 95+ domains, ~1M req/day), then rows for cloud, CI/CD, IaC, observability, data, stream, edge, security and shell. Below those are certs (AWS Certified DevOps Engineer · CCNA), education, open-to-work status and email, plus the colour-palette strip.

Install in your repo Mrhudson69/Mrhudson69:

bash
cp neofetch.svg assets/neofetch.svg
cp README.md README.md
git add README.md assets/neofetch.svg
git commit -m "feat: neofetch ASCII portrait header"
git push
terminal.svg is no longer in the header. You can delete it, or keep it lower in the README under $ whoami if you like the typing effect.

Caveats:

GitHub caches images. If the old header still shows after you push, add ?v=2 to the end of the image URL in the README.
The animation is plain SVG with CSS and SMIL, no JavaScript, so it works in GitHub’s image proxy. The text uses whatever monospace font the viewer has installed. Each portrait row is stretched to a fixed width, so the portrait stays aligned no matter which font is used.

Readme
Document·MD 

Neofetch
Image·SVG 



Claude is AI and can make mistakes.


Readme · MD
<div align="center">
<img src="https://raw.githubusercontent.com/Mrhudson69/Mrhudson69/main/assets/neofetch.svg" width="100%" alt="neofetch — ASCII portrait of Rohan Sirohi with DevOps stack and experience" />
<br/>
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/starboyjaat)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rohansirohi5@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Mrhudson69)
![Profile views](https://komarev.com/ghpvc/?username=Mrhudson69&style=flat-square&color=3fb950&label=visitors)
 
</div>
---
 
## `$ whoami`
 
DevOps & Infrastructure Engineer with **4+ years** running production systems end to end — bare-metal Proxmox clusters through to CI/CD, observability and edge security.
 
Founding infrastructure engineer at **Spraxa Solutions (Noida)**, where I own production infrastructure across **four organisations** — Stream4Tech, Spraxa, Coolr and Volza.
 
> `Automate everything. Monitor everything. Then alert on what actually matters.`
 
**Open to:** DevOps / SRE / Platform / Cloud Engineer roles — Delhi NCR (hybrid or remote) and Germany (relocation ready).
 
---
 
## `$ cat infrastructure.yaml`
 
<div align="center">
<img src="https://raw.githubusercontent.com/Mrhudson69/Mrhudson69/main/assets/topology.svg" width="760" alt="Live infrastructure topology with animated request flow" />
</div>
| | |
|---|---|
| **Organisations** | 4 production estates — Stream4Tech · Spraxa · Coolr · Volza |
| **Edge** | 95+ domains behind nginx reverse proxy, automated TLS |
| **Traffic** | ~1M requests / day |
| **Delivery** | 100+ GoCD pipelines — Node.js, .NET, containers, rollbacks |
| **Virtualisation** | Multi-node Proxmox clusters — LXC, VMs, HA, vzdump + fleecing |
| **Observability** | Prometheus · Grafana · Mimir · Alertmanager · OpenObserve |
| **Security** | Greenbone/OpenVAS + OWASP ZAP scanning, NSG/firewall review, patch policy |
 
---
 
## `$ ls -1 skills/`
 
**Cloud & Virtualisation**
<br/>
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
 
**Automation & CI/CD**
<br/>
![GoCD](https://img.shields.io/badge/GoCD-94399E?style=flat-square&logo=gocd&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
 
**Observability**
<br/>
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Mimir](https://img.shields.io/badge/Mimir-F46800?style=flat-square&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F46800?style=flat-square&logo=grafana&logoColor=white)
 
**Data**
<br/>
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![StarRocks](https://img.shields.io/badge/StarRocks-00A1E0?style=flat-square&logo=apachespark&logoColor=white)
![Flink](https://img.shields.io/badge/Flink_CDC-E6526F?style=flat-square&logo=apacheflink&logoColor=white)
 
**Systems, Network & Security**
<br/>
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)
![OpenVAS](https://img.shields.io/badge/Greenbone_OpenVAS-5C9E31?style=flat-square&logo=shield&logoColor=white)
![ZAP](https://img.shields.io/badge/OWASP_ZAP-00549E?style=flat-square&logo=owasp&logoColor=white)
![SoftEther](https://img.shields.io/badge/VPN_SoftEther-1E88E5?style=flat-square&logo=wireguard&logoColor=white)
 
---
 
## `$ git log --oneline --author=rohan`
 
**Zero-touch CI/CD platform** — 100+ GoCD pipelines for Node.js and .NET services with automated rollback and environment promotion.
<br/>→ [Install-go-agent-in-linux-container](https://github.com/Mrhudson69/Install-go-agent-in-linux-container)
 
**Centralised observability** — Prometheus/Grafana/Mimir across the whole estate, with alerting on uptime, service health, SSL expiry and MSSQL backup freshness.
<br/>→ [Devops-guide](https://github.com/Mrhudson69/Devops-guide)
 
**Production mail server in LXC** — Mailcow on Proxmox with automated TLS renewal, SPF/DKIM/DMARC.
<br/>→ [Mailcow-Setup-inside-LXC-Proxmox](https://github.com/Mrhudson69/Mailcow-Setup-inside-LXC-Proxmox)
 
**Remote desktop infrastructure** — XRDP inside Debian 12 containers for dev workstations.
<br/>→ [setup-xrdp-on-debian-12-container-lxc](https://github.com/Mrhudson69/setup-xrdp-on-debian-12-container-lxc)
 
---
 
## `$ cat certifications.txt`
 
- **AWS Certified DevOps Engineer – Professional**
- AWS Cloud Architecture — Coursera
- Cisco CCNA — Udemy
- BCA, CCS University
---
 
## `$ systemctl status github`
 
<div align="center">
<img height="150" src="https://github-readme-stats.vercel.app/api?username=Mrhudson69&show_icons=true&hide_border=true&bg_color=0d1117&title_color=3fb950&text_color=8b949e&icon_color=58a6ff" alt="GitHub stats" />
<img height="150" src="https://github-readme-streak-stats.herokuapp.com/?user=Mrhudson69&hide_border=true&background=0d1117&ring=3fb950&fire=d29922&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e" alt="Streak" />
</div>
---
 
<div align="center">
**rohansirohi5@gmail.com** · [linkedin.com/in/starboyjaat](https://linkedin.com/in/starboyjaat)
 
<sub><code>$ echo "I automate things so I don't have to do them twice."</code></sub>
 
</div>
 
Claude finished the response
