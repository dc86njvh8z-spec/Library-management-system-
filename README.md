Library Management System 📖
A sophisticated Python-based application designed for inventory precision and automated financial tracking. This system is built with a focus on modular architecture, data integrity, and a user-centric experience.
🛠️ Structural Traits
Modular Package Architecture: Separates core business logic from the user interface to ensure maintainability.
Dictionary-Based Data Management: Utilizes nested dictionary structures for 



 complexity lookups of book records and student status.
Encapsulated Logic: All fine calculations and date-handling operations are isolated within a dedicated management module.
Persistent State Emulation: Designed to track real-time availability and issue dates across a continuous session.
✨ Key System Characters
1. Advanced Inventory Control
Dynamic tracking of book availability.
Automated status updates upon issuance and return.
2. Intelligent Issuance Tracking
Records student metadata (Name, Issue Date).
Calculates custom return windows based on user input.
3. Progressive Fine Engine
The system features a calculated penalty algorithm for overdue materials:
Phase 1 (Week 1): ₹10/day/book.
Phase 2 (Week 2): ₹20/day/book (Rate doubles).
Phase 3 (Week 3+): ₹60/day/book (Rate triples).
4. Interactive UX Design
Redesigned input/output statements for high clarity.
Menu-driven navigation powered by a resilient infinite loop.
📂 File Architecture
text
.
├── library_system/
│   ├── __init__.py
│   ├── manager.py     # Fine logic & record management
│   └── main.py        # User Interface & Input handling
└── README.md
Use code with caution.
📥 Installation & Usage
Clone the repository:
bash
git clone https://github.com
Use code with caution.
Execute the application:
bash
python library_system/main.py
Use code with caution.
📜 License
Distributed under the MIT License.
