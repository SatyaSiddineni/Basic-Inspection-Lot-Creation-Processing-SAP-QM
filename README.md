# Basic Inspection Lot Creation & Processing (SAP QM)

## 📌 Overview
This project demonstrates the complete end-to-end Quality Management process in SAP S/4HANA for creating and processing an **Inspection Lot**.  
It includes master data setup, inspection plan preparation, Goods Receipt, results recording, usage decision, and final stock posting.

This is a beginner-friendly SAP QM project and serves as the foundation for advanced QM scenarios.

---

## 🎯 Objectives
- Configure and activate relevant QM settings for a material
- Create Master Inspection Characteristics (MICs)
- Build an inspection plan with assigned characteristics
- Trigger an inspection lot via Goods Receipt (GR)
- Perform results recording (RR)
- Make a Usage Decision (UD)
- Move stock to unrestricted / blocked based on quality decision

---

## 🧱 Project Scope
### **1. Master Data**
- Material Master (QM View)
- Inspection Types (01 & 04)
- MICs (Quantitative & Qualitative)
- Sampling Procedure (optional)
- Inspection Plan / Task List

### **2. Transactions Covered**
- **MM01** – Material Creation  
- **QS21** – MIC Creation  
- **QP01** – Inspection Plan  
- **ME21N/MIGO** – PO & Goods Receipt  
- **QA32/QE51N** – Results Recording  
- **QA11** – Usage Decision  

