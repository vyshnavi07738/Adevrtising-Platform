# Adevrtising-Platform
Campaign Dependency DAG CRUD

# 📢 Advertising Platform – Campaign Dependency DAG (CRUD)

## 👥 Team Members
-p.vyshnavi
- k.shanmukha lakshmi

---

## 🎯 Problem Statement
In modern advertising platforms, campaigns often depend on the execution of other campaigns. For example, an awareness campaign must run before a conversion campaign. Managing these dependencies manually can lead to errors such as circular dependencies or incorrect execution order.

This project aims to design and implement a system that efficiently manages advertising campaigns and their dependencies using a Directed Acyclic Graph (DAG).

---

## 💡 Objective
- To manage campaign data dynamically
- To represent dependencies using a graph structure
- To prevent cyclic dependencies
- To implement CRUD operations on campaigns and dependencies

---

## 🧠 Data Structure Used
- Graph (Adjacency List)
- Implemented using Linked Lists
- Uses dynamic memory allocation (`malloc`, `free`)

---

## ⚙️ Features
- Add Campaign (Create)
- Add Dependency
- Display Campaigns (Read)
- Display Dependencies
- Update Campaign
- Delete Campaign
- Delete Dependency
- Cycle Detection (Prevents circular dependencies)

---

## 🏗️ System Design
- Each campaign is represented as a node
- Dependencies are represented as directed edges
- The system ensures a Directed Acyclic Graph (DAG)

---

## 🔄 Algorithm Overview

### Add Campaign
1. Allocate memory using `malloc`
2. Insert into linked list

### Add Dependency
1. Validate campaign IDs
2. Check for cycle using DFS
3. Add edge if no cycle

### Delete Campaign
1. Remove campaign node
2. Remove all related dependencies
3. Free memory

### Cycle Detection
- Uses Depth First Search (DFS)
- Prevents adding edges that form a cycle

---

## 💻 Technologies Used
- Language: C
- Compiler: GCC
- Concepts:
  - Structures
  - Dynamic Memory Allocation
  - Linked Lists
  - Graph (DAG)

---

## ▶️ Compilation & Execution

gcc main.c -o project
./project

---

## 📊 Sample Output

--- Advertising Platform ---

1. Add Campaign  
2. Add Dependency  
3. Display Campaigns  
4. Display Dependencies  
5. Update Campaign  
6. Delete Campaign  
7. Delete Dependency  
8. Exit  

Enter choice: 1  
Enter Campaign ID: 1  
Enter Campaign Name: Launch Ad  

Campaign added successfully!

---

## 🎥 Demo Video
Google Drive Link: (Add your private link here)

Note: Keep the video private or restricted.

---

## 📂 Project Structure

project-name/
 ├── src/
 │    └── main.c
 ├── docs/
 │    └── project_report.pdf
 ├── ppt/
 │    └── presentation.pptx
 ├── README.md
 └── sample_output.txt

---

## 📈 Real-World Applications
- Digital Advertising Platforms
- Campaign Scheduling Systems
- Workflow Management Tools
- Task Dependency Systems

---

## 🔮 Future Enhancements
- Topological Sorting (execution order)
- GUI interface
- File handling (save/load data)
- Advanced filtering and search

---

## 📚 References
- Data Structures using C – Reema Thareja
- Introduction to Algorithms – Cormen
- GeeksforGeeks

---

## ✅ Conclusion
This project demonstrates the use of graph data structures to manage campaign dependencies efficiently while ensuring no cycles exist, making it suitable for real-world applications.
```
