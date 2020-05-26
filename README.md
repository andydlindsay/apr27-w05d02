# W5D2 - Database Design

### To Do
- [x] Primary Keys/Foreign Keys
- [x] Data Types
- [x] Relationship Types
- [x] Naming Conventions
- [x] Normalization
- [x] Design Concepts
- [x] Entity Relationship Diagrams
- [x] Breakout: Convert 2 Spreadsheets [20 mins]
- [x] Student Suggestion ERD(s)

### Primary Key
- Unique within the table
- Always use an autoincrementing integer
- The primary should not even be meta-data about the record
- Compound keys - 2 or more fields form a unique pairing
- Foreign key needs to be the same data type as the primary key

### Data Types
- Every field NEEDS to have a data type
- On insert does type comparison
- VARCHAR(255) CHAR(60)
- What do we do with phone numbers and postal codes?

### Relationship Types
- One-to-One: one record in the first table is related to only one record in the second table
- One-to-Many: one record in the first table is related to zero or more records in the second table
- Many-to-Many: zero or more records in the first table are related to zero or more records in the second table (junction table)

### Naming Conventions
- Always use snake_case
- Table names should be plural
- `id` for PK
- Append `_id` to the singular of the PK table name
  - users.id === user_id
- Please don't use spaces in your field/table names "users table"

### Design Concepts
- Required fields - based on the initial state of the record
- Default values - intelligent defaults (timestamps) NOW()
- Calculated fields are a big no-no - a field whose value can be calculated from one or more other fields (single source of truth)
- Try not to ever delete anything - use something like an `active` boolean instead
- Pull repeating values out to a separate table
- Consider using a `type` field

















# 
