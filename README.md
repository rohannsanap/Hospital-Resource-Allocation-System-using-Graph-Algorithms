Hospital Resource Allocation System using Graph Algorithms (Java)

🚀 Overview

A CLI-based resource allocation system for hospital departments, using graph algorithms to optimize connections and resource management efficiently.

The system allows:

Adding hospital departments with bed and equipment data.

Adding connections between departments with allocation costs.

Computing Minimum Spanning Trees (MST) using Prim's and Kruskal's algorithms for optimal resource allocation.

Finding the cost-efficient path between any two departments.

Allocating resources across departments based on MST structure.

This project applies Object-Oriented Programming, Graph Theory, and Data Structures to a real-world scenario, strengthening algorithmic and system design skills.

⚙️ Features

✅ CLI-based management for interactive control.✅ Prim's and Kruskal's MST implementation for optimal connectivity.✅ Resource allocation tracking across departments.✅ Path cost calculation using graph traversal over MST.✅ Unit-test ready for algorithm correctness validation.✅ File-based I/O (optional extension) for data persistence.

🛠️ Technologies Used

Java 17

Collections API: ArrayList, HashSet, HashMap, PriorityQueue

Object-Oriented Design

Graph Algorithms (Prim's, Kruskal's)

CLI interaction

📈 Algorithms Implemented

Prim’s Algorithm: To construct MST dynamically by connecting the nearest department.

Kruskal’s Algorithm: (Optional extension) For MST using disjoint sets.

Dijkstra-like traversal over MST for finding minimum cost paths.

🖥️ Sample Usage

Add Departments

Enter your choice: 1
Enter department name: Cardiology
Enter number of beds: 20
Enter amount of equipment: 15
Department added: Cardiology

Add Edge

Enter your choice: 2
Select department 1: Cardiology
Select department 2: Neurology
Enter cost of allocation: 10
Edge added: Cardiology <-> Neurology

Compute MST

Enter your choice: 3
Prim's Minimum Spanning Tree:
Cardiology <-> Neurology (Cost: 10)
Neurology <-> Orthopedics (Cost: 5)

Allocate Resources

Enter your choice: 4
Allocating resources between departments based on MST...
Total Beds Allocated: 75
Total Equipment Allocated: 53

Find Cost of Path

Enter your choice: 5
Select source: Cardiology
Select destination: Orthopedics
Cost of path from Cardiology to Orthopedics: 15

🧪 Testing

Unit tests using JUnit can be implemented for:

MST correctness validation.

Path cost accuracy.

Edge case handling for disconnected graphs.

📂 Project Structure

HospitalResourceAllocator/
│
├── Department.java
├── Edge.java
├── HospitalResourceAllocator.java
├── README.md
└── test/
    └── HospitalResourceAllocatorTest.java

📝 Future Improvements

✅ Add graph visualization (Java Swing/JavaFX) for MST display.✅ Add file-based CSV/JSON data loading/saving for persistence.✅ Extend to dynamic resource reallocation based on usage changes.✅ Integrate JUnit test suites for CI pipelines.

💼 Relevance for Placements

This project demonstrates:✅ Strong grasp of Graph Algorithms and Data Structures.✅ Practical application of OOP in Java.✅ Problem-solving approach with real-world modeling.✅ System design thinking with algorithm efficiency considerations.



🤝 Contributing

Contributions, issue reports, and improvements are welcome! Fork the repository and open a pull request.

📜 License

This project is open-sourced under the MIT License.

📬 Contact

If you have any questions or want to discuss the project:

Email: [rohansanap6663@gmail.com]


“Connecting departments efficiently, managing resources smartly.”

