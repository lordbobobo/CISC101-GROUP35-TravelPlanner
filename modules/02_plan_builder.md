## **Module 2 — Plan Builder (Revised)**

### Candidate Activities
Each activity is represented with a clear schema for comparability:

- **Type:** Attraction, restaurant, park, museum, market, event  
- **Name:** Human-readable title  
- **Area:** Neighborhood/district; nearest transit stop  
- **Duration:** Estimated time window (e.g., 60–90 min)  
- **Hours:** Typical open hours; slot compatibility  
- **Cost band:** $, $$, $$$ (aligned with local ranges and user budget style)  
- **Distance/transit:** Walk minutes or transit time from prior point  
- **Weather tag:** Indoor, outdoor, mixed  
- **Accessibility:** Step-free, seating, elevator availability  
- **Booking:** Recommended/required  

---

### Day Plan Construction Loop
For each day:

1. **Morning → near lodging**  
   - Select an activity within walking distance (≤20 minutes).  
   - Prioritize indoor/mixed options if forecast is rainy/cold.  

2. **Midday → nearby attraction**  
   - Choose an activity within short transit (≤15 minutes) of the morning stop.  
   - Ensure it differs in theme from the morning activity (e.g., food vs. culture).  

3. **Afternoon → different theme**  
   - Select an activity that shifts category (e.g., nature after food/culture).  
   - Allow wider transit (≤30 minutes) if needed.  
   - Auto-swap to indoor/mixed if weather is poor.  

4. **Evening → restaurant or optional event**  
   - Pick a dining option or cultural event.  
   - Respect dietary restrictions and budget.  
   - Provide one alternate indoor option if the primary is outdoor-sensitive.  

---

### Theme Diversification Rule
- Within a single day, avoid repeating the same activity type (e.g., two museums).  
- Categories include: food, culture, nature, viewpoint, market, hands-on.  
- Each slot must differ from the previous one unless user explicitly prefers repetition.  

---

### Day Diversity Across Trip
- Track marquee categories (e.g., temples, major museums, iconic markets).  
- Avoid repeating the same marquee type across consecutive days unless requested.  
- Encourage variety across the trip (e.g., one day focused on culture, another on nature/food).  

---

### Weather Adaptation
- Tag each activity as indoor, outdoor, or mixed.  
- If forecast indicates rain/cold, auto-swap outdoor picks with indoor/mixed alternatives.  
- Always provide at least one indoor backup per day.  
- On clear days, include at least one outdoor option for balance.  

---

### Fallbacks
- If no eligible activity is found for a slot:  
  - Insert rest or scenic walk.  
  - Widen search radius incrementally.  
  - Adjust duration to fit pacing.  
- If hours unknown, mark “verify” and provide alternate.  

---
