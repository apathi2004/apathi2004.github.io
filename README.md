# apathi2004.github.io
# Portfolio Project Outlines — Advaiith Pathi

## RISC-V Processor

Repo Link: https://github.com/apathi2004/RISC_V-Processor.git

### Quick Summary
Designed and implemented a custom RISC-V processor capable of executing core instruction sets and handling low-level hardware operations. The project focused on computer architecture concepts including instruction decoding, ALU operations, memory access, and pipelined execution.

---

### Key Features
- Custom RISC-V instruction implementation
- Arithmetic Logic Unit (ALU) design
- Register file and memory subsystem integration
- Instruction fetch, decode, execute, memory, and write-back stages
- Pipeline hazard handling and control logic
- Assembly-level testing and debugging

---

### Technologies Used

#### Languages
- Verilog / SystemVerilog
- C++
- Assembly

#### Tools & Platforms
- ModelSim / Vivado
- GTKWave
- GitHub

---

### System Architecture / Workflow
1. Fetch instruction from instruction memory
2. Decode opcode and control signals
3. Execute operation using ALU
4. Access memory if required
5. Write results back to registers

---

### Challenges & Solutions
- Managed pipeline hazards using forwarding and stall logic
- Optimized instruction execution timing
- Debugged low-level hardware behavior through waveform analysis

---

### What I Learned
- Processor architecture fundamentals
- Hardware description languages and digital logic
- Instruction-level execution and optimization
- Low-level debugging techniques

---

### Future Improvements
- Add branch prediction
- Implement cache memory
- Extend support for additional RISC-V instructions
- Improve pipelining efficiency

---

# Evil Wordle

Repo Link: 

### Quick Summary
Developed a terminal-based version of Evil Wordle where the game dynamically changes the possible secret word to maximize difficulty for the player. The project emphasized algorithm optimization, efficient data structures, and file processing.

---

### Key Features
- Dynamic “evil” word selection strategy
- Real-time filtering of valid word pools
- Optimized sorting algorithms for large datasets
- Fast game initialization and gameplay performance
- Interactive command-line interface

---

### Technologies Used

#### Languages
- C++
- Python

#### Algorithms & Concepts
- Quick Sort
- Fast Sort / Custom Sorting
- File I/O Optimization
- Hash Maps and Sets

---

### System Architecture / Workflow
1. Load dictionary file into memory
2. Player submits a guess
3. Program partitions remaining word possibilities
4. Largest valid word family is selected
5. Feedback is generated while maximizing ambiguity

---

### Challenges & Solutions
- Reduced lag caused by large dictionary processing
- Optimized sorting and filtering algorithms
- Balanced gameplay fairness with difficulty scaling

---

### What I Learned
- Algorithm optimization techniques
- Efficient file handling
- Time complexity analysis
- Game logic design and state management

---

### Future Improvements
- GUI implementation
- Multiplayer mode
- Adaptive difficulty system
- Online leaderboard integration

---

# Terminal-Based Snake Game

Repo Link: https://github.com/apathi2004/Snake.git

### Quick Summary
Built a terminal-based Snake game featuring real-time keyboard controls, collision detection, score tracking, and dynamic game logic. The project focused on event-driven programming and efficient rendering inside a command-line environment.

---

### Key Features
- Real-time movement controls
- Dynamic snake growth mechanics
- Collision detection system
- Score tracking and game-over conditions
- Lightweight terminal rendering

---

### Technologies Used

#### Languages
- C++
- Python

#### Concepts
- Game loops
- Data structures
- Event handling
- Coordinate-based movement systems

---

### System Architecture / Workflow
1. Initialize game board and snake position
2. Continuously update player input
3. Move snake based on direction
4. Detect food consumption and collisions
5. Update terminal display in real time

---

### Challenges & Solutions
- Managed smooth real-time updates in terminal environments
- Implemented efficient collision detection
- Optimized rendering to reduce flickering

---

### What I Learned
- Real-time game programming fundamentals
- State management
- Input handling and rendering loops
- Debugging interactive applications

---

### Future Improvements
- Add AI-controlled snake mode
- Implement power-ups and obstacles
- Create graphical UI version
- Add save/load functionality

---

# PDF Parser

### Quick Summary
Developed a PDF parsing tool capable of extracting and processing text data from PDF documents. The project focused on document analysis, text extraction, and efficient handling of structured and unstructured data.

---

### Key Features
- PDF text extraction
- Structured document parsing
- Keyword and pattern detection
- Multi-page document support
- Efficient file processing pipeline

---

### Technologies Used

#### Languages
- Python
- C++

#### Libraries & Tools
- PyPDF
- Regex
- OCR tools (if applicable)

---

### System Architecture / Workflow
1. Load PDF document
2. Extract raw text from pages
3. Process and clean extracted content
4. Detect patterns or keywords
5. Output structured data for analysis

---

### Challenges & Solutions
- Handled inconsistent PDF formatting
- Improved parsing accuracy through text preprocessing
- Optimized large-document processing speed

---

### What I Learned
- File parsing and document processing
- Text preprocessing techniques
- Pattern recognition using regular expressions
- Working with semi-structured data


Repo Link: https://github.com/apathi2004/Zombies.git

---

### Future Improvements
- Add OCR support for scanned PDFs
- Build searchable indexing system
- Export parsed data to JSON/CSV
- Add web-based upload interface


