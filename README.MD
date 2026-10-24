# MongoDB CRUD Operations Checkpoint

## Introduction

In this exercise, I practiced the basic CRUD operations in MongoDB using MongoDB Shell through MongoDB Compass. The goal was to learn how to create a database and collection, insert documents, retrieve information, update records, and delete documents.

## Objectives

- Create a database named `contact`.
- Create a collection named `contactlist`.
- Insert five contact documents.
- Display all contacts and find a specific contact using its ID.
- Find contacts based on age and name conditions.
- Update a contact's first name.
- Delete contacts younger than five years old.
- Display the final list of contacts.

## Work Completed

### 1. Database and Collection Creation

I created a database called `contact` and a collection called `contactlist` using MongoDB Shell.

### 2. Inserting Contacts

I inserted five contacts with their first name, last name, email address, and age. Some contacts did not have an email address, as specified in the exercise.

### 3. Retrieving Data

I used MongoDB's `find()` and `findOne()` methods to display all contacts and retrieve a single contact using its unique `_id`.

I also used query filters to find contacts older than 18 and searched for names containing `"ah"` while applying the age condition.

### 4. Updating a Contact

I updated the first name of the contact with the last name `Kefi` from `Seif` to `Anis` using the `updateOne()` method and the `$set` operator.

### 5. Deleting Contacts

I used `deleteMany()` with the `$lt` operator to delete contacts younger than five years old. This removed the contacts named Alex brown and Denzel Washington.

### 6. Final Results

After completing all the operations, three contacts remained in the collection:

- Ben Moris — age 26
- Kefi Anis — age 15
- Emilie brouge — age 40

## What I Learned

Through this exercise, I improved my understanding of MongoDB Shell and how to perform CRUD operations:

- **Create:** Creating databases and collections and inserting documents.
- **Read:** Retrieving documents with `find()` and `findOne()`.
- **Update:** Modifying existing documents with `updateOne()` and `$set`.
- **Delete:** Removing documents with `deleteMany()` and query operators.

I also learned how to use MongoDB query operators such as `$gt`, `$lt`, `$regex`, `$options`, and `$or` to filter data.

## Screenshots

I included screenshots of my MongoDB Shell commands and their outputs to demonstrate each step of the exercise, from inserting the contacts to displaying the final list.

## Conclusion

This checkpoint gave me practical experience working with MongoDB and helped me understand how CRUD operations are used to manage data in a database. I am now more comfortable writing basic MongoDB queries and manipulating documents using MongoDB Shell.

