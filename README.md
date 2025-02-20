# Introduction

This database system allows for the management of user accounts and posts. It supports operations such as creating and editing users, creating and viewing posts, and viewing the most recent updates. The system tracks user and post data for ease of access and management.

![image](https://github.com/user-attachments/assets/7798f8e5-c631-4338-a6e7-1ef9c2bcab08)

![image](https://github.com/user-attachments/assets/16d614b5-e72d-4725-84c4-4bff0a238346)


## Features

Create Users: Allows the creation of new user accounts.
Find Users: Enables searching for users based on their details.
Edit Users: Allows modification of user information.
Create Posts: Allows users to create new posts.
Find Posts: Enables searching for posts based on certain criteria.
View Posts: Allows viewing posts by users.
Edit Posts: Lets users modify existing posts.
Last 3 Updated Data: Displays the last three updated entries, making it easier to track recent activity.

## Database Structure

The system uses a relational database to store the following tables:

###Users

user_id (Primary Key)
username
email
password
created_at
updated_at

###Posts

post_id (Primary Key)
user_id (Foreign Key to Users)
title
content
created_at
updated_at

###Audit Log (to track recent updates)

log_id (Primary Key)
entry_type (User or Post)
entry_id (ID of the updated user/post)
timestamp


## Usage

Creating Users:
Use the 'Create Users' feature to add new users to the system.

![image](https://github.com/user-attachments/assets/da23466f-780c-4513-9f73-0953218eca21)


Finding Users:
Use the 'Find User' feature to search for users based on criteria such as username or email.

![image](https://github.com/user-attachments/assets/cf34eb6b-18a7-4e70-986a-9eafe3eb6469)


Editing Users:
After locating a user, use the 'Edit User' feature to modify their details.

![image](https://github.com/user-attachments/assets/279cd557-7715-411c-bbd2-c021b1e6f42c)


Creating Posts:
Use the 'Create Post' feature to allow users to create posts under their accounts.

![image](https://github.com/user-attachments/assets/68c1a10a-5f1b-48e0-be7e-265316b33743)


Finding Posts:
Search for posts based on the user or title using the 'Find Post' feature.

![image](https://github.com/user-attachments/assets/4a4bd572-5a92-4f83-8fe6-cb49815789d6)


Viewing Posts:
The 'View Post' feature allows viewing the full content of the post.

![image](https://github.com/user-attachments/assets/3c7a4834-4973-4c52-b1c3-eb97a93c5d6b)


Editing Posts:
Edit an existing post using the 'Edit Post' feature.

![image](https://github.com/user-attachments/assets/475b8fd6-3d3c-4e1f-a9ad-fdee8203702e)


Last 3 Updated Data:
View the last three updated user or post entries from the system's log.

![image](https://github.com/user-attachments/assets/f95ae61c-11cd-4715-9915-5fd29f67a550)



