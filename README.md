
---

## 📁 Folder & File Descriptions

### **1. Analytics/**
Contains analytical SQL queries such as:
- Senior-most employee  
- Top 3 invoices  
- Revenue by city  
- Best customers  
- Rock music listeners  
- Popular genres per country  
- Artist, genre, and customer spending analytics  
- Tracks above average duration  

These scripts are used for generating insights and reports.

---

### **2. Source code/**
Contains all SQL required to:
- Create database  
- Create tables with primary & foreign keys  
- Add constraints  
- Setup relationships  
- Insert Employee sample data  
- Prepare database structure before loading CSVs  

This is the **core schema + setup** for the music store system.

---

### **3. music_store_management_system_project.sql**
This is the **main master SQL file** that includes:
- Database creation  
- All table creation queries  
- Integrity constraints  
- Employee data insertion  
- CSV loading code using `LOAD DATA LOCAL INFILE`  
- Data cleaning using `NULLIF`  
- All analytics queries  

Running this file will build the entire project end-to-end.

---

## 🛠️ Features

- Fully normalized database schema  
- Correct PK–FK relationships  
- ON DELETE / ON UPDATE cascading rules  
- Self-referencing employee hierarchy  
- Junction table for playlists  
- CSV data loading support  
- Advanced analytical SQL queries  

---

## 💡 SQL Insights Included

- Senior-most employee  
- Countries with most invoices  
- Highest-value invoices  
- Best performing city (revenue)  
- Best customer by spending  
- Rock genre listeners  
- Top Rock artists  
- Longest tracks (above average)  
- Customer spending per artist  
- Most popular genre per country  
- Top customer in each country  

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone <your-repo-link>
