Development of a Construction Management App


Problem Statement
In our observations, we noticed a significant issue: many laborers spend their days idly waiting by roadsides, hoping for work opportunities. These laborers often rely on contractors who may not compensate them fairly or provide consistent employment. This results in financial instability for laborers and inefficiency in the job market. Additionally, customers seeking skilled labor for various tasks face challenges in finding reliable workers, ensuring transparency, and managing project timelines effectively.


Proposed Solution
To address these issues, we propose developing "THE BUILDERS" a web application using Blazor that directly connects customers with skilled laborers. The app will serve as a comprehensive platform where laborers can create profiles showcasing their skills, experience, availability, and fees. Customers can use the app to browse through these profiles, check ratings and reviews, and book laborers for specific tasks such as carpentry, construction, and painting.




Module Descriptions

1.	User Management Module
Module Objective: Manage authentication, authorization, and access control.
Module Description: This module facilitates user registration, login, and profile management. It includes role-based access controls to ensure secure access.
Module Interconnections: Integrates with other modules for controlled access to project data.

2.	Project Management Module
Module Objective: Facilitate project creation, organization, and monitoring.
Module Description: Enables project creation, defining scope, setting milestones, task assignment, and progress tracking.
Module Interconnections: Core functionality, interfaces with task management and reporting.

3.	Task Management Module
Module Objective: Manage and track individual project tasks.
Module Description: Allows task creation, assignment, prioritization, and monitoring. Features task status updates and dependencies.
Module Interconnections: Integrates with project management for aligned task execution.

4.	Service Selection Module
Module Objective: Enable users to choose from a variety of construction services.
Module Description: This module allows users to browse through a list of available services such as carpentry, construction, painting, plumbing, electrical work, etc. Users can select the specific service they require for their project.
Module Interconnections: Integrates with user management to ensure authenticated access to service selection options.

5.	Worker Selection Module
Module Objective: Allow users to view and hire workers based on selected services.
Module Description: Once users have selected a service, this module displays a list of available workers skilled in that particular service. Users can view worker profiles, including ratings and reviews, to make informed hiring decisions.
Module Interconnections: Interacts with user management for authentication and with resource management for labor allocation.

6.	History Management Module
Module Objective: Track and manage the history of assigned work and reviews.
Module Description: This module is responsible for maintaining a record of all tasks and projects that have been assigned to workers, as well as tracking reviews and feedback provided by customers. It helps in generating historical data for performance analysis and future reference.
Module Interconnections: Interacts with the Task Management Module for task-related history and the User Management Module for authenticated access.

FUNCTIONALITY DETAILS
1.	User Management
	User Registration: Users can register by providing necessary details.
	User Login: Users can log in using their credentials.
	Profile Management: Users can update their profile details.
	Role Management: Users are assigned roles (User or Worker).
	Authentication: Verify user credentials during login.
	Authorization: Ensure users access only their authorized resources.

2.	Project Management 
	Project Creation: Users can create new projects.
	Project Scope: Define the scope and details of the project.
	Milestones: Set project milestones and deadlines.
	Task Assignment: Assign tasks to workers.
	Progress Tracking: Track the progress of the project

3.	Task Management 
	Task Creation: Users can create tasks within a project.
	Task Assignment: Assign tasks to specific workers.
	Task Prioritization: Set priority levels for tasks.
	Task Status: Update the status of tasks (e.g., pending, in progress, completed).
	Task Dependencies: Define dependencies between tasks.

4.	Service Selection 
	Service List: Display a list of available services.
	Service Selection: Users can select the desired service for their project.
	Service Details: Provide details about each service, including descriptions and pricing.

5.	Worker Selection
	Worker List: Display a list of workers available for the selected service.
	Worker Profiles: Show detailed profiles of workers, including skills, experience, and pricing.
	Ratings and Reviews: Display ratings and reviews for each worker.
	Hire Worker: Allow users to hire a worker based on their profile and reviews.

6.	History Management
	Retrieve the historical data of work assigned to a specific user.
	Users can see the list of all workers they hired

Resources
	Programming Languages: C#, HTML, CSS
	Framework: Blazor for frontend development
	Database: SQL Server for data storage
	Development Tools: Visual Studio, SQL Server Management Studio
	Project Management Tools: Trello, Microsoft Project
Conclusion
The Construction Management System project endeavors to streamline construction project management by offering a cohesive platform for planning, executing, and monitoring. By integrating various modules, the system aims to enhance collaboration, optimize resource allocation, and empower data-driven decision-making, ultimately fostering efficiency and success in construction projects.
