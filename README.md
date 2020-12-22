# social-media-db-scripts

This repository holds the scripts required to create and configure the social-media-database.

#Database

`SOCIAL-MEDIA-DATABASE` - Database created for the puprose of this project.

#Schema
`SM-USERS-SCHEMA` - Schema created under *SOCIAL-MEDIA-DATABASE* to hold Social-Media related user details.

#Table

`SM-USERS` - Table created under *SM-USERS-SCHEMA* to hold basic details of all Social-Media users. **userId** is the PRIMARY-KEY.

`SM-USER-FRIENDS` - Table createed under *SM-USERS-SCHEMA* to map the relation between a user and her/his friend. **userId** is the PRIMARY-KEY. **friendId** is the FOREIGN-KEY referencing **userID** from `SM-USERS`table.
