# SentinelGraph

SentinelGraph is a modular cybersecurity analysis platform designed to map network attack surfaces, perform vulnerability discovery, and analyze infrastructure using graph algorithms and machine learning.

The project emphasizes transparency, performance, and understanding systems at a low level rather than relying solely on black-box libraries.

---

## 🚀 Features

### Current (Phase 1)
- TCP port scanning using raw sockets
- Host discovery
- Structured JSON scan output
- Graph-based network modeling
- BFS, DFS, Dijkstra, A*, and MST implementations
- SQLite-based scan persistence
- Modular architecture

### Planned (Phase 2+)
- Attack surface visualization
- Vulnerability correlation
- Web-based dashboard (FastAPI)
- Network traffic clustering (K-Means)
- Dockerized deployment
- CI/CD pipeline

---

## 🛠 Tech Stack

- **Language:** Python 3.11+
- **Networking:** socket, scapy
- **Graphs:** NetworkX
- **Backend API:** FastAPI
- **Database:** SQLite, SQLAlchemy
- **ML:** scikit-learn, NumPy, Pandas
- **Testing:** pytest
- **Formatting:** black, flake8
- **Deployment:** Docker (planned)

---

## ⚙️ Setup Instructions

### 1. Clone Repository

### 2. Create venv and activate
create: python3 -m venv venv

windows: source venv/Scripts/activate
linux: source venv/bin/activate

### 3. Install Dependencies
pip install -r requirements.txt
pip install e .

###After project created, to work on just activate, deactivate when finished 
