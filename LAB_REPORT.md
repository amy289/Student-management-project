# Lab 6 — Short Lab Report

## Title
DOM, Events, Validation + localStorage — Student Management Frontend

## Objective
To manipulate the DOM, handle events, perform client-side CRUD, validate input, persist records with localStorage, and support searching, filtering and sorting.

## Tools
HTML5, CSS3, JavaScript and Browser DevTools.

## Implementation
A student form collects name, student ID, email, department, semester and optional phone. JavaScript validates required fields and email format, creates student objects with unique IDs, stores them in an array and saves the array as JSON in localStorage. The table is rendered dynamically without reloading. Edit and delete actions update the array. Search, department/semester filters, sorting, pagination, JSON import/export, record-count cards and a recent activity log are included.

## Result
A browser-based Student Management Frontend was created. Records can be added, viewed, edited, deleted, searched, filtered and sorted. Data remains after refreshing the same browser because it is stored in localStorage.

## Problems and Solutions
- Data disappears: check the localStorage key and JSON parsing; export a backup before clearing browser data.
- Duplicate IDs: generate unique IDs and check for duplicates.
- Edit changes the wrong row: locate records by their unique ID.
- Invalid email: validate format before saving.
- Table does not update: call the render function after each data change.

## Screenshots to add
1. Dashboard with multiple student records.
2. Add/Edit form and validation.
3. Search/filter/sort or student detail view.
4. JSON export/import or recent activity.
