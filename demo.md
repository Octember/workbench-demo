
## Data model:

### Client/customer
All of the stuff below is scoped to the client

### Project
- Name
- Description
- List of milestones

### Milestone
- Name
- Description
- Owners
- Subscribers
- Due date
- Comments
- Status
    - who can change it? only owners?
- List of Tasks

### Task
- Name
- Description
- Owners
- Due date (validation?)
- list of files
    - *File upload*

### Supplier
- name
- description
- List of users

### User

## Pages

### My Tasks
- List of my owned tasks
- List of my subscribed tasks

### Task detail
- Activity thread
- List of all updates

### Project detail
- List of milestones
- Settings modal
    - add/remove users to milestones

### All Suppliers
- List of suppliers
- Ability to invite users or *invite by email*

## Misc functionality
- Comments on tasks create emails
    - Emails can be replied to and show up in the app as comments


## Noah Feedback
- The menu to edit members access is a bit hidden IMO
- What exactly does "access to the milestone" mean. Can they see the rest of the project? How can they request additional context if they need it?
- Can you give me more examples of businesses that are onboard to use this?
- It would be worth trying to see how far we could build this using some off the shelf CMS like https://webflow.com/ I think I could get it pretty close in a few hours with no-code ;)
