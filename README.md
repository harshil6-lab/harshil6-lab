<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,50:0a1628,100:0D1117&height=1&section=header"/>
</div>

<br>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=venom&color=0:00FF88,100:00C2FF&height=200&section=header&text=HARSHIL%20P.%20KALSARIYA&fontSize=38&fontColor=ffffff&fontAlignY=55&desc=Backend%20Engineer%20%E2%80%94%20Surat%2C%20Gujarat%2C%20India&descSize=14&descAlignY=75&descColor=aaaaaa&animation=fadeIn"/>
</div>

<br>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=13&duration=2000&pause=700&color=00FF88&center=true&vCenter=true&width=600&lines=API+Infrastructure+%26+Service+Architecture;Workflow+Automation+%26+Orchestration+Engines;LLM+Routing+%26+Document+Processing+Pipelines;Enterprise+ETL+%26+Data+Warehouse+Systems;SMTP+%26+Notification+Automation)](https://git.io/typing-svg)

</div>

<br>

---

<br>

## &nbsp;`01` &nbsp; Core Domains

<br>

<table>
<tr>
<td width="50%" valign="top">

**⬡ &nbsp;API & Backend Systems**
```
FastAPI  ·  REST APIs  ·  Python
SMTP Pipelines  ·  Auth Layers
```

**⬡ &nbsp;Workflow Automation**
```
n8n Orchestration  ·  Event-Driven Execution
Trigger Chains  ·  Automation-First Architecture
```

</td>
<td width="50%" valign="top">

**⬡ &nbsp;AI / LLM Integration**
```
OpenAI  ·  Gemini  ·  Grok
LLM Routing Pipelines  ·  Document Processing
```

**⬡ &nbsp;Data Engineering**
```
ETL Pipelines  ·  PostgreSQL Warehousing
Raw JSON Lakes  ·  Airflow-Ready DAGs
```

</td>
</tr>
</table>

<br>

---

<br>

## &nbsp;`02` &nbsp; Technology Stack

<br>

<div align="center">

| Layer | Technologies |
|:---|:---|
| **Languages** | Python &nbsp;·&nbsp; C &nbsp;·&nbsp; C++ |
| **Backend** | FastAPI &nbsp;·&nbsp; REST APIs &nbsp;·&nbsp; SMTP Pipelines |
| **Databases** | PostgreSQL &nbsp;·&nbsp; MySQL &nbsp;·&nbsp; Firebase &nbsp;·&nbsp; Supabase |
| **Automation** | n8n &nbsp;·&nbsp; OCR Pipelines &nbsp;·&nbsp; Google APIs |
| **AI / LLM** | OpenAI &nbsp;·&nbsp; Gemini &nbsp;·&nbsp; Grok |
| **Infrastructure** | Docker &nbsp;·&nbsp; Linux CLI &nbsp;·&nbsp; GitHub Actions |
| **Deployment** | Docker &nbsp;·&nbsp; Vercel &nbsp;·&nbsp; Netlify |

</div>

<br>

<div align="center">
<img src="https://skillicons.dev/icons?i=python,cpp,fastapi,postgres,mysql,firebase,docker,linux,git,github&perline=10"/>
</div>

<br>

---

<br>

## &nbsp;`03` &nbsp; Systems Built

<br>

<details open>
<summary><b>&nbsp;◈ &nbsp;CertifyPro &nbsp;—&nbsp; Bulk Certificate Generation & Verification</b></summary>

<br>

```
INPUT              PROCESSING                        OUTPUT
─────────────────────────────────────────────────────────────
Excel Sheet   →   Template Engine   →   Bulk Certs (PDF/PNG)
                       │
                  Field Injection
                  Multi-Org Config
                       │
                  Verification API   →   GET /verify/{id}
                                         { valid: true }
─────────────────────────────────────────────────────────────
Stack: Python · FastAPI · Excel Automation
```

<br>
</details>

---

<details>
<summary><b>&nbsp;◈ &nbsp;AI Resume Screening Pipeline &nbsp;—&nbsp; LLM-Powered Candidate Ranking</b></summary>

<br>

```
STAGE 1          STAGE 2               STAGE 3          STAGE 4
────────────────────────────────────────────────────────────────
Resume Upload → LLM Extraction  →  Rule-Based Rank  →  Dispatch
                (skill map)        (weight scoring)    (SMTP)
                OpenAI/Gemini      experience ×         ↓
                                   role match        Shortlist /
                                        │            Rejection
                                   n8n Orchestration   Notify
────────────────────────────────────────────────────────────────
Stack: Python · n8n · OpenAI · SMTP
```

<br>
</details>

---

<details>
<summary><b>&nbsp;◈ &nbsp;Gmail Routing System &nbsp;—&nbsp; LLM-Classified Inbox Automation</b></summary>

<br>

```
Gmail Trigger
      │
      ▼
Multi-Stage Classifier (Gemini API)
      │
      ├── support  →  Auto-Reply Template
      ├── billing  →  Escalation Queue
      ├── general  →  LLM-Drafted Response
      └── spam     →  Archive & Discard
                           │
                    n8n Execution Layer
────────────────────────────────────────
Stack: n8n · Gemini API · Google Workspace APIs
```

<br>
</details>

---

<details>
<summary><b>&nbsp;◈ &nbsp;Invoice OCR Pipeline &nbsp;—&nbsp; Layout-Adaptive Document Extraction</b></summary>

<br>

```
Invoice (PDF / Image)
        │
        ▼
Layout-Adaptive Extraction Engine
  ├── tabular invoices
  ├── free-form layouts
  └── scanned documents
        │
        ▼
Structured Parser
  fields: vendor · date · line_items · total · tax
        │
        ▼
Google Sheets API  →  append row · format · notify
────────────────────────────────────────────────────
Stack: Python · OCR · Google Sheets API
```

<br>
</details>

---

<details>
<summary><b>&nbsp;◈ &nbsp;Enterprise ETL & Data Warehouse &nbsp;—&nbsp; <code>active build · 80%</code></b></summary>

<br>

```
 ┌──────────────┐     ┌──────────────────────┐
 │  Stripe API  │     │  Salesforce (JWT/SSO) │
 └──────┬───────┘     └──────────┬────────────┘
        └──────────┬─────────────┘
                   ▼
        [ Extraction Layer ]
          Raw JSON Data Lake
                   │
                   ▼
        [ Dockerized Backend ]
         mTLS Certificate Auth
                   │
         ┌─────────┴──────────┐
         ▼                    ▼
  Transformation         PostgreSQL
     Engine               Warehouse
         └─────────┬──────────┘
                   ▼
        [ Airflow-Ready Scheduler ]
          DAG-compatible structure
─────────────────────────────────────────────────────────
Stack: Python · Docker · PostgreSQL · Stripe · Salesforce
Progress: ▓▓▓▓▓▓▓▓░░  80%
```

<br>
</details>

<br>

---

<br>

## &nbsp;`04` &nbsp; GitHub Analytics

<br>

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=harshil6-lab&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00FF88&icon_color=00C2FF&text_color=8B949E&ring_color=00FF88"/>
&nbsp;
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=harshil6-lab&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00FF88&text_color=8B949E"/>

</div>

<br>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=harshil6-lab&theme=tokyonight&hide_border=true&background=0D1117&ring=00FF88&fire=00C2FF&currStreakLabel=00FF88&sideLabels=8B949E&dates=555555"/>

</div>

<br>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=harshil6-lab&theme=react-dark&hide_border=true&bg_color=0D1117&color=00FF88&line=00C2FF&point=FFFFFF&area=true&area_color=00FF8822"/>
</div>

<br>

<div align="center">
<img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"/>
</div>

<br>

---

<br>

## &nbsp;`05` &nbsp; Connect

<br>

<div align="center">

<a href="mailto:harshilkalsariya28@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-harshilkalsariya28%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/>
</a>
&nbsp;&nbsp;
<a href="https://linkedin.com/in/harshil-kalsariya-629651318">
  <img src="https://img.shields.io/badge/LinkedIn-harshil--kalsariya-0077B5?style=flat-square&logo=linkedin&logoColor=white"/>
</a>
&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Location-Surat%2C%20Gujarat%2C%20India-00FF88?style=flat-square&logo=googlemaps&logoColor=white"/>

</div>

<br>

---

<div align="center">
<sub><code>backend · api · automation · etl · llm · surat · india</code></sub>
</div>
