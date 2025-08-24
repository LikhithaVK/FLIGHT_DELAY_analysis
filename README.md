#Flight Delay Analysis

#📌 Project Overview

This project analyzes flight performance using a synthetic dataset of airline operations. It focuses on departure delays, arrival delays, and cancellations, with breakdowns by airline, time of day, and reason for disruption.

The Excel file (flight_analysis.xlsx) includes raw flight data, summary tables, and a dashboard structure for visualization.

📂 File Structure

synthetic_flight_delays (2)
Raw dataset with detailed flight-level data.

FlightDate → Date of the flight

Airline → Airline name

FlightNumber → Flight identifier

Origin / Destination → Airports

ScheduledDeparture → Planned departure time

TimeSlot → Part of day (Morning, Afternoon, Evening, Night)

DepartureDelay / ArrivalDelay → Delay in minutes (can be negative if early)

Cancelled → Binary flag (1 = cancelled, 0 = operated)

CancellationReason → Cause of cancellation (e.g., Weather, Carrier, Security)

DelayCause → Cause of delay (e.g., Late Aircraft, NAS, Weather)

Distance → Flight distance in miles

DayOfWeek → Day of week (1 = Monday, …, 7 = Sunday)

sheetdesign
Aggregated performance summary:

Average departure delay per airline

Average arrival delay per airline

Cancellation counts per airline

dashboard
Placeholder for visual analytics (charts, KPIs, etc.).

🚀 How to Use

Open the Excel file in Excel / Google Sheets / Power BI / Tableau.

Use the synthetic_flight_delays (2) sheet for raw data analysis.

Explore sheetdesign for airline-level summaries.

Build custom dashboards in the dashboard sheet or external BI tools.

📊 Possible Analyses

Compare airlines by average departure/arrival delays.

Identify peak delay periods (by TimeSlot or DayOfWeek).

Study most common causes of delays and cancellations.

Correlate flight distance with delays.

