# Social-Network

##### A social network web application where user can create an account and then create or join group, 
#### Functions
- Users can create a public or a private group. Users can only post content into a group.
- Users can request to join a public group or can be invited into a group
- Users can only be invited to join a private group
- Only the group administrators can exclude and invite members to a (private) group
- The group creator is automatically the group administrator and can make other
members administrators
- An administrator can promote other members as administrators or revoke the
administrator status of another member
- A group has topics (or tags) that must be provided when the group is created.
- Each group has its board (or feed) where members can post text, audio, image, video content
- Users can belong to 0 or more groups
- Users can only have a private conversation (chat) with people (one or many) with
whom they share at least one group
- The app must list all the public groups and users should be able to filter groups
based on their tags/topics
- The main view should list all the groups that the user belongs to
- Members can flag a post for deletion
- Only group admin can delete other members posts
- A member can always delete their own post

#### Tech Stacks
- web server: Express (on top of Node.js)
- frontend: ReactJS
- frontend/backend communication: RESTful API
- Testing: Jest and cypress 
- CI: Travis


![pic04](https://user-images.githubusercontent.com/43489975/184638260-3b73c8c1-a05d-4efa-8e0e-a809abd4ac44.jpg)
![social2](https://user-images.githubusercontent.com/43489975/184656094-f67cc8b6-bd62-4b8a-a4e7-fb6d00053c95.png)
