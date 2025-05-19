# Mongoose_Relationships_Practice
# Mongoose_Relationships_Practice

This project contains practice examples for understanding different types of relationships using Mongoose and MongoDB.

## Relationship Types Covered

- **One-to-Many (Reference)** – e.g., Customers and Orders
- **One-to-One / Many-to-One** – e.g., Posts and Users
- **Embedded Subdocuments** – e.g., Users with embedded addresses

## Files

- `customer.js`: One-to-Many relationship (referenced orders in customer)
- `post.js`: Post referencing a User (like a foreign key)
- `user.js`: User document with embedded array of address subdocuments

## Tech Used

- Node.js
- MongoDB
- Mongoose ODM

## How to Run

1. Make sure MongoDB is running locally on default port.
2. Install dependencies:
   ```bash
   npm install mongoose

