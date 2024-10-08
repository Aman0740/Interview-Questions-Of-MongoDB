# Interview-Questions-Of-MongoDB

### **★ Basic MongoDB Questions:**

1. **What is MongoDB?**
   - MongoDB is a NoSQL database that stores data in flexible, JSON-like documents, which means fields can vary from document to document, and data structure can change over time.

2. **What is a NoSQL database? How is it different from SQL databases?**
   - NoSQL databases are non-relational databases that provide a mechanism for storage and retrieval of data modeled in means other than the tabular relations used in relational databases (SQL). NoSQL databases are schema-less, horizontally scalable, and generally handle large volumes of unstructured or semi-structured data.

3. **What are the advantages of using MongoDB?**
   - Schema flexibility, horizontal scalability, high availability, powerful querying and indexing, and support for distributed systems are some of the key advantages.

4. **Explain the concept of a document in MongoDB.**
   - A document in MongoDB is a set of key-value pairs. Documents are analogous to JSON objects. They are the basic unit of data in MongoDB.

5. **What is a collection in MongoDB?**
   - A collection is a group of MongoDB documents. It is equivalent to an RDBMS table.

### **★ Intermediate MongoDB Questions:**

6. **What is sharding in MongoDB?**
   - Sharding is a method for distributing data across multiple machines. It allows MongoDB to scale horizontally by partitioning data across shards, which are distributed across multiple servers.

7. **Explain indexing in MongoDB.**
   - Indexes support the efficient execution of queries in MongoDB. Without indexes, MongoDB must scan every document in a collection to select those that match the query statement.

8. **What is a replica set in MongoDB?**
   - A replica set in MongoDB is a group of mongod instances that maintain the same data set. Replica sets provide redundancy and high availability, ensuring that data remains available even in the event of hardware failure.

9. **What is the Aggregation Framework in MongoDB?**
   - The Aggregation Framework is a powerful tool in MongoDB that processes data records and returns computed results. It allows for filtering, grouping, sorting, and transforming data using aggregation pipelines.

10. **How does MongoDB handle transactions?**
    - MongoDB supports multi-document ACID transactions since version 4.0. Transactions allow for complex operations involving multiple documents to be executed atomically.

### **★ Advanced MongoDB Questions:**

11. **How does MongoDB ensure data consistency and reliability?**
    - MongoDB ensures data consistency using Write Concerns and data redundancy through Replica Sets. Write Concern specifies the level of acknowledgment requested from MongoDB for write operations.

12. **What is the difference between `find()` and `findOne()` in MongoDB?**
    - The `find()` method returns a cursor that can iterate over all matching documents, while `findOne()` returns the first document that matches the query criteria.

13. **How does MongoDB achieve horizontal scalability?**
    - MongoDB achieves horizontal scalability through sharding, where data is distributed across multiple servers.

14. **Can you explain what Map-Reduce is in MongoDB and when would you use it?**
    - Map-Reduce is a data processing model used to perform operations such as filtering and aggregation on large data sets. It is generally used when complex aggregations are needed that cannot be handled by the Aggregation Framework.

15. **What is the purpose of the `ObjectId` in MongoDB?**
    - `ObjectId` is the default primary key for MongoDB documents. It is a 12-byte identifier that is unique and generated by MongoDB. It includes a timestamp, a machine identifier, a process identifier, and a counter.
