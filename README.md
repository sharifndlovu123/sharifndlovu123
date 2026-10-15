<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Sharif Ndlovu — Cloud Infrastructure / DevOps Engineer" src="assets/banner-light.svg" width="100%">
</picture>

<p>
  Python and cloud engineer with production AWS and Django experience across QA, UAT and Production.
  I ship live government and commercial platforms, owning both the application and the infrastructure underneath it.
</p>

<p>
  🏢 Founder of <a href="https://devbridge.co.za"><b>DevBridge</b></a>, a Pretoria-based software and cloud infrastructure company serving government and enterprise clients across South Africa.
</p>

> [!NOTE]
> **Open to opportunities:** hybrid or remote work in the Centurion / Pretoria area.

<p>
  <a href="https://portfolio.devbridge.co.za"><img alt="Portfolio" src="https://img.shields.io/badge/PORTFOLIO-100F0D?style=for-the-badge"></a>
  <a href="https://devbridge.co.za"><img alt="DevBridge" src="https://img.shields.io/badge/DEVBRIDGE-E2231A?style=for-the-badge"></a>
  <a href="https://knowledgebase.devbridge.co.za"><img alt="Knowledge Base" src="https://img.shields.io/badge/KNOWLEDGE_BASE-100F0D?style=for-the-badge"></a>
  <a href="https://linkedin.com/in/sharif-ndlovu-3b54a2275"><img alt="LinkedIn" src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:sharifndlovu@gmail.com"><img alt="Email" src="https://img.shields.io/badge/EMAIL-6B6962?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

### `01` &nbsp;Projects

Several of these are government systems, so I don't link them directly. Full write-ups are on my [portfolio](https://portfolio.devbridge.co.za).

<table>
  <tr>
    <td width="50%" valign="top">
      <b>Livi</b> · <code>live</code><br>
      <sub>Multi-tenant citizen-services platform, Office of the Premier, Mpumalanga</sub>
      <ul>
        <li>One Django deployment serving 10 departments across 30 subdomains</li>
        <li>Celery Beat + Amazon MQ SLA escalation across 12 queues</li>
        <li>SSE chat, Rekognition media gating, DRF mobile API on ECS Fargate</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <b>e-PGLUM</b> · <code>live</code><br>
      <sub>Nationwide land-use and building-plan management, live for CoGHSTA, Mpumalanga</sub>
      <ul>
        <li>Owned the full AWS estate (QA, UAT, Production) in a team of 7</li>
        <li>Configurable workflow engine over a 96-form codebase</li>
        <li>Async S3 document pipeline, CloudFormation</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>The Workplace Basics</b><br>
      <sub>Django commerce and publishing platform</sub>
      <ul>
        <li>Paystack subscriptions with HMAC-SHA512 webhook verification</li>
        <li>Tiered access with JWT sessions</li>
        <li>S3 presigned URLs, Celery + Redis</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <b>Community Web Modernization</b> · <code>pro bono</code><br>
      <sub>Annual programme: 6 sites for schools, churches, NGOs and sports clubs</sub>
      <ul>
        <li>Static sites on Cloudflare Pages</li>
        <li>Automatic HTTPS and DDoS protection</li>
        <li>Full source handover</li>
      </ul>
    </td>
  </tr>
</table>

### `02` &nbsp;Products I'm building at DevBridge

Our own products, with the codebases largely complete and now heading into users' hands. Feature additions and gap-filling follow once real feedback comes in.

<table>
  <tr>
    <td width="50%" valign="top">
      <b>EO Risk Platform</b> · <code>in development</code><br>
      <sub>Satellite Imagery · Risk Analytics · REST API · Insurance</sub><br><br>
      A B2B satellite-imagery analytics API that turns Earth observation data into property risk scores for insurers. One call returns a composite score, hazard exposure and the evidence behind them.
    </td>
    <td width="50%" valign="top">
      <b>Heavy Fleet Intelligence</b> · <code>in development</code><br>
      <sub>Telemetry · CAN / J1939 · MQTT 5 · Multi-Tenant</sub><br><br>
      A white-label, hardware-agnostic operational intelligence platform for mining and heavy logistics: live telemetry, trip reconstruction, route compliance and stop analysis over industrial gateways.
    </td>
  </tr>
</table>

### `03` &nbsp;Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="Django" src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white">
  <img alt="DRF" src="https://img.shields.io/badge/DRF-A30000?style=flat-square&logo=django&logoColor=white">
  <img alt="Celery" src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white">
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white">
  <img alt="RabbitMQ" src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
  <img alt="Azure" src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white">
</p>

| | |
| --- | --- |
| **Languages** | Python (expert), Java, JavaScript, C# (.NET MVC), Kotlin, SQL, Delphi |
| **Data & messaging** | PostgreSQL, PostGIS, MySQL, Redis, pgvector, RabbitMQ, Amazon MQ, Celery |
| **DevOps** | Docker, Git, GitHub Actions, CI/CD, Infrastructure as Code |

<details>
<summary><b>Full AWS service list</b></summary>
<br>

ECS Fargate, Lambda, S3, EFS, RDS, ElastiCache, SQS, SNS, EventBridge, SES, CloudFront, Route 53, ACM, IAM, KMS, Secrets Manager, Rekognition, CloudWatch, CloudFormation, WAF

</details>

<details>
<summary><b>Azure bastion host: SSH into a private subnet</b></summary>
<br>

A network-isolation pattern I built on Azure: only the bastion in the public subnet is reachable from the internet, and only from my own IP. The private instance has no public address at all.

```mermaid
flowchart LR
    ME([My machine<br/>single allowed IP]) -- "SSH :22" --> NSG1{{NSG: allow SSH<br/>from my IP only}}
    subgraph VNET["Azure Virtual Network"]
        subgraph PUB["Public subnet"]
            NSG1 --> BASTION[Bastion VM<br/>public IP]
        end
        subgraph PRIV["Private subnet"]
            NSG2{{NSG: allow SSH<br/>from bastion subnet only}} --> TARGET[Private VM<br/>no public IP]
        end
        BASTION -- "SSH jump" --> NSG2
    end
```

Firewall rules (network security groups) restrict inbound SSH at both layers, so the private VM can only be reached by jumping through the bastion.

</details>

### `04` &nbsp;Record

<table>
  <tr>
    <td width="50%" valign="top">
      <b>Certifications</b>
      <ul>
        <li>AWS Certified Solutions Architect – Associate</li>
        <li>AWS Certified Developer – Associate</li>
        <li>AWS Certified Cloud Practitioner</li>
        <li>Microsoft Certified: Azure Fundamentals (AZ-900)</li>
        <li>CompTIA Network+</li>
        <li>CompTIA Project+</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <b>Education</b>
      <ul>
        <li>BSc Computer &amp; Application Development, Varsity College (2021–2023)</li>
        <li>Programming Languages &amp; AI short course, University of Pretoria (2025)</li>
      </ul>
      <b>Currently (2026)</b>
      <ul>
        <li>Studying: AZ-204 Azure Developer · CompTIA Linux+ · HashiCorp Terraform Associate · Bash</li>
        <li>Up next: Kubernetes · Jenkins CI/CD · Firebase &amp; NoSQL</li>
      </ul>
    </td>
  </tr>
</table>

### `05` &nbsp;Knowledge base

I keep my study notes in public at **[knowledgebase.devbridge.co.za](https://knowledgebase.devbridge.co.za)**: a regularly updated hub covering cloud, databases, Linux, networking, orchestration and programming. They're rough working notes, tidied with an LLM, written as I learn.

<sub><code>Pretoria · ZA</code> &nbsp;·&nbsp; <code>REF · SN—2026</code></sub>
