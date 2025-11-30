# Meeting Agenda / Minutes

**Date/Time:** 04-Nov-2025, 10:30 PM – 11:00 PM  
**Location:** Discord  
**Attendees:** Kotha (K), Ruponti (RM), Sadia (SA), Muttakin (MM)  
**Chair:** Muttakin (MM)  
**Notetaker:** Kotha (K)  

---

## Discussions

- **Ruponti (RM):** Presented and discussed the Entity-Component-Base (ECB) and Model-View-Controller (MVC) patterns, highlighting their use cases, strengths, and limitations.  
- **Sadia (SA):** Presented on Model-View-Template (MVT), particularly its use in Django, and the benefits of Command Query Responsibility Segregation (CQRS) for complex domain models.  
- **Muttakin (MM):** Discussed the Model-View-Intent (MVI) pattern, emphasizing its unidirectional data flow and state management.  
- **Kotha (K):** Presented the Model-View-ViewModel (MVVM) pattern, focusing on its separation of concerns and testability through the ViewModel layer.  

---

## Decisions

- **Architecture Pattern:** After comparing the presented models, the team decided to adopt **MVVM (Model-View-ViewModel)** as the core architecture pattern for the project due to its strong separation of UI logic from business logic, which aids in maintenance and testing.

---

## Actions

| Action No. | Description | Allocated Team Members | Deadline |
|------------|-------------|----------------------|----------|
| 1 | Prepare a brief (1-page) guide on implementing MVVM for the team's specific stack. | Sadia (S) | 07/11/25 |
| 2 | Apply the new MVVM architecture to all components developed for Week 6B tasks. | K, RM, SA, MM | 10/11/25 |
| 3 | Review and provide feedback on the MVVM implementation in Week 6B tasks. | K, RM, SA, MM | 12/11/25 |
