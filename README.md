# Naya Rishta
### *Service Design Analysis of Pakistan's Remarriage System*

> **"Everyone deserves a system that supports their second chance, not one that punishes them for it."**

**Version:** 2.0  
**Last Updated:** June 12, 2025  

---

## 🚀 Project Overview

**Naya Rishta** (New Relationship) is a service design research project analyzing Pakistan's complex remarriage system. Through comprehensive system mapping, we've created a detailed knowledge graph to identify pain points and improvement opportunities for people navigating divorce, widowhood, and remarriage processes.

---

## 📋 The Problem

Imagine finding someone to marry after a divorce or death of your spouse, but you can't marry them due to social and legal permission delays that drag on for months. This is the reality for millions in Pakistan.

### Current Journey: A Bureaucratic Nightmare
**The Path:** Person → Union Council → Family Court → Arbitration Council → NADRA → Municipal Office → Back to Union Council

### The Human Impact
1. **Divorced individuals** struggling through complex remarriage procedures
2. **Widows and widowers** facing bureaucratic barriers during vulnerable times
3. **Women in messy divorces** - Pakistan being a patriarchal society creates obstacles for women to get proper documentation
4. **Widows dealing with property disputes** - opposing families often block access to necessary documents
5. **Illiterate citizens** who can't navigate different bureaucratic hoops to complete documentation
6. **People avoiding documentation entirely** - some lie about marrying for the first time, risking court cases that could send the groom, bride, witnesses, and marriage registrar to jail or monetary fines

---

## 🗂️ Repository Contents

```
naya-rishta/
├── README.md                                                      # This file (v2.0)
├── Pakistan's Remarriage System: A Service Design Challenge.md   # Problem analysis & international examples
├── naya_rishta_definitions.md                                   # Knowledge graph entity definitions
├── systems.json                                                  # 12 government systems with complexity ratings
├── roles.json                                                    # 20 stakeholder roles and interactions
├── processes.json                                                # 5 processes with 12 detailed steps
├── departments.json                                              # 8 government departments
├── documents.json                                                # 20 required documents with relationships
└── stages.json                                                   # 8 user journey stages with emotional states
```

### What Each File Contains

**📖 Documentation Files**
- **Pakistan's Remarriage System: A Service Design Challenge.md** - Complete problem statement with international best practices from Estonia and Brazil
- **naya_rishta_definitions.md** - Explains the six entity types: Systems, Roles, Processes, Departments, Documents, and Stages

**📊 Knowledge Graph Data**
- **systems.json** - All 12 government workflows from Union Council divorce filing to NADRA marriage updates
- **roles.json** - All stakeholders from government officials to applicants, witnesses, and legal professionals
- **processes.json** - 5 main processes (divorce, widowhood, first marriage, remarriage, additional marriage) broken into 12 steps
- **departments.json** - 8 government organizations involved in the remarriage system
- **documents.json** - All forms, certificates, and legal papers required with input/output relationships
- **stages.json** - User experience phases showing emotional states from "Very Unhappy" to "Very Happy"

---

## 🎯 What We've Mapped

### Complete System Analysis
Our knowledge graph captures:

| Entity Type | Count | Description |
|-------------|-------|-------------|
| **Systems** | 12 | Government workflows with complexity and accessibility ratings |
| **Processes** | 5 | Legal pathways from divorce to remarriage |
| **Steps** | 12 | Detailed breakdown of process requirements |
| **Roles** | 20 | All people involved in the remarriage system |
| **Departments** | 8 | Government organizations operating the systems |
| **Documents** | 20 | Forms, certificates, and paperwork required |
| **Stages** | 8 | User journey phases with emotional states |

### Key Insights from the Data

**System Complexity:**
- Most complex: Family Court Divorce (Level 5) - requires lawyer, multiple hearings, legal documentation
- Simplest: Union Council Marriage Registration (Level 2) - straightforward when documents are complete

**Processing Times:**
- Fastest: Hospital Death Certificate (1-3 days)
- Slowest: Family Court Divorce (up to 3 months)
- Most Variable: Property Inheritance Documentation (up to 3 months, can be contentious)

**System Types:**
- **Manual Systems:** Union Council processes, Family Courts, Arbitration Council
- **Hybrid Systems:** NADRA processes (online application + center verification)

### Process Complexity Ranking
1. **First Marriage Process** - Streamlined, 1-3 days when prepared
2. **Remarriage Process** - Requires completion of prior legal processes
3. **Widowhood Process** - 2-4 weeks for straightforward cases
4. **Additional Marriage Process** - Most complex due to consent requirements
5. **Divorce Process** - 6+ months minimum for simple cases

---

## 🌍 International Best Practices

### 🇪🇪 Estonia's Digital Solution
Estonia achieved 100% Digital Government Service:
1. One partner fills out the application through the population registry portal, which is pre-filled with existing data
2. Mandatory 30-day cooling-off reflection period, but built into the digital system
3. Only one physical meeting with an official is required to finalize the divorce
4. Digital tools for dividing marital property and guidance for custody agreements included in the system

### 🇧🇷 Brazil's One-Office Solution
Brazil allows "pure and simple divorce" registration directly at Civil Registry Offices (Cartório) for consensual cases:
1. One office where consensual divorces can be processed directly at civil registry
2. If amicable and no children involved, can be done without court proceedings
3. Some registry offices offer 24-hour civil registry services

---

## 📊 System Improvements Identified

Based on our analysis, the following improvements have been identified:

1. **Better system awareness** - Clear, accessible information about the process and requirements
2. **Enhanced NADRA services** - Expand their existing SMS service (send NIC to get details) to include marital status verification and spouse information
3. **Early digital notification** - Simple system to register the start of divorce proceedings OR death certificate process, automatically updating all relevant departments when someone becomes divorced or widowed
4. **One-stop service center** - Streamlined process for:
   - Consensual divorce cases without property or custody disputes (like Brazil's model)
   - Death certificate registration to officially declare widow/widower status
   - Both leading directly to remarriage eligibility without multiple office visits

---

## 🔍 Knowledge Graph Structure

### Entity Definitions

**Systems:** Specific workflows or procedures that citizens must complete to achieve a particular outcome in the remarriage process.

**Roles:** Individual people or positions that participate in or are affected by the remarriage process.

**Processes:** High-level legal/administrative pathways that group multiple related systems together to achieve a major lifecycle change.

**Departments:** Government organizations or institutional units responsible for operating systems and implementing processes.

**Documents:** Physical or digital paperwork, certificates, forms, and records required as inputs or generated as outputs by systems.

**Stages:** User experience phases that represent where applicants are in their emotional and practical journey through the remarriage process.

### Data Structure Features
- **UUID-based unique identifiers** for all entities
- **Complexity ratings** (1-5 scale) for each system
- **Accessibility levels** for different user types
- **Time estimates** (minimum and average processing times)
- **Relationship mappings** between all entities
- **Emotional state tracking** through user journey stages

---

## 🤝 Call to Action

Seeking collaborators to research this problem and develop implementable solutions for government.

Whether you're in service design, tech, policy, or just care about impact - let's connect.

Because everyone deserves a system that supports their second chance, not one that punishes them for it.

---

*This research provides the foundation for designing integrated solutions that could reduce Pakistan's 6+ month remarriage journey to weeks while supporting millions seeking their second chance at happiness.*

**Tags:** #ServiceDesign #DigitalTransformation #Pakistan #Government #UXResearch #SocialImpact #PublicService
