# RiskMAPX v1 - Agent-Based & Discrete-Event Simulation for Risk Management

---

## Overview

**RiskMAPX v1** is an advanced simulation model developed using **AnyLogic**, designed for in-depth analysis and optimization of risk management within intricate systems.  This project uniquely integrates both Agent-Based Modeling (ABM) and Discrete-Event Simulation (DES) methodologies to dynamically simulate threats, tasks, assets, objectives, and countermeasures. It leverages graph-based modeling to capture real-time interactions, providing stakeholders with actionable insights for strategic decision-making in uncertain environments. This model is particularly useful for understanding complex system behaviors and testing risk mitigation strategies in a virtual setting before real-world implementation.  The use of XML for configuration and parameterization enhances the model's flexibility and adaptability. <cite>https://florianhuebler.com/xml-for-anylogic/</cite>

This project aims to provide a robust and flexible framework for risk assessment and management, suitable for researchers, security analysts, and decision-makers who need to evaluate and improve resilience in complex operational environments.

---

## Features

### Core Simulation Capabilities
- **Hybrid Simulation Approach**: Integrates Agent-Based Modeling for entity interactions and Discrete-Event Simulation for process flow, providing a comprehensive system view.
- **Dynamic Entity Modeling**: Simulates `Threats`, `Objectives`, `Assets`, `Tasks`, and `Countermeasures` as interactive agents within a dynamic environment.
- **Customizable Risk Parameters**:
  - **Budget Constraint**:  `MaxBudget` parameter to define the maximum budget available for countermeasure deployment (default: 5000 units).
  - **Risk Prioritization Weights**:  Adjustable weights for risk factors:
    - Cost Weight (`W_RR_C`): Default `0.1`.
    - Importance Weight (`W_RR_I`): Default `0.4`.
    - Urgency Weight (`W_RR_A`): Default `0.5`.
- **Dynamic Data Structures**: Utilizes `LinkedHashSet` collections (`AllThreats`, `AllAssets`, `AllTasks`, `AllMissionObjectives`, `AllCountermeasures`) for efficient management of simulation entities.

### Simulation Environment
- **Continuous 2D Space**:  Simulates within a 500x500 meter continuous space, allowing for spatial interaction of agents.
- **Predefined Connectors**: Employs connectors for structured communication between key simulation elements like `Sources`, `Objectives`, and `Sinks`.
- **GIS Map Integration**: Capable of integrating GIS tile maps to enhance spatial realism and context within simulations. <cite>https://www.anylogic.com/resources/educational-videos/linking-maps-and-simulation/</cite> (Although not explicitly used in `RiskMAPX v1.alp` as described, AnyLogic's capability is noted for potential future enhancements.)

### Operational Features
- **Scenario Injection**: Utilizes `runSimulation()` method alongside injection triggers (e.g., `source1.inject(1)`) for dynamic scenario execution and testing of specific events.

---

## Screenshots


---

## Technologies Used

- **AnyLogic 8.9.3 or later**:  Primary simulation software environment. <cite>https://www.anylogic.com/</cite>
- **Agent-Based Modeling (ABM)**: For simulating autonomous agents and their interactions.
- **Discrete-Event Simulation (DES)**: For modeling process-driven events and system dynamics.
- **ALP**: For project file structure and potentially for data input and output. <cite>https://florianhuebler.com/xml-for-anylogic/</cite>
- **Java**: Underlying programming language within AnyLogic, used for advanced model customization. <cite>https://anylogic.help/</cite>

> *Listing technologies helps developers understand the project's technical stack.* <cite>https://dev.to/saurabhnative/10-useful-sections-to-improve-your-github-readme-files-3hgj</cite>

---

## Installation & Usage

### Prerequisites
1. **AnyLogic Software**: Ensure you have **AnyLogic version 8.9.3 or later** installed on your system. You can download it from [AnyLogic Website](https://www.anylogic.com/).
2. **Basic AnyLogic Knowledge**: Familiarity with AnyLogic interface, simulation setup, and model execution is recommended. Tutorials are available at [AnyLogic Tutorials](https://anylogic.help/). <cite>https://anylogic.help/</cite>

Advanced Settings

    Environment Dimensions: The simulation space dimensions (default 500x500 meters) can be modified within the AnyLogic Main agent properties.
    Agent Properties: Velocity, initial positions, and other agent-specific parameters are configurable within their respective agent type definitions.
    Simulation Runtime: Simulation duration and speed can be adjusted in the Run Configurations before execution.

    Detailed configuration information allows users to tailor the project to their specific needs.

Project Status

Active Development: This project is currently under development and may be subject to ongoing updates and improvements.

    Current Status: Proof of concept and functional core simulation implemented.
    Future Enhancements:
        Integration of more sophisticated risk assessment algorithms.
        Enhanced visualization and reporting capabilities.
        Expansion of entity types and interaction complexities.
        User interface improvements for parameter input and output analysis.

    Clearly stating the project status helps manage user expectations. EVERHOUR.COM

Contributing

Contributions are welcome! If you’d like to contribute to RiskMAPX v1, please follow these guidelines:

    Fork the repository.
    Create a new branch for your feature or bug fix.
    Make your changes and ensure they are well-documented.
    Submit a pull request with a clear description of your changes.

    Providing contribution guidelines encourages community involvement. DEV.TO , EVERHOUR.COM

Supervisors & Contributors
Supervisors

This project was guided by:

    Dr. Babak Sadeghiyan
    Dr. Motahareh Dehghan
    Dr. Alireza Hashemi Golpayegani

Contributors

    Parmida Jamgohari: Key contributor in AnyLogic model development and implementation.


Contact

For questions, feedback, or collaborations, please contact:

Sajed Yousefi Mashhour

Sajed.yousefi@aut.ac.ir
[
Link to your Website/Profile <!-- Optional: Add a link to your website or profile -->
](https://github.com/sajious/My-Page)
