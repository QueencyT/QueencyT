# 👋 Hi, my name is Queency Tan! 

I'm a Computer Engineering student at the University of California, Irvine, interested in software engineering, algorithms, systems programming, and building practical applications.

I enjoy developing projects that combine problem-solving with software architecture, from implementing data structures and algorithms to building graphical applications and multiplayer systems.

---

## Featured Projects

### 🃏 Anteater Poker | C, GTK3, TCP Sockets
**GUI Development · Networking · Multiplayer Systems · AI-controlled opponents**

A multiplayer Texas Hold'em poker game developed in C, featuring:
- **Multiplayer Networking:** Implements TCP socket-based communication, allowing multiple players to connect to a centralized game server and participate in multiplayer poker sessions.
- **AI-Controlled Opponents:** Uses Monte Carlo simulations to estimate poker-hand strength and guide AI betting decisions based on simulated outcomes.
- **GTK3 Graphical User Interface:** Provides an interactive game lobby for joining and organizing multiplayer sessions, along with a responsive gameplay interface displaying player information, cards, betting controls, chip counts, and dynamically updated game states.
- **Real-Time Game Synchronization:** Coordinates player actions, betting decisions, and game-state updates between the server and connected clients to maintain consistent multiplayer gameplay.

### [🔗 View Repository →](https://github.com/QueencyT/anteater-poker)

<br>

### 🗄️ SQL Database Engine | C++
**Data Structures · Parsing · Database Systems**

A database management system developed from scratch in C++ featuring: 
- **SQL-Like Query Processing:** Supports table creation, record insertion, data retrieval, and conditional selection.
- **Vector of B+ Tree-backed multimaps:** Used to provide efficient indexed lookups and range-based queries.
- **Persistent Binary Storage:** Stores table records in binary files for retrieval across program executions.
- **Error Handling:** Validates commands and reports invalid SQL syntax or table-related errors.
- **Interactive Console Interface:** Allows users to execute supported database commands and access usage instructions.

### [🔗 View Repository →](https://github.com/QueencyT/sql-database-engine)

<br>

### 🐍 Snake Solver | x86 Assembly
**Graph Algorithms · Pathfinding · Simulation**

An autonomous Snake solver developed in x86 Assembly to solve the game in as few moves as possible while avoiding collisions and self-trapping featuring: 
- **Dijkstra's algorithm** with dynamic graph updates to calculate shortest paths while accounting for the snake's changing body positions.
- **Custom Simulation-based path validation algorithm** that predicts future body configurations and verifies tail reachability to preserve movement options.
- **Multi-level waypoint-based pathfinding** to explore alternative routes when the shortest path is unsafe, with tail-following as a fallback when no valid route to an apple is found.

### [🔗 View Repository →](https://github.com/QueencyT/snake-solver)

<br>

### ♟️ Anteater Chess | C, GTK4, Cairo

**Artificial Intelligence · Game Development · GUI Design**

A custom chess game developed in C, featuring: 

- **Chess AI** with three difficulty levels, incorporating heuristic board evaluation and minimax search with alpha-beta pruning to optimize move selection.
- **Interactive GTK4 graphical interface** using Cairo for board rendering, piece movement, legal-move highlighting, player timers, move history, and pawn promotion dialogs.
- **Custom game mechanics and move validation** for traditional chess rules and Anteater-specific captures, including special moves such as castling and en passant.
- **Integrated game-state management** with stack-based undo functionality, move logging, and automatic detection of game-ending conditions.

### [🔗 View Repository →](https://github.com/QueencyT/anteater-chess)

<br>

### 📈 Graphing Calculator | C++, SFML

**Data Structures · Expression Parsing · GUI Development**

An interactive graphing calculator developed in C++, featuring a graphical interface built with SFML, mathematical expression parsing, postfix evaluation, and real-time function visualization featuring: 

- **Mathematical Expression Parsing:** Implements the Shunting Yard algorithm to convert infix mathematical expressions into postfix notation, correctly handling operator precedence and parentheses.
- **Custom Data Structures:** Uses linked-list-based stacks and queues to manage tokens, evaluate expressions, and support the parsing pipeline.
- **Interactive SFML Graphical Interface:** Provides a coordinate plane for plotting mathematical functions, along with an expression input interface and interactive graph controls. 
- **Function Evaluation and Visualization:** Evaluates postfix expressions using Reverse Polish Notation (RPN) and generates graphical plots of mathematical functions across coordinate ranges.

### [🔗 View Repository →](https://github.com/QueencyT/graphing-calculator)

--- 

## Data Structures & Algorithms

A collection of data structures implemented <ins>**from scratch in C++**</ins>, focusing on efficient data organization, searching, insertion, deletion, and memory management.

<br>

| Data Structure | Key Features | Repository |
|---|---|---|
| **B+ Tree / Map / Multimap** | Dynamic insertion/deletion, linked-leaf traversal | [View Repository →](https://github.com/QueencyT/b-plus-tree) |
| **B-Tree** | Multi-key nodes, tree rebalancing, efficient searching | [View Repository →](https://github.com/QueencyT/b-tree) |
| **Binary Search Tree** | Recursive operations, traversal, deep copying, memory management | [View Repository →](https://github.com/QueencyT/binary-search-tree) |
| **AVL Tree** | Self-balancing rotations, insertion, deletion, and traversal | [View Repository →](https://github.com/QueencyT/avl-tree) |
| **Hash Table** | Linear probing, double hashing, AVL-tree-based separate chaining | [View Repository →](https://github.com/QueencyT/hash-table-implementations) |
| **Heap & Priority Queue** | Template-based max heap, priority scheduling, FIFO tie-breaking | [View Repository →](https://github.com/QueencyT/heap-priority-queue) 
| **Stack & Queue** | Singly linked list implementation, LIFO/FIFO operations, custom iterators, templates, dynamic memory management | [View Repository →](https://github.com/QueencyT/stack-and-queue) |


---

## Technical Skills

| Category | Technologies |
|---|---|
| Programming Languages | C, C++, Python, Java, x86 Assembly, RISC-V Assembly, SQL, Verilog |
| GUI Development | GTK3, GTK4, Cairo, SFML |
| Development Tools | Git, GitHub, GDB, Bash, VS Code |
| Environments | Linux, Windows, WSL |
| Libraries | scikit-learn, Matplotlib |
| Core Concepts | Data Structures, Algorithms, OOP, Networking, Database Systems |

## Explore My Work

Browse all my repositories on [GitHub](https://github.com/QueencyT?tab=repositories).
