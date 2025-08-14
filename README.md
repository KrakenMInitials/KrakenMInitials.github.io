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
-	Study participants were shown non-linear movie Memento and asked to freely recall information, responses were manually transcribed by research assistants into an excel sheet with a corresponding scene number being recalled, results were analyzed into various graphs and compared against ideal templates to see whether semantic, chronological, causal, or temporal memory recall was strongest
-	Familiarized self with completed research and theories in tensors, sentence encoders, and LLMS    
-	Contributed to research-level codebase working with matrixes and plots in Numpy and Matplotlib libraries
    -	Grouped sentences in a participant’s response according to provided scene numbers from sheet through Pandas and produced sentence embeddings of each group and the movie script (grouped by scene number) using TensorFlow
    -	Applied cosine similarities to the sentence embeddings of the two to calculate how accurate the manually tagged scene numbers are. 

-	Working towards replacing manually tagging responses to scene numbers with using cosine similarities on sentence embeddings of a sentence of a participant’s response and the script’s sentence embeddings to find which scene number the participant is most likely recalling, the strongest r-value match between the two embeddings will indicate the most-likely recalled scene number.


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
C, VS Code, Valgrind, GDB                   | Oct 1 - Oct 21, 2024                                                                  
- Implemented single level file directory management with mkdir, touch, cd, ls commands
- String argument parsing/inodes and inode list/memory allocations/binary parsing/file access/file permissions    
- Read/wrote inodes and file information on a binary level in C
- Learned to solve memory leaks using Valgrind and debugging with GDB

### Downloader 
C | 31 Oct - Nov 10, 2024
- Replicated UNIX curl command to curl from a .txt file with multiple items to download
- Forked processes to handle x downloads at a time

### Assembly Interrupt/Exception Handling
RISC-V, RARS                                     |  May 29 - June 6, 2024
- Used polling to code read and print for strings and integers connected to an MMIO Simulator in RARS
- ASCII read from input and saved to memory or read from memory and printed to output
- Coded an assembly Interrupt Service Routine that mimicked the trap process in interrupt handling

### Database query tool
C, VS Code, Valgrind, GDB
- Parsed and operated a text file containing operations on a .csv file containing real demographics data from https://corgis-edu.github.io/corgis/ 
- Operations: display/filter-state/filter/population-total/population/percent
- C structures/malloc/realloc/free/s

### Little World Simulation 
Java, IntelliJ                                               | June - July, 2024 
- Dijkstra & A* Pathing Strategies/lambda functions and functional interfaces/code refactoring 

### Graph Implementation with Hash Functions                                                                                     
Git, Python, VS Code                          | Mar 7 - Mar 18, 2024 
- Vertex and edge creations and deletions/DFS Graph traversal/Hash table/linear probing hash collision 
resolution/graph representation & hash-table theory 

### Huffman Coding                                                                                                                               
Git, Python, VS Code                         | Feb 28 – Mar 7, 2024                                     
- Used a frequency Dictionary and priority queues to 
construct a Huffman Tree from a string input 
- Compressed the string using Huffman theory

### Big Number Calculator 
Java, IntelliJ                                        | Apr 15 - Apr 22, 2024 
- Used linked lists to bypass 32bit integer 
representation
- Programmed a calculator with addition, 
multiplication, and exponentiation functions 
- Included text file reading and parsing functions 
from which numbers were calculated 

