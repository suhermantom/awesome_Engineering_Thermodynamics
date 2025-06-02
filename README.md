# Awesome Thermodynamics for Engineering 
This is my notes for all available Engineering Thermodynamics resources I have found. I'll keep updating it.

## How to Cite

If you use resources from this repository in your research, teaching, or other activities, please cite it as follows:

### APA Style
Suhermanto, M. (2025). Awesome Engineering Thermodynamics. GitHub. https://github.com/suhermantom/awesome_Engineering_Thermodynamics

### BibTeX
```bibtex
@misc{suhermanto2025awesome,
  author = {Suhermanto, Muhammad},
  title = {Awesome Engineering Thermodynamics},
  year = {2025},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/suhermantom/awesome_Engineering_Thermodynamics}}
}
```
## Contents

- [Python Libraries for Thermodynamics](#python-libraries-for-thermodynamics)
- [Educational Resources](#educational-resources)
- [Thermodynamic Cycles and Applications](#thermodynamic-cycles-and-applications)
- [Books and Learning Materials](#books-and-learning-materials)
- [Software and Tools](#software-and-tools)
- [Research and Development Resources](#research-and-development-resources)
- [Getting Started Resources](#getting-started-resources)
- [Community and Support](#community-and-support)

## Python Libraries for Thermodynamics

### Core Calculation Libraries

| Library | Description | Features | License | Installation | Documentation |
|---------|-------------|----------|---------|--------------|---------------|
| **kilojoule** | Convenience library for thermodynamic and heat transfer calculations with simplified syntax and improved output formatting | - Wrapper functions for multiple thermodynamic property sources<br>- Consistent syntax regardless of source<br>- Units integration via Pint library<br>- Variable names consistent with ME textbooks<br>- Prioritizes readability over speed | MIT | `pip install kilojoule` | [PyPI](https://pypi.org/project/kilojoule/)<br>[GitHub](https://github.com/johnfmaddox/kilojoule)<br>[Jupyter Notebooks](https://github.com/johnfmaddox/kilojoule-notebooks) |
| **PYroMat** | Flexible platform for working with thermodynamic data with an intuitive object interface | - Expanding collection of substances<br>- Intuitive object interface<br>- Customizable units<br>- Ideal gas properties<br>- Extensive documentation | GNU GPL v3.0 | `pip install pyromat` | [PyPI](https://pypi.org/project/PYroMat/)<br>[API Documentation](https://chmarti1.github.io/PYroMat/doc_api.html)<br>[User Handbook](https://chmarti1.github.io/PYroMat/) |
| **CoolProp** | Thermophysical property database and wrappers for various programming environments | - Properties for 122+ fluids<br>- Real fluid properties<br>- Mixture properties<br>- Humid air calculations<br>- Multiple language wrappers<br>- High accuracy | MIT | `pip install coolprop` | [Official Website](http://www.coolprop.org)<br>[Python Wrapper](http://www.coolprop.org/coolprop/wrappers/Python/index.html)<br>[GitHub](https://github.com/CoolProp/CoolProp) |
| **PyFluids** | Simple, full-featured, lightweight CoolProp wrapper for Python | - Easy-to-use interface<br>- All CoolProp features included<br>- Process calculations for fluids and humid air<br>- JSON/dict conversion<br>- User-friendly interface | MIT | `pip install pyfluids` | [PyPI](https://pypi.org/project/pyfluids/)<br>[GitHub](https://github.com/portyanikhin/PyFluids) |
| **Cantera** | Software for chemical kinetics, thermodynamics, and transport | - Ideal and non-ideal thermodynamic models<br>- Chemical equilibrium<br>- Reaction kinetics<br>- Transport properties | BSD | `pip install cantera`<br>`conda install -c cantera cantera` | [Website](https://cantera.org)<br>[Python Examples](https://cantera.org/examples/jupyter/index.html)<br>[Python Tutorial](https://cantera.org/tutorials/python-tutorial.html) |
| **Thermo** | Thermodynamics and phase equilibrium package | - Pure component and mixture properties<br>- Flash calculations<br>- CAPE-OPEN compliant<br>- 50+ equations of state | MIT | `pip install thermo` | [Documentation](https://thermo.readthedocs.io)<br>[GitHub Repository](https://github.com/CalebBell/thermo) |

### Specialized Thermodynamic Tools

| Library | Description | Features | License | Installation | Documentation |
|---------|-------------|----------|---------|--------------|---------------|
| **iapws** | Python implementation of IAPWS standards | - Water and steam properties<br>- Industrial formulation IAPWS-IF97<br>- High accuracy | MIT | `pip install iapws` | [Documentation](https://iapws.readthedocs.io)<br>[GitHub Repository](https://github.com/jjgomera/iapws) |
| **thermopy** | Python library for thermodynamics | - NASA polynomial data for thousands of compounds<br>- Thermodynamic properties as functions of temperature | BSD | `pip install thermopy` | [Documentation](https://pythonhosted.org/thermopy/)<br>[GitHub Repository](https://github.com/guillemborrell/thermopy) |
| **PyThermoDB** | Lightweight thermodynamic data access | - Quick access to essential thermodynamic data | MIT | `pip install PyThermoDB` | [GitHub Repository](https://github.com/sinagilassi/PyThermoDB) |
| **pyCycle** | Thermodynamic cycle modeling for propulsion | - Jet engine performance modeling<br>- Power and refrigeration cycles | Apache 2.0 | See GitHub | [GitHub Repository](https://github.com/OpenMDAO/pyCycle) |
| **thermopack** | Multi-component/phase thermodynamics library | - Cubic EoS<br>- SAFT models<br>- Phase equilibrium | GPL-3.0 | `pip install thermopack` | [PyPI Package](https://pypi.org/project/thermopack/)<br>[GitHub Repository](https://github.com/thermotools/thermopack) |
| **TESPy** | Thermal Engineering Systems in Python | - Modeling of power plants, heat pumps, refrigeration systems<br>- Design and off-design simulations | MIT | `pip install TESPy` | [Documentation](https://tespy.readthedocs.io)<br>[GitHub Repository](https://github.com/oemof/tespy) |

### Visualization and Animation Tools

| Library | Description | Features | License | Installation | Documentation |
|---------|-------------|----------|---------|--------------|---------------|
| **Manim** | Animation engine for creating mathematical animations | - Precise programmatic animations<br>- Mathematical visualization<br>- High-quality output<br>- Community maintained<br>- Jupyter integration | MIT (dual license) | `pip install manim` | [Official Website](https://www.manim.community/)<br>[GitHub](https://github.com/ManimCommunity/manim)<br>[Documentation](https://docs.manim.community/) |
| **Plotly** | Interactive data visualization library | - Interactive plots<br>- Publication-quality graphs<br>- Web-based visualization<br>- Dash framework for web apps<br>- Wide range of chart types | MIT | `pip install plotly` | [Official Website](https://plotly.com/python/)<br>[Fundamentals](https://plotly.com/python/plotly-fundamentals/) |

## Educational Resources

### Jupyter Notebooks and Tutorials

1. **kilojoule Notebooks**
   - Repository: [https://github.com/johnfmaddox/kilojoule-notebooks](https://github.com/johnfmaddox/kilojoule-notebooks)
   - Features: Interactive examples demonstrating kilojoule capabilities
   - Binder Integration: Available for immediate use without installation
   - Content: Thermodynamic calculations and heat transfer examples

2. **Computational Thermodynamics**
   - Repository: [https://github.com/kyleniemeyer/computational-thermo](https://github.com/kyleniemeyer/computational-thermo)
   - Online Book: [https://kyleniemeyer.github.io/computational-thermo/content/intro.html](https://kyleniemeyer.github.io/computational-thermo/content/intro.html)
   - Features: Collection of example problems in thermodynamics adapted from Klein & Nellis textbook
   - Content: Comprehensive thermodynamics concepts, solving problems with Python, Cantera and SciPy
   - Experience Level: Intermediate
   - Interactive Access: [Google Colab](https://colab.research.google.com/github/kyleniemeyer/computational-thermo/blob/master/colab-demo.ipynb) | [Binder](https://mybinder.org/v2/gh/kyleniemeyer/computational-thermo/master)

3. **PyTherm Applied Thermodynamics**
   - Repository: [https://github.com/iurisegtovich/PyTherm-applied-thermodynamics](https://github.com/iurisegtovich/PyTherm-applied-thermodynamics)
   - Project Website: [https://iurisegtovich.github.io/PyTherm-applied-thermodynamics/](https://iurisegtovich.github.io/PyTherm-applied-thermodynamics/)
   - Features: Educational notebooks for applied thermodynamics with the SciPy ecosystem
   - Content: 1st Law, problem-solving with Python, van der Waals EoS, jupyter-notebook basics
   - Experience Level: Beginner-Intermediate
   - Interactive Access: [Static Notebooks](http://nbviewer.jupyter.org/github/iurisegtovich/PyTherm-applied-thermodynamics/blob/master/index.ipynb) | [Interactive (Binder)](http://mybinder.org/repo/iurisegtovich/PyTherm-applied-thermodynamics)

4. **PYroMat Teaching Modules**
   - Paper: ["Problem-based Learning Module for Teaching Thermodynamic Cycle Analysis using PYroMat"](https://pdfs.semanticscholar.org/c170/87d22e1c272a0dc202608f8e504275c9a01f.pdf)
   - Features: Structured learning modules for thermodynamic cycles
   - Content: Rankine cycle analysis, efficiency calculations

5. **CoolProp Examples**
   - Documentation: [http://www.coolprop.org/coolprop/examples.html](http://www.coolprop.org/coolprop/examples.html)
   - Features: Code examples for various thermodynamic calculations
   - Content: Property lookups, cycle analysis, phase diagrams

6. **Thermodynamics Jupyter Notebooks**
   - Repository: [https://github.com/MatSciEd/Thermodynamics](https://github.com/MatSciEd/Thermodynamics)
   - Features: Collection illustrating fundamental concepts in materials thermodynamics
   - Content: Basic thermodynamic principles, phase diagrams, reactions
   - Experience Level: Beginner

7. **ThermoDRIL**
   - Repository: [https://github.com/c-hebert/thermoDRIL](https://github.com/c-hebert/thermoDRIL)
   - Features: Teaching thermodynamics at EPFL with interactive notebooks
   - Content: Various thermodynamic topics, MIT licensed
   - Experience Level: Intermediate

8. **Thermodynamic Cycles in Python**
   - Repository: [https://github.com/lucianafem/Thermodynamics-cycles-in-Python](https://github.com/lucianafem/Thermodynamics-cycles-in-Python)
   - Features: Implementation of thermodynamic cycles
   - Content: Carnot, Otto, Diesel, and Stirling cycles
   - Experience Level: Intermediate
   - Tutorial: [YouTube Tutorial](https://www.youtube.com/watch?v=w_AG78rqphM)

### Educational Websites and Courses

1. **Computational Thermodynamics**
   - Website: [https://kyleniemeyer.github.io/computational-thermo/](https://kyleniemeyer.github.io/computational-thermo/)
   - Features: Comprehensive guide to computational thermodynamics using Python
   - Content: Tutorials, examples, and theoretical background

2. **Thermodynamics Python Codes - NTU**
   - Website: [https://www.mmlab-ntu.tw/teaching](https://www.mmlab-ntu.tw/teaching)
   - Features: Educational Python codes for thermodynamics
   - Content: Gas expansion, enthalpy and entropy calculations, equation of state implementations

3. **AwesomeThermodynamics**
   - Repository: [https://github.com/iurisegtovich/AwesomeThermodynamics](https://github.com/iurisegtovich/AwesomeThermodynamics)
   - Features: Curated list of thermodynamics resources
   - Content: Educational materials, programming tools
   - Experience Level: All Levels

### Video Tutorials and Online Learning

1. **Thermodynamics in Python**
   - Creator: Dave's Space
   - Content: Tutorial series on Python simulation
   - Topics: Particle simulations, Maxwell-Boltzmann distribution
   - Experience Level: Beginner
   - Access: [Part 1](https://www.youtube.com/watch?v=idwnFn2jJ94) | [Part 2](https://www.youtube.com/watch?v=E29Itf-yxcQ)

2. **Basic CoolProp Tutorial**
   - Creator: Engineering Solutions
   - Content: Python thermodynamics using CoolProp
   - Topics: Fluid properties, state calculations
   - Experience Level: Beginner-Intermediate
   - Access: [YouTube Tutorial](https://www.youtube.com/watch?v=E6JHOJtWRGc)

3. **Thermodynamics Cycles in Python**
   - Creator: Luciana FEM
   - Content: Implementation and visualization of cycles
   - Topics: Carnot, Otto, Diesel, Stirling cycles
   - Experience Level: Intermediate
   - Access: [YouTube Tutorial](https://www.youtube.com/watch?v=w_AG78rqphM)

4. **Cantera-Based Steam Power Cycles**
   - Creator: Brandon Lane
   - Content: Python for steam power plant modeling
   - Topics: Superheating, cycle analysis
   - Experience Level: Intermediate-Advanced
   - Access: [YouTube Tutorial](https://www.youtube.com/watch?v=JQl4Tcb0pAY)

## Thermodynamic Cycles and Applications

### Power Cycles

1. **Rankine Cycle**
   - Description: Steam power cycle used in power plants
   - Key Components: Boiler, turbine, condenser, pump
   - Python Implementations:
     - [PyTherm Rankine Example](https://github.com/iurisegtovich/PyTherm-applied-thermodynamics/blob/master/notebooks/ideal-rankine.ipynb)
     - [CoolProp Rankine Cycle](https://github.com/CoolProp/CoolProp/blob/master/dev/scripts/examples/RankineCycle.py)
   - Educational Resources:
     - [Rankine Cycle Animation](https://www.youtube.com/watch?v=JQl4Tcb0pAY)
     - [Rankine Cycle Improvements](https://github.com/OpenMDAO/pyCycle/tree/master/example_cycles)

2. **Brayton Cycle**
   - Description: Gas turbine cycle used in jet engines and gas turbines
   - Key Components: Compressor, combustion chamber, turbine
   - Python Implementations:
     - [pyCycle Brayton Example](https://github.com/OpenMDAO/pyCycle/blob/master/example_cycles/brayton.py)
     - [FanaticalFighter/brayton-cycle](https://github.com/FanaticalFighter/brayton-cycle)
   - Educational Resources:
     - [Brayton Cycle Improvements](https://github.com/OpenMDAO/pyCycle/tree/master/example_cycles)

### Refrigeration Cycles

1. **Vapor Compression Refrigeration**
   - Description: Standard refrigeration cycle used in air conditioners and refrigerators
   - Key Components: Compressor, condenser, expansion valve, evaporator
   - Python Implementations:
     - [CoolProp Refrigeration Cycle](https://github.com/CoolProp/CoolProp/blob/master/dev/scripts/examples/RefrigerationCycle.py)
     - [TESPy Heat Pump Example](https://github.com/oemof/tespy/blob/master/examples/heat_pump/heat_pump_exergy.py)

2. **Absorption Refrigeration**
   - Description: Heat-driven refrigeration cycle without mechanical compression
   - Key Components: Generator, condenser, evaporator, absorber
   - Python Implementations:
     - [Absorption Cycle Model](https://github.com/DANA-Laboratory/CoolProp2Modelica)

### Heat Pumps

1. **Ground Source Heat Pumps**
   - Description: Heat pumps that use the ground as a heat source/sink
   - Python Implementations:
     - [TESPy Heat Pump Example](https://github.com/oemof/tespy/blob/master/examples/heat_pump/heat_pump.py)

2. **Air Source Heat Pumps**
   - Description: Heat pumps that use ambient air as a heat source/sink
   - Python Implementations:
     - [Heat Pump Simulation](https://github.com/oemof/tespy/blob/master/examples/heat_pump/heat_pump_design.py)

### Engine Cycles

1. **Otto Cycle**
   - Description: Spark ignition engine cycle used in gasoline engines
   - Key Components: Compression, combustion, expansion, exhaust
   - Python Implementations:
     - [Thermodynamics-cycles-in-Python](https://github.com/lucianafem/Thermodynamics-cycles-in-Python)
     - [Ideal-Gas-Simulator](https://github.com/donald-pinckney/Ideal-Gas-Simulator)

2. **Diesel Cycle**
   - Description: Compression ignition engine cycle used in diesel engines
   - Key Components: Compression, combustion, expansion, exhaust
   - Python Implementations:
     - [Thermodynamics-cycles-in-Python](https://github.com/lucianafem/Thermodynamics-cycles-in-Python)

3. **Dual Cycle**
   - Description: Combined Otto and Diesel cycle characteristics
   - Python Implementations:
     - [Thermodynamics-cycles-in-Python](https://github.com/lucianafem/Thermodynamics-cycles-in-Python)

## Books and Learning Materials

### Free/Open Access Textbooks

1. **Computational Thermodynamics**
   - Author: Kyle Niemeyer
   - Format: Online Book
   - URL: [https://kyleniemeyer.github.io/computational-thermo/content/intro.html](https://kyleniemeyer.github.io/computational-thermo/content/intro.html)
   - Description: Comprehensive guide to computational thermodynamics using Python

2. **Engineering Thermodynamics - A Graphical Approach**
   - Author: Israel Urieli
   - Format: Online Book
   - URL: [https://www.ohio.edu/mechanical/thermo/](https://www.ohio.edu/mechanical/thermo/)
   - Description: Graphical approach to thermodynamics with interactive simulations

### Reference Materials

1. **NIST Chemistry WebBook**
   - Format: Online Database
   - URL: [https://webbook.nist.gov/chemistry/](https://webbook.nist.gov/chemistry/)
   - Description: Comprehensive thermochemical data for chemical compounds

2. **Engineering Thermodynamics Solutions Manual**
   - Format: PDF
   - URL: Various GitHub repositories
   - Description: Solutions to common thermodynamics problems

### Problem Sets and Solutions

1. **SmartPhysicsThermodynamics**
   - Repository: [https://github.com/jaime5/SmartPhysicsThermodynamics](https://github.com/jaime5/SmartPhysicsThermodynamics)
   - Description: Solutions to thermodynamics problems with interactive Python code

2. **Thermodynamics Problem Sets**
   - Repository: [https://github.com/jeffgoms/Thermodynamics](https://github.com/jeffgoms/Thermodynamics)
   - Description: Collection of thermodynamics problems and solutions

## Software and Tools

### Simulation Software

1. **DWSIM**
   - Description: Open-source process simulator for Windows, Linux, macOS, Android and iOS
   - Repository: [https://github.com/DanWBR/dwsim](https://github.com/DanWBR/dwsim)
   - Features: Chemical process simulation, thermodynamic calculations, unit operations

2. **ClaRa**
   - Description: Simulation of Clausius-Rankine cycles
   - Repository: [https://github.com/TLK-Thermo/ClaRa](https://github.com/TLK-Thermo/ClaRa)
   - Features: Power plant components, dynamic behavior simulation

3. **Reaktoro**
   - Description: Framework for modeling chemically reactive systems
   - Repository: [https://github.com/reaktoro/reaktoro](https://github.com/reaktoro/reaktoro)
   - Features: Chemical equilibrium, chemical kinetics, or a combination of both

### Visualization Tools

1. **ThermoSolver**
   - Description: Thermodynamic property calculator and visualizer
   - Features: Property diagrams, cycle analysis

2. **ThermoBuild**
   - Description: Interactive tool using NASA Glenn thermodynamic database
   - Features: Property tables, data subsets for various programs

### Web Applications

1. **Checalc**
   - URL: [http://checalc.com/](http://checalc.com/)
   - Description: Online chemical engineering calculations

2. **PE 2000**
   - Description: Process engineering calculation tool
   - Features: Thermodynamic properties, unit operations

## Research and Development Resources

### Research Groups and Organizations

1. **ATOMS (Applied Thermodynamics and Molecular Simulation)**
   - Description: Research group at Federal University of Rio de Janeiro (UFRJ), Brazil
   - Focus: Classical and statistical thermodynamics, molecular simulation
   - Repository: [https://github.com/atoms-ufrj](https://github.com/atoms-ufrj)

2. **CERE (Center for Energy Resources Engineering)**
   - Institution: Technical University of Denmark
   - Focus: Chemicals in Gas Processing, thermodynamic modeling
   - Website: [https://www.cere.dtu.dk/](https://www.cere.dtu.dk/)

3. **NIST Thermodynamics Research Center**
   - Institution: National Institute of Standards and Technology
   - Focus: Thermophysical properties, reference data
   - Website: [https://www.nist.gov/trc](https://www.nist.gov/trc)

### Open Source Projects

1. **OpenCalphad**
   - Description: Thermodynamic software for calculation of multicomponent phase diagrams
   - Repository: [https://github.com/sundmanbo/opencalphad](https://github.com/sundmanbo/opencalphad)

2. **BurnMan**
   - Description: Library for modeling mantle thermodynamics and thermoelasticity
   - Repository: [https://github.com/geodynamics/burnman](https://github.com/geodynamics/burnman)

3. **OPM (Open Porous Media)**
   - Description: Initiative for open innovation and reproducible research for porous media processes
   - Repository: [https://github.com/OPM](https://github.com/OPM)
   - Features: Thermodynamic relations, capillary pressure curves

### Databases and Data Sources

1. **NIST RefProp**
   - Description: Reference fluid thermodynamic and transport properties database
   - Python Interface: [https://github.com/BenThelen/python-refprop](https://github.com/BenThelen/python-refprop)

2. **ThermoFun**
   - Description: Universal open-source client for thermodynamic properties
   - Repository: [https://bitbucket.org/thermomod/thermofun](https://bitbucket.org/thermomod/thermofun)

3. **NASA CEA (Chemical Equilibrium with Applications)**
   - Description: Calculates chemical equilibrium compositions and properties of complex mixtures
   - Website: [https://www.grc.nasa.gov/www/CEAWeb/](https://www.grc.nasa.gov/www/CEAWeb/)

## Getting Started Resources

### Installation Guides

1. **Python Environment Setup**
   ```bash
   # Core scientific packages
   pip install numpy scipy matplotlib jupyter
   
   # Thermodynamic packages
   pip install CoolProp thermo cantera iapws PYroMat
   ```

2. **Online Options (No Installation Required)**
   - [Google Colab](https://colab.research.google.com/) - Run notebooks in the cloud
   - [Binder](https://mybinder.org/) - Turn repositories into interactive notebooks
   - Many resources listed above have direct Binder links to run their examples

### Environment Setup

1. **IDE Recommendations**
   - Jupyter Notebook/Lab - Interactive documentation and visualization
   - VS Code with Python extension - Code completion and integrated terminal
   - Spyder (included in Anaconda) - MATLAB-like environment

2. **Anaconda Distribution**
   - Recommended for beginners: [https://www.anaconda.com/download/](https://www.anaconda.com/download/)
   - Includes Python, Jupyter notebooks, and many scientific packages

### Beginner Tutorials

1. **PyTherm Applied Thermodynamics**
   - Start with: [https://github.com/iurisegtovich/PyTherm-applied-thermodynamics/blob/master/notebooks/jupyter-notebook-basics.ipynb](https://github.com/iurisegtovich/PyTherm-applied-thermodynamics/blob/master/notebooks/jupyter-notebook-basics.ipynb)
   - Covers Jupyter notebook basics and thermodynamics fundamentals

2. **Basic CoolProp Tutorial**
   - Video: [https://www.youtube.com/watch?v=E6JHOJtWRGc](https://www.youtube.com/watch?v=E6JHOJtWRGc)
   - Covers fluid properties and state calculations

### Learning Paths

1. **Beginner Path**
   - Start with PyTherm tutorials
   - Practice basic property calculations using CoolProp or PYroMat
   - Implement simple thermodynamic cycles

2. **Intermediate Path**
   - Explore Computational Thermodynamics by Kyle Niemeyer
   - Implement more complex cycles with kilojoule or Cantera
   - Create visualizations with Plotly

3. **Advanced Path**
   - Contribute to open-source thermodynamics libraries
   - Implement custom equations of state
   - Create interactive simulations with Manim and Plotly

## Community and Support

### Forums and Discussion Groups

1. **Stack Overflow**
   - Tags: [thermodynamics](https://stackoverflow.com/questions/tagged/thermodynamics), [coolprop](https://stackoverflow.com/questions/tagged/coolprop), [cantera](https://stackoverflow.com/questions/tagged/cantera)

2. **Cantera Users' Group**
   - Google Group: [https://groups.google.com/g/cantera-users](https://groups.google.com/g/cantera-users)

3. **CoolProp Users**
   - GitHub Discussions: [https://github.com/CoolProp/CoolProp/discussions](https://github.com/CoolProp/CoolProp/discussions)

### Conferences and Events

1. **International Conference on Thermodynamics**
   - Annual conference on thermodynamics research and applications

2. **AIChE Annual Meeting**
   - Sessions on thermodynamics and process simulation

### Contributing Guidelines

1. **How to Contribute to This Repository**
   - Fork the repository
   - Add your resources following the established format
   - Submit a pull request with a clear description of your additions

2. **Contributing to Thermodynamics Libraries**
   - Most libraries welcome contributions through GitHub pull requests
   - Check individual repositories for specific contribution guidelines

## Recommended Implementation Approach

For developing comprehensive teaching materials for Thermodynamics using Python, we recommend the following approach:

1. **Core Calculation Engine**: Use kilojoule as the primary calculation library due to its:
   - Simplified syntax aligned with mechanical engineering textbooks
   - Integration with both CoolProp (for real fluids) and PYroMat (for ideal gases)
   - Built-in unit handling through Pint

2. **Visualization Strategy**:
   - Use Plotly for interactive property diagrams, cycle analysis, and real-time simulations
   - Implement Manim for creating explanatory animations of complex concepts
   - Develop Jupyter notebooks with interactive widgets for student exploration

3. **Delivery Format**:
   - Provide materials in both Jupyter Notebook (.ipynb) and Python script (.py) formats
   - Include implementation instructions for Visual Studio Code
   - Package materials in a zipped file for easy distribution
   - Include modification instructions for customization

4. **Topic Coverage**:
   - Specific volume, pressure, temperature relationships
   - Mechanical concepts of energy and work
   - Moving boundary work; electrical, spring and rotating shaft work
   - Thermodynamic cycles and efficiency calculations
   - Property diagrams and phase changes

## License

This awesome list is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

## Acknowledgments

This repository was inspired by:
- [Awesome Lists](https://github.com/sindresorhus/awesome)
- [AwesomeThermodynamics](https://github.com/iurisegtovich/AwesomeThermodynamics)
- [Awesome Math](https://github.com/rossant/awesome-math)
- [Awesome Courses](https://github.com/prakhar1989/awesome-courses)
