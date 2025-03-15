# Library Management System Case Study

## Problem Statement
Design an object-oriented library management system that manages books and other media, tracks borrowing and returns, handles member accounts, calculates fines, and generates reports.

## System Requirements
1. **Book and Media Management**:
   - Track different types of items (books, magazines, DVDs, etc.)
   - Categorize items by genre, author, subject
   - Maintain copies and availability status

2. **Member Management**:
   - Store member information
   - Track borrowing history
   - Manage membership types and privileges

3. **Borrowing Operations**:
   - Check-out and check-in processes
   - Reservations and renewals
   - Due date calculations

4. **Administrative Functions**:
   - Fine calculations for overdue items
   - Reporting on inventory and circulation
   - Acquisition of new items

5. **Search Functionality**:
   - Search by title, author, subject, ISBN
   - Advanced search options
   - Recommendations based on borrowing history

## Classes and Relationships

**Item-related Classes:**

**Member-related Classes:**

**Borrowing-related Classes:**

**Administrative Classes:**


## Key OOP Concepts to Identify

1. **Inheritance**: LibraryItem → Book/Magazine/DVD, Person → Member/Librarian
2. **Abstraction**: LibraryItem defines common interfaces
3. **Encapsulation**: Private member data with getter/setter methods
4. **Polymorphism**: Different item types have different borrowing rules
5. **Composition**: Library contains Catalog, BorrowRecord links Member and ItemCopy
6. **Aggregation**: Library contains LibraryItems
