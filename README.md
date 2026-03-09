# Enforcing-Mandatory-fields-
README

Project Title

Enforcing Mandatory Fields Using UI Policies and Migrating Changes with Update Sets in ServiceNow

Project Description

This project demonstrates how to enforce mandatory fields in the Incident Management module of the ServiceNow platform using UI Policies. The main objective of the project is to ensure that the Priority field becomes mandatory when the Incident State is changed to "In Progress".

The project also explains how configuration changes are captured using Update Sets and how they can be exported and imported between different ServiceNow instances. This ensures a structured and reliable migration process without manual reconfiguration.

Objectives

- To implement a UI Policy on the Incident table.
- To make the Priority field mandatory when the State is set to "In Progress".
- To capture all configuration changes using an Update Set.
- To export the Update Set as XML.
- To import and apply the configuration in another ServiceNow instance.

Tools and Technologies

- ServiceNow Personal Developer Instance (PDI)
- Incident Table
- UI Policies
- UI Policy Actions
- Update Sets
- Web Browser (Google Chrome recommended)

Implementation Steps

1. Create a new Update Set in ServiceNow.
2. Make the Update Set as Current.
3. Create a UI Policy on the Incident table.
4. Add the condition: State is In Progress.
5. Create a UI Policy Action for the Priority field.
6. Set the Mandatory property to True.
7. Verify that the configuration is captured in the Update Set.
8. Export the Update Set as XML.
9. Import the Update Set into the target instance.
10. Preview and Commit the Update Set.

Features

- Enforces data accuracy in incident records.
- Provides real-time validation for users.
- Does not require custom scripting.
- Supports easy configuration migration across instances.

Advantages

- Improves data quality in incident management.
- Provides immediate feedback to users.
- Simple low-code configuration.
- Easy to maintain and migrate.

Conclusion

This project successfully demonstrates how UI Policies can be used to enforce mandatory fields dynamically in ServiceNow. It also highlights the importance of Update Sets for managing and migrating configuration changes across different ServiceNow environments. The solution improves data accuracy, ensures proper workflow enforcement, and follows best practices in ServiceNow administration.

Team Members

- Megasri R
- Jerlin Jeno V
- Padma Sree M
- Pavithra T
