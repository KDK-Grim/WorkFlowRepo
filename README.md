<link rel="stylesheet" type="text/css" href="custom.css">
<div align="center">
  <img  
	  src="https://raw.githubusercontent.com/KDK-Grim/WorkFlowRepo-Mirror/master/docs/ticker-bot/ticker.gif" 
  alt="Repo Ticker Stats" 
  style="height:33px;" />
  <div align="center">
  <img  
	  src="https://img.shields.io/github/stars/statikfintechllc/WorkFlowRepo?style=social" alt="Stars"/>
  <img  
	  src="https://img.shields.io/github/forks/statikfintechllc/WorkFlowRepo?style=social" alt="Forks"/>
  <img  
	  src="https://img.shields.io/github/last-commit/statikfintechllc/WorkFlowRepo?style=social" alt="Last Commit"/>
</div>
  
# WorkFlowRepo

</div>

> [!CAUTION]
>
> Just workflows, charts, banners, and traffic data lives here.
>
> More as We Need them.
>
> Clone/Mirror these flows in your own Repos to show banners and Graphs.
>
> Just change Naming Conventions to align with you're Systems.
>
> *(Instructions below)*

Use:

```bash
# Clone the repo
git clone https://github.com/statikfintechllc/WorkFlowRepo.git
cd WorkFlowRepo
ls
cd .github/workflows
ls
cd .. && cd ..
cd docs
ls
cd ticker-bot
ls && cd ..
cd graph
ls
cd .. && cd ..
```

> [!IMPORTANT]
>
> The above fully Installs, and Displays in terminal *ALL* folder content.
> To ensure easy navigation.

---

<details>
<summary>🔎 Expand for Setup 🔍</summary>

## 🧷 STEP 1: Create Your GitHub Personal Access Token (PAT)

1.	Go to: `https://github.com/settings/tokens` → Fine-grained tokens

2.	Click → Generate new token

3.	Set Token name: workflow-access

4.	Expiration: No expiration

5.	Select Repo: choose your target repo

6.	Permissions:
- ✅ Contents: Read and Write
- ✅ Metadata: Read-only

7.	Generate token → Copy it

--- 

## 🔒 STEP 2: Save as a Repository Secret

1.	Go to your repo:
`https://github.com/<your-username>/<your-repo>/settings/secrets/actions`

2.	Click → New repository secret
- Name: PAT_GITHUB
- Value: (Paste the token you copied)

---

## 🧬 STEP 3: Edit Workflow .yml Files

1.    Find and update Lin 31 in the traffic_graph.yml workflow file change:

```yml
REPO: statikfintechllc/AscendAI
```

> To match you're repo's naming.

---

## 🗃️ Files to Modify:

### Inside docs/ticker-bot/fetch_stats.py, Update lines 9-16:

```python
REPOS = [
    "statikfintechllc/AscendAI",
    "statikfintechllc/Mobile-Developer",
    "statikfintechllc/AscendDocs-of-GovSeverance",
    "statikfintechllc/GodCore",
    "statikfintechllc/AscendNet",
    "statikfintechllc/WorkFlowRepo"
]
```

> To match you're repo's naming.

</details>

---

<details>
<summary>🌀 Expand to See Options 🌀</summary>

---

<div align="center">

The Ticker-Bot

 ---

  <img  src="https://raw.githubusercontent.com/statikfintechllc/WorkFlowRepo/master/docs/ticker-bot/ticker.gif" 
  alt="Repo Ticker Stats" 
  style="height:33px;" />
</div>

---

<div align="center">

The Graph

 ---
 
  <a href="https://raw.githubusercontent.com/statikfintechllc/AscendAI/master/About US/">
  <img src="https://raw.githubusercontent.com/KDK-Grim/WorkFlowRepo-Mirror/master/docs/graph/traffic_graph.png" alt="Traffic Graph" />
</div>

</details>

---

*Enjoy!*
