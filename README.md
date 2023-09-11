<p align="center">
  <img src="logo.png">
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/nuiben/pathfinder?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/nuiben/pathfinder?style=for-the-badge">
  <img src="https://img.shields.io/github/issues/nuiben/pathfinder?color=blueviolet&style=for-the-badge">
  <img src="https://img.shields.io/github/forks/nuiben/pathfinder?color=teal&style=for-the-badge">
  <img src="https://img.shields.io/github/issues-pr/nuiben/pathfinder?color=tomato&style=for-the-badge">
</p>


Python Logistics Pathfinding Application

- Pathfinder uses a Greedy Algorithm because the routes in question are part of a closed circuit where pathing is never restricted. K-Nearest Neighbors (KNN) would be more optimal but is overkill for the scope of this particular solution.
- The csv data is stored in a Hashmamp data structure due to it's O(1) access time.
- Output creates standard reports as deliveries are executed by trucks:

![](figure_1.png)
