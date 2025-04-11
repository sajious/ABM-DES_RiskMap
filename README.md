RiskMAPX v1
Overview

RiskMAPX v1 is a research-oriented simulation project created using AnyLogic 8.9.3. It provides an advanced framework for modeling risk management scenarios, focusing on threats, objectives, assets, tasks, and countermeasures. This project leverages agent-based modeling and dynamic architecture to facilitate real-world decision-making processes under uncertainty.

This repository includes the AnyLogic project file (RiskMAPX v1.alp) and detailed documentation to support its usage.
Features
Core Simulation Elements

    Threat Modeling: Dynamic prioritization of threats using the variable MostImportantThreat.
    Agent-Based Design: Interactions between agents representing objectives, countermeasures, and tasks in a continuous 2D environment.
    Configurable Parameters

Dynamic Environment

    Continuous Space: Simulations run in a customizable environment.
    Graph-Based Architecture: Components such as connectors link agents and manage sequential/parallel flows dynamically.

Predefined Connectors

    Logical connections enable communication between elements like tasks, objectives, sources, and sinks.

Ensure the following:

    AnyLogic Software: Version 8.9.3 or newer.
    Basic understanding of AnyLogic simulation configurations.

Configuration
Parameters

Before running the simulation, the following parameters can be configured:

    Budget:
        MaxBudget: Define the maximum allowable budget for implementing countermeasures. Default value: 5000.
    Risk Factor Prioritization:
        W_RR_C (Cost Weight): Default value: 0.1.
        W_RR_I (Importance Weight): Default value: 0.4.
        W_RR_A (Urgency Weight): Default value: 0.5.

Supervisors & Contributors
Supervisors

This project is developed under the supervision of:

    Dr. Babak Sadeghiyan
    Dr. Motahareh Dehghan
    Dr. Alireza Hashemi Golpayegani

Development Contributors

The main simulation logic was created by:

    Parmida Jamgohari: Contributor in AnyLogic model development.


For inquiries, feel free to contact:
Sajed Yousefi Mashhour
sajed.yousefi@aut.ac.ir

Repository URL: [RiskMAPX GitHub Repository](https://github.com/sajious/ABM-DES_RiskMap)
