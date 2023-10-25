Project Title: Post Office Queuing System Simulation using Simul8

**Objective:**
This project aimed to simulate a queuing system within a high-street post office in Cardiff City Centre using Simul8. Real-life data, including service times, inter-arrival times, and customer behavior, was collected to ensure the model accurately reflected the post office's operations. The key objectives were to evaluate customer waiting times, identify optimal resource allocation, and measure staff and machine utilization for the purpose of improving customer satisfaction and operational efficiency.

**Data Collection:**
- Data was collected through observations at the Cardiff post office during an average weekday between 09:00 and 17:50.
- Data points included inter-arrival times, service times, resource values (number of staff and machines), and customer behavior.
- Customer behavior was categorized as manual clerk interaction or machine usage.

**Data Analysis:**
- Inter-arrival times followed a Beta distribution with specific parameters.
- Service times had different distributions for various activities, such as money orders, parcel collection, letter collection, and machine usage.
- Resource values included five staff members and two machines.
- Customer behavior showed that 80% visited a manual counter while 20% used machines. Subsequently, a percentage of customers switched between these options.

**Simulation Model:**
- The simulation modeled the customer journey upon entering the post office, selecting a service, and exiting.
- It used real-world data to determine the arrival rate and resource allocation.
- The model featured queues for manual and machine-based activities, with separate counters for money, letters, and parcels.
- Staff were assigned to specific activities, and customers could move between activities if necessary.
- The simulation assumed customers would not leave the queue until they completed their intended task.

**Experiments and Results:**
- 26 trials were conducted to gather results, with each trial representing a full day's operation.
- Key performance indicators (KPIs) included average and maximum time in the system, as well as service utilization.
- The results showed that customers spent an average of 265 seconds in the post office, with parcel queues having the longest wait times.
- Manual clerk engagement ranged from 22.57% to 32.34%, while machine usage was around 31.30%.

**Key Findings:**
- The findings suggested that the post office should consider reorganizing its infrastructure to offer all services at a standard counter instead of separate tills.
- This change would likely increase efficiency and reduce waiting times.
- Implementing a first-in, first-out queuing system, based on arrival time rather than the service required, was also recommended.

**Conclusion:**
This project's simulation and data analysis provided insights into improving the queuing system at a high-street post office, potentially leading to enhanced customer satisfaction and operational efficiency. The findings could be valuable for post office management and decision-makers in redefining their service delivery methods.

For the full project details, please refer to the project report and Simul8 model.
