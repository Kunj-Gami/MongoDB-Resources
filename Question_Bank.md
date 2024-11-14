# 📘 Question Bank: MongoDB

## 1. MongoDB Basics
1. What is MongoDB, and how is it different from traditional relational databases?
2. What are the advantages of using MongoDB for storing data?
3. What is BSON in MongoDB, and how is it different from JSON?
4. How do you install MongoDB on different operating systems?
5. What is a collection in MongoDB, and how is it different from a table in a relational database?
6. What is a document in MongoDB, and how is it different from a row in a relational database?
7. What are the key features of MongoDB?
8. What are the data types supported by MongoDB?
9. What is the use of the `ObjectId` data type in MongoDB?
10. What is a primary key in MongoDB, and how does it work?

## 2. MongoDB CRUD Operations
11. What are CRUD operations in MongoDB?
12. How do you create a database in MongoDB?
13. How do you insert a document into a MongoDB collection?
14. How do you update an existing document in MongoDB?
15. How do you delete a document from a MongoDB collection?
16. How do you retrieve all documents from a MongoDB collection?
17. How do you find a document by its `ObjectId` in MongoDB?
18. What is the purpose of the `findOne()` method in MongoDB?
19. How do you query documents with specific field values in MongoDB?
20. What is the difference between `updateOne()`, `updateMany()`, and `replaceOne()` in MongoDB?

## 3. Advanced Queries
21. How do you use comparison operators (e.g., `$eq`, `$gt`, `$lt`) in MongoDB queries?
22. How do you perform a text search in MongoDB?
23. How do you use logical operators (e.g., `$and`, `$or`, `$nor`) in MongoDB queries?
24. What is the purpose of the `$in` operator in MongoDB?
25. How do you query nested fields in MongoDB documents?
26. How do you sort query results in MongoDB?
27. How do you limit the number of documents returned by a query in MongoDB?
28. How do you skip a specific number of documents in MongoDB queries?
29. How do you perform a case-insensitive search in MongoDB?
30. How do you use the aggregation framework in MongoDB?

## 4. Aggregation Framework
31. What is the MongoDB aggregation framework, and why is it used?
32. What are the basic stages of an aggregation pipeline in MongoDB?
33. What is the purpose of the `$match` stage in MongoDB aggregation?
34. How do you use the `$group` stage in MongoDB aggregation?
35. What is the `$sort` stage in MongoDB aggregation, and how does it work?
36. How do you use the `$project` stage in MongoDB aggregation?
37. What is the `$lookup` stage in MongoDB, and how is it used for joins?
38. How do you use the `$unwind` stage in MongoDB aggregation?
39. What is the `$limit` and `$skip` stages in MongoDB aggregation, and when should you use them?
40. How do you use the `$facet` stage in MongoDB aggregation?

## 5. Indexing in MongoDB
41. What is indexing in MongoDB, and why is it important?
42. What are the types of indexes in MongoDB?
43. How do you create a simple index on a field in MongoDB?
44. How do you create a compound index in MongoDB?
45. What is a unique index in MongoDB, and how is it different from a regular index?
46. How do you create a text index in MongoDB, and when should you use it?
47. What is a geospatial index in MongoDB, and how is it used for spatial queries?
48. What is the `hint()` method in MongoDB, and how does it affect query execution?
49. How do you drop an index in MongoDB?
50. How do you analyze the performance of MongoDB queries using indexes?

## 6. MongoDB Aggregation and Data Modeling
51. How do you design a schema in MongoDB?
52. What is the difference between embedding documents and referencing documents in MongoDB?
53. When should you use embedded documents over referenced documents in MongoDB?
54. How do you handle one-to-many and many-to-many relationships in MongoDB?
55. How does MongoDB handle schema-less data?
56. What is the `$push` operator in MongoDB, and how is it used?
57. How do you normalize data in MongoDB when using references between collections?
58. How do you aggregate data from multiple collections in MongoDB?
59. How do you create and update an array of subdocuments in MongoDB?
60. How do you use the `$addToSet` operator in MongoDB?

## 7. MongoDB Security and Authentication
61. How do you enable authentication in MongoDB?
62. What are the different authentication mechanisms available in MongoDB?
63. How do you create a user with specific roles in MongoDB?
64. How do you implement role-based access control (RBAC) in MongoDB?
65. What are the default roles in MongoDB, and what permissions do they have?
66. How do you enable encryption in MongoDB?
67. What is SSL/TLS encryption in MongoDB, and how do you enable it?
68. How do you prevent unauthorized access to MongoDB servers?
69. What is IP whitelisting, and how can you configure it for MongoDB?
70. How do you audit user actions in MongoDB?

## 8. Replication and Sharding
71. What is replication in MongoDB, and how does it work?
72. What are the components of a MongoDB replica set?
73. How do you configure a replica set in MongoDB?
74. What is a primary node, and what is a secondary node in a MongoDB replica set?
75. What is the process of electing a new primary in a MongoDB replica set?
76. How do you perform a failover in MongoDB replica sets?
77. What is sharding in MongoDB, and why is it used?
78. How does MongoDB distribute data across multiple shards?
79. How do you create a sharded cluster in MongoDB?
80. What is a shard key in MongoDB, and how is it selected?

## 9. Backup and Restore
81. How do you back up a MongoDB database?
82. What are the different backup methods available in MongoDB?
83. How do you perform a point-in-time backup of MongoDB?
84. How do you restore a MongoDB database from a backup?
85. How do you back up and restore a sharded cluster in MongoDB?
86. What is the `mongodump` and `mongorestore` tool, and how do you use them?
87. What are the limitations of `mongodump` and `mongorestore` for backups?
88. How do you use the MongoDB Atlas backup service for cloud-based backups?
89. How do you ensure backup integrity in MongoDB?
90. How do you schedule regular backups in MongoDB?

## 10. Performance and Monitoring
91. How do you monitor the performance of a MongoDB instance?
92. What are the common performance bottlenecks in MongoDB?
93. How do you use the `mongostat` command to monitor MongoDB?
94. What is the `mongotop` tool, and how does it help in performance monitoring?
95. How do you use the MongoDB Atlas dashboard to monitor your database?
96. How do you check the health of a MongoDB replica set?
97. What is the role of the `Profiler` in MongoDB for performance analysis?
98. How do you optimize queries in MongoDB?
99. How do you handle memory management in MongoDB?
100. What are the best practices for scaling MongoDB for large applications?

