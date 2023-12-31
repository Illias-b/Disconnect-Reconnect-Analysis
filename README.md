## Disconnect-Reconnect Dashboard

![Dashboard Visual](link-to-dashboard-snapshot.jpg)
*Figure 1: Snapshot of the Disconnect-Reconnect Dashboard*

### GOAL
The goal of this dashboard is to track "disconnect-reconnect" (DCRC) events where customers add or remove lines in the same transaction. This is crucial for understanding commissions and net additions, and is tracked at both the parent BAN level and company name level. The dashboard accounts for the 30-day notice period for disconnections to provide accurate insights.

### RESULT
The dashboard effectively captures DCRC events, providing valuable insights for commission calculations and understanding net additions. This has significantly improved decision-making related to customer account management in the B2B sector.

### APPROACH AND TOOLS
- **SQL Query for Data Processing**: Developed a complex SQL query to identify and analyze DCRC events. This involved:
   - Parsing acquisition and disconnection data to identify DCRC events.
   - Calculating the days between disconnections and subsequent acquisitions.
- **Tableau Dashboard Visualization**: 
   - An interactive Tableau dashboard was created to visualize the frequency and details of DCRC events, providing a clear view of these occurrences over time.
   - ![Tableau Dashboard Screenshot](link-to-tableau-dashboard.jpg)
   - *Figure 2: Snapshot of the Tableau Dashboard*
- **SQL Code Screenshot**: 
   - ![SQL Logic Screenshot](link-to-sql-code-screenshot.jpg)
   - *Figure 3: Snapshot of SQL Code for DCRC Logic*
