# SQL Projects

This repository contains beginner-friendly SQL projects that demonstrate database design, relationships, and querying concepts.

## 📚 Projects

### 1. Albums, Tracks, and Artists
- **Concepts Demonstrated**: `JOIN`, `SELECT`, `ORDER BY`
- **Description**:  
  A music database that stores information about artists, their albums, and the tracks in each album.  
  Sample queries include:
  - Listing all tracks by a given artist
  - Sorting tracks by length or release date
  - Using `JOIN` to combine information across tables

📂 [View Project](https://github.com/Darkmatter126ms/Introduction-to-SQL/blob/main/Music.sql)

---

### 2. Courses, Participants, and Status (Junction Table)
- **Concepts Demonstrated**: Junction tables, many-to-many relationships
- **Description**:  
  A training/course management database where:
  - Each participant can register for multiple courses
  - Each course can have multiple participants
  - The `Member` table serves as a **junction table** connecting participants and courses, storing enrollment details like registration date or completion status
 
📂 [View Project](https://github.com/Darkmatter126ms/Introduction-to-SQL/blob/main/Course%20Management.sql)
