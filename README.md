Parametric Environmental Optimization Toolkit

This repository contains a parametric model developed using Grasshopper 1.0.0007 within Rhino 7. The project focuses on optimizing architectural designs using climate, energy, and comfort analysis. By leveraging plugins like Ladybug Tools, Honeybee, and TTToolbox, the study explores Key Performance Indicators (KPIs) for energy efficiency, thermal comfort, visual comfort, and view quality.

🚀 Features

Parametric Modeling: Developed in Grasshopper for highly flexible and iterative design.
Climate Analysis: Conducted using Ladybug Tools with EPW climate files.
Energy & Comfort Simulations: Performed with EnergyPlus and Radiance via Honeybee.
Key Performance Indicators (KPIs): Optimization based on energy use, thermal comfort, visual comfort, and view quality.
TTToolbox Integration: Comprehensive analysis of design variables to support decision-making.
🛠 Tools and Technologies

Grasshopper: Version 1.0.0007 (within Rhino 7)
Ladybug Tools: Version 1.8.0 (Climate analysis, view calculation)
Honeybee: Simulations for energy, comfort, and performance optimization
EnergyPlus: Energy consumption and thermal comfort evaluation
Radiance: Visual comfort analysis
TTToolbox: Simulation of design variables
📁 Repository Structure


🌍 Climate Analysis

Using the EPW climate file, the model incorporates site-specific environmental conditions to enhance design outcomes. Key factors analyzed include:

Solar radiation
Wind patterns
Temperature fluctuations
📊 Simulations and Optimization

Energy & Thermal Comfort
EnergyPlus evaluates energy consumption and thermal comfort for all parametric variations.
Visual Comfort
Radiance assesses daylight quality and visual comfort levels.
View Quality
Ladybug Tools calculates unobstructed view quality using advanced algorithms.

💡 Getting Started

Prerequisites
Rhino 7: Ensure Rhino 7 is installed.
Grasshopper Plugins:
Ladybug Tools (v1.8.0)
Honeybee
TTToolbox
Installation
Clone this repository:
git clone https://github.com/granludo/seccond-skin-parametric.git

Open the Grasshopper definitions in Rhino 7.
Load the required plugins and ensure all dependencies are installed.
🎯 How to Use

Load the parametric model in Grasshopper.
Input the desired EPW climate file.
Define design variables and objectives for optimization.
Run the simulation and analyze results in the /Results/ folder.
📝 Citation

If you use this project for research or publications, please cite:

Seyedesara Yazdi, Marc Alier. "Parametric Environmental Optimization Toolkit." GitHub repository, 2024. https://github.com/yourusername/parametric-environmental-optimization

Yazdi Bahri, Seyedehsara, Marc Alier Forment, and Albert Sanchez Riera. "Thermal comfort improvement by applying parametric design panel as a second skin on the facade in building refurbishment in moderate climate." In Ninth International Conference on Technological Ecosystems for Enhancing Multiculturality (TEEM'21), pp. 763-767. 2021.

🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.

📧 Contact Sara  Yazdi <seyedehsara.yazdibahri@upc.edu>


You can copy and paste this directly into your README.md. Let me know if you want me to fix anything else!
