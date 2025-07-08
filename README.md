# Sunspace Design Tool

This Grasshopper file helps identify optimal sunspace configurations for passive heating based on a given base case. It is intended for use in early-stage design and energy analysis of educational buildings and similar spaces.

---

## Requirements

- **Rhinoceros** 6 or later  
- **Ladybug Tools 1.6.0**  
  [Installation Guide](https://github.com/ladybug-tools/lbt-grasshopper/wiki/1.1-Windows-Installation-Steps)  
- **Colibri 2.0.0**  
  [Download from Food4Rhino](https://www.food4rhino.com/en/app/colibri)

---

## How to Use

1. Clone or download this repository, or simply download the `.gh` file.
2. Open Rhino and launch Grasshopper.
3. Drag and drop the `.gh` file onto the Grasshopper canvas.
4. Follow the input instructions inside the canvas:
   - Define climate conditions and seasonal parameters.
   - Specify base-case geometry, construction, and boundary conditions.
   - Select sunspace attributes for optimization.
   - Set ventilation requirements and thermal setpoints, then start the simulation.
5. Analyze the results by uploading the folder containing the `.csv` file and generated images to:  
   [http://tt-acm.github.io/DesignExplorer/](http://tt-acm.github.io/DesignExplorer/)
6. Use the “sort by” dropdown and slider tools in Design Explorer to explore optimal cases.

---

## Output

- **Heating and cooling loads** are reported in **kWh/m²**.
- **Sunspace solar gains** are reported in **kWh**.

---

## Contact

For questions or feedback, please contact:  
Atousa Momenaei — [amomenae@uoregon.edu](mailto:amomenae@uoregon.edu)  
Or submit an issue via the GitHub repository.
