# Product Requirements Document (PRD)  
## Project: FAQ Chatbot MVP (Nonprofit Engagement App)

---

## 1. Product Overview
We are building an **FAQ Chatbot MVP** inside Glide to help nonprofits answer community questions instantly.  
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
**Primary users:**  
- Parents: “When is back-to-school night?”  
- Volunteers: “How do I sign up to help?”  
- Staff: “How do we update the FAQs easily?”  

**Use case flow (Glide):**  
1. User opens the app → taps “Ask a Question.”  
2. User enters text → Glide searches FAQ database (Google Sheet).  
3. If match → chatbot returns the answer.  
4. If no match → response = “We’ll get back to you” + logs unanswered question.  

---

## 4. Core Requirements
**Functional**  
- FAQ database stored in Google Sheets (Q&A pairs).  
- Glide app interface with “Ask a Question” form.  
- Automated lookup → return matching answer.  
- Unanswered queries logged to a sheet.  

**Non-Functional**  
- Must be mobile-friendly.  
- Responses under 3 seconds.  
- Easy for staff to update the FAQ list.  

---

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

