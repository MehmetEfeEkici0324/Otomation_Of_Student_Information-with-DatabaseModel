# 🎓 StudentNotes Management System

A desktop-based student record management application developed using C# and WinForms. This project implements a structured Data Access Layer (DAL) to interact with SQL databases via ADO.NET.



## 🚀 Key Features

* [cite_start]**Full CRUD Functionality:** Seamlessly add, update, delete, and list student records[cite: 1, 2, 3].
* [cite_start]**Database Integration:** Direct connectivity with SQL Server LocalDB using `SqlConnection` and `SqlCommand`[cite: 3].
* [cite_start]**Search & Filter:** Real-time search by Name and specific search by Student ID using LINQ-based filtering[cite: 1].
* [cite_start]**Data Integrity:** "Delete Confirmation" logic with dynamic UI buttons to prevent accidental record removal[cite: 1].
* [cite_start]**Auto-Population:** Selecting a record in the DataGridView automatically fills update forms for a smoother user experience[cite: 1].

## 🛠 Technical Architecture

* [cite_start]**Entity Layer (`Student.cs`):** Defines the core student data model[cite: 4].
* [cite_start]**Data Access Layer (`StudentDal.cs`):** Encapsulates all SQL logic (queries, connection management) away from the UI[cite: 3].
* [cite_start]**Presentation Layer (`Form1.cs`):** Handles event-driven UI logic and real-time grid updates[cite: 1].

## ⚙️ Requirements

* [cite_start].NET Framework 4.7.2 [cite: 2]
* Visual Studio 2017+
* [cite_start]SQL Server (LocalDB) with `Ogrenciler` database [cite: 3]
