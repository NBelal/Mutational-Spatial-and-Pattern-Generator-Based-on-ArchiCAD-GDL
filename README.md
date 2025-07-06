# Mutational Spatial and Pattern Generator Based on ArchiCAD Geographic Description Language(GDL)

## Overview
This project, **Mutational Spatial and Pattern Generator**, explores the creation of dynamic architectural patterns and spaces using ArchiCAD's GDL scripting language. It allows the generation and manipulation of spatial forms and patterns through parametric design principles, including variations in grids, shapes, and material properties.

The project is a continuation of previous work, with a focus on spatial exploration, pattern differentiation, and the application of architectural logic to generate complex forms. The methodology behind the project has been documented in several phases, as outlined in accompanying booklets.

This project was developed under the direction of Professor Vito Bertin, and many of the basic scripts were created within his framework. For more detailed information about the course, please refer to the [course website](http://www.vitobertin.hk/zju24).

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Development Methodology](#development-methodology)
- [Project Files](#project-files)
- [License](#license)

## Installation
To install and run this project:
1. Clone the repository:
   ```bash
   git clone https://github.com/Francis-Teng/Mutational-Spatial-and-Pattern-Generator.git
   ```
2. Open **ArchiCAD 27** or a later version.
3. Create a new **.pln** file within ArchiCAD.
4. Load the `.gsm` files included in the repository, using Archicad's Library Manager (File > Libraries and Objects > Library Manager).
5. Add the necessary file paths and libraries to ensure linked files are properly referenced.

## Usage
This project uses parametric objects such as shapes, grids, and spaces. It allows for the manipulation of spatial forms by adjusting parameters such as:
- **Grid spacing**
- **Shape sizes**
- **Material types**

### Steps to Use:
1. First, create a `.pln` file.
2. Once the `.pln` file is created, open the `.gsm` file.
3. **Note**: Parameters cannot be duplicated automatically, so you will need to add them manually if you plan to write your own `.gsm` files or copy the scripts into new files.
4. Ensure you add all the file paths and functions (e.g., those found in **functions.zip**) to the ArchiCAD library, so that any linked files are properly referenced.
5. For 2D patterns, switch to **stories** mode, and for 3D spaces, switch to **perspectives** mode.
6. Refer to the included PDF documentation or `.gsm` files for parameter details.

## Features
- **Customizable shapes and grids**: Generate patterns with varying shape types, from simple forms to complex combinations of grids and spatial units.
- **Parameter adjustments**: Modify aspects like height, color, material, and shape visibility using intuitive sliders.
- **Architectural exploration**: The generated patterns are linked to architectural principles and can be explored in 3D space.
  
## Development Methodology
The development process followed a logical approach based on architectural theory and iterative exploration. The steps included:
- **Base Creation**: Initial shapes such as cylinders and rectangles are used as the foundation for further explorations.
- **Shape Modifications**: Adjustments to height, scale, and rotation allow for dynamic form changes.
- **Grid Variations**: Grids were modified with random, stepped, or alternate variations to generate interesting patterns.
- **Exploration and Testing**: Continuous testing of shapes, materials, and visibility options to create diverse architectural outcomes.

More detailed background and explanations of the design logic can be found in the attached **booklet PDFs**.

## Project Files
- **base.gsm**: Base structure file for the background of the following objects.
- **shape.gsm**:Shape structure file for creating one unit.
- **grid.gsm**: Grid structure file for creating complex grid patterns.
  
- **example.pln**: ArchiCAD plan file with example configurations.
  
- **scripts.zip**: Contains GDL scripts for form generation. For those who want to create their own gsm files.
- **functions.zip**: Additional functions used in parametric modifications.

### Documentation Files:
- **[booklet1-construction.pdf](https://github.com/Francis-Teng/Mutational-Spatial-and-Pattern-Generator-Based-on-ArchiCAD-GDL/blob/main/booklet1-construction.pdf)**: Background and logic for the project's construction phases.
- **[booklet2-study-1.pdf](https://github.com/Francis-Teng/Mutational-Spatial-and-Pattern-Generator-Based-on-ArchiCAD-GDL/blob/main/booklet2-study-1.pdf)**, **[booklet3-study-2.pdf](https://github.com/Francis-Teng/Mutational-Spatial-and-Pattern-Generator-Based-on-ArchiCAD-GDL/blob/main/booklet3-study-2.pdf)**: In-depth exploration of spatial logic, testing, and architectural outcomes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

Let me know if you need any further changes!
