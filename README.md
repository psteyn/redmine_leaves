Redmine Leaves
==============

A simple plugin for user leaves management. It allows user to check-in and
check-out for attendance marking. Leave is marked for any user that does not 
check-in by the specified time. Administrator can define leave types via the 
administrative interface for the plugin

Only users with permission eligible_for_leave are shown in the list. A report 
summary page similar to the Timesheet Plugin shows the leaves summary. Leaves 
are also integrated into the Calendar Module (if possible). User who does not 
check-in, is automatically marked as off after some cut-off period Leave Types 
are defined through Redmine settings

After installing the plugin for the first time, it is advised to make Redmine 
groups and add users into these groups. This will allow admin to assign 
permissions to users accordingly.

For Auto-Leave marking, admin is required to install "whenever gem" to 
automate the process.
