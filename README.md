# Echo: Intelligent Multi-Drone System with a Custom Network

**Echo** is an experimental platform for developing an intelligent, decentralized drone fleet system. It integrates custom communication protocols, real-time control, computer vision, and graph-based machine learning.

### 🛰️ Project Components

- **Rust-based core**: Low-level control and communication logic.
- **Python layer**: AI and high-level management layer.
- **Custom network**: Central, relay, and client nodes in a graph structure.
- **Simulation**: AirSim / Gazebo-ROS2 environment for testing before real-world deployment.
- **Computer Vision**: Object detection, tracking, and navigation.
- **Graph ML**: Using GNNs for swarm decision-making and topology optimization.

### 📦 Folder Overview

- `framework/`: Core logic in Rust + Python integration layer
- `network/`: Communication prototypes and simulation tools
- `simulation/`: Sim environments and configs
- `vision/`: AI modules for perception
- `ml/gnn/`: Graph Neural Networks for swarm intelligence
- `hardware/`: Drone design, PCB, and configs
- `docs/`: Architectural documentation

---

> ⚙️ This project is under active development. Contributions are welcome.
