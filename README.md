# **Car Pathfinding Simulation**

This project is an interactive simulation of cars navigating through a grid-based map using basic pathfinding algorithms. It dynamically visualizes the movement of cars from their starting positions to designated parking spots, avoiding obstacles along the way. The simulation is built using **p5.js**, making it visually engaging and easy to run directly in a browser.

---

## **Features**

- **Dynamic Grid System**: 
  - The grid size adapts to the screen size for a responsive layout.
  - Each cell can represent different types of terrain, such as roads, trees, or buildings.

- **Car Navigation**: 
  - Multiple cars move towards their goals using turn-based logic.
  - Cars avoid obstacles like trees and buildings dynamically.

- **Customizable Visuals**: 
  - Supports visually distinct car colors and destination markers.
  - Terrain and car assets are rendered using image sprites for enhanced visual appeal.

- **Obstacle Management**:
  - Obstacles such as trees and buildings are randomly placed on the grid.
  - Cars intelligently navigate around obstacles to reach their destinations.

---

## **Technologies Used**

- **HTML5 & CSS3**: For structuring and styling the web page.
- **p5.js**: A JavaScript library for creative coding and interactive visualizations.
- **JavaScript**: Handles the simulation logic, including grid setup, pathfinding, and car movements.

---

## **Getting Started**

### **Prerequisites**
Ensure you have the following installed:
- A modern web browser (Google Chrome, Firefox, etc.)
- An internet connection (to load the p5.js library).

### **Running the Project**
1. Clone the repository:
   ```bash
   git clone git@github.com:Naveen-Singh8783/carPathFindingSimulation.git
   ```
2. Open the `index.html` file in a browser to start the simulation.

---

## **How It Works**

1. The grid initializes based on the screen size, adapting to create a responsive simulation space.
2. Each car is assigned a random starting point and a destination on the grid.
3. Cars move in turns, following a pathfinding algorithm to avoid obstacles and reach their destinations.
4. The grid updates dynamically, reflecting the movement of cars in real-time.

---

## **Future Enhancements**

- Implement advanced pathfinding algorithms (e.g., A* or Dijkstra's Algorithm).
- Add user interaction for placing obstacles and defining car paths.
- Include a scoring system to evaluate the efficiency of navigation.
- Optimize the simulation for larger grids and more cars.

---

## **Contributing**

Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss potential improvements.

---

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## **NOTE**
This is AI Assignment for the PG course Msc in computing(Major AI) from DCU by Naveen Singh.
Please go through the CarNavigation_AI_Assignment docs to know more about the world.
If you want to see the simulation working please visit the below world on ancient brain:
//https://ancientbrain.com/world.php?world=3753396853
