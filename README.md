# social-media-db-scripts

This repository holds the scripts required to create and configure the social-media-database.

### Database
1. `SOCIAL-MEDIA-DATABASE` - Database created for the puprose of this project.

### Schema
1. `SM-USERS-SCHEMA` - Schema created under *SOCIAL-MEDIA-DATABASE* to hold Social-Media related user details.

### Table
1. `SM-USERS` - Table created under *SM-USERS-SCHEMA* to hold basic details of all Social-Media users. **userId** is the PRIMARY-KEY.

2. `SM-USER-FRIENDS` - Table createed under *SM-USERS-SCHEMA* to map the relation between a user and her/his friend. **userId** is the PRIMARY-KEY. **friendId** is the FOREIGN-KEY referencing **userID** from `SM-USERS`table.
