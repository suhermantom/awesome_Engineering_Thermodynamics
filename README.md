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

Excellent. I will enhance your curated GitHub repository on Thermodynamics for Engineering by incorporating the most relevant and current resources available online. This includes classical engineering thermodynamics and computational modeling, with additions spanning academic papers, software tools, MOOCs, visual resources, and interactive simulations—all in English and formatted to fit GitHub-flavored Markdown.

I'll let you know once the enriched Markdown file is ready for your review.



## Details on Python Libraries and Tools for Thermodynamic Modeling

* **CoolProp** – An open-source thermophysical property database (with wrappers for Python and other languages) providing high-accuracy fluid and humid air properties for pure and mixed substances. It offers similar functionality to NIST REFPROP and is widely used in refrigeration and power cycle analysis.
* **Thermo (ChE**⸺**DL)** – A Python library by Caleb Bell designed for retrieving chemical constants and calculating thermodynamic and transport properties of pure compounds and mixtures. *Thermo* features multiple models (equations of state, activity models, etc.) and supports phase equilibrium calculations, all with an easy-to-use interface.
* **PYroMat** – A flexible Python package for working with thermodynamic properties of various substances. PYroMat provides an expanding collection of fluids with an intuitive object-oriented interface for property evaluation. It is open-source (GPLv3) and has been peer-reviewed (JOSS 2023) for accuracy near phase transitions and the critical point.
* **pyCALPHAD** – An open-source Python library for Computational Thermodynamics using the CALPHAD method. It allows designing thermodynamic models, reading thermodynamic databases, and computing multi-component phase diagrams by solving Gibbs energy minimization problems. *pyCALPHAD* is ideal for materials phase equilibrium studies and supports symbolic manipulation of models for flexible model development.
* **ThermoPack** – A thermodynamic model library developed at SINTEF/NTNU, written in Fortran with a Python API. ThermoPack implements a broad range of equations of state for multi-component, multi-phase systems and provides fast computations of thermophysical properties. It is open-source (Apache 2.0) and has been used to compare various EoS models against reference data (a supplementary Python tool “realtpl” is provided for real-gas property evaluation).
* **TESPy (Thermal Engineering Systems in Python)** – An open-source simulation toolkit for thermal energy systems (part of the Open Energy Modeling Framework). TESPy can model power plants, refrigeration cycles, heat pumps, and any steady-state thermodynamic process by connecting component models (pumps, turbines, heat exchangers, etc.) into networks. It supports custom component definitions, integration with optimization libraries, and includes fluid property libraries for common working fluids.
* **OpenMDAO/pyCycle** – A Python-based thermodynamic cycle modeling library for aerospace and gas turbine applications. Built on OpenMDAO, *pyCycle* is designed to model jet engine performance by assembling elements like compressors, burners, turbines, etc.. It draws inspiration from NASA’s NPSS and allows optimization and analysis of Brayton (and other) cycles. *(Users should be acquainted with OpenMDAO or NPSS to use pyCycle effectively.)*
* **PDSim** – A Python/Cython library for simulating positive-displacement machines (e.g. compressors and expanders) in steady state. PDSim provides a flexible framework to model various machine geometries with a shared core code. It has been validated in academic studies and supports integration with CoolProp for fluid properties. Example models (scroll compressors, reciprocating compressors, etc.) and documentation are available, along with Jupyter Notebook examples (via Binder) for hands-on learning.
* **Cantera** – An open-source toolkit for chemical kinetics, combustion, and thermodynamics. Cantera isn’t solely a thermo library, but it provides extensive thermodynamic **phase objects** (ideal gas, Peng–Robinson fluid, etc.) and can compute properties, chemical equilibrium, and even simulate reacting systems. It’s often used for combustion and reacting flow simulations, making it valuable for thermodynamics involving combustion or high-temperature reactions.
* **IDAES** – The *Institute for the Design of Advanced Energy Systems* provides a Pyomo-based process modeling framework that includes rigorous thermodynamic property packages. IDAES offers open-source models for power generation and chemical processes, allowing custom thermodynamic modeling and even integration of external property calculators (like REFPROP). It is suited for process simulation, optimization, and advanced energy systems design.

## Online Courses and MOOCs in Thermodynamics

| Course / Resource                          | Platform / Institution           | Focus and Coverage                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------------------------------ | -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Introduction to Thermodynamics** (UMich) | Coursera (Univ. of Michigan)     | *Entry-level engineering thermodynamics.* Covers energy and mass conservation, first law analysis for closed/open systems, properties of pure substances, and steady-state power cycle applications. Includes short lecture videos with integrated quizzes and practical problem sets (audit free, certificate available).                                                                                                                                                       |
| **Thermodynamics & Kinetics** (MIT OCW)    | MIT OpenCourseWare               | *Undergraduate thermodynamics (with chemical kinetics).* Focuses on equilibrium properties of macroscopic systems, thermodynamic laws, and chemical equilibrium in gas and solution phases. Materials include lecture notes and assignments from an MIT course in chemistry/chemical engineering.                                                                                                                                                                                |
| **Advanced Thermodynamics** (MIT OCW)      | MIT OpenCourseWare (Course 2.43) | *Graduate-level classical & non-equilibrium thermodynamics*. A concise review of classical thermo concepts (multi-component equilibria, chemical and electrochemical potentials) leading into non-equilibrium thermodynamics. Applications include exergy analysis, chemical availability, phase equilibria, and transport processes for energy systems. Features full lecture videos, slides, and an online textbook from Spring 2024.                                          |
| **Thermodynamics of Materials** (MITx)     | MITx Online (self-paced MOOC)    | *Computational and materials-focused thermodynamics.* Emphasizes laws of thermodynamics, equilibrium, and thermodynamic potentials applied to materials science. Teaches use of materials property data and thermodynamic software for phase diagrams and process design. Covers classical and statistical thermodynamics of materials, including phase equilibria, solution models, and an introduction to computational thermodynamics tools. (16-week course, free to audit). |
| **Statistical Molecular Thermodynamics**   | Coursera (Univ. of Minnesota)    | *Physical chemistry approach to thermodynamics.* Connects molecular properties to macroscopic behavior of systems. Introduces statistical mechanics fundamentals (Boltzmann distribution, partition functions) to explain classical thermodynamic observables. Highly rated for its clear linking of micro- and macro-scales (average 4.9/5★, \~21 hours, beginner-level).                                                                                                       |
| **Thermodynamics and Phase Equilibria**    | Stanford Online (MATSCI204)      | *Graduate course on thermodynamics in materials.* Covers classical thermodynamics and how it governs phase diagrams and phase equilibria. Topics include solution thermodynamics, free energy vs. composition, phase rule, and real-world material phase studies. Available via Stanford’s online platform (often as part of a professional certificate).                                                                                                                        |
| **Energy and Thermodynamics**              | Harvard/edX (HarvardX PHYSICS)   | *General introduction to energy concepts, with thermodynamics.* Part of an introductory physics sequence covering energy, atomic structure, and thermodynamic principles. Geared towards a broad audience; introduces the laws of thermodynamics and applications in everyday phenomena (offered via Harvard’s PLL or edX).                                                                                                                                                      |

**Structured Learning Paths:** In addition to individual courses, learners can follow curated paths like Class Central’s *Thermodynamics* subject guide, which lists 1200+ thermodynamics courses and certification programs from various providers. Platforms such as **Class Central** and **Coursera Specializations** aggregate courses into sequences for comprehensive learning (e.g., a specialization covering *classical thermo ➔ statistical thermo ➔ applications*). For a focused path on computational thermodynamics, university materials science departments (MIT, NCSU, etc.) often provide sequences: classical thermo → phase equilibria → computational materials thermodynamics.

## Research Papers and Preprints in Engineering Thermodynamics

* **Modeling Thermodynamic Cycles in Python (Dumka *et al*., 2022)** – Demonstrates the use of Python to model standard air cycles (Carnot, Otto, Diesel, Dual, Atkinson, Stirling, etc.). The authors developed algorithms for each cycle and verified \$p\$–\$v\$ diagrams and state points against literature, showing excellent agreement. This work highlights how scripting can extend to any thermodynamic cycle and underscores Python’s utility in engineering education and research. *Reference:* *Adv. Eng. Software* **172**, 103186 (2022).
* **Generalized EoS Framework & realtpl Library (Trümmler *et al*., 2022)** – Presents a generalized cubic equation-of-state formulation encompassing Soave–Redlich–Kwong, Peng–Robinson, and others under one framework. The paper derives a complete thermodynamic property model for CFD simulations, comparing EoS predictions to CoolProp reference data. Supplementary material includes *realtpl*, an open-source Python library (“real gas thermodynamic python library”) that researchers can use to evaluate thermodynamic properties for various fluids across different EoS models. (*arXiv:2209.14616*, also published in *Phys. Fluids* **34**, 116126).
* **pyCALPHAD Software Paper (Otis & Liu, 2017)** – Documents the design and capabilities of pyCALPHAD, an open-source Python package for CALPHAD-based thermodynamic modeling. It explains how pyCALPHAD reads thermodynamic databases and solves multi-phase equilibria by minimizing Gibbs energy, enabling calculation of complex phase diagrams. The paper emphasizes the flexibility of programmatically overriding thermodynamic models at runtime, aiding rapid model prototyping in materials thermodynamics. (*J. Open Res. Software* **5**(1): 1, 2017).
* **Positive-Displacement Machine Simulation (Bell *et al*., 2020)** – Two companion papers introducing *PDSim* (open-source library) for simulating compressors and expanders. The first outlines a quasi-steady modeling approach for positive-displacement compressors/expanders, and the second demonstrates PDSim’s capabilities through case studies. Notably, these works show how open tools (PDSim + CoolProp) can achieve high-fidelity performance predictions for refrigeration compressors. (*Int. J. of Refrigeration* **119**, 2020, pp. 137–148 and **119**, 2020, pp. 149–161).
* **Accelerating Thermodynamic Simulations with ML (Du *et al*., 2025)** – Explores a cutting-edge approach to simulate electrochemical interface thermodynamics using machine learning potentials. It extends a Monte Carlo surface reconstruction method (VSSR-MC) by incorporating fine-tuned interatomic ML force fields to efficiently sample surface phase space. The study successfully predicts known and new surface phases (e.g., Pt(111) and perovskite surfaces) and explicitly accounts for electrolyte equilibrium, improving the realism of surface Pourbaix diagrams. *(arXiv:2503.17870 \[cond-mat.mtrl-sci], 2025 – preprint from MIT/Stanford researchers).*

**Note:** The above papers underscore trends in engineering thermodynamics: leveraging Python and open-source tools for cycle analysis, unified property libraries for simulation reproducibility, integration of thermodynamics with machine learning, and democratizing complex calculations via open software. For further literature, see journals like *Energy*, *Journal of Thermodynamics*, *Chemical Engineering Science*, and preprint servers (arXiv) for the latest methods in computational thermodynamics and simulation.

## Interactive Simulations and Visualizations

* **PhET Interactive Simulations – Gas Properties & States of Matter:** The PhET project (University of Colorado) offers free web-based simulations for thermodynamics concepts. For example, *Gas Properties* lets you pump gas molecules into a chamber and adjust volume or heat to see real-time changes in pressure and temperature (visualizing the ideal gas law). Similarly, *States of Matter* allows exploration of phase change at the particle level. These HTML5 simulations provide an intuitive, game-like environment for understanding kinetic molecular theory, heat, work, and state variables. *(All PhET sims are free and support multiple languages.)*
* **LearnChemE Thermodynamics Simulations:** LearnChemE (developed by University of Colorado Boulder) hosts over 50 interactive simulations for thermodynamics and related engineering topics. These include visualizations of cycles (Otto, Rankine), property diagrams, and process operations. For instance, an interactive *Pressure-Volume Diagram for Water* lets students toggle isotherms, isentropes, and quality lines to understand two-phase behavior and critical points. Each sim is accompanied by conceptual questions and video screencasts explaining how to use it. The simulations run in-browser and encourage predicting outcomes before adjusting parameters, reinforcing conceptual learning.
* **MIT Thermodynamics Coding Labs:** MIT OpenCourseWare’s *Thermodynamics and Climate Change* course (RES.2-008) provides Jupyter-based *coding labs* for thermodynamics. These interactive notebooks (runnable via Jupyter nbviewer or Binder) guide learners through simulations such as energy balances, gas mixtures, and climate-related thermo problems. For example, a lab might have students use Python to compute the efficiency of a Rankine cycle or explore the impact of greenhouse gases on atmospheric thermodynamics. The labs combine narrative, equations, and live code, allowing learners to tinker with parameters and immediately see results. (An “Online Textbook” and problem sets are also provided for a full interactive learning experience.)
* **UBC Thermodynamics OER with Interactive Diagrams:** The University of British Columbia’s open textbook *Engineering Thermodynamics* (Thermo-OER) incorporates interactive diagrams and Python widgets. Readers can manipulate \$P\$–\$v\$, \$T\$–\$s\$, and \$h\$–\$s\$ diagrams for water and refrigerants, observing how changes in state affect properties and phases. The OER includes Jupyter notebooks on topics like Rankine cycles and refrigeration cycles. Embedded interactive plots (powered by libraries like Plotly) let users, for example, drag a point along an isotherm and see pressure or entropy values update in real time – reinforcing the relationship between thermodynamic variables.
* **Virtual Labs (Amrita Vishwa Vidyapeetham):** A collection of virtual lab experiments for thermodynamics and heat transfer, part of India’s *Virtual Labs* project. These web modules simulate real lab setups (requiring a one-time free signup). For instance, Amrita’s Thermodynamics lab includes a virtual *Otto Cycle apparatus* and *Refrigeration test rig*, complete with interactive gauges and charts. Users can vary inputs (heat addition, compressor work, etc.) and observe outputs instantly. *Note:* Many of these require Adobe Flash or JavaScript; modern browser support may vary. They offer a safe, accessible way to perform experiments like bomb calorimetry or vapor-compression cycles remotely.
* **Process Simulation Software (with GUI):** For a more engineering-oriented interactive experience, tools like **DWSIM** and **COCO** provide graphical flowsheet simulators with robust thermodynamic engines. **DWSIM** is an open-source chemical process simulator that includes unit operation models and property packages (Peng–Robinson, etc.) to simulate power plants, refrigeration cycles, and more via a drag-and-drop interface. It even has a web version (DWSIM Cloud) for browser-based use. **COCO Simulator** (CAPE-OPEN to CAPE-OPEN) is another free tool allowing interactive steady-state process modeling with various thermo property package options. While these are desktop applications rather than web apps, they offer interactive visualization of cycles and processes (TS diagrams, Mollier charts, etc.) as you manipulate the system, which can deeply enhance understanding of thermodynamic systems.

## Textbooks and Open Educational Resources

* **Thermodynamics and Chemistry – Howard DeVoe (Free PDF)**: A comprehensive **free** textbook covering classical thermodynamics with a chemistry emphasis. DeVoe’s book (University of Maryland) meticulously develops the laws of thermodynamics, entropy, and free energy, and applies them to phase equilibria and chemical reactions. It’s suitable for self-study, with end-of-chapter problems and downloadable in PDF or e-book format. Particularly useful for deeper dives into topics like solution thermodynamics and reaction equilibrium beyond the scope of standard engineering texts.
* **DOE Fundamentals Handbook (Thermodynamics, Heat Transfer, and Fluid Flow)** – A U.S. Department of Energy training handbook that provides a clear, modular introduction to thermodynamics. The Thermodynamics module (Module 1) covers basics like the first and second laws, thermodynamic processes, and cycles in a concise manner. While originally written for nuclear facility operators, it serves as an excellent primer or reference (available as free PDFs from energy.gov). The language is accessible, and the material includes practical examples and simple illustrations of concepts like reversibility and enthalpy.
* **Introduction to Engineering Thermodynamics** – An open textbook (Open Textbook Library) geared toward a one-semester undergraduate course. It starts from basic definitions and the underlying physics, then builds up through properties of gases, the First and Second Laws, and applications to real-world systems. Each chapter includes examples with step-by-step solutions (though some steps assume prior exposure to thermo, per reviews). This OER text is praised for clarity and consistency, and while the PDF formatting is basic, it covers all essential topics with a balance of theory and solved problems. *(Available through University of Minnesota’s Open Textbook initiative.)*
* **UBC Engineering Thermodynamics OER** – A modular online textbook from University of British Columbia (Faculty of Applied Science), integrating text, videos, and **interactive Jupyter notebooks**. It covers the standard curriculum (laws of thermodynamics, property relations, power and refrigeration cycles, psychrometrics, etc.) with an emphasis on problem-solving using computational tools. The content is organized by chapters and sections, and many sections link to live notebook examples where readers can modify inputs (like initial states, process steps) and observe computed outcomes. This resource is released under CC-BY-SA 4.0, encouraging adaptation by instructors.
* **LearnThermo (Bucknell University)** – An interactive thermodynamics *website* that functions as an online textbook and resource hub. It provides concise notes on key topics, along with animations, concept questions, and over 80 video tutorials created via an NSF project. LearnThermo also curates external resources: it links to free textbooks (such as DeVoe’s and the DOE Handbook above), recommended readings on specialized topics (like non-equilibrium thermodynamics), and even research papers for further exploration. It’s a great starting point for students who prefer a more guided, multimedia approach than a traditional text.
* **Classic Texts (for reference)** – While not free, it’s worth noting widely used references that might be listed elsewhere in the repository. Books like *Moran & Shapiro’s “Fundamentals of Engineering Thermodynamics”*, *Çengel & Boles’ “Thermodynamics: An Engineering Approach”*, and *Sonntag, Borgnakke, Van Wylen’s “Fundamentals of Thermodynamics”* remain gold-standard references in engineering thermodynamics. Many universities also use *Smith, Van Ness & Abbott’s “Introduction to Chemical Engineering Thermodynamics”* for chemical thermo and *Bejan’s “Advanced Engineering Thermodynamics”* for graduate studies. If not already included, these texts can provide additional depth and a multitude of practice problems (though they are commercial titles). For open alternatives, the resources above cover much of the same ground without cost.

---


## License

This awesome list is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

## Acknowledgments

This repository was inspired by:
- [Awesome Lists](https://github.com/sindresorhus/awesome)
- [AwesomeThermodynamics](https://github.com/iurisegtovich/AwesomeThermodynamics)
- [Awesome Math](https://github.com/rossant/awesome-math)
- [Awesome Courses](https://github.com/prakhar1989/awesome-courses)
