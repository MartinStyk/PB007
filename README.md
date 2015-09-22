# PB007

Project for the Autumn 2015 semester: Call centre and issue tracking system
An issue tracking system is a software that manages and maintains lists of issues, as needed by an organization. Issue
tracking systems are commonly used in an organization's customer-support call centre to create, update, and resolve
reported customer issues, or even issues reported by that organization's employees. Information about encountered
issues is stored as issue tickets. An issue tracking system also contains a knowledge base with information on each
customer and resolutions to common problems.
A customer (or employee) experiencing a problem can either call the support centre, where a support technician
files the issue in the system, or can report the issue via an online form on the organization website. In case of the
latter, the system notifies the support manager who assigns the reported problem to a technician (both the
customer and the technician get notified). Then:
1. The technician verifies that the problem is real, and ensures that enough information about the problem is
obtained from the customer (see below).
2. The technician creates the issue ticket in the system, entering all relevant data, as provided by the customer. The
customer is notified about the issue creation and a way to follow the status of the issue online.
An issue ticket is a running report on a particular issue and its status. It has a unique reference number, which is
used to allow the customer or support technician to quickly locate and check the status of the issue. Issues can have
several aspects to them. Each issue has an urgency value based on the overall importance of that issue. Low urgency
issues are minor and should be resolved as time permits. Normal and High urgency issues must be assigned with a
deadline that has to be met. Deadline violations are checked periodically (at midnight each day) and reported to the
support manager. Other details of issues include the customer experiencing the issue (whether external or internal),
date of submission, the environment of the customer, when and how the problem occurs, detailed descriptions of
the problem, attempted solutions or work-arounds, and other relevant information (e.g. people involved in repairing
the issue).
3. As work is done on the issue, the system is updated with new data by the technician. Each issue maintains a
history of each change, including all attempts at fixing the problem. Ticket status can be: Open, In Progress, Pending,
Resolved, Closed.
 Open indicates an issue that has been just created and no operation has yet been performed, such as
assignment;
 In Progress marks an issue that has been assigned for the resolution and is actively progressing towards
resolution;
 Pending marks an issue that is stalled and is waiting for more feedback from the side of the user;
 Resolved marks that the issue has been solved, but the resolution has not been yet confirmed by the
customer;
 Closed identifies issues that users confirm to have been resolved.
Advanced functionality (may be added by you or your seminar tutor):
 automatic generation of tickets by alarming systems, e.g. network monitoring
 monitoring of handling, time spent and quality of work
 statistical analysis of the number of tickets
 further ticket statuses, such as Duplicate, Invalid, Incomplete (e.g. in the description), Working (i.e. not
found/reproduced in the system)
 integration with development tools and other systems
