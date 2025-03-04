﻿# Typescript-Task
## 📝 TypeScript User & Admin Filter

This project provides a TypeScript function to filter users and admins based on specific criteria while ensuring type safety.

## 📌 Task Description

Fix the typings for the filterPersons function so that:

It returns User[] when personType is 'user'.

It returns Admin[] when personType is 'admin'.


Ensure the function only accepts relevant filtering criteria:

If personType is 'user', allow filtering by User properties (excluding type).

If personType is 'admin', allow filtering by Admin properties (excluding type).



## 🔧 Example Usage

const usersOfAge23 = filterPersons(persons, 'user', { age: 23 });
const adminsOfAge23 = filterPersons(persons, 'admin', { age: 23 });

## ✅ Expected Output

Users of age 23:
 - Kate Müller, 23, Astronaut
 - Wilson, 23, Ball

Admins of age 23:
 - Agent Smith, 23, Anti-virus engineer

This ensures type safety and correct filtering behavior. 🚀

