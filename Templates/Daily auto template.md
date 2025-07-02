<%*
const fileDate = tp.date.now("YYYY-MM-DD");
const dayOfWeek = tp.date.now("dddd");
const yesterday = tp.date.now("YYYY-MM-DD", -1);

tR += `---
tags: journal, PB, daily
date: ${fileDate}
---

# 📅 ${fileDate} (${dayOfWeek}) – PB Journal Entry

## 🧠 Energy & Mental Clarity
- **Sleep Quality (1–10):**  
- **Morning Energy (1–10):**  
- **Focus During Work/Study:**  
- **Did I Fall Asleep Unintentionally?:**  
- **Brain Fog Moments / Triggers:**

## 💊 Methadone Taper
- **Daily Dose (mg):**  
- **Physical Symptoms:**  
- **Mental/Emotional Symptoms:**  
- **Stable at This Level? (Y/N):**  
- *(Compare to yesterday’s log: ${yesterday})*

## 🧘 Spiritual Work
- **Did I Meditate/Pray?:**  
- **Duration (min):**  
- **Insight or Reflection:**

## 🏋️ Physical Routine
- **Exercise (Type + Duration):**  
- **Diet:**  
  - Sugar Intake: \`Low/Moderate/High\`  
  - Carbs: \`< 100g?\`  
- **Weight (optional):**  
- **Hernia/Shoulder Notes:**

## 📈 Productivity & Focus
- **Today’s Goals:**  
- **Completed:**  
- **Distractions / Triggers:**  
- **Improvement Notes:**

## 💰 Financial Moves
- **Income Activity (Job Apps, DAS, etc.):**  
- **Spending Summary:**  
- **Saved/Budgeted for Move/Teeth?:**

## 📓 Notes & Wins
- **Highlight of the Day:**  
- **Setback (If Any) & Lesson:**  
- **Gratitude:**
`
%>
