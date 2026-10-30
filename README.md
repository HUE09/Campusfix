# CampusFix 🛠️

**Lion Code Challenge 2026** — Penn State Abington  
**Team Members:** Hue Pham, Derek Clementson, Samiha Aladin  

- **Live Web App:** https://hue09.github.io/Campusfix  
- **GitHub Repository:** https://github.com/hue09/Campusfix  
- **GitHub App:** https://github.com/apps/hpscampusfix  

---

## 📌 Project Overview
CampusFix is a real-time facility maintenance and incident reporting application engineered for the Penn State Abington campus community. It streamlines issue logging, prevents duplicate work orders, and empowers students, faculty, and staff to maintain a safer campus environment.

## 🚀 Key Features
- **Structured Issue Logging:** Categorize campus issues (Restroom, Electrical, HVAC, Safety) with severity ratings and location tagging.
- **Client-Side Photo Capture:** Live image preview leveraging FileReader API for visual evidence.
- **Real-Time Duplicate Detection:** Heuristic text matching to alert users if an issue has already been reported nearby.
- **Community Upvoting:** Crowd-sourced prioritization for urgent repairs.
- **3-Stage Lifecycle Tracking:** Reported -> In Progress -> Resolved.
- **Staff Resolution Portal:** PIN-gated administrative panel (STAFF2026, FACILITIES123, ADMIN01) to update tickets and mark repairs complete.
- **Offline / Local Persistence:** localStorage synchronization to retain tickets across sessions.
