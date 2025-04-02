# TA Scheduling Optimization Dashboard

## Overview
This project analyzes the Teaching Assistant (TA) scheduling system at the Kelley School of Business to identify inefficiencies and propose data-driven improvements. Using Power BI for visualization and Power Query for data transformation, I conducted an in-depth analysis of appointment data and provided actionable recommendations to optimize TA scheduling and enhance student support.

## Key Findings from Analysis
- **Tuesday Appointment Peaks**: Noticed a spike in available appointments on Tuesdays, which didn’t align with project deadlines (typically Sundays), suggesting a mismatch between TA availability and student demand.  
- **Evening Slot Popularity**: Found that late afternoon slots (2:30 PM to 4:00 PM) had the highest demand, indicating students prefer these times for assistance.  
- **High Cancellation Rates**: Identified that afternoon slots (e.g., 2:00 PM and 4:00 PM) had higher cancellation rates, often due to bookings made a week in advance, highlighting the need for more flexible booking options.  
- **TA Utilization Gaps**: Discovered that 70.64% of appointments remained open, with some TAs (e.g., Kevin Malone) having a surplus of unbooked slots, pointing to inefficiencies in resource allocation.

## Recommendations
- **Reschedule TA Availability**: Shift more TA hours to Thursday, Friday, and Saturday to better match student demand as they approach Sunday project deadlines.  
- **Limit Advance Bookings**: Introduce a rolling booking system to limit how far in advance students can book, ensuring slots are available closer to deadlines.  
- **Implement a Walk-In Model**: Add walk-in hours during high-demand times to reduce unused slots and improve flexibility.  
- **Use Feedback and Predictive Analytics**: Incorporate student feedback and predictive models to dynamically adjust TA schedules based on real-time demand.

## Technologies Used
- **Power Query**: For transforming raw data (e.g., converting Unix timestamps into readable formats).  
- **Power BI**: For creating an interactive dashboard to visualize scheduling patterns.  
- **Excel**: For initial data storage and analysis.

## Dataset
The dataset includes appointment details like Appointment ID, TA ID, Appointment Time (Unix timestamp), Status (open/booked), and Booking Time. Transformed data added columns such as Appointment Date, Time Segments, and Lead Days for deeper insights.

## Results
- Highlighted inefficiencies in the current scheduling system, such as a 70.64% open appointment rate.  
- Proposed strategies to improve TA utilization and better align schedules with student needs, enhancing academic support.

## How to Use
1. Clone the repository:  
   ```bash
   git clone <repository-url>
   ```
2. Open the Power BI file (TA_Scheduling_Dashboard.pbix) to explore the dashboard.
3. Review the Memo.pdf for a detailed analysis and recommendations.
4. Check the transformed dataset in Transformed_Data.xlsx.

## Future Improvements
1. Add real-time feedback mechanisms for students to share scheduling preferences.
2. Explore predictive analytics to forecast demand and optimize TA schedules dynamically.
