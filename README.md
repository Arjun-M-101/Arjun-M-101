<p align="center">
  <a href="https://arjun-m-101.github.io/">
    <img width="1536" height="1024" alt="Github_profile_pic" src="https://github.com/user-attachments/assets/01781b8c-6d99-4470-83aa-f0e1c927ee15" />
  </a>
</p>

<h1 align="center">Hello <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px"> I'm Arjun</h1>
<h3 align="center">DBA ➔ Data Engineer</h3>

---

## 🙋‍♂️ About Me

- 👨‍💻 **On the Job:** Managing the extraction side of an active Mainframe (Db2 z/OS)-to-AWS Cloud migration - successfully shipped clean data across 400+ tables.
- 🧪 **Latest Build:** **SpecFlow** (🔒 private repo, walkthrough on **[my portfolio](https://arjun-m-101.github.io/)**) - an **AI-assisted, human-approved pipeline builder**. Drop a file or connect a live feed; it profiles every field, proposes cleaning steps and business metrics, asks only where a wrong guess would be costly, and runs the approved spec into Silver, Gold and Quarantine tables with an auto-generated dashboard. The AI only writes a validated JSON spec, never code that runs. One spec runs as **batch, streaming or hybrid** on **DuckDB**, **Spark Structured Streaming on Kafka**, or **Apache Iceberg on AWS**. **105 tests** (4 on real Spark + Kafka), green in GitHub Actions; the AWS run is next.
- 🏗️ **Earlier Builds:** Shipped **[Connected-Car Telemetry on AWS](https://github.com/Arjun-M-101/connected-car-telemetry-aws)** - an IoT pipeline for simulated vehicle sensors (tyre pressure, pedals, fuel) on a live AWS account: IoT Core (MQTT, one X.509 certificate per vehicle) → Data Firehose with a validation Lambda → S3 → Glue → Athena, plus a DynamoDB latest-state path, SNS low-tyre alerts, CloudWatch monitoring and an AI chatbot that can only run fixed read-only queries. Deployed from one CloudFormation template, covered by 79 tests and CI, and fixed **11 real issues** across five live-tested versions. Before that, shipped **[YouTube Lakehouse](https://github.com/Arjun-M-101/youtube-lakehouse)** - a fully AWS-native batch lakehouse (S3 → Lambda → Step Functions → Glue/Spark → Redshift Serverless → QuickSight), 100% Terraform-managed, tested, and torn down on demand to control cost. Gold also lands as a genuine **Apache Iceberg** table (ACID + time-travel queries via Athena), written independently of the live Redshift/dbt/QuickSight path. Deployed against a live AWS account end-to-end - diagnosed and fixed **12 real production issues** along the way, including IAM, VPC/PrivateLink networking, Terraform state, data-quality, schema-drift, and incremental-loading problems.
- 🌱 **The Transition:** Fusing 3 years of deep enterprise database infrastructure experience with modern engineering tools to architect scalable, high-performance data systems.  
- 🛠️ Passionate about building scalable, reliable data pipelines that turn raw data into actionable insights.
- 👯 Open to collaborating on **Data Engineering & Open Source projects**
- 👨‍💻 Explore my work here:  --> **[My Portfolio](https://arjun-m-101.github.io/)** 
- 📫 Reach me at **arjunmpec101@gmail.com**  
- ⚡ Fun fact: **I debug pipelines the way I play games - with persistence and strategy**  

---

<p align="left">

## 🛠️ Tech Stack

<table align="center" border="0">
  <tr>
    <td align="center" valign="top" width="50%">
      <h3 align="center">Languages</h3>
      <table align="center" border="0">
        <tr>
          <td>
            <a href="https://www.w3schools.com/sql/" target="_blank">
              <img src="https://img.icons8.com/?size=100&id=J6KcaRLsTgpZ&format=png&color=000000" alt="SQL" width="48" height="48"/>
            </a>
          </td>
          <td>
            <a href="https://python.org" target="_blank">
              <img src="https://img.icons8.com/color/48/000000/python.png" alt="Python" width="48" height="48"/>
            </a>
          </td>
        </tr>
      </table>
    </td>
    <td align="center" valign="top" width="50%">
      <h3 align="center">Data Engineering & Analytics</h3>
      <table align="center" border="0">
        <tr>
          <td>
            <a href="https://spark.apache.org/" target="_blank">
              <img src="https://i.pinimg.com/736x/cd/ea/b2/cdeab2ba87244b2ce8bbbb046a48549f.jpg" alt="Spark" width="48" height="48"/>
            </a>
          </td>
          <td>
            <a href="https://kafka.apache.org/" target="_blank">
              <img src="https://juststickers.in/wp-content/uploads/2019/07/apache-kafka.png" alt="Kafka" width="48" height="48"/>
            </a>
          </td>
          <td>
            <a href="https://airflow.apache.org/" target="_blank">
              <img src="https://images.seeklogo.com/logo-png/63/1/apache-airflow-logo-png_seeklogo-630191.png" alt="Airflow" width="48" height="48"/>
            </a>
          </td>
          <td>
            <a href="https://www.getdbt.com/" target="_blank">
              <img src="https://media.trustradius.com/product-logos/96/cb/5OO11QWM1UTI.PNG" alt="dbt" width="48" height="48"/>
            </a>
          </td>
          <td>
            <a href="https://pandas.pydata.org/" target="_blank">
              <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="Pandas" width="48" height="48"/>
            </a>
          </td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="50%">
      <h3 align="center">Databases</h3>
      <table align="center" border="0">
        <tr>
          <td>
            <a href="https://www.postgresql.org/" target="_blank">
              <img src="https://img.icons8.com/color/48/000000/postgreesql.png" alt="Postgres" width="48" height="48"/>
            </a>
          </td>
          <td>
            <a href="https://www.mysql.com/" target="_blank">
              <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="48" height="48"/>
            </a>
          </td>
          <td>
            <a href="https://www.microsoft.com/en-us/sql-server/" target="_blank">
              <img src="https://img.icons8.com/color/48/000000/microsoft-sql-server.png" alt="MS SQL" width="48" height="48"/>
            </a>
          </td>
          <td>
            <a href="https://www.ibm.com/products/db2" target="_blank">
              <img src="https://www.simpleindex.com/wp-content/uploads/2023/07/IBM-DB2-Logo.png" alt="IBM DB2" width="48" height="48"/>
            </a>
          </td>
        </tr>
      </table>
    </td>
    <td align="center" valign="top" width="50%">
      <h3 align="center">Cloud & DevOps</h3>
      <table align="center" border="0">
        <tr>
          <td>
            <a href="https://aws.amazon.com/" target="_blank">
              <img src="https://img.icons8.com/color/48/000000/amazon-web-services.png" alt="AWS" width="48" height="48"/>
            </a>
          </td>
          <td>
            <a href="https://www.linux.org/" target="_blank">
              <img src="https://img.icons8.com/color/48/000000/linux.png" alt="Linux" width="48" height="48"/>
            </a>
          </td>
          <td>
            <a href="https://git-scm.com/" target="_blank">
              <img src="https://img.icons8.com/color/48/000000/git.png" alt="Git" width="48" height="48"/>
            </a>
          </td>
          <td>
            <a href="https://www.terraform.io/" target="_blank">
              <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/terraform/terraform-original.svg" alt="Terraform" width="48" height="48"/>
            </a>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>

---

## 📂 Featured Projects

- 🧪 **SpecFlow (AI-Assisted, Human-Approved Pipeline Builder)** 🔒 *Private repo · walkthrough and evidence on **[my portfolio](https://arjun-m-101.github.io/)*** 🆕 *Latest Build*  
  Drop a file or connect a live feed. SpecFlow profiles every field, proposes cleaning steps and business metrics, and asks only where a wrong guess would be costly. A person approves the plan, and a tested engine runs it into **Silver, Gold and Quarantine** tables plus an auto-generated dashboard.
  * **The AI plans, the engine executes:** The planner (rules, optionally improved by **Gemini, Bedrock or Claude** through tool use) only returns a **JSON spec** from a frozen catalog of **22 operations**; it sees a masked profile and never writes code that runs. Every plan is checked for schema, column references and SQL safety, then dry-run, with the rules plan as the fallback
  * **Asks instead of guessing:** Business metrics, dedupe keys and personal-data handling become questions with options; nothing runs until a person approves the spec
  * **One spec, every engine:** The same approved spec compiles to **DuckDB, Athena and Spark SQL** and runs as **batch**, **micro-batch streaming** (watermark + dead letter) or **hybrid** (backfill, then the live feed), merging on the business key so replays never duplicate
  * **Streaming at scale:** **Spark Structured Streaming on Kafka** (Amazon MSK or Kinesis on AWS) with an exact layer that **MERGEs into Iceberg** and survives a crash, plus a live layer with an event-time watermark and RocksDB state - a crashed batch replayed merged 206 rows and added **0 new rows**
  * **Every row accounted for:** Each run reconciles rows in = clean + quarantined + malformed; failing error-level checks block publishing, and every rejected row keeps a reason code. On real Kaggle YouTube data: **78,301 rows in = 73,357 clean + 4,944 quarantined**
  * **Lineage, catalog & cost:** Column-level lineage in a Lineage tab and as **OpenLineage** events, notes written to the **Glue Data Catalog**, personal-data columns tagged for **Lake Formation**, and the cost of each AWS run measured
  * **Web app:** FastAPI app for plan review, dry runs, runs and reconciliation, the dashboard, live streams and lineage, with a light/dark theme
  * **Testing & CI:** **105 tests** - 101 pytest (including 6 eval datasets) plus 4 on real **Spark 3.5 + Kafka** - with ruff, the eval harness and `terraform validate`, green in **GitHub Actions** on every push. AWS infrastructure is **Terraform**; the live AWS run is the next phase
  * Real issues found and fixed along the way: Gemini plans arriving with missing parameters (caught by the validator every time), real Kaggle CSVs breaking auto-detection (fixed with a parsing fallback ladder), Spark misreading SQL-escaped quotes in date formats, and a crash-replay test that left a stale checksum file

- 🏗️ **[YouTube Lakehouse (AWS-Native Batch Lakehouse)](https://github.com/Arjun-M-101/youtube-lakehouse)** 🔥 *Flagship Project*  
  End-to-end **AWS-native batch lakehouse** implementing the **Medallion Architecture (Bronze → Silver → Gold)** on a live AWS account, orchestrated top to bottom as infrastructure-as-code.
  * **Ingestion & orchestration:** S3 (lake) → Lambda (event trigger) → **Step Functions** (retries, DQ-gate branching, crawler polling, failure alerting)
  * **Transformation:** Two **AWS Glue (Spark)** jobs — Bronze→Silver validation/cleaning/dedup **with schema-drift detection**, and Silver→Gold aggregation with **full-refresh or opt-in incremental loading**
  * **Incremental processing:** **S3 watermark + filtered Spark reads + Redshift `MERGE`**, with full-refresh behavior retained as the safe default
  * **Modern table format:** Gold also lands as a genuine **Apache Iceberg** table (ACID commits, snapshot isolation, time-travel queries) via Glue 5.1's native Iceberg support — an additive, independently-written copy that can never affect the live Redshift/dbt/QuickSight path
  * **Warehouse & BI:** **Redshift Serverless** (private, VPC-only) feeding a published **QuickSight** dashboard; **Athena** for ad-hoc Silver queries and Iceberg time-travel queries on Gold
  * **Data quality:** A real DQ gate that quarantines (never silently drops) bad rows with a reason code, distinguishing duplicates from genuine corruption; schema-drift results are included in the DQ report
  * **Testing:** **pytest** unit tests for transformation/API logic + **27 dbt tests** against the warehouse
  * **IaC & automation:** Fully **Terraform**-managed, including a scripted open/close toggle for secure dbt runs against a private Redshift workgroup and dedicated VPC interface endpoints (Secrets Manager, Logs, STS, Glue) to avoid a NAT Gateway
  * **CI/CD:** **GitHub Actions** runs pytest, `terraform fmt`/`validate`, and `dbt parse` on every push — credential-free by design
  * Diagnosed and fixed **12 real production issues** on a live AWS account — including IAM, Terraform state drift, VPC/PrivateLink networking (QuickSight and Glue Catalog access), DQ false positives, schema drift, and incremental-loading/orchestration issues - with the deployment and teardown lifecycle fully documented in-repo

- 🚗 **[Connected-Car Telemetry on AWS (IoT Streaming Pipeline)](https://github.com/Arjun-M-101/connected-car-telemetry-aws)**  🔥 *Flagship Project*  
  End-to-end **IoT telemetry pipeline** for connected cars on a live AWS account: simulated vehicle sensors (tyre pressure, accelerator/clutch pedals, fuel level and efficiency) → **AWS IoT Core** → storage, real-time state, alerts and an AI chatbot, all deployed from **one CloudFormation template**.
  * **Device ingestion & identity:** Cars publish over **MQTT/TLS** to `vehicles/<id>/telemetry`; **one X.509 certificate and IoT policy per vehicle**, so a car can publish only to its own topic (spoofing test rejected by AWS IoT). Three **IoT rules** all take the vehicle ID from the authenticated topic, never from the payload
  * **Cold path (history):** IoT rule → **Amazon Data Firehose** (60 s buffer) → **S3** partitioned by date/hour → **Glue Data Catalog** table with **partition projection** (no crawler) → **Athena** SQL reports
  * **Data validation & schema drift:** A **Lambda transform** inside Firehose checks types and plausible ranges, keeps unknown device fields in an `extras` column (queryable immediately), flags bad values in `dq_issues` instead of dropping them, and stores an untouched raw copy of every message
  * **Hot path (real time):** A rule writes the latest reading per car to **DynamoDB** (point-in-time recovery on), so current vehicle state is available in about a second
  * **Alerts:** **SNS** e-mails the driver/support team when any tyre drops below **28 psi** (configurable parameter, based on TPMS regulations); tested with a simulated slow leak
  * **AI chatbot:** An LLM (Google Gemini via an OpenAI-compatible API, Amazon Bedrock or OpenAI) picks **one of 7 fixed, read-only Athena queries** and phrases the answer — it never writes SQL (prompt-injection safe by design), with a keyword fallback when no LLM is set
  * **Observability:** **CloudWatch** dashboard, 5 alarms (+1 optional no-data alarm) to a separate operations SNS topic, and 3 log groups with 30-day retention — e-mail path and a real no-data alarm and its recovery tested live
  * **Security:** Least-privilege IAM roles, TLS-only encrypted S3 bucket with public access blocked, no secrets in code (API keys entered silently, certificates git-ignored)
  * **Testing & CI:** **79 pytest tests** (validation, rule SQL, chatbot routing and injection attempts, device and event scripts) + **cfn-lint**, run by **GitHub Actions** on every push; README playbook covers deploy, 10 live test steps (including bad-data and spoofing tests) and a verified tear-down
  * Built in five versions (v1 → v4.1), each deployed and tested on AWS; diagnosed and fixed **11 real issues** along the way — including an IoT rule defect that only a live run exposed (vehicle ID taken from the payload instead of the topic), Bedrock access errors, Firehose buffering and CloudShell session pitfalls - all documented with redacted evidence

- 🗄️ **[YouTube Data Engineering Pipeline (Local Batch Processing)](https://github.com/Arjun-M-101/Youtube_DE_Project)**  
The **local precursor** to YouTube Lakehouse above — same Medallion Architecture, built first on local/open-source tooling before the AWS-native rebuild.
  - Orchestrated with **Apache Airflow (3.x)**  
  - Transformations with **Apache Spark**  
  - Data lake layers on **local filesystem** (Bronze/Silver/Gold)  
  - Serving layer in **Postgres** (analytics‑ready tables)  
  - Interactive **Streamlit + Altair dashboard** via SQLAlchemy  
  - Ingests raw **YouTube trending data (CSV/JSON)**, cleans, enriches, and computes derived metrics for BI  

- 📊 **[StockPulse (Streaming Pipeline)](https://github.com/Arjun-M-101/Stock_Pulse)**  
Real‑time **streaming pipeline** simulating stock ticks and processing them end‑to‑end.  
  - Ingestion via **Kafka producer** publishing to `stock_ticks` topic  
  - Processing with **Spark Structured Streaming** (schema enforcement + derived metrics)  
  - Dual sinks: **Postgres (serving layer)** + **Parquet (partitioned by index/date)**  
  - Interactive **Streamlit + Altair dashboard** for real‑time visualization  
  - Fully orchestrated with **Apache Airflow**

- 🧱 **[Retail Sales SQL Data Warehouse](https://github.com/Arjun-M-101/Retail-Sales-SQL-Data-Warehouse)**  
End‑to‑end **SQL data warehouse** implementing a **Bronze → Silver → Gold** layered architecture for retail sales.
  - Built entirely in **SQL Server/MySQL** (no external ETL tool)
  - Bronze layer mirrors raw **CRM & ERP** source tables (customers, products, sales, locations)
  - Silver layer applies **data quality checks** (ID normalization, date validation, gender/marital‑status standardization)
  - Gold layer models a **star schema** with fact_sales, dim_customers, and dim_products using surrogate keys
  - Uses **window functions (ROW_NUMBER)** and joins to integrate history, resolve conflicts, and conform dimensions
  - Produces **analytics‑ready views/tables** suitable for BI tools and downstream reporting

---

## 📜 Certifications

<table border="0">
  <tr>
    <td>
      <a href="https://aws.amazon.com/certification/certified-cloud-practitioner/" target="_blank">
        <img width="100" height="100" src="https://github.com/user-attachments/assets/58ceb4b2-d556-4eaf-94af-a353d1039cc8" alt="AWS Badge"/>
      </a>
    </td>
    <td>
      <a href="https://coursera.org/share/0ea80e3e8ef0a19fcddd5805f12a11b3" target="_blank">
        <img width="100" height="100" src="https://1000logos.net/wp-content/uploads/2022/06/Coursera-Logo.png" alt="Coursera Python Badge"/>
      </a>
    </td>
    <td>
      <a href="https://coursera.org/share/f5bfc62d51c5094a8bffae3651f360ae" target="_blank">
        <img width="100" height="100" src="https://1000logos.net/wp-content/uploads/2022/06/Coursera-Logo.png" alt="Coursera SQL Badge"/>
      </a>
    </td>
  </tr>
</table>

---

## 📊 My GitHub Stats

<p align="center">
  <a href="https://github.com/Arjun-M-101">
    <img alt="Arjun's streak"
         src="https://streak-stats.demolab.com?user=Arjun-M-101&theme=black-ice&hide_border=true&background=0D1117&stroke=FFFFFF"/>
  </a>
</p>
<p align="center">
<a href="https://github.com/Arjun-M-101">
  <img alt="Arjun M's Github Stats" 
     src="https://github-readme-stats-one.vercel.app/api?username=Arjun-M-101&show_icons=true&count_private=true&theme=black-ice&hide_border=true&bg_color=0D1117&title_color=FFFFFF&text_color=FFFFFF&icon_color=00FFFF"/>
</a>
<a href="https://github.com/Arjun-M-101">
  <img alt="Arjun M's Top Languages" 
     src="https://github-readme-stats-one.vercel.app/api/top-langs/?username=Arjun-M-101&langs_count=8&count_private=true&layout=compact&theme=black-ice&hide_border=true&bg_color=0D1117&title_color=FFFFFF&text_color=FFFFFF"/>
</a>
</p>

---

## 🌐 Connect with Me

<p align="left">
  <a href="https://www.linkedin.com/in/arjun-m-327a7a1a5/"><img src="https://img.icons8.com/fluent/48/000000/linkedin.png"/></a>
</p>

---

## ❤ Views and Followers

<a href="https://github.com/Arjun-M-101/github-profile-views-counter">
  <img src="https://komarev.com/ghpvc/?username=Arjun-M-101">
</a>
<a href="https://github.com/Arjun-M-101?tab=followers">
  <img src="https://img.shields.io/github/followers/Arjun-M-101?label=Followers&style=social" alt="GitHub Badge">
</a>
