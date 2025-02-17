
<div align="center">
  
  # Ticket Activity Manager
  made by fac.e
  
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
<div align="center">
  <br />
  <p>
    <a href="https://discord.js.org"><img src="https://discord.js.org/static/logo.svg" width="246" alt="discord.js" /></a>
  </p>
</div>

  <p>
    Tool that monitors opened tickets, ensuring quick responses by notifying users and admins about inactivity or delays.
    <br>
    It helps maintain efficient ticket handling and improves support workflow.
  </p>
</div>



> [!WARNING]  
> You need **`npm i node-cron`** or **`npm i cron`** installed for scheduled jobs.

---

![image(2)](https://github.com/user-attachments/assets/510ce86c-87fa-4d95-9fd8-3f2213618bef)

---

### Features  

- [x] Efficient monitoring of opened tickets with minimal resource usage.  
- [x] Automated notifications for users and admins on inactivity or delayed responses.
  - [x] Sends reminders to users if their ticket is inactive for too long.  
  - [x] Notifies administrators when a user is waiting too long for a response.   
- [x] Customizable response time thresholds to trigger alerts.  
- [x] Supports scheduled and recurring checks (**`CRON`**).
- [x] Rate limiting to control notification frequency.  
- [x] Retry mechanism for failed notifications.  
- [x] Handles cases where channels are empty or lack a valid message history.  
- [x] Ensures only active guild members are processed, avoiding errors with missing members.  
- [x] Designed for efficient processing without excessive API calls (e.g., avoids mass fetching of members).  
- [x] Logs activity and decisions for easy debugging and monitoring.  
- [x] Ability to pause/resume monitoring as needed.  


In progress:
- [ ] Parent-child ticket dependencies for better tracking.
- [ ] Configurable inactivity thresholds per ticket type.  
- [ ] More advanced admin escalation options based on urgency.  
- [ ] Integration with external logging or tracking systems.  


---
