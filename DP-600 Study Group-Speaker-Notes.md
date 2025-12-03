

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

---

If you’d like, I can now continue with the **next ten slides**, maintaining the same level of detail and pacing.
