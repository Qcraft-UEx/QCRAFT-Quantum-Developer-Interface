<p align="center">
   <picture>
     <source media="(prefers-color-scheme: dark)" srcset="https://github.com/Qcraft-UEx/Qcraft/blob/main/docs/_images/qcraft_logo.png?raw=true" width="60%">
     <img src="https://github.com/Qcraft-UEx/Qcraft/blob/main/docs/_images/qcraft_logo.png?raw=true" width="60%" alt="Qcraft Logo">
   </picture>
</p>

# QCRAFT Quantum Developer Interface
![Python Versions](https://img.shields.io/badge/python-3.9%20|%203.10%20|%203.11%20|%203.12-blue.svg)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/Qcraft-UEx/QCRAFT/blob/main/LICENSE)

**QCRAFT Quantum Developer Interface** is a DevOps-oriented web interface for designing, managing, and deploying quantum circuits across multiple quantum computing platforms. QCRAFT integrates tools like Quirk for circuit design, Docker for containerized deployments, and supports IBM Quantum and AWS Braket. The interface provides users with a seamless quantum development environment for continuous deployment, enabling efficient execution and visualization of quantum services.

## Components and Interaction Overview
QCRAFT Quantum Developer Interface consists of multiple integrated components to provide a seamless DevOps workflow for quantum computing:

* Quirk Integration: Enables visual circuit design through a drag-and-drop interface. Circuits designed in Quirk are compatible with the QCRAFT execution pipeline.
  
* Platform Translators: QCRAFT translates circuits to formats compatible with IBM Quantum (Qiskit) and AWS Braket, allowing cross-platform deployment.
  
* Docker Containerization: Docker is used to create isolated environments, ensuring that dependencies and configurations remain consistent across different deployment setups.
  
* Execution Manager: QCRAFT handles the execution of circuits on the specified backend, retrieves results, and enables result visualization and analysis directly in the interface.

**Workflow**
* Design: Users create quantum circuits using Quirk or a coding library (Qiskit, Braket).
  
* Platform Selection: Select the quantum backend (e.g., IBM or AWS).
  
* Deployment: QCRAFT deploys the circuit in a Docker container, ensuring environment consistency.
  
* Execution & Analysis: Circuits are executed on the selected platform, and results are retrieved for review and further analysis within QCRAFT.

## License
QCRAFT AutoSchedulQ is licensed under the [MIT License](https://github.com/Qcraft-UEx/QCRAFT/blob/main/LICENSE)

