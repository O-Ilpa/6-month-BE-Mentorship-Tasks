# **Vacation tracking system**

## 1. ***Requirements***

### -  **Vision**
  the VTS (Vacation Tracking System) aims to to provide all the employees with direct control on managing their vacations, sick leave by sumiting, updating, viewing their reqests through an easy to use platform, without having to be aware of the company policies or sending manual requests to the HR department and waiting for managers to proccess them. this platform redueces delays and lessen the HR work. it saves time for the company, improves communication, and provides a history for old requests.

### - **Functions**

  - the system should allow employees to view, edit, cancel or create vacation requests  
  - the system should notify HRs and request approval for employees requests 
  - the system should should allow HRs and managers to update users vacation bundle 
  - the system should allow employees to make requests up to 1.5 years in the future, and view old requests 
  - the system should email the manager to request approval and notify the employee with their status 
  - the system shouldn't allow requests to be made if the vacation bundle is exceeded
  - the system should allow HRs and managers to override all actions restricted by rules

### - **Non-Functions**
  - Is implemented as an extension to the existing intranet portal system, and uses the portal’s single-sign-on mechanisms for all authentication
  - the system should be easy to use 
  - the system should have a clean UI and responsive on all screen sizes
  - the system should generate logs for accetped, rejected, cancled requests
  - the system should log HRs override actions

### - **Constraints**
  - the platform should only be accessible by the company intranet
  - the system should run on the company existing infrastructure 


# **Remaining:** Domain, Actors, **UseCase:** entities, flowchart, seq diagram, pseudo code (manage time)