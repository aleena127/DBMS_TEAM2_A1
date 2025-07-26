# study-group-finder
Peer_Pods
A web application that helps students find and join study groups based on specific courses and subjects. Designed to foster collaborative learning with a simple, course-focused interface and real-time chat (optional).

🚀 Features

- 👥 Students can create or join study groups
- 📚 Browse groups by subject/course
- 🔐 User registration & login
- 🔍 Search and filter study groups
- 🧑‍💻 Group member limit (max 10 per group)
- 💬 Optional: Real-time group chat with Socket.io

🛠️ Tech Stack

| Layer      | Technology              |
|------------|--------------------------|
| Frontend   | HTML, CSS, JavaScript    |
| Backend    | Python (Flask)           |
| Database   | SQLite                   |
| Optional   | Socket.io (for real-time chat) |

 🧱 Database Schema

- `Users`: Stores user info
- `Courses`: List of subjects/courses
- `StudyGroups`: Group details linked to a course
- `GroupMembers`: Tracks group participation
- `ChatMessages` *(optional)*: Real-time chat data

> See `schema.sql` for full structure

📦 Installation

1. Clone the repository
```bash
https://github.com/aleena127/DBMS_TEAM2_A1.git
cd DBMS_TEAM2_A1
[PeerPods Presentation.pdf](https://github.com/user-attachments/files/21441321/PeerPods.Presentation.pdf)
