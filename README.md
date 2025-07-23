# clinical-db-sqlserver-bmig

# 🗃️ Clinical Database Design (Learning Project – BMIG 60103)

> **Note:** This was a learning exercise to practice ER modeling, normalization, and T-SQL in Microsoft SQL Server. The schema, data, and queries are simplified and not production-ready. I currently only have the final PDF and one SQL script; additional scripts will be added if/when I locate them.

---

## 📄 Deliverable
- `report/BMIG_Term_Project_Nuzhat_Faizah.pdf` — full write-up with ERD, schema, sample queries, trigger, and normalization discussion.

---

## 🎯 What This Project Does
- Designs a small healthcare database (patients, providers, visits, billing, labs, etc.)
- Builds an ERD and translates it into a normalized relational schema (up to 3NF)
- Demonstrates data loading with dummy records, analytical SQL queries, and a trigger
- Briefly explores when/why you might denormalize

---

## 🛠 Stack / Tools
- **DBMS:** Microsoft SQL Server / SSMS  
- **Language:** T-SQL (DDL, DML, queries, trigger)  
- **Modeling:** ER diagram built in **Lucidchart** (exported as PNG/PDF)

---

## 🎓 Learning Focus & Caveats
- Goal = **skill-building**, not a production system  
- Dummy data and simplified rules = intentional shortcuts  
- No SQL scripts in the repo yet (lost/archived); will add if found  
- Normalization prioritized; denormalization only explored conceptually

- ## 🧼 Normalization & Denormalization
**Normalization:**  
- Attributes are atomic (e.g., split full names).  
- Non-key attributes fully depend on the primary key.  
- Redundancy minimized across tables.

**Denormalization:**  
- Demonstrated conceptually—denormalize only when performance justifies added redundancy.

---[BMIG Term Project_Nuzhat Faizah.pdf](https://github.com/user-attachments/files/21379482/BMIG.Term.Project_Nuzhat.Faizah.pdf)
