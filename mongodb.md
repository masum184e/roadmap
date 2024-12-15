# MongoDB Topics for MERN Stack

## 1. MongoDB Basics
- Introduction to NoSQL and MongoDB
- Differences between SQL and NoSQL
- Installing MongoDB locally or using MongoDB Atlas (cloud)
- MongoDB Compass (GUI tool)

## 2. Data Modeling
- Databases, collections, and documents
- BSON (Binary JSON) format
- Data types in MongoDB (string, number, array, object, etc.)
- Schema design principles:
  - Embedding vs. Referencing
  - Designing for read-heavy/write-heavy operations

## 3. CRUD Operations
- **Create**: `insertOne`, `insertMany`
- **Read**: `find`, `findOne`, query filters, projection
- **Update**: `updateOne`, `updateMany`, `$set`, `$inc`, `$push`
- **Delete**: `deleteOne`, `deleteMany`

## 4. Indexing and Performance
- Creating indexes: `createIndex`
- Types of indexes: single field, compound, multikey, text
- Query optimization using indexes
- Analyzing query performance with `explain()`

## 5. Aggregation Framework
- Basics of the aggregation pipeline
- Common stages:
  - `$match`
  - `$group`
  - `$project`
  - `$sort`
  - `$lookup` (joins)
- Writing complex aggregation pipelines

## 6. MongoDB Relationships
- **One-to-One**: Embedding or referencing
- **One-to-Many**: Using arrays or separate collections
- **Many-to-Many**: Leveraging array fields or linking collections

## 7. Working with Mongoose (ODM)
- Setting up Mongoose in Node.js
- Defining schemas and models
- Data validation and default values
- Schema methods and virtuals
- Middleware (pre and post hooks)

## 8. Authentication and Security
- Securing MongoDB with users and roles
- Database authentication and authorization
- Encrypting communication (SSL/TLS)
- MongoDB Atlas security (IP whitelisting, VPC peering)

## 9. Transactions
- Introduction to MongoDB transactions
- Using transactions for multi-document operations
- ACID compliance in MongoDB

## 10. Advanced Features
- Working with GridFS (file storage)
- Using `$text` and `$regex` for text search
- Change streams for real-time data updates
- TTL (Time-To-Live) indexes for data expiration

## 11. MongoDB Atlas (Cloud)
- Setting up clusters
- Configuring backups
- Monitoring performance and metrics
- Scaling (sharding and replication)

## 12. Integration with MERN
- Connecting MongoDB to a Node.js server:
  - Using `mongodb` native driver
  - Using Mongoose for better abstraction
- Designing APIs to interact with MongoDB (via Express)
- Fetching and displaying MongoDB data in React using REST or GraphQL

## 13. Best Practices
- Avoiding common pitfalls (e.g., unindexed queries, excessive updates)
- Using environment variables to secure credentials
- Structuring collections for scalability
- Database backups and recovery

## Tools to Explore
- MongoDB Atlas (for cloud-based MongoDB)
- Robo 3T or MongoDB Compass (local database management)
- Mongo Playground (for practicing queries)
