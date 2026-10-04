MongoDB Basic Practice Task

A beginner-friendly MongoDB project created as part of Global Data Structures & Algorithms in 21 Days – Week 12.

📌 Project Overview

This project demonstrates the basic concepts of MongoDB, a NoSQL database.

The project covers how to:

- Create a MongoDB database
- Create collections
- Insert documents
- Read/find documents
- Update documents
- Delete documents
- Work with MongoDB using basic queries

🛠️ Technologies Used

- MongoDB
- MongoDB Compass / mongosh
- Node.js (if used in the project)
- JavaScript

📂 Project Structure

MongoDB-Project/
│
├── README.md
├── package.json
├── package-lock.json
└── src/
    └── ...

«Project structure may vary depending on the implementation.»

🚀 MongoDB Basic Operations

1. Create / Use Database

use week12_mongodb

2. Create Collection

db.students.insertOne({
    name: "Sakthi",
    age: 23,
    course: "Full Stack Development"
})

3. Read Documents

db.students.find()

4. Find a Specific Document

db.students.find({
    name: "Sakthi"
})

5. Update a Document

db.students.updateOne(
    { name: "Sakthi" },
    { $set: { age: 24 } }
)

6. Delete a Document

db.students.deleteOne({
    name: "Sakthi"
})

🎯 Learning Outcomes

Through this project, I learned:

- Fundamentals of NoSQL databases
- MongoDB database and collection concepts
- CRUD operations
- MongoDB query syntax
- Working with documents
- Basic database management using MongoDB

📚 Week 12 Task

Course: Global Data Structures & Algorithms in 21 Days
Week: 12
Topic: MongoDB / Database

👨‍💻 Author

Sakthivel Arumugam

- GitHub: "Sakthivelan02" (https://github.com/Sakthivelan02/MongoDB-Basic-Practice-Task)

---

⭐ If you find this project useful, feel free to give it a star!
