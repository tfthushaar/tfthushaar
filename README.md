<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=24&pause=1000&color=7AA2F7&center=true&vCenter=true&width=640&lines=Full-stack+%2B+AI+engineer;Data+pipelines+%E2%86%92+backend+%E2%86%92+frontend+%E2%86%92+ML;Shipping+to+production%2C+not+just+demos" alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/k-n-thushaar-rangan-4668352300)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:thushaarrangan@gmail.com)
![Location](https://img.shields.io/badge/Bangalore%2C_India-4285F4?style=flat-square&logo=googlemaps&logoColor=white)
![Open to](https://img.shields.io/badge/Open_to-Full--time_%26_Freelance-brightgreen?style=flat-square)

</div>

I build full-stack products and reach for ML when it actually earns its place. I built a Telegram bot that catches crop disease before farmers can see it, a hybrid rules+LLM engine that reconciles payment settlements for Razorpay's AI Buildathon, a CRM that runs a real outdoor-advertising business, and a fitness app that's live on the Play Store. I don't stop at a demo — I take things through to a backend that holds up and a deployment that stays up.

## In Practice

<table>
<tr>
<td valign="top" width="50%">

- I've built multi-agent LLM pipelines — ADVOCATE runs five agents arguing both sides of a legal case, and my trading platform routes through a LangGraph graph of specialist agents
- Before I trust a model, I hold it to held-out statistical testing with confidence intervals — my Razorpay Buildathon project is basically me trying to prove my own model wrong, three times, before admitting it was right
- I've taken a product all the way through myself: Play Store release build, the backend API behind it, the data pipeline feeding it
- I provision infra with Terraform, configure it with Ansible, and run blue/green deploys through Jenkins with OWASP ZAP and Burp Suite as security gates
- I build real-time systems — WebSocket notifications, Redis pub/sub, geo-based outbreak alerting

</td>
<td valign="top" width="50%">

- I integrate third-party platforms myself — OAuth2 for Discord/Steam/Riot, the Telegram Bot API, Gemini Vision, payment gateway APIs
- I design role-based systems — multi-tenant dashboards, approval chains, GST invoicing for a business that actually runs on it
- I write my own backend when it matters — custom JWT auth with PBKDF2-SHA256 in OmniSkill rather than whatever a BaaS hands me for free, FastAPI/SQLModel and Flask services alongside it
- I apply computer vision and predictive ML — segmentation, object detection, anomaly and risk prediction
- I deploy differently depending on what the project needs — Vercel for Next.js apps, Cloudflare Workers for a static site, Supabase for Postgres + auth, and a hand-provisioned AWS EC2/ALB setup when the project was specifically about the infra

</td>
</tr>
</table>

## Featured Projects

#### [Settlement Reconciliation Copilot](https://github.com/tfthushaar/razorpay_buildathon) — [live](https://razorpay-buildathon-five.vercel.app) · [research write-up](https://github.com/tfthushaar/CAPSTONE)
I built a hybrid deterministic + LLM engine that reconciles Razorpay settlements against bank statements and ERP ledgers, for Razorpay's AI Buildathon 2026 (Track 04). I wrote 615+ tests and ran a held-out evaluation — 420 judgements per cell — to measure exactly where my rule-based matching silently fails and a model actually earns its place.
<br>`Python` `TypeScript` `Docker` `pytest`

#### [Metakai](https://github.com/tfthushaar/metakai) — [Android](https://github.com/tfthushaar/metakai/releases/latest) · [web / iOS](https://tfthushaar.github.io/metakai/app/)
My own fitness and nutrition tracker, private and ad-free — log meals in plain language, sync with a watch, get a goal date forecast from trend weight instead of day-to-day noise. I shipped it to the Play Store.
<br>`TypeScript` `Kotlin` `Python`

#### [ADVOCATE](https://github.com/tfthushaar/ADVOCATE) — [live demo](https://advocate-pretrial-simulator.streamlit.app/)
I built a five-agent adversarial pipeline that argues both sides of a wrongful-termination case, scores each side on a structured legal rubric, and surfaces the gaps one side never answered.
<br>`Python` `Streamlit` `Supabase`

#### [Reklama CRM](https://github.com/tfthushaar/reklama-crm) — [live demo](https://reklama-crm-sandy.vercel.app)
I built a role-based CRM for a real outdoor-advertising business — one system that takes a lead from first call to signed quote to GST invoice, across 5 permission levels.
<br>`TypeScript` `React` `PostgreSQL`

#### [CropRadar](https://github.com/KernelLex/CropRadar-01) *(built with KernelLex)*
Telegram-first crop disease diagnosis for farmers. Send a photo, get an AI diagnosis in English or Kannada, plus predictive outbreak alerts I built from live weather and regional disease history.
<br>`Python` `Gemini Vision` `Streamlit` `Telegram API`

#### [Automated Secure Deployment](https://github.com/tfthushaar/library_management_devops)
I set up an end-to-end AWS pipeline for a library portal myself — Terraform-provisioned blue/green EC2 behind an ALB, Ansible config, a Jenkins pipeline that rolls back on failed verification, OWASP ZAP and Burp Suite as security gates.
<br>`Terraform` `Ansible` `Jenkins` `AWS`

## Tech Stack

**Languages**
<br>![](https://skillicons.dev/icons?i=python,ts,js,html,css,kotlin,c)

**Frontend**
<br>![](https://skillicons.dev/icons?i=react,nextjs,vite,tailwind,threejs)

**Backend & Data**
<br>![](https://skillicons.dev/icons?i=nodejs,fastapi,flask,postgres,supabase,sqlite)

**AI / ML**
<br>![](https://skillicons.dev/icons?i=pytorch,sklearn)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![LangChain](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Cloud & DevOps**
<br>![](https://skillicons.dev/icons?i=docker,terraform,ansible,jenkins,aws,cloudflare,vercel,githubactions)

**Tools**
<br>![](https://skillicons.dev/icons?i=git,linux,bash,androidstudio)

## GitHub Stats

<table>
<tr>
<td><img src="https://github-readme-stats.vercel.app/api?username=tfthushaar&show_icons=true&theme=tokyonight&hide_border=true&icon_color=7aa2f7&count_private=false" alt="GitHub stats" /></td>
<td><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tfthushaar&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" /></td>
</tr>
</table>

<img src="https://streak-stats.demolab.com/?user=tfthushaar&theme=tokyonight&hide_border=true" alt="GitHub streak" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tfthushaar/tfthushaar/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tfthushaar/tfthushaar/output/github-contribution-grid-snake.svg" />
  <img src="https://raw.githubusercontent.com/tfthushaar/tfthushaar/output/github-contribution-grid-snake.svg" alt="Contribution snake animation" />
</picture>

---

<div align="center">
<i>Thanks for reading this far — reach out if you want to talk shop.</i>
<br/><br/>
<img src="https://komarev.com/ghpvc/?username=tfthushaar&style=flat-square&color=7aa2f7&label=Profile+views" alt="Profile views" />
</div>
