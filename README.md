# Distributed Data Management Systems.
## PostgreSQL

PostgreSQL is a powerful, open source object-relational database system with over 30 years of active development.
The origins of PostgreSQL date back to 1986 as part of the POSTGRES project at the University of California at Berkeley.

### **ACID compitable**

* Atomic
  * Transactions are often composed of multiple statements. Atomicity guarantees that each transaction is treated as a single "unit", which either succeeds completely, or fails completely
* Consistency
  * Ensures that a transaction can only bring the database from one valid state to another. This prevents database corruption by an illegal transaction.
* Isolation
  * Transactions are often executed concurrently,
    Isolation ensures that concurrent execution of transactions leaves the database in the same state that would have been obtained if the transactions were executed sequentially.
* Durability
  * guarantees that once a transaction has been committed, it will remain committed even in the case of a system failure.

### **Oracle compitability**

Postgres database is easy to port to an Oracle database, because 
of its **ACID** compitability and relational structure

---

### **Pros:**
1. Data Types

  Supports a big variety of primitive and complex datatypes. 

 *Primitives: Integer, Numeric. String, Boolean
 Structured: Date/Time, Array, Range / Multirange, UUID
 Document: JSON/JSONB, XML, Key-value (Hstore)
 Geometry: Point, Line, Circle, Polygon
 Customizations: Composite, Custom Types*

2. Data Integrity

ensure data integrity for a relational database using all of the constrains that makes a relational database so poverful and secure.

*UNIQUE, NOT NULL
Primary Keys
Foreign Keys
Exclusion Constraints
Explicit Locks, Advisory Locks*

3. Extensebility

Stored functions and procedures
Procedural Languages: PL/PGSQL, Perl, Python (and many more)
SQL/JSON path expressions
Foreign data wrappers: connect to other databases or streams with a standard SQL interface
Customizable storage interface for tables
Many extensions that provide additional functionality, including PostGIS

### **Cons:**

* Opensource

Postgres is not owned by one organization. So, it has had trouble getting its name out there despite being fully featured and comparable to other DBMS systems
Changes made for speed improvement requires more work than MySQL as PostgreSQL focuses on compatibility
Many open source apps support MySQL, but may not support PostgreSQL
On performance metrics, it is slower than MySQL.

---

### **Applications of PostgreSQL**

**Financial Industry**

PostgreSQL is an ideal DBMS system for the financial industry. Moreover, It is fully ACID compliant which makes it an ideal choice for OLTP (Online Transaction Processing). It is also capable of performing database analytics. It can be integrated with mathematical software like Matlab and R.

**Manufacturing**

Nowadays, industrial manufacturers also using PostgreSQL to speed up their overall business process. It also helps them to optimize supply chain performance by using this open-source DBMS as storage backend. It allows companies to reduce the operation cost of their business.

---

### **Web technology and NoSQL**

If your website requires to deal with hundreds or even thousands request per second at that time, scalability is a surely big issue. Here, Postgre proves the best solution.

PostgreSQL works fine with all modern web frameworks like Django, Node.js,

Hibernate, PHP, etc. It also offers replication capabilities which allow to scale out as many database servers as you want.





