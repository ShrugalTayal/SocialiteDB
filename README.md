# SocialiteDB

SocialiteDB is a messaging platform that allows users to send messages and media to other users through direct messages (DM) or in groups. Users can also create their own groups, manage their profiles, block/unblock contacts, save contacts, search through contacts, share messages with multiple contacts, forward messages, delete chat messages, and customize notification settings.

## Project Scope

The project aims to provide the following functionalities:

- Users can send messages and media to other users through direct messages (DM) or in groups.
- Users can create their own groups and have control over group administration.
- Users can make changes to their profile information, such as bio and phone number.
- Users can block/unblock contacts to control their messaging interactions.
- Users can save contacts for easy access and management.
- Users can search through their contacts to quickly find specific users.
- Users can share messages with multiple contacts simultaneously.
- Users can forward messages from one chat to one or more other chats.
- Users can delete chat messages for everyone or for themselves.
- Additional settings and features related to notifications and unread messages display can be implemented.

## Entities

The project involves the following entities:

- User (id, bio, phone number)
- Groups (id, name, create_date)
- Group_info (id, user_id, group_id, is_active)
- Contacts (id, user_id, contact_id, is_blocked)
- Message (id, sender_id, receiver_id, message_body, time/date, status)
- Recipient (id, receiver_id, is_read, message_id)

## SQL Queries

The project requires the implementation of various SQL queries. Some example queries are:

- Alter table to make the primary key ID columns of all tables auto-incremental.
- Adding constraints and default values to table columns.
- Creating views for user profiles and other functionalities.
- Selecting information about users, groups, messages, and contacts.
- Inserting messages and recipients into the database.
- Updating message status and recipient information.
- Deleting messages for everyone or for the current user.
- Retrieving specific information related to user groups and contacts.
- Aggregating data and counting the number of members, messages, etc., in a group.

Please note that these queries are just examples, and the actual queries will depend on the specific implementation and database management system being used.

## Internal and External Stakeholders

In the context of this project, internal stakeholders include the owners, managers, employees, and investors of the messaging platform. External stakeholders are the customers, competitors, suppliers, creditors, the general public, and the government.

## ER Diagram and Relational Schemas

The project involves mapping the entity-relationship (ER) diagram into relational schemas. The ER diagram includes tables such as User, Groups, Group_info, Contacts, Message, and Recipient, along with their respective attributes and relationships.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository.
2. Install the necessary dependencies.
3. Set up the database and execute the SQL scripts to create the required tables and relationships.
4. Configure the application settings, including database connection details and other parameters.
5. Start the application and test the implemented functionalities.
6. Make any necessary modifications or improvements based on the project requirements.

## Contributors

The SocialiteDB project is developed and maintained by the following contributors:

- Aditya Peer
- Ayush Raje Chak
- Shreya Bhatia
- Shrugal Tayal
