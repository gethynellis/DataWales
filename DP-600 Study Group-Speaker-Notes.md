

# **Slide 1 – DP-600 Study Group: Overview Session**

**Speaker Script (2–3 minutes)**
“Welcome everyone, and thanks for joining our DP-600 Study Group session. Today is all about helping you understand what the DP-600 exam covers, how it fits into the wider Microsoft Fabric ecosystem, and what you should focus on as you prepare.

The DP-600 certification is aimed at Analytics Engineers—people who build, maintain, and optimise enterprise-scale analytics solutions using Microsoft Fabric. If you’ve taken the PL-300 or have experience with Power BI, you’ll find some familiar ground here, but DP-600 goes much deeper. It moves beyond report-building and into areas like data engineering, semantic modelling, governance, pipelines, and optimisation.

As we go through the session today, keep the exam in mind: it is very scenario-driven. You’ll be given business problems and asked to determine the correct Fabric component, design pattern, or modelling technique. So this study group is designed to give you both conceptual understanding and practical insights that map directly to what you’ll face in the exam.

By the end of today’s session, you should have a clear roadmap for your preparation and know exactly where to focus your learning.”

---

# **Slide 2 – From PL-300 to DP-600: Level Up Your Analytics Skills**

**Speaker Script (2–3 minutes)**
“This slide sets the tone for what makes DP-600 different. Many of you may already hold the PL-300 or have Power BI experience, and that’s a fantastic foundation. PL-300 is the analyst-focused certification—mostly working at the semantic modelling and reporting layer.

DP-600 takes you *behind the scenes* into Fabric’s full analytics stack. Instead of using only Power BI Desktop, you’re working across Lakehouses, Warehouses, Pipelines, Dataflows Gen2, Notebooks, semantic models, and more. You're expected to understand end-to-end architecture, not just visuals.

This exam also assumes you can solve problems such as:
– Which Fabric item should be used for a particular data scenario?
– When to use a Lakehouse versus a Warehouse?
– How to manage delta tables?
– How to optimise a semantic model for large-scale analytics?
– How governance, security, and workspace structure impact an organisation?

Think of DP-600 as the bridge between data engineering and analytics: the role that connects raw data to business-ready insights.

If PL-300 focuses on *using* the data, DP-600 focuses on *preparing, modelling, governing,* and *optimising* it.”

---

# **Slide 3 – What We’ll Cover Today**

**Speaker Script (2–3 minutes)**
“Today’s session is structured around the three major skill areas you’ll be tested on in the DP-600 exam.

First, we’ll explore **data analytics in the context of Fabric**. Fabric is a unified SaaS analytics platform, so understanding how the different workloads connect—Lakehouse, Warehouse, Real-Time Intelligence, Data Factory—is core to the exam.

Second, we’ll break down the core responsibilities of an **Analytics Engineer**:
• Preparing data: working with medallion architecture, dataflows, notebooks, pipelines
• Implementing and managing semantic models: relationships, Direct Lake vs Import vs DirectQuery, model optimisation
• Maintaining an analytics solution: governance, monitoring, workspace strategies, lifecycle and deployment considerations

Third, we’ll discuss **exam preparation tips** and recommended learning resources. The exam requires not only knowledge of individual Fabric features, but also when to use which feature in a given scenario. So practice using the platform is just as important as studying.

By the end of the session, you’ll have a structured view of the exam and the competencies needed to pass it.”

---

# **Slide 4 – Who Are We**

**Speaker Script (2 minutes)**
“Before we dive in, a quick introduction to who’s guiding you through the session. This study group brings together practitioners who not only teach Fabric but actively implement it across real-world projects. You’ll see three different perspectives—consultancy, training, and community leadership—which gives you a well-rounded view of the exam and the tech.

One thing we all share is hands-on experience deploying analytics solutions at scale. That’s important because DP-600 isn’t a theoretical exam. It tests practical judgement—something you only get from working with the tools in real projects. So as we go through the slides, we’ll draw on examples from our field work to help reinforce the concepts.”

---

# **Slide 5 – Justin Bird**

**Speaker Script (2–3 minutes)**
“Justin brings deep experience in Microsoft data technologies, and he wears several hats in the community—as a consultant, Microsoft Certified Trainer, STEM ambassador, and a leader in major community events like Data Toboggan and Data Weekender.

From a DP-600 perspective, Justin’s strengths lie in semantic modelling, Power BI architecture, and practical performance tuning—skills that feature heavily in the exam. His hands-on experience helping organisations adopt Fabric gives him insight into the types of real-world challenges that the exam scenarios mirror.

If you have questions around modelling strategies, workspace design, governance structures, or getting started with Fabric from a Power BI background, Justin is the person to ask.”

---

# **Slide 6 – Gethyn Ellis**

**Speaker Script (2–3 minutes)**
“Gethyn has a long background in data platform engineering and training, and his perspective is particularly valuable for DP-600 because the certification sits at the intersection of data engineering and analytics. As a Microsoft MVP and MCT, he brings both deep technical knowledge and teaching experience.

Many of the exam topics—like pipelines, data ingestion strategies, Lakehouse/Warehouse comparison, and governance—map directly to the kinds of SQL Server and Azure data architecture projects he has worked on for years.

Gethyn also runs community events like SQLBits sessions, Data Weekender and Data Wales, which means he’s constantly engaged in discussions around how organisations are adopting Fabric today. This kind of real-world context helps enormously when breaking down exam scenarios.”

---

# **Slide 7 – Ryan Gillett**

**Speaker Script (2–3 minutes)**
“Ryan completes our trio of presenters and brings deep technical expertise as a consultant, Microsoft Certified Trainer, and STEM Ambassador. His work spans Fabric, Power BI, and data engineering—again, the perfect alignment for the DP-600 exam.

Ryan’s strengths include hands-on engineering across Lakehouse architecture, data ingestion, notebooks, and semantic modelling—practical skills that feature extensively in the exam blueprint. He also contributes to community initiatives like Code Club and wider STEM engagement, making him particularly good at explaining complex concepts clearly.

If you're looking to understand the more technical aspects of Fabric—like pipelines, delta tables, or the distinction between items within the OneLake ecosystem—Ryan’s your go-to.”

---

# **Slide 8 – Data Analytics Certifications**

**Speaker Script (2–3 minutes)**
“This slide is about understanding where DP-600 fits within Microsoft’s certification landscape. Over the last few years, Microsoft has been moving certifications into role-based pathways—so rather than learning a product, you’re learning skills for a job role.

In the data analytics space, the two primary certifications are PL-300 and DP-600. PL-300 focuses on data analysis and visualisation using Power BI. DP-600 is the step up for those who architect, build, and maintain enterprise-grade analytics solutions.

One important thing to note is that DP-600 aligns with the shift towards Fabric as Microsoft’s unified analytics platform. Fabric brings together services that were previously separate—Synapse, Power BI, Data Factory—so the certification now reflects a much broader analytics lifecycle. This exam is about being the person who connects all of those pieces.

Understanding the difference between the two certifications will help you position your career and your learning path.”

---

# **Slide 9 – Fabric Role-Based Certifications**

**Speaker Script (2–3 minutes)**
“Here we see the two certifications side by side: PL-300 and DP-600. Think of them as covering different layers of the Fabric architecture.

PL-300 is about working at the *consumption* layer—building reports, shaping data at a personal or departmental level, working mainly inside Power BI Desktop and Service.

DP-600 expands that into the *platform* and *engineering* layer:
– building semantic models at an enterprise scale
– designing ingestion frameworks
– working with Lakehouses and Warehouses
– managing workspaces, pipelines, and governance
– implementing CI/CD using Fabric Git integration
– optimising performance across the full stack

One thing to emphasise for candidates: DP-600 expects you to understand the roles of each Fabric item and when to use them. The exam will often give you multiple technically possible solutions, and you’ll need to pick the most appropriate one based on performance, governance, or cost considerations.

That’s why study groups like this are so valuable—Fabric is broad, and the exam covers both breadth and depth.”

---

# **Slide 10 – Fabric Analytics Engineer Certification**

**Speaker Script (2–4 minutes)**
“This slide summarises the DP-600 certification itself. As you can see, the exam is aimed at Analytics Engineers and advanced Data Analysts. It’s classified as ‘intermediate’, but make no mistake—many people find it significantly more demanding than PL-300 because of how broad Fabric is.

The exam covers three main skill areas:
• **Maintain an analytics solution** – governance, monitoring, workspace design, lifecycle management
• **Prepare data** – Lakehouse architecture, Delta tables, Dataflows Gen2, notebooks, ingestion pipelines
• **Implement and manage semantic models** – relationships, storage modes, large models, Direct Lake optimisation, incremental refresh, calculation groups

Another key exam expectation is familiarity with query languages like SQL, KQL, and DAX. You don’t need to be an expert in every one, but you should recognise their purpose and where each fits within Fabric.

The exam scenarios also emphasise working with stakeholders, interpreting requirements, and selecting the correct Fabric component for the problem. It’s not just ‘how does this feature work’ but ‘should I use this feature at all?’

We’ll return to this throughout the study group because that judgement-based thinking is essential for passing DP-600.”


Below is a **professional speaker script** for Slides **11–20**, each written to comfortably support **2+ minutes of delivery**, aligned to the DP-600 exam expectations and suitable for your multi-presenter flow.

---

# **Slide 11 – Analytics Engineer (DP-600) Skills in Depth**

**Speaker Script (2–3 minutes)**
“This slide breaks down the *actual skill areas* tested in the DP-600 exam, and this is where your study plan should really focus.

The first area—**Maintain a data analytics solution**—accounts for around 25–30% of the exam. This is all about governance, security, workspace architecture, deployment pipelines, Git integration, and managing analytics in a controlled, scalable way. Many candidates underestimate this section, but Fabric is an enterprise platform, so governance is a core exam theme. You should expect scenario questions like:
*'Which workspace structure is appropriate for this team?'*
*'How should data lineage and access be handled?'*
*'When should deployment pipelines be used versus Git?'*

The second—and largest—area is **Prepare data**, at 45–50%. This is nearly half the exam. It covers ingestion, transformation, and querying data using Lakehouses, Warehouses, Dataflows Gen2, Spark, and pipelines. You must know when to use each tool and *why*. For example:
– When is Dataflows Gen2 appropriate?
– When should Spark be used?
– How do delta tables behave in Fabric?
– Which ingestion pattern fits a specific business scenario?

Then we have **Implement and manage semantic models** at 25–30%. This is the link between Power BI and the Fabric data estate. You need to understand enterprise modelling, Direct Lake versus Import, incremental refresh, relationships, calculation groups, and optimisation techniques. Expect exam items around large-scale performance, star schema correctness, and choosing the right storage mode.

So this slide is essentially the exam blueprint. If you understand these three sections deeply, you are in very good shape for the DP-600 certification.”

---

# **Slide 12 – Introduction to Microsoft Fabric**

**Speaker Script (2–3 minutes)**
“Before diving deeper into the skills, we need to establish a clear foundation: What *is* Microsoft Fabric?

Fabric is Microsoft’s unified analytics platform. It brings together what were previously separate services—Synapse, Data Factory, Power BI, and parts of Azure Machine Learning—into a single integrated environment.

For the exam, think of Fabric not as *one tool* but as a *collection of workloads on a single SaaS foundation*, all running on OneLake, all governed the same way, all integrated automatically. This end-to-end integration is central to both the technology and the DP-600 exam.

Candidates should understand that Fabric’s core purpose is to reduce friction between data engineering, analytics, business intelligence, and real-time systems. Instead of stitching services together manually, Fabric provides a single place where ingestion, transformation, modelling, security, and reporting all live together.

In the exam, you’ll often see scenario-based questions that test your ability to choose the right Fabric workload. Understanding the overall Fabric concept helps anchor all those choices.”

---

# **Slide 13 – Unified Data Platform for the Era of AI**

**Speaker Script (2–3 minutes)**
“This slide breaks down the workloads inside Fabric, each of which corresponds to a capability you’ll use in the exam.

**Data Factory** brings Power Query plus orchestration into Fabric. Whenever you see questions about ETL, pipelines, scheduling, ingestion from SaaS systems, or low-code transformations, think Data Factory or Dataflows Gen2.

**Data Engineering** is all about Spark and notebooks. The exam will test when Spark is needed—for example, large-scale processing, machine learning preparation, or complex transformations.

**Data Warehouse** gives you the modern SQL warehouse inside Fabric. Expect exam questions on when Warehouses are appropriate versus Lakehouses, as well as T-SQL patterns, indexing behaviour, and performance optimisation.

**Data Science** integrates Azure ML and Spark-based training. You don’t need to be a machine learning expert, but you should be familiar with how ML workloads run within Fabric and where the compute happens.

**Real-Time Intelligence** is Microsoft’s solution for streaming analytics and events. It appears in the exam in questions asking about real-time dashboards, KQL, or analysing live data flows.

Finally, **Power BI** is still the front end—but now it’s fully integrated with OneLake. Semantic models can use Direct Lake storage, which is a major exam topic.

So this is your mental model: Fabric is one platform with multiple specialised workloads, and the DP-600 exam tests your ability to pick the right one for the job.”

---

# **Slide 14 – Data Storage in Fabric**

**Speaker Script (2–3 minutes)**
“This slide brings us to one of the most examined concepts: **OneLake**.

Fabric’s entire storage layer is unified. Whether you're using a Warehouse, a Lakehouse, KQL database, or SQL database, they all sit on OneLake. That means a single logical data lake for the entire organisation.

Key things to emphasise for the exam:

1. **Fabric is centred on OneLake**—a single logical storage layer, not lots of disconnected lakes.
2. **Powered by Synapse Analytics**—so the underlying compute patterns follow the modern Synapse approach.
3. **Supports T-SQL natively** in Warehouses and SQL Databases.
4. **Uses Parquet and Delta formats** in Lakehouses.

A classic exam trick is to describe a scenario where an organisation is duplicating data across systems. The correct Fabric answer is almost always to centralise through OneLake and expose it via Shortcuts.

Another area: understanding that Workspaces map to containers inside OneLake. This allows governance and secure multi-tenancy.

If you understand OneLake deeply, a large portion of the exam becomes much easier.”

---

# **Slide 15 – Warehouses and SQL Databases in Fabric**

**Speaker Script (2–3 minutes)**
“Fabric includes two SQL-based options, and the exam often tests the difference.

The **Warehouse** is the enterprise-grade SQL engine. It supports full T-SQL, indexing, stored procedures, and scale. It is designed for mission-critical workloads, formal modelling, and integrating into the semantic model layer.

The **SQL Database** is a lightweight relational store within a workspace. It’s ideal for line-of-business scenarios, smaller datasets, and quick prototypes.

Both sit on top of OneLake—this is a recurring exam theme. That means they inherit the unified storage benefits: data sharing, shortcuts, governance, and integration with semantic models.

Expect questions such as:
– When do you use a Warehouse versus a Lakehouse SQL endpoint?
– What are the performance considerations?
– How does SQL Database differ in capability from Warehouse?

Remember: if you need enterprise-grade T-SQL and performance, the Warehouse is your answer.”

---

# **Slide 16 – Lakehouses in Fabric**

**Speaker Script (2–3 minutes)**
“Here we see the idea behind a Lakehouse: combining the flexibility of a *data lake* with the structured querying of a *data warehouse*.

The Lakehouse uses Apache Spark and Delta Lake technology to provide scalable storage, schema-on-read, and compatibility with big data tools. It’s ideal for raw, semi-structured, or large datasets.

Paired with this is the **SQL analytics endpoint**, which gives relational access to the underlying delta tables. This hybrid capability is heavily tested in the exam.

Expect exam items like:
– When should you use a Lakehouse instead of a Warehouse?
– How do Delta tables behave?
– What capabilities belong to the Lakehouse versus the SQL endpoint?

The takeaway: Lakehouses give you the flexibility of a lake and the structure of a warehouse, all inside OneLake. This hybrid design is unique to Fabric.”

---

# **Slide 17 – Prepare Data in Fabric**

**Speaker Script (2–3 minutes)**
“This slide introduces the flow of preparing data for analytics: **Get → Transform → Query and Analyse**.

Almost half the DP-600 exam is about the Prepare Data domain. You need to know the tools Fabric provides, when to use them, and how they interact.

Fabric gives you multiple ingestion methods (pipelines, shortcuts, notebooks, Dataflows Gen2) and then multiple ways to transform and model the data.

In the exam, you’ll often be asked:
– Which ingestion tool is appropriate?
– How should data be transformed?
– Should Spark or Dataflows be used?
– How do you configure incremental refresh in a semantic model?

This slide sets the stage for the deeper sections that follow.”

---

# **Slide 18 – Get Data**

**Speaker Script (2–3 minutes)**
“This slide covers ingestion, which is a major exam theme. Fabric can ingest from almost anywhere: databases, files, SaaS applications, APIs, streaming sources—you name it.

You have several ingestion tools:
• **Dataflows Gen2** – Low-code Power Query experience.
• **Notebooks** – For Spark-based, large-scale ingestion.
• **Pipelines** – Orchestration, scheduling, automation.
• **Shortcuts** – Virtual links to external data without copying.

Shortcuts appear frequently in exam questions—they’re Fabric’s solution for eliminating data duplication and supporting cross-workspace sharing.

A typical exam scenario might describe a business wanting to share Lakehouse data with multiple departments without copying it. The correct answer: *use a shortcut into OneLake*.

Another scenario: ingesting data hourly from a SaaS source with transformation before landing in a curated zone. That points to Dataflows Gen2 and Pipelines.

So the key here is: Fabric gives you the right tool for each ingestion pattern, and the exam will test your judgment in choosing between them.”

---

# **Slide 19 – Transform and Explore Data**

**Speaker Script (2–3 minutes)**
“Once the data is ingested, Fabric provides multiple transformation paths.

**Dataflows Gen2** is ideal for standardised transformations—business users or analysts can use them with governed, reusable logic.

**Data Pipelines** let you orchestrate multi-step processes, combining Dataflows, Notebooks, SQL scripts, and more.

**SQL analytics endpoints** allow relational querying of Lakehouse delta tables. This is useful for joining, filtering, aggregating, and previewing data.

**Apache Spark** and **Notebooks** handle larger or more complex transformations, machine learning preparation, or file-based operations. Spark Job Definitions let you formalise and schedule Spark logic.

The exam wants you to know *which tool to use when*. For example:
– If a business user needs to join multiple sources and apply basic transformations, Dataflows Gen2 is correct.
– If you need heavy processing or machine learning prep, Spark is correct.
– If you need governance and scheduled processing, Pipelines are correct.

Another frequent theme: transformations should be reusable and governed—Fabric’s design reinforces that across Dataflows and Notebooks.”

---

# **Slide 20 – Get and Transform Data with Dataflow Gen2**

**Speaker Script (2–3 minutes)**
“This slide dives deeper into Dataflows Gen2, a tool you will see frequently in DP-600 exam questions.

Dataflows Gen2 provides a low-code Power Query environment for ETL. It lets you connect to multiple sources, transform the data, and *load it into a destination* such as a Lakehouse or Warehouse.

Key exam considerations:
– Dataflows Gen2 can be triggered manually, scheduled, or run as part of a Pipeline.
– They support advanced Power Query transformations and integrate directly with OneLake.
– They are excellent for business-standard cleaning logic—things like type conversions, merges, joins, filters, and aggregations.

A common exam pattern:
*'A team without Spark expertise needs to join several SaaS datasets and load cleaned results into a Lakehouse. What should they use?'*
The correct answer will almost always be: **Dataflows Gen2**.

Another exam scenario: orchestrating multiple Dataflows and Notebooks in a single controlled workflow. The correct solution would be: **use a Data Factory Pipeline**.

Understanding Dataflow Gen2 is essential because it represents Fabric’s modern ETL approach.”

Below is a **clear, presenter-ready speaker script** for **Slides 21–30**, written to support **at least two minutes of delivery per slide** and aligned to DP-600 exam expectations.

---

# **Slide 21 – Orchestrate Data with Pipelines**

**Speaker Script (2–3 minutes)**
“Pipelines in Fabric are the orchestration engine that ties your entire data ecosystem together. They allow you to coordinate ingestion, transformation, and downstream processing across multiple sources and destinations—all in a consistent, governed way.

In the DP-600 exam, you will see scenarios that require choosing between Dataflows, Notebooks, and Pipelines. The key is this: **Pipelines handle orchestration and automation**, not just transformation. They let you schedule workflows, add control-flow logic like IF/FAIL branches, and chain together multiple activities—Spark notebooks, Dataflows Gen2, SQL scripts, copy activities, and more.

Pipelines also integrate directly with Lakehouses, Warehouses, and SQL Databases, so they become the backbone of enterprise data operations.

Two exam-relevant features are:
• **Parameters** – Pipelines can take inputs to make processes reusable, for example switching between environments.
• **Monitoring and logging** – You can see past runs, identify failures, and capture lineage, which supports governance.

A common exam pattern is:
‘You need to orchestrate ingestion from several systems, apply transformations, and handle failures gracefully.’
The correct answer is usually: **Use a Data Factory Pipeline**, because Dataflows and Notebooks alone don’t provide orchestration or error handling.

Pipelines scale your ETL beyond single-report refreshes—they’re your enterprise-grade workflow engine inside Fabric.”

---

# **Slide 22 – Data Transformation and Exploration with Notebooks**

**Speaker Script (2–3 minutes)**
“Notebooks are Spark-powered, multi-language environments inside Fabric that let you perform advanced data transformations and exploratory analysis. They support Python, SQL, R, and Spark, and are ideal for large data volumes or complex logic that goes beyond what Dataflows Gen2 can do.

In the exam, you need to know *when* to use a Notebook instead of a Dataflow or SQL:
• Use **Dataflows Gen2** for governed, standard, low-code transformations.
• Use **Notebooks** for scale, experimentation, or custom code.
• Use **Warehouses** for relational transformations in SQL.

Notebooks integrate directly with Lakehouses—they can read and write Delta tables, manage partitions, and prepare data for semantic modelling. They also complement Dataflows: you might stage raw data with a Notebook and then refine it with Dataflows Gen2.

The exam may ask when to use Spark for performance reasons—for example, handling tens of millions of rows or running ML transformations.

A typical DP-600 scenario:
‘Data scientists need to explore data, test transformations, and prepare features for downstream modelling.’
Correct answer: **Use a Notebook in the Data Engineering workload**.

So for your study, focus on understanding the role of Notebooks in the ingestion → transformation → modelling pipeline.”

---

# **Slide 23 – Query and Analyse Data**

**Speaker Script (2–3 minutes)**
“This slide focuses on the *exploration and validation* stage—an essential part of the analytics engineering lifecycle and a recurring theme in the exam.

Fabric lets you query data using:
• T-SQL against Warehouses and SQL Endpoints
• KQL for real-time and log data
• DAX for semantic model queries
• Spark or Python for large-scale operations

You’ll use these tools to validate transformations, test joins, preview data, and prototype calculations before they reach the semantic model.

The exam often tests:
– When to use SQL vs Spark?
– How to validate transformations before modelling?
– How to perform ad hoc queries without affecting production?

A common scenario:
‘The team wants to test a transformation pipeline before loading data into production tables.’
The recommended approach: **Use SQL or Notebook queries in a dev workspace**.

Another exam theme is supporting multiple downstream consumers—dashboards, ML pipelines, external tools—so understanding SQL endpoints and Lakehouse querying is key.

Being able to explore data at scale is what separates analytics engineering from traditional BI.”

---

# **Slide 24 – Implement and Manage Semantic Models**

**Speaker Script (2–3 minutes)**
“Now we move into one of the most exam-heavy areas: semantic models. This is where all your upstream engineering work becomes usable for reporting, analytics, and AI workloads.

Semantic models provide structured relationships, measures, hierarchies, security rules, and optimised storage. DP-600 expects you to understand how to build and maintain enterprise-grade models—not just simple Power BI datasets.

Key exam themes include:
• Storage modes (Import, DirectQuery, Direct Lake) and when to use each
• Model design—fact tables, dimensions, star schemas
• Optimising performance
• Applying Row-Level Security and Object-Level Security
• Managing large models and incremental refresh
• Integrating semantic models with Fabric pipelines and governance

A typical exam scenario might ask:
‘Which storage mode supports real-time performance against a Lakehouse without scheduled refresh?’
Correct answer: **Direct Lake**.

By this part of the presentation, the audience should understand that semantic modelling is where engineering and BI converge, and the DP-600 exam tests that intersection heavily.”

---

# **Slide 25 – Design for Scalability**

**Speaker Script (2–3 minutes)**
“This slide highlights three pillars of scalable semantic model design. These principles appear repeatedly in the exam because Fabric is used for enterprise-scale analytics, not just small BI solutions.

1. **Flexibility** – Models must adapt to new data sources, schema changes, or business evolution.
   The exam may ask how to future-proof a model: use a clean star schema, stable surrogate keys, and avoid over-engineering.

2. **Data Growth** – As data volumes increase, the model must still perform.
   Solutions include incremental refresh, aggregations, proper indexing upstream, and choosing the right storage mode.

3. **Reduced Complexity** – Overly complicated models cause performance problems and governance issues.
   In the exam, this often appears as:
   ‘The model is slow due to multiple snowflake chains and unnecessary tables—what should you do?’
   The answer: simplify the model into a star schema.

The overarching message is: scalable models are clean, structured, predictable, and designed for enterprise growth. DP-600 will test whether you can identify and correct anti-patterns.”

---

# **Slide 26 – Storage Modes Reimagined (Import, DirectQuery, Direct Lake)**

**Speaker Script (2–3 minutes)**
“This is one of the *most important exam slides* because storage mode questions appear frequently.

Let’s break the modes down:

### **Import**

• Data is stored in-memory inside the semantic model
• Fastest query performance
• Requires scheduled refresh
• Best for curated, stable datasets

### **DirectQuery**

• No data stored in the model—queries go back to the source
• Near real-time
• Performance depends on source
• Limited transformations

### **Direct Lake**

• Unique to Fabric
• Directly reads delta tables from the Lakehouse
• Combines DirectQuery freshness with Import-like speed
• Limited transformations allowed

Direct Lake is a core DP-600 topic. Microsoft strongly emphasises its use because it’s Fabric’s differentiator.

Finally, **Composite models** let you mix storage modes. The exam may ask when combining Import and DirectQuery is beneficial—for example, aggregations in Import with detailed data in DirectQuery.

A good rule for the exam:
If you want **performance + freshness**, and you’re working with a Lakehouse → choose **Direct Lake**.”

---

# **Slide 27 – Optimise Semantic Models**

**Speaker Script (2–3 minutes)**
“This slide describes the key best practices for optimising models, and many of these appear directly in DP-600 questions.

**Prepare data upstream** – Fabric expects transformations to occur before modelling. The semantic model should not be doing heavy shaping.

Exam-relevant practices include:
• Use **views instead of tables** when working with relational databases
• Only include rows, tables, and fields that are necessary
• Use **incremental refresh** or **partitioning** to reduce load
• Choose optimal data types—integers over strings, for example
• Ensure **query folding** is preserved wherever possible

A typical exam trick:
‘Your model is slow and refreshes take too long. What should you do?’
The correct answers often involve:
– Reducing columns
– Using views
– Enabling incremental refresh
– Pushing transformations upstream

Model performance is central to the DP-600 exam, so mastering these principles is essential.”

---

# **Slide 28 – Maintain an Analytics Solution in Fabric**

**Speaker Script (2–3 minutes)**
“This module covers the governance, monitoring, deployment, lineage, and operational aspects of analytics solutions—roughly 25–30% of the exam.

Maintaining a Fabric solution means ensuring everything runs reliably and securely over time. You need to understand workspace structure, access control, deployment pipelines versus Git integration, monitoring refreshes and pipeline runs, and auditing data movement.

DP-600 exam questions often describe enterprise scenarios where multiple teams collaborate. You’ll need to choose between:
• Multiple controlled workspaces
• Shared datasets and semantic models
• Deployment pipelines for lifecycle management
• Git integration for version control and CI/CD
• Monitoring solutions like Fabric’s built-in admin tools

This section tests your architectural judgement more than technical syntax.

Fabric is an enterprise tool, and the exam expects you to think like an enterprise engineer.”

---

# **Slide 29 – Data Security in Fabric**

**Speaker Script (2–3 minutes)**
“This slide outlines Fabric’s multi-layered security model—another heavily tested exam area.

Fabric security includes:

### **Workspace Roles**

These control access at the workspace level—Admin, Member, Contributor, Viewer. The exam will test which role is appropriate for each scenario.

### **Item Permissions**

Every Fabric item—Lakehouses, Warehouses, Notebooks, Pipelines—has its own permission model. You need to know when to grant item-level permissions instead of workspace-level permissions.

### **Granular Engine Permissions**

This is where things become detailed:
• Lakehouses have permissions at the folder and table level
• Warehouses have SQL permissions like SELECT, INSERT, EXECUTE
• Semantic models have build permissions and RLS

### **OneLake Access Controls**

Shortcuts and data sharing require secure configuration of underlying storage.

A common exam scenario:
‘Users must be able to query a Warehouse but not modify objects.’
Correct answer: **Assign the appropriate SQL permissions (e.g., SELECT)**, not workspace-level Contributor.

Security is one of the highest-weighted governance areas in DP-600.”

---

# **Slide 30 – Security at the Semantic Model Level**

**Speaker Script (2–3 minutes)**
“Semantic model security focuses on Row-Level Security (RLS), Object-Level Security (OLS), and designing models that enforce access consistently.

Key best practices tested in the exam include:

• Use **fewer, well-structured models** and avoid duplication
• Create **dynamic roles**—for example, filtering based on USERPRINCIPALNAME()
• Apply RLS on **dimension tables**, not fact tables
• Validate all relationships to ensure filtering works as designed
• Use USERPRINCIPALNAME(), not USERNAME(), especially in cloud scenarios
• Thoroughly test RLS and OLS in both Desktop and the Service
• Make sure credentials match between Desktop and Service

An exam scenario might describe a security leak where users can see data they shouldn’t. The correct answer often involves:
– Fixing relationships
– Moving RLS to the correct table
– Using dynamic RLS
– Ensuring filters propagate correctly

Security is an essential competency for Analytics Engineers, so expect multiple nuanced questions in the DP-600 exam.”

Below is a polished **speaker script for Slides 31–35**, each written so you can comfortably talk for **two minutes or more**, reinforcing DP-600 exam expectations and providing practical context for your attendees.

---

# **Slide 31 – Manage Assets Through the Development Lifecycle**

**Speaker Script (2–3 minutes)**
“This slide brings together the full lifecycle of developing and managing analytics assets in Fabric, which is a major focus area for the DP-600 exam. What Microsoft wants candidates to understand is that Fabric projects aren’t just about building datasets or pipelines—they need to be engineered, versioned, validated, and deployed with the same discipline as any enterprise software solution.

Let’s break down the key components:

### **Version Control**

Fabric supports Git integration at the workspace level. This means your Lakehouses, Warehouses, semantic models, and reports can all be version-controlled, allowing rollback, collaboration across teams, and change tracking. A common exam scenario describes multiple developers making updates simultaneously. Git is the correct answer for coordinating changes.

### **Deployment Pipelines**

These provide structured movement from development → test → production. They ensure consistent deployments, proper governance, and reduce the risk of accidental production changes. The exam will often test whether a scenario is better suited to deployment pipelines or Git. Pipelines move *content*; Git manages *code and versioning*.

### **Testing & Validation**

Before promoting anything to production, accuracy and integrity must be verified—data quality checks, relationship validation, security rules, and performance testing. The exam may ask:
‘How do you ensure an RLS change won’t break downstream reports?’
The correct approach: test in a non-production workspace before promoting.

### **Monitoring**

Fabric provides built-in tools for monitoring capacities, pipeline runs, refresh histories, and model utilisation. DP-600 scenarios frequently require choosing the right monitoring tool.

### **Automation**

With APIs, CI/CD, service principals, and scripted deployments, Fabric solutions can be deployed hands-off. This is especially important in larger organisations with strict release processes.

Altogether, this slide reinforces a core DP-600 message: Fabric is an enterprise analytics platform—and enterprise engineering practices must be applied throughout the lifecycle.”

---

# **Slide 32 – Exam Prep Tips and Learning Resources**

**Speaker Script (2 minutes)**
“As we approach exam preparation, the most important advice is that DP-600 is not a purely theoretical exam—it is hands-on and scenario-based. You will be asked to choose the best architecture or design pattern for a given business problem.

So your preparation should focus on *experience* rather than memorisation. The more time you spend inside Fabric—building Lakehouses, modelling data, configuring pipelines—the easier the questions become.

The next few slides outline specific strategies and resources that have proven effective for learners preparing for this exam.”

---

# **Slide 33 – DP-600 Exam Prep Tips**

**Speaker Script (2–3 minutes)**
“This slide breaks down four practical tips that we strongly recommend for your preparation.

### **1. Get Hands-On**

Nothing replaces real experience. Even going through Microsoft-supplied sample datasets in a Fabric workspace will help you build intuition for differences between Warehouses, Lakehouses, Dataflows Gen2, and Direct Lake models. The exam heavily tests ‘when to use which tool.’

### **2. Review Available Prep Resources**

Microsoft publishes a detailed skills outline for DP-600. Every topic listed there is fair game for the exam. Use this outline as your study map.

### **3. Complete Microsoft Learn Modules**

Learn modules are structured exactly around the competencies assessed in DP-600. They include guided exercises that mirror the style of tasks seen in real projects.

### **4. Take the Practice Assessment**

This gives you a real feel for the question structure—multi-select questions, case studies, scenario-based items. When reviewing your missed answers, pay close attention to *why* each incorrect option is wrong. These reasons often reveal common exam traps, such as mixing up Warehouses and Lakehouses.

By combining these four prep strategies, you greatly reduce surprises on exam day.”

---

# **Slide 34 – Resources**

**Speaker Script (2–3 minutes)**
“These are some of the most effective learning resources available today:

### **Microsoft Learn**

This is the authoritative source aligned directly to the exam blueprint. It covers semantic modelling, governance, data engineering, and performance optimisation.

### **Fabric Labs**

These labs offer hands-on exercises that help you practise real Fabric workloads. They’re essential for building the muscle memory needed for DP-600.

### **Reactor DP-600 Series**

The Microsoft Reactor team has delivered multiple practical sessions on Fabric’s capabilities. These recordings are ideal for reinforcing understanding and seeing real demos in action.

We’ve also included a link to our curated learning hub. Everything you need to prepare—labs, videos, documentation—is centralised there. Use this as your starting point when planning your study approach.”

---

# **Slide 35 – Questions?**

**Speaker Script (2 minutes)**
“This brings us to the end of today’s session. The DP-600 exam is one of the most exciting certifications right now because it reflects the future of analytics engineering: unified storage, integrated workloads, and a seamless development lifecycle across the entire data platform.

If you have questions—technical, exam-related, or about your learning path—now is the perfect time to ask. We’re happy to expand on anything we’ve covered today, whether it’s storage modes, semantic modelling, governance, or Fabric workloads.

And remember, all the resources we’ve mentioned—Microsoft Learn modules, practice assessments, labs—are available at the link shown here. They’re designed to give you both the conceptual understanding and the practical experience needed to pass DP-600 with confidence.

Thank you for joining us, and we’re looking forward to your questions.”







