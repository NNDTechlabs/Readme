
# 🌐 Ergon Process Review – Full Detailed Meeting Summary  
**Date:** 27 Nov 2025  
**Duration:** 1 hr 23 mins  

---

# 📘 1. Program Overview  
Argon is undergoing a **4.5–5 year SAP S/4HANA Greenfield transformation**, covering multiple businesses across the US and international locations. The program is divided into **five major phases**.

---

# 📊 2. Visual Roadmap Diagram  

```
                          ┌──────────────────────────────────────┐
                          │      ARGON S/4HANA PROGRAM           │
                          │   4.5–5 YEAR TRANSFORMATION ROADMAP  │
                          └──────────────────────────────────────┘
                                           │
                                           ▼

┌────────────────────────────────────────────────────────────────────────────┐
│                             PHASE 1 – ESS                                  │
│                Specialty Oils & Lubes (Global Rollout)                     │
│--------------------------------------------------------------------------- │
│ Scope: Core S/4, BTP, CPI, MDG, OpenText, HighRadius, Atlas, EHS-lite      │
│ Countries: US, Mexico, Singapore, Indonesia, Belgium                       │
│ Status: UAT → Go-Live Target: Feb 2026                                     │
└────────────────────────────────────────────────────────────────────────────┘
                                           │
                                           ▼

                    ┌────────────────────────────┐
                    │   PARALLEL PHASE EXECUTION │
                    │ (Phase 2, Phase 3, Phase 4)│
                    └────────────────────────────┘
                                           │
                                           ▼

┌────────────────────────────────────────────────────────────────────────────┐
│                             PHASE 2 – FINANCE HEAVY                        │
│ ERI, EWB Refineries, Argon Inc (Finance), EMIS, EMMT (Marine & Lubes)      │
│ Target Go-Live: Oct–Dec 2026                                                │
└────────────────────────────────────────────────────────────────────────────┘
                                           │
                                           ▼

┌────────────────────────────────────────────────────────────────────────────┐
│                          PHASE 3 – TRANSPORTATION                          │
│     Argon Trucking, Back Energy, EOP/EML — Midstream + TM + Fleet Mgmt     │
│ Target Go-Live: Feb–Apr 2027                                                │
└────────────────────────────────────────────────────────────────────────────┘
                                           │
                                           ▼

┌────────────────────────────────────────────────────────────────────────────┐
│                       PHASE 4 – PCR (Asphalt & Coatings)                   │
│        60–100 Terminals, largest scope, 2-wave rollout                     │
│ Target Go-Live: Late 2027 – 2028                                            │
└────────────────────────────────────────────────────────────────────────────┘
                                           │
                                           ▼

┌────────────────────────────────────────────────────────────────────────────┐
│                      PHASE 5 – KRAFCO (Machinery Mfg.)                     │
│ Variant Configuration, Manufacturing, Service Mgmt                          │
│ Target Go-Live: 2028                                                        │
└────────────────────────────────────────────────────────────────────────────┘
                                           │
                                           ▼

                   ┌─────────────────────────────────────────┐
                   │      END STATE – FULL S/4 LANDSCAPE     │
                   │   All Argon Businesses Unified on S/4   │
                   └─────────────────────────────────────────┘
```

---

# 🏭 3. Refineries, Terminals, & Industrial Images

### **Refinery (Large-scale crude processing plant)**
![Refinery](https://media.sciencephoto.com/c0/40/99/57/c0409957-800px-wm.jpg)

![Refinery](https://www.sterlingtt.com/wp-content/uploads/2023/02/oil-refinery.jpg)

### **Oil Terminal (Storage & Distribution Facility)**
![Terminal](https://www.honiron.com/wp-content/uploads/2017/05/storagetanks.jpg)

### **Large Storage Tanks**
![Storage Tanks](https://images.openai.com/static-rsc-1/DjEozHpmu2zDhltqCc09KjPp5ITIeYKI1z_0jmRL8MQ8pf-XwjC2km5d8EPcw6nBSvLL_mV7zKLg_E_E2rZSuVz8iRQ5YMSmX-0Je6VsSCoWjcGBn6y3Z0hAiO4MmWIlR-YhHA1R52n0bN577ablnw)
![Storage Tanks](https://www.hima.com/sharepoint-sync/Images/Industries%20%26%20Solutions/Solutions/Tanklager/23759/image-thumb__23759__heroimage/Tankfarm_Hero%20Image.371f84a3.jpg)

### **Truck Loading Bay (Terminal Operations)**
![Truck Loading](https://www.isoilmeter.it/media/24rkvew4/truck-loading-sigemi.jpg?anchor=center&format=webp&height=450&mode=crop&rnd=133250964516570000&width=800)
![Truck Loading](https://saferack.com/wp-content/uploads/2022/10/truck-loading-maxrack.jpg)

---

# 📂 4. Workstreams Covered  
- R2R – Finance  
- P2C – Prospect to Cash  
- P2S – Plan to Ship  
- TM + Fleet Management  
- B2R – Plant Maintenance  
- D2D – Project Systems/EPPM  
- EHS  
- Data Migration  
- MDG  
- Integrations (CPI/BTP)  
- Salesforce, Atlas, HighRadius  
- OpenText (VIM/XECM)  
- DNA (Data Analytics)  
- Basis, Security, Fiori, ABAP  

---

# 🧩 5. Tools & Methodology  
### **Requirements & Documents**
- RTM (L1–L4 Processes)  
- RICEF-WA (Estimations)  
- BPD  
- FTD (Functional + Technical Combined)  
- COA Configuration Docs  

### **Testing & Tracking**
- Cloud ALM – Processes + SIT  
- QTest – UAT  
- JIRA – Build + Defects  
- Power BI – Dashboards  

### **Process Flow**
Signavio → Cloud ALM → JIRA → Power BI  

---

# 🔄 6. Key Business Processes Explained

## **Sales & Distribution Processes**
- Direct Terminal Sales  
- Drop Shipments  
  - Cross-company (CROSS Vendor)  
  - Standard vendor drop ship  
- Intercompany Sales  
- Consignments  
- Returns  
- Cancel & Rebill  

## **Procurement & Inventory**
- Refinery → Terminal transfers  
- 3rd Party Direct Procurement  
- STO (Intra & Intercompany)  
- Subcontracting (Vendor inside terminal)  
- Customs: Bonded/Non-bonded  
- Inventory Adjustments (CORPPI)  

## **Manufacturing**
- Tank Blending (Process Orders)  

## **Transportation & Freight**
- Truck / Rail / Ship / Barge shipments  
- Freight PO automation  
- TM + Fleet  

## **Finance**
- AP / AR  
  - US: HighRadius  
  - International: S/4  
- Treasury  
- Asset Accounting  
- Period Close  

---

# 🧠 7. Expectations from Offshore  
- Update & own FTD/Technical specs  
- Cross-functional thinking across P2C–P2S–P2P–Finance  
- No silo work  
- Better communication across time zones  
- More consistent documentation  
- Follow change control processes  

---

# ❓ 8. Q&A Highlights  

### **Refinery vs Terminal**
- **Refinery** = full crude→product manufacturing  
- **Terminal** = storage, blending, loading, distribution  

### **Custom Fiori Apps**
- 70% custom  
- Heavy Z-tables + complex backend logic  

### **Third-Party Systems**
- Salesforce  
- Atlas (Forecasting)  
- HighRadius (AR)  
- OpenText VIM/XECM  
- CORPPI (Inventory reconciliation)  

---

# 📥 9. Action Items  
- Offshore to review Signavio + ALM  
- Update specs  
- Setup recurring knowledge sessions  
- Upload team structure to SharePoint  
- Mital to share Argon Business PPT  

---

# ✔ Final Notes  
This document consolidates **all discussions** from the meeting, including:  
✔ timelines  
✔ processes  
✔ tools  
✔ team structures  
✔ expectations  
✔ architecture  
✔ business operations context (refinery, terminal, logistics)

