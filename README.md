# aws-recoverability


#### Relational Database Resilience

- [x] ***SWBAT build networks that will continue to operate through the loss of a single data center*** 
Screenshot of successfully created VPCs in two different AWS regions

- [x] ***SWBAT build systems that align to a business availability objectives for redundancy.*** 
Screenshot of a MySQL database configured to run in multiple availability zones in the "Primary" VPC. Database must have automatic backups enabled and be in a private subnet.
Screenshot of route tables for the configured database subnets

- [x] ***SWBAT build systems that align to business availability objectives for resiliency.*** 
Screenshot of a read-replica MySQL database configured to run in the "Secondary" VPC. Database must be in a private subnet.
Screenshot of route tables for the configured database subnets


#### Manage applications in AWS

- [x] ***SWBAT predict the availability of a configuration*** 
Paragraph describing the Recovery Time Objective (RTO) and Recovery Point Objective (RPO) of this database configuration

- [x] ***SWBAT use correct data access patterns.*** 
Log of the student connecting to, reading from and writing to the primary database
Log of the student connecting to the read-replica database and being able to read data from the database, but not able to write (insert) data.

- [x] ***SWBAT monitor highly available system*** 
Screenshot of “Database connections” metric of database.
Screenshot showing database replica configuration.


- [x] ***SWBAT operate a highly resilient database*** 
Screenshot of the read-replica database before promotion.,
Another screenshot after promotion.
Log of the student connecting to, reading from, and writing to the database in the standby region, after promotion.


#### Website recovery

- [x] ***Screenshot of the website with a winter scene as the background and displaying a timestamp.*** 
Screenshot of the website with a winter scene as the background and displaying a timestamp.

- [x] ***SWBAT recover from “accidental” modification to website*** 

Screenshot of same website with a different season (picture) as the background, still displaying a timestamp
Screenshot of AWS S3 object “index.html” showing multiple versions of the object exist.
Screenshot of the same website once again with the original background, still displaying a timestamp.
Screenshot of the same website with no background image.
Screenshot of AWS S3 object “winter.jpg” showing multiple versions of the object exist with the latest being a “deletion marker”.
Screenshot of the same website once again with the original background, still displaying a timestamp.
