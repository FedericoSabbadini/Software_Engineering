Project Overview
This software system supports the exchange of work performances without involving any monetary transactions. It is developed using an incremental and iterative development process and is designed to be adopted by organizations that manage such exchanges across different activity categories and potentially across multiple locations.

Purpose
The goal is to facilitate time-based exchanges of work (measured in hours) between users, within a predefined set of activity categories configured by the organization. The system enables:

Matching of potential exchanges

Monitoring of ongoing or completed exchanges

Configuration of exchangeable activity categories

⚠️ No financial compensation is ever involved in the exchanges.

User Roles
The application defines two types of users:

1. Configurator
A representative of the organization who:

Sets up and maintains the category structure.

Oversees exchanges (only visible to them, not handled automatically).

Is notified by the system when a potential exchange is identified.

Notifies participants manually (outside the system).

2. Participant
A user interested in exchanging hours of work. Participants:

Browse available categories.

Submit offers or requests for exchange.

Wait for the configurator to validate and notify them of matching opportunities.

Category Hierarchy
The exchangeable activities are organized in a tree-like category hierarchy, configured by the configurator:

Non-leaf categories:

Have a characteristic field (name and domain are category-specific).

Each field value defines a subcategory.

Each value may include an optional description.

Leaf categories:

Represent actual exchangeable work.

Do not have fields or further subdivisions.

Exchanges can only occur at this level.

Example:

Category: "Tutoring" (field: subject → domain: Math, English, Science)

Subcategory: "Tutoring > Math"

Further breakdown may occur depending on structure depth.

Final leaf: "Tutoring > Math > High School Level" (exchangeable).

Key Features (Planned/Implemented Incrementally)
 Category configuration interface (for configurators)

 Exchange offer/request submission (for participants)

 Matching engine for identifying potential exchanges

 Notification system for configurators

 Hierarchical category viewer

Notes
All interactions between participants happen through the configurator; direct contact between participants is not handled by the application.

Each organization can customize its own set of categories and characteristic fields.

For More Details
Refer to the full project specification in Traccia.
