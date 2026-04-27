
Behind every messy dataset lies a story waiting to be told! 📊🏥

I recently wrapped up a comprehensive Healthcare Data Analysis project using SQL. This wasn’t just about writing queries; it was a deep dive into solving real-world operational and financial challenges in a clinical setting.

Starting with a raw, chaotic database of Electronic Health Records (EHR) and billing data, here is the journey of how I turned the noise into business strategy:

1️⃣ The Cleanup Phase: Real-world data is messy. I used CTEs and clever Self-Joins to impute missing patient data and standardized formatting across the board. Because "Garbage In = Garbage Out."
2️⃣ Revenue vs. Bottlenecks: Through complex aggregations and multi-table JOINs, I mapped the patient flow. We discovered the ER was our biggest operational bottleneck, while Orthopedics drove the highest average revenue per visit.
3️⃣ The "Aha!" Moment (Anomaly Detection): While analyzing our "Frequent Flyers," I spotted a bizarre pattern—patients diagnosed with a medically impossible combination of acute and chronic diseases simultaneously. This led to the discovery of IT test/dummy accounts polluting the database, which were promptly excluded to save our reporting accuracy!
4️⃣ The Ultimate KPI (Readmission Rate): The biggest challenge was calculating how many patients returned within 30 days. By utilizing Advanced SQL Window Functions (LAG()), I calculated a concerning 25% readmission rate, providing a clear signal to management to revamp discharge protocols.

💡 The Takeaway: SQL is a powerful tool, but the real value of a Data Analyst lies in Business Acumen—connecting the dots between code, anomalies, and actionable business decisions.

Next step? Bringing these insights to life in a Dashboard! 📈



Skills: SQL · MySQL · CTEs · Window Functions · Data Cleaning · EDA · Problem Solving
