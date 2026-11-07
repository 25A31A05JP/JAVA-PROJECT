# 🚦 Smart City Navigation System

## 📌 Project Description
The **Smart City Navigation System** is a Java-based application designed to find the shortest routes between different cities using graph-based algorithms.

The system considers road distances and traffic weights to calculate the shortest path. When traffic conditions change, road weights can be updated dynamically, and the shortest route is recalculated.

This project compares classical and optimized shortest path algorithms based on execution time and space complexity.

## 🎯 Objectives
- To find the shortest path between two locations.
- To dynamically update road traffic weights.
- To implement and compare different shortest path algorithms.
- To improve route calculation efficiency.
- To analyze algorithm execution time and memory complexity.

## 🛠️ Technologies Used
- Programming Language: Java
- Data Structure: Graph
- Algorithms: Dijkstra's Algorithm, Optimized Dijkstra, Bellman-Ford
- IDE: Online Java Compiler
- Platform: GitHub

## 🧠 Algorithms Implemented

### 1. Classical Dijkstra's Algorithm
Finds the shortest path using a linear search to select the minimum-distance unvisited vertex.

Time Complexity: O(V² + E)

### 2. Optimized Dijkstra's Algorithm
Uses a Priority Queue to efficiently select the vertex with the minimum distance.

Time Complexity: O((V + E) log V)

### 3. Bellman-Ford Algorithm
Calculates shortest paths by repeatedly relaxing graph edges.

Time Complexity: O(V × E)

## ⚙️ Project Features
- City and road network representation using graphs.
- Shortest route calculation.
- Dynamic traffic weight updates.
- Classical and optimized algorithm comparison.
- Execution time measurement.
- Interactive menu-driven interface.

## 🏙️ Sample Cities
1. Rajahmundry
2. Kakinada
3. Vijayawada
4. Visakhapatnam
5. Eluru

## ▶️ How to Run the Project

1. Download or clone this repository.
2. Open the project in any Java IDE or online Java compiler.
3. Compile the Main.java file.
4. Run the program.
5. Select the required option from the menu.

## 📋 Menu Options
1. Display Cities
2. Find Shortest Route
3. Update Traffic
4. Compare Algorithms
5. Exit

## 📊 Expected Output

**Before Traffic Update:**

Shortest Distance: 140

Route: Rajahmundry → Kakinada → Visakhapatnam

**After Traffic Update:**

Shortest Distance: 185

Route: Rajahmundry → Vijayawada → Eluru → Visakhapatnam

## 📈 Algorithm Comparison

| Algorithm | Time Complexity |
|---|---|
| Classical Dijkstra | O(V² + E) |
| Optimized Dijkstra | O((V + E) log V) |
| Bellman-Ford | O(V × E) |

## 🔮 Future Enhancements
- Integration with real-time traffic APIs.
- Graphical user interface (GUI).
- Interactive city maps.
- GPS-based navigation.
- Traffic prediction using Machine Learning.

## 👩‍💻 Developer
**Palla Ushasri Venkata Sai**

## 📝 Conclusion
The Smart City Navigation System demonstrates how graph algorithms can be used to solve shortest path problems in city road networks. By comparing classical and optimized algorithms, the project highlights the importance of algorithm optimization in efficient route planning.

**Note:** Traffic updates in the current implementation are manually simulated. Real-time traffic API integration is planned as a future enhancement.
