# SmartHome-I

Multi tiered Architecture:


Implemented the database in the back end tier and all the sensors and gateway are assumed to be in front end tier.

All the sensors and devices either push events to gateway or pull events from sensors and devices.

Gate way is made to communicate with the database to populate the database with all the push and pull events from sensors and devices at a particular time stamp.
Gateway can query the database and get the current status of a device or sensor and can report the particular machine. 
 
Database is Synchronized to avoid multiple threads accessing at same time.
