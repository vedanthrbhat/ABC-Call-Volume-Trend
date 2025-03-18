# ABC-Call-Volume-Trend

---

# **Customer Experience (CX) Analytics and Call Center Optimization**  

## **Tech Stack**  
**Tool:** Excel  

## **About**  
The dataset provided pertains to the **inbound calling operations** of an insurance company, ABC. The project aims to analyze **call volume trends, call duration, and manpower requirements** to optimize **customer experience (CX) and minimize abandoned calls**.  

One key challenge is the high **abandon rate (30%)**, which leads to poor customer satisfaction. The objective is to **analyze patterns in call volume and duration** to recommend the **optimal number of agents required** to bring the abandon rate down to **10%** during peak hours and extend coverage to **night shifts**.  

## **Description**  
The project involves the following steps:  
- **Data Cleaning**: Handling missing values, removing duplicates, and formatting time-based data.  
- **Data Analysis**: Exploring call volume, average call duration, and agent efficiency.  
- **Manpower Optimization**: Estimating the required number of agents to meet demand.  
- **Report & Data Storytelling**: Visualizing insights to support business decision-making.  

---

## **Data Analytics Tasks**  

### **A) Average Call Duration Analysis**  
**Task:** Determine the **average duration of all incoming calls** for each time bucket.  
- Calculate the **mean call duration** in each hourly bucket (e.g., 9-10 AM, 10-11 AM, etc.).  
- Identify peak hours where **calls tend to last longer**, indicating potential agent workload.  

**Hint:** Use **AVERAGEIFS** in Excel to compute call duration per time bucket.  

---

### **B) Call Volume Analysis**  
**Task:** Visualize the **total number of calls received** across different time buckets.  
- Create a **bar chart** or **line graph** displaying the number of calls received **hourly**.  
- Analyze which hours see the highest and lowest call volume.  
- Identify any **trends** such as peak hours or unexpected fluctuations.  

**Hint:** Use **Pivot Tables** to count calls per time bucket and plot a graph.  

---

### **C) Peak-Hour Manpower Planning**  
**Task:** Reduce the **abandon rate from 30% to 10%** by adjusting manpower allocation.  
- Calculate the **minimum number of agents** required per time bucket to ensure at least **90% of calls are answered**.  
- Consider **agent efficiency**, assuming each agent handles an average of **X calls per hour**.  
- Compare **current vs. optimized** agent allocation.  

**Hint:**  
- Use **(Total Calls × 90%) / Calls Handled Per Agent** to determine staffing needs.  
- Use **conditional formatting** to highlight time slots with the highest demand.  

---

### **D) Night Shift Manpower Planning**  
**Task:** Extend customer support **overnight** (9 PM – 9 AM) while keeping the abandon rate **≤10%**.  
- Assume that for every **100 calls** received between 9 AM – 9 PM, there are **30 additional calls** at night.  
- Distribute the **30 night-time calls** into predefined hourly buckets.  
- Calculate the **required number of agents** for night shifts while maintaining a **10% abandon rate**.  

**Hint:**  
- Use **(Total Night Calls × 90%) / Calls Handled Per Agent** for night shift planning.  
- Consider whether **part-time agents** or **AI-driven solutions (IVR, chatbots, etc.)** could optimize efficiency.  

---

## **Interactive Dashboard Development**  

### **1. Call Volume Distribution Over Time**  
- **Visualization:** Line chart displaying call volume trends.  
- **Insight:** Identify peak hours and potential staffing gaps.  

### **2. Call Duration Trends by Time Bucket**  
- **Visualization:** Scatter plot showing call duration vs. time bucket.  
- **Insight:** Longer calls may indicate complex queries, requiring specialized agents.  

### **3. Agent Allocation Plan**  
- **Visualization:** Clustered column chart comparing **current vs. optimized** agent allocation.  
- **Insight:** Highlights efficiency gains by reducing wait times.  

### **4. Night Shift Call Handling Efficiency**  
- **Visualization:** Stacked bar chart comparing **day vs. night call volume** and agent availability.  
- **Insight:** Helps justify resource allocation for night shifts.  

---

## **Insights On**  
- **Call Volume Trends:** Peak hours require additional agent support to reduce abandon rates.  
- **Call Duration Patterns:** Extended calls suggest a need for better training or IVR support.  
- **Optimized Staffing Needs:** Redistribution of agents can reduce **abandoned calls from 30% to 10%**.  
- **Night Shift Strategy:** Ensuring **after-hours support** improves customer satisfaction and retention.  

---

## **More Information**  
This project was completed as part of a [Trainity](https://trainity.in/) data analytics course. For further insights, visit my [profile](https://trainity.space/recruitersProfile/public/66e52eb6fd616408e13b683f). 📞💡  

---
