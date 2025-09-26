# Prisma Topics to Learn

## [1. Basics](#)
- [What is Prisma (ORM vs Query Builder vs Prisma)](#)
- [Setting up Prisma in a project](#)
- [Prisma Client overview](#)
- [Connecting to a database (PostgreSQL, MySQL, SQLite, MongoDB, etc.)](#)

## [2. Prisma Schema](#)
- [Datasource & Generator blocks](#)
- [Defining models](#)
- [Scalar types (String, Int, Boolean, DateTime, Json, etc.)](#)
- [Relations](#)
  - [One-to-One](#)
  - [One-to-Many](#)
  - [Many-to-Many](#)
- [Enums](#)
- [Indexes & unique constraints](#)
- [ID and @@id (compound primary keys)](#)

## [3. Migrations](#)
- [Prisma Migrate workflow](#)
- [Creating & applying migrations](#)
- [Resetting the database](#)

## [4. Prisma Client (CRUD)](#)
- [Create](#)
- [Read (findUnique, findMany, findFirst)](#)
- [Update](#)
- [Delete](#)
- Upsert
- Filtering & sorting
- Pagination (skip, take, cursor)
- Selecting fields & relations (select, include)
- Nested writes
- [Eager loading with `include`](#)
- [Lazy loading alternatives](#)

## [5. Advanced Querying](#)
- [Aggregations (count, avg, sum, min, max)](#)
- [GroupBy queries](#)
- [Distinct queries](#)
- [Raw database queries ($queryRaw, $executeRaw)](#)

## [6. Middleware](#)
- [Query middleware](#)
- [Logging queries](#)
- [Custom logic with middleware](#)

## [7. Transactions](#)
- [Atomic operations](#)
- [Batch operations](#)
- [Interactive transactions (`prisma.$transaction`)](#)

## [8. Performance & Optimization](#)
- [Connection pooling](#)
- [N+1 problem & solutions](#)

## [9. Tooling & Ecosystem](#)
- [Prisma Studio (GUI for DB)](#)
- Introspection (`prisma db pull`)
- Using with GraphQL (Nexus, Apollo)

## 10. Deployment & Best Practices
- Environment-specific configs
- Handling migrations in production
- Seeding databases
- Error handling & logging
- Best practices for schema design
