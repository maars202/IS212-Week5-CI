
# # CREATE A users TABLE USING RAW SQL QUERY
# db.engine.execute(
#     '''
#     CREATE TABLE `Role` (
#     `role_id` int PRIMARY KEY AUTO_INCREMENT,
#     `role_name` varchar(20) NOT NULL);
#     '''
# )
  


# # CREATE A users TABLE USING RAW SQL QUERY
# db.engine.execute(
#     '''
#     CREATE TABLE `Staff` (
#         `staff_id` int PRIMARY KEY,
#         `staff_Fname` varchar(50) NOT NULL,
#         `staff_Lname` varchar(50) NOT NULL,
#         `department` varchar(50) NOT NULL,
#         `email` varchar(50) NOT NULL,
#         `role` int NOT NULL
#     );
#     '''
# )
  