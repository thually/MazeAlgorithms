# 🚀 **Maze Generation and Solving Algorithms!** 🧩

Click here 👇🏼 so see the animations, the code and a detailed breakdown of everything!  
ENG: <a href="https://colab.research.google.com/github/thually/MazeAlgorithms/blob/main/MazeAlgorithms_eng.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>  
ESP: <a href="https://colab.research.google.com/github/thually/MazeAlgorithms/blob/main/MazeAlgorithms_esp.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>  

Here's a quick overview of the project:

### 🔍 **Maze Generation with Kruskal's Algorithm**
Kruskal's algorithm is typically used to find a minimum spanning tree in a weighted graph, but I've repurposed it to create intricate mazes! Here’s a breakdown of the process:
1. **Initialize:** Create a list of all walls and a set for each cell.
2. **Random Selection:** Iterate through the walls in random order.
3. **Union-Find:** Remove walls that separate cells in different sets, merging the sets.

### 🔄 **Maze Solving with Dead-End Filling Algorithm**
To solve these mazes, I've implemented the Dead-End Filling algorithm. It’s a fascinating method that fills in all dead ends, leaving only the correct path from start to finish. The process includes:
1. **Identify Dead Ends:** Find all dead-end cells in the maze.
2. **Fill Paths:** Continuously fill in paths from dead ends to the first junction.

### 💡 **Visualizing the Algorithms**
I’ve also created animations to visualize both the maze generation and solving processes. These animations illustrate:
- How Kruskal's algorithm progressively removes walls to form the maze.
- How the Dead-End Filling algorithm systematically eliminates dead ends to reveal the correct path.

### 📊 **Technical Details**
- **Language:** Python
- **Libraries:** NetworkX for graph representation, Matplotlib for plotting and animations.
