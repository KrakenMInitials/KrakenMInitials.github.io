# Work Experience

## 💼 DormMe Application, Internship  
*Apr 2025 – Present*  
**Tech:** Vertex AI, Google ADK, Firebase, Typesense, Google Maps/Places API, Python, Postman, Pydantic

- Implemented vector search using Vertex AI embeddings in Firebase Functions to replace slow, GPT-based profile matching, improving scalability as user count exceeded 200  
- Tested secured Google Cloud Run functions using Postman, Identity Tokens, and service accounts to debug and verify backend behavior during development  
- Architected AI agents using Google ADK and Vertex AI Engine to support natural language queries about housing listings and roommate discovery via structured tools  
- Built a property-specific assistant agent using ADK that answers questions about a housing listing and its neighborhood using session state and external APIs  
- Integrated Google Places API via the `googlemaps` Python SDK to retrieve nearby amenities, businesses, and schools for location-based responses  
- Bootstrapped agent session state from only `user_id` and `housing_id`, querying Typesense to populate housing data and simplify frontend integration  
- Introduced Pydantic models to replace raw `dict` access when parsing Typesense documents, improving code structure and type safety  
- Implemented schema validation to ensure Pydantic models stayed in sync with remote Typesense schemas, preventing field mismatches and reducing future integration risk  
- Structured agent outputs for UI parsing by returning either conversational summaries or structured JSON depending on tool response context


# Research Experience

### Using Large Language Models to Analyze Memory | Dr. James Anthony
Research Assistant | Jan 2025 - Present 
- Contributed to codebase that produced graphs and visualizations using Pandas, Numpy, and Matplotlib to 
analyze spreadsheet-based data 
- Produced heatmap visualizations of semantic similarities of each of 200 subject responses against the official 
screenplay utilizing Google’s Universal Sentence Encoder embeddings, revealing potential biases in memory 
recall 
- Optimized data loading and processing in Pandas by caching spreadsheets, reducing repeated file reads and 
cutting total runtime by ~85% (15 minutes → 3 minutes) 
- Designed a quantifiable metric of accuracy for Large Language Model predictions against human labels, 
enabling objective accuracy evaluations and reproducible analysis

# My Projects

## 💻 Networking Systems Projects

### 🚀 P2P File Sharing System
[GitHub Repo](https://github.com/KrakenMInitials/CSC364_Assignment4)  
**Tech:** Python, TCP Sockets, File I/O, Protocol Design  
Built a peer-to-peer file sharing system over TCP where peers advertise, request, and transfer files using a custom protocol.  
✔️ Custom message types (Offer, Request, Transfer, Ack)  
✔️ Central tracker server for peer discovery  
✔️ Chunked file transfer with retransmissions and checksum-based file validation

---

### 🌐 TCP Congestion Control Simulator over UDP
[GitHub Repo](https://github.com/KrakenMInitials/CSC364_Assignment3)  
**Tech:** Python, UDP Sockets, RTT Simulation, Data Visualization  
Simulated TCP-like file transfer over UDP to explore congestion control mechanisms.  
✔️ Implements Slow Start, Congestion Avoidance, and Fast Retransmit  
✔️ Simulates packet loss and visualizes cwnd vs. RTT under different network conditions  
✔️ Custom packet format with checksums, ACKs, and timeouts

---



## 💾 Filesystem Projects

### 📂 TinyFS (ZFS-inspired Educational Filesystem)
[GitHub Repo](https://github.com/KrakenMInitials/tinyfs)  
[Watch Demo Video (Google Drive)](https://drive.google.com/file/d/1rVkdr50zKSI2eMQdF26UdKRi6SBIcHcW/view?usp=sharing)

**Tech:** C, File I/O, Bitmap Allocation, CRC32, Copy-on-Write  
Implemented a toy block-based filesystem to explore core filesystem concepts and integrity mechanisms.  
✔️ Flat namespace with root directory inode (no subdirectories)  
✔️ Inodes with two direct pointers + one indirect pointer  
✔️ Copy-on-write writes with CRC32 checksums on superblock, inodes, and data blocks  
✔️ Unified error codes for FS + disk ops (`errors.h`)  
✔️ Demo program showcasing mounting, read/write, permissions, rename, and directory listing

---

<br><br><br><br>
## Other Projects
### FoodFlow ([UI](https://www.figma.com/proto/kFwNKAbGFcDzhaic6yJtA1/NewFigmaHackathonW24?t=lJEYJWBrMNwQNvBr-1&node-id=0-940&starting-point-node-id=0%3A888)) ([backend](https://github.com/suesuee/FoodFlow))
Figma, Spoonacular API, Tableau, Python                                            ‎                            | Jan 24, 2025 - Present  
-	a UI design purposed during PolyHacks 2025 to assist the Cal Poly food pantry in tracking stock levels, recommending recipes based on availability, and queue time monitoring
•	60-hour hackathon entry for PolyHacks 2025, won “Best Demo” 
•	Contributed heavily to UI design through Fall Q24’ Figma workshop experience
•	Learned that working towards a common goal with the right people boosts my productivity significantly


### 2D Platformer ([game](https://editor.p5js.org/KrakenM/full/Q5i-It2eU))([code](https://editor.p5js.org/KrakenM/sketches/Q5i-It2eU))               
p5js, JSON                                           | Oct 18 – Dec 10, 2023                    
Created a game with an interactive menu and two levels in a team of 5  | Oct 19 - Dec 15, 2023                    
- Worked on movement, collision and hitbox mechanics based heavily on complex geometry, coordinates and ‘forces’, essentially replicating a physics engine from prior knowledge of game design and physics
     - Player movement moves the camera and environment along x-cord; player model kept stationary
     - Jumping/gravity modifies player model’s y-cord
     - Resulted in smooth controls and unique camera follow
- Utilized object-oriented programming in creating of platforms and game map for infinite scaling potential 
- Employed a feedback loop of new content>discovering bugs>solving bugs>implementing feedback.  

### Emulated UNIX file system in C 
C, VS Code, Valgrind, GDB                   | Oct 1 - Oct 8, 2024                                                                  
- Implemented single level file directory management with mkdir, touch, cd, ls commands
- String argument parsing/inodes and inode list/memory allocations/binary parsing/file access/file permissions    
- Read/wrote inodes and file information on a binary level in C
- Learned to solve memory leaks using Valgrind and debugging with GDB

