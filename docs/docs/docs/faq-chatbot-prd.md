# Product Requirements Document (PRD)  
## Project: FAQ Chatbot MVP (Nonprofit Engagement App)

---

## 1. Product Overview
We are building an **FAQ Chatbot MVP** inside Glide to help nonprofits , specifically MASK, education advocacy organization. Answer community questions instantly.  
- **Why**: Parents miss updates, staff get overwhelmed repeating the same info, communities feel disconnected.  
- **Goal**: Deliver a simple, no-code chatbot that pulls answers from a structured FAQ list and provides a friendly, mobile-first interface.  

---

## 2. Objectives & Success Metrics
- ✅ Reduce staff time spent on repetitive questions.  
- ✅ Improve parent/volunteer satisfaction with quick, clear answers.  
- ✅ Track unanswered questions for future FAQ updates.  

**KPIs**:  
- % of questions answered by chatbot.  
- # of unique users interacting with the bot.  
- # of repeated staff inquiries reduced.  

---

## 3. Target Users & Use Cases
**Primary users (M.A.S.K. pilot):**
- Parent: “When is the next M.A.S.K. board meeting?”  
- Parent: “Who is the school principal and how do I contact them?”  
- Parent: “Where is the school located and what’s the phone number?”  
- Parent: “What events are coming up?”  

---

## 4. Core Requirements (Categories)
**Functional**
- FAQ database seeded with categories:
  - **Board Meetings** → Dates, times, agendas.  
  - **School Info** → Admin names, emails, phone, fax, address.  
  - **Events** → Parent nights, workshops, community briefings.  
  - **Programs** → M.A.S.K. advocacy initiatives.  


## 5. Data & AI Considerations
- **Data Source:** CSV/Google Sheet maintained by nonprofit staff.  
- **MVP:** Simple keyword lookup (Glide logic).  
- **Future:** Replace with Retrieval-Augmented Generation (RAG) using OpenAI for more natural language flexibility.  

---

## 6. Dependencies & Risks
- Clean, updated FAQ data is required.  
- Glide limitations: may require future migration if features are too advanced.  
- Staff adoption depends on ease of updating the FAQ sheet.  

---

## 7. Scalability Notes
- **Phase 1:** Single nonprofit with one FAQ database.  
- **Phase 2:** Multi-tenant (each org can upload their own FAQ sheet).  
- **Phase 3:** Add AI-powered natural language search (OpenAI/Claude + RAG).  
- **Phase 4:** Extend to SMS/email integration for FAQs.  

---

## 8. Timeline / Next Steps
- Week 1: Draft PRD ✅  
- Week 2: Build prototype in Glide with Google Sheet backend.  
- Week 3: Test with one nonprofit group (parents/volunteers).  
- Week 4: Collect feedback + refine.  

---

## 9. Deliverables
- `/docs/faq-chatbot-prd.md` (this doc).  
- Glide app prototype link.  
- Demo video or screenshots.  
- Case study documenting impact.



