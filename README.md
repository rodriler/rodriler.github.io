# Rodrigo Leroux
San Francisco Bay Area  
rodrigo.leroux@gmail.com  
[linkedin.com/in/rodriler](https://www.linkedin.com/in/rodriler) &nbsp;&nbsp;|&nbsp;&nbsp;
[rodriler@github](https://github.com/rodriler) &nbsp;&nbsp;|&nbsp;&nbsp;
[⬇ Download PDF](./RodrigoLeroux-ResumeGithub-202605.pdf) &nbsp;&nbsp;|&nbsp;&nbsp;
[✉ Get in touch](mailto:rodrigo.leroux@gmail.com)

---

## 🦊 Summary

### Staff+/Principal Engineer & Data Architect

Hands-on technical anchor with deep experience building, operating, and evolving production-grade software platforms across enterprise and consumer domains, including sales instrumentation, recruiting, education, online dating, movies, music, and games.

I am strongest where backend systems, data architecture, product workflows, operational reality, and long-term technical stewardship intersect. My work has repeatedly involved taking ownership of systems beyond initial design: understanding how they behave in production, how they scale, how they fail, how they cost money, how teams depend on them, and how they need to evolve as the business changes.

### Selected Scale / Impact

- Principal technical owner for Atrium’s sales performance, analytics, and optimization platform, supporting **3K+ customer/prospect accounts**, from small teams to enterprise accounts with **1K+ active users**.
- Operated and evolved a PostgreSQL/AWS platform managing roughly **20TB of sales-operations data** across **8 db.m6i.16xlarge RDS PostgreSQL 16 instances**, sustaining approximately **18K IOPS** and **1,500 MiB/s throughput**.
- Proactively managed production cloud spend in the **$80K–$120K/month** range at peak utilization.
- Owned backend/search systems at TalentBin indexing **15M candidate profiles** in a **3TB Apache Solr index**.
- Co-founded and architected VigLink’s content monetization platform, which handled **~600M page views/month** and later generated **$20M+ in annual revenue**.
- Designed and operated Flixster’s backend/data architecture as it grew to **millions of daily users**, including **100+ stateless app servers** and a **30-node MySQL cluster**.
- Increased Atlas Mobile / Infospace tournament-game throughput from **<30 to >1,000 games/sec** through concurrency and transaction redesign.

### Technical Leadership

- Accountable for the long-term technical success, operational reality, and evolutionary direction of systems, product areas, and platforms, often without formal managerial authority.
- Trusted by founders and engineering leaders for hands-on technical ownership from early product stage through scaling, operational maturity, acquisition, and post-acquisition integration.
- Strong mentor, reviewer, pragmatic systems architect, and owner of high-leverage technical work that is often underrepresented in product roadmaps: scalability, observability, performance, operational efficiency, reliability, maintainability, and prudent refactoring.
- Experienced in applying LLMs and agentic development workflows to both product features and engineering execution, including technical documentation, source-code analysis, automated test coverage, debugging, refactoring, package upgrades, and customer-support triage.

---

## 🐘 Professional Experience

### Principal Engineer / Technical Lead

**Atrium HQ / Fullcast** — San Francisco Bay Area  
**May 2016 – Present**

Principal technical owner for Atrium’s sales performance, analytics, and optimization SaaS platform, later through its acquisition by Fullcast. The product sits at the intersection of revenue-operations workflows, data modeling, analytics, integrations, prioritization, forecasting, and recommendation systems for sales and revenue teams.

- Owned long-term architecture and operational stewardship for a platform supporting **3K+ customer/prospect accounts**, from teams of roughly a dozen users to enterprise accounts with **1K+ active users**.
- Managed approximately **20TB of sales-operations data** partitioned across **8 db.m6i.16xlarge RDS PostgreSQL 16 instances**, sustaining roughly **18K IOPS** and **1,500 MiB/s throughput**.
- Proactively managed production cloud spend in the **$80K–$120K/month** range at peak utilization, balancing performance, reliability, cost, and operational simplicity.
- Designed and evolved backend/data architecture across **OLTP + OLAP workloads**, using PostgreSQL/RDS, Java/Spring Boot, AWS, Terraform/Ansible, Protobuf APIs, and caching/search/reporting pipelines.
- Led data-modeling and analytics strategy across star/snowflake schemas, metric definitions, KPI design, aggregation/search/reporting workflows, and stable data contracts for product and frontend teams.
- Supported sales and revenue-operations workflows including dashboards, prioritization engines, forecasting inputs, activity analysis, pipeline inspection, and AI-assisted recommendations.
- Helped introduce LLM and AI-assisted product workflows, including sales-coaching and recommendation features grounded in production customer data.
- Applied LLMs to engineering workflows: generating accurate technical documentation and specifications from source code, improving automated test coverage, triaging and debugging from customer-support tickets, and planning/executing broad code refactorings and package upgrades.
- Owned infrastructure-as-code and operational workflows using Terraform and Ansible, enabling reproducible environments, predictable deployments, and safer operational changes.
- Acted as a force multiplier through architecture direction, design review, mentoring, debugging, documentation, incident analysis, operational planning, and pragmatic refactoring.

**Core technologies:** Java 8, Spring Boot, Hibernate, PostgreSQL 9–16, RDS, Protobuf, React-facing APIs, Memcached, AWS, Terraform, Ansible, GitHub, IntelliJ IDEA, Windsurf, Cascade, Claude, LLMs, agentic development workflows

---

### Technical Lead

**TalentBin — acquired by Monster Worldwide** — San Francisco, CA  
**July 2012 – Apr 2016**

Technical lead for TalentBin’s candidate data/search platform, recruiting workflows, product APIs, and ingestion systems through acquisition by Monster Worldwide.

- Owned backend search and candidate-data systems indexing **15M candidate profiles** in a **3TB Apache Solr index**.
- Combined skills, roles, and related professional signals from public sources including **GitHub, Bitbucket, Stack Exchange, and PubMed** into recruiter-facing search and discovery workflows.
- Built and operated ingestion, enrichment, search, and API systems supporting candidate discovery, profile understanding, and recruiter outreach workflows.
- Collaborated closely with product and business stakeholders to deliver features iteratively while preserving search relevance, data quality, and operational reliability.
- Helped evolve a recruiting data product where public professional activity, search infrastructure, and recruiter workflow design needed to reinforce each other.

**Core technologies:** Java, Spring, Apache Solr, MySQL, PHP/Yii, AWS, GitHub, Pivotal Tracker

---

### Senior Member of Technical Staff

**Salesforce** — San Francisco, CA  
**Aug 2010 – June 2012**

- Built CRM features as part of the Knowledge Access and Management team.
- Worked within large-scale enterprise systems with strict reliability, security, performance, release, and backward-compatibility requirements.
- Delivered product functionality in a mature engineering environment with large customer impact, established platform constraints, and disciplined operational expectations.

**Core technologies:** Java, Lucene, Oracle, Perforce

---

### Co-Founder & Architect

**VigLink — acquired by Sovrn** — San Francisco, CA  
**Sept 2009 – July 2010**

Co-founded and architected a content monetization platform serving major publishers.

- Architected early platform systems that handled **~600M page views/month** and later generated **$20M+ in annual revenue**.
- Built the initial bare-metal JavaScript library for outbound click modification, a publisher analytics dashboard, and a high-throughput click-tracking backend using distributed, log-based ingestion.
- Worked across product prototyping, customer onboarding, early marketing, PR, affiliate-network approvals, and early business development.
- Helped move the company from product concept to operational publisher monetization infrastructure.

**Core technologies:** JavaScript, Cassandra, Hadoop

---

### Data Architect

**Flixster — acquired by Warner Bros.** — San Francisco, CA  
**Apr 2006 – Aug 2009**

First employee and data architect for a high-traffic consumer movie platform that grew to millions of daily users before acquisition by Warner Bros.

- Owned backend architecture, data modeling, and capacity planning as Flixster grew to **millions of daily users** and a **top-1000 Alexa** ranking.
- Designed a sharded MySQL architecture with shard-aware data access patterns, replication, and extensive caching for high-traffic consumer workloads.
- Operated production infrastructure including **100+ stateless app servers** and a **30-node MySQL cluster** with replication for read scaling and failover.
- Partnered across product and engineering to support rapid consumer growth while preserving system reliability and operational simplicity.

**Core technologies:** Java, Spring, Hibernate, Apache/Tomcat, MySQL, Ant, CVS, Eclipse

---

### Data Architect

**Engage Corporation — acquired by Spark Networks** — Oakland, CA  
**Dec 2004 – Mar 2006**

- Technical owner for backend data architecture supporting profiles, matching, and messaging on a large-scale online dating platform.
- Built Java/Spring/Hibernate backend services over PostgreSQL.
- Implemented PostgreSQL replication using **Slony** and optimized transactional workflows for reliability and performance.
- Worked on production systems where data correctness, query performance, and user-facing workflow behavior were tightly connected.

**Core technologies:** Java, Spring, Hibernate, PostgreSQL, Slony

---

### Freelance Consultant

**2004 – 2006**

- **Atlas Mobile / Infospace:** Redesigned concurrency and transaction flow for tournament-based mobile games, increasing throughput from **<30 to >1,000 games/sec** and adding replication, backup, and recovery processes.
- **Autodesk:** Upgraded data models and optimized queries for reseller support portal workflows.
- **Tapatap:** Delivered pre-launch feature development and post-launch performance stabilization.

---

### Earlier Career

**Senior Software Engineer, Echo Networks** — San Francisco, CA  
**2000 – 2002**

- Core engineer on a distributed messaging backbone for an online radio service.
- Led performance profiling using custom load-testing harnesses.

**Developer / Consultant, Trilogy Software** — Austin, TX  
**1999 – 2000**

- Built enterprise software systems and customer-specific implementations in a high-expectation consulting environment.

---

## 🦫 Academic Experience

### Research Assistant

**Sociable Media Group, MIT Media Lab** — Cambridge, MA  
**1997 – 1999**

- Architected **Load Plateau**, a toolkit for building scalable real-time collaborative applications using distributed shared memory, weak consistency, atomic broadcast, and prioritized message queues.
- Used Load Plateau to improve scalability and robustness in collaborative applications including **Chat Circles**, an experimental graphical chat system exploring social presence and online conversation.
- Worked on systems where user-interface behavior, distributed systems architecture, consistency models, and scalability constraints interacted directly.
- Research focused on scalable collaborative systems, real-time distributed applications, social computing, and the relationship between system architecture and user experience.

### Teaching Assistant

**Massachusetts Institute of Technology** — Cambridge, MA  
**1999**

- Teaching Assistant for **6.042J — Mathematics for Computer Science**.
- Conducted weekly recitations and tutorials covering discrete mathematics, proofs, graph theory, and probabilistic reasoning.
- Course materials publicly available via MIT OpenCourseWare:  
  https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-spring-2015/

---

## Education

**Massachusetts Institute of Technology (MIT)** — Cambridge, MA  
**M.Eng. & B.S. — Computer Science & Engineering**

Concentration in Artificial Intelligence, with additional coursework in Distributed Systems, Data Mining, Operating Systems, Security, Network Optimization, and Economics.

Advanced study in distributed computing, networked systems, scalable collaborative software, and cache coherency.

---

## Technical Skills

### Programming Languages

- Java 8–21
- SQL and PL/pgSQL
- JavaScript, TypeScript, Python, Bash
- Experience with JVM-adjacent languages and ecosystems including Kotlin, Scala, and Groovy
- Additional production exposure to PHP and Go

### Backend / Platform Engineering

- Service-oriented architectures
- RESTful APIs and API/data-contract design
- Java/Spring Boot production systems
- Hibernate and ORM-heavy applications
- Protobuf-based APIs
- Gradle, JUnit, automated testing, package upgrades, and large refactors
- Performance profiling, debugging, and production troubleshooting

### Data Architecture

- OLTP and OLAP data modeling
- PostgreSQL and MySQL schema design, partitioning, replication, query optimization, and operational tuning
- Star and snowflake schemas
- Metric definitions, KPI design, reporting models, and analytical data products
- Search, ingestion, enrichment, aggregation, and reporting pipelines
- Data quality, workflow correctness, and operational source-of-truth design

### Storage / Search / Data Systems

- PostgreSQL 9–16, AWS RDS, Aurora, MySQL
- Apache Solr and Lucene
- Memcached
- Cassandra, Hadoop
- Snowflake, Redshift, DuckDB
- Kafka and event/log-based ingestion patterns
- Data lake / warehouse architecture concepts including medallion-style modeling, Data Vault, and Kimball-style dimensional modeling

### Infrastructure / Operations

- AWS: ALB/ELB, EC2, RDS, S3, EBS, ElastiCache, Athena, Glue
- Terraform, Ansible
- Docker, Kubernetes
- Jenkins, GitHub Actions-style workflows, CI/CD
- Datadog, observability, metrics, logging, incident analysis
- Cost/performance tradeoff analysis and cloud-spend management

### AI / LLM / Agentic Development

- LLM-assisted product workflows and AI-assisted recommendations
- Claude, Claude Code, Cursor, Windsurf/Cascade, GitHub Copilot, Codex-style workflows
- Generating technical documentation and specifications directly from source code
- Automated test coverage improvement using LLM-assisted analysis
- Customer-support-ticket triage and debugging workflows
- Planning and executing broad code refactors, dependency upgrades, and package migrations
- Agentic development workflows for source-code understanding, maintenance, and engineering acceleration

### Languages

- English
- Spanish
- Technical translation across engineering, product, business, and operations
