Hi, I'm Ashwini Kumar Mishra 👋

IAM Engineer | Database Sleuth | Automating Everything That Needs Doing Twice

class Engineer:
    def __init__(self):
        self.name = "Ashwini Kumar Mishra"
        self.role = "Identity & Access Management / IGA Specialist"
        self.primary_weapon = "SQL Queries That Make DBAs Sweat"
        self.superpower = "Finding why that one Leaver still has domain admin access"


I spend my time at the messy intersection of Identity Governance, relational databases, REST APIs, and automation. If an identity sync fails, a job hangs in the process queue, or an account mysteriously disappears, I don’t just restart the service—I dig into the database tables to figure out which exact constraint screamed for help.

🧰 The Arsenal

Domain

Weapons & Concepts

IAM & Governance

One Identity Manager (1IM), JML Lifecycles, Attestations, SoD, Entitlement Cleanups

Databases

SQL (Window Functions, Aggregations, Deep Dives into Person & ADSAccount), Schema Audits

Automation & Code

Python (Pandas, ETL pipelines, "don't make me do this manually" scripts), Bash

APIs & AppSec

REST APIs, Postman, AuthN/AuthZ Flows, Input Sanitization, SQLi Prevention

🔎 What I Actually Do

Identity Governance & Administration (IGA): Keeping Joiner/Mover/Leaver (JML) workflows honest. Making sure access requests don't sit in approval limbo forever and audit reports actually pass on the first try.

Database Forensics: One Identity Manager UI tells you what failed; the database tells you who to blame. I track down orphaned objects, mismatched foreign keys, and stuck job queues at the data layer.

ETL & Data Hygiene: Building Python workflows to ingest, validate, and normalize messy real-world datasets before they corrupt downstream production systems.

API & App Security: Testing authorization boundaries so the wrong token doesn't open the wrong door.

⚙️ How I Triage Enterprise Chaos

[ Problem Reported: "The UI looks broken" ]
                     │
                     ▼
       [ Check Job Engine & Queue ] ── (Is it just backlogged?)
                     │ No
                     ▼
        [ Interrogate the Database ] ── (Checking constraints & foreign keys)
                     │ 
                     ▼
          [ History / Audit Logs ] ── (Who changed this at 4:58 PM on a Friday?)
                     │
                     ▼
       [ Root Cause Found & Fixed via Python / SQL Automation ]


📊 GitHub Activity

☕ Let's Connect