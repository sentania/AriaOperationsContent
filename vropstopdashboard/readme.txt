===============
OVERVIEW
===============
The vROpsTOP dashboard is meant to be like using ESXTOP to look at host and VM stats. This is not a 1:1 mapping but more of a similar group of metrics. One advantage here is having a list of the VM's CPU, Memory, Network and Disk info all on one page. This is a basic dashboard with five object pickers. No additional views or metric configs are needed. However, policy may need some metrics enabled or they could show up as question marks. A sample policy with all metrics enabled is included.

===============
Installation
===============
1. Unzip vROpsTOP.zip
2. Go to Dashbaords > Manage Dashboards > click the gear > Import dashboard
3. Select the file vROPsTOP-Dashboard.zip

===============
USAGE
===============
The vROpsTOP dashboard will show up in the Operations dashboard group. The hosts section lists all hosts connected to vROps and displays property info like number of running VMs and parent cluster as well as some esxtop-like KPIs. Select a host and the details for all VMs on that host are displayed in the panes below. 

===============
TIPS
===============
- Click columns to sort greatest to smallest or smallest to greatest
- Hover over the top right corner of each section to get the "show toolbar" box to enter text to filter on
- Update refresh intervals as needed, however still limited by vROps polling intervals
- Edit the widget > click pick metrics > update box labels with KPI thresholds per your standards i.e. “CPU Contention (%) (<6!)” to show a value of 6 or higher needs investigation