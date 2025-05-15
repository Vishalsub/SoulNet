# 🧠 SoulNet

> A universal AI soul that lives beyond bodies — adaptable across machines, agents, and humans.

**SoulNet** is a modular intelligence framework that separates the *soul* (core learning policy) from the *shell* (interface to any embodiment). Whether it's a robot, an EMG-controlled wearable, or a virtual software agent — SoulNet can adapt, learn, and act.

---

## ⚙️ Architecture Overview

- **🧠 Soul:** A cloud-deployed policy core powered by deep reinforcement learning.
- **🧩 Shell:** A modular adapter for each "host" (robot, API, exosuit, etc.)
- **🌉 Bridge:** Communication layer (FastAPI/gRPC) between the Soul and Shells.
- **🧬 Memory Core:** Learns from every host, builds transferable knowledge.
- **👁️ Watcher:** Monitors training logs, detects drift, guides evolution.

---

## 🔄 Use Cases

| Domain             | Application                                |
|--------------------|--------------------------------------------|
| 🤖 Robotics         | Navigation, manipulation, search-and-rescue bots |
| 🧍 Human Interfaces | Exosuits, EMG/EEG-based prosthetics        |
| 🕹️ Software Agents  | Web/API agents, automation, game AIs       |
| 🧠 BCI              | Brain-computer interfaces for adaptive control |
| 🐾 Biohybrid        | Animal-AI coordination, feedback modulation |

---

## 📁 Project Structure
```bash
soulnet/
├── core/ # Soul: DRL policy core, training, memory
├── adapters/ # Shells: interfaces for ROS2, EMG, software
├── bridge/ # Bridge: Soul-Shell communication
├── sim_world/ # Sim environments (e.g., Gazebo + TurtleBot3)
├── watcher/ # Real-time training analyzer (Mojo/Python)
├── tests/ # Unit & integration tests
├── scripts/ # Demos and execution scripts
└── README.md # This file
```


---

## 🧰 Tech Stack

- Python + PyTorch
- ROS 2 Foxy + Gazebo Classic
- Stable-Baselines3 or Neural Circuit Policies (`ncps`)
- FastAPI or gRPC (communication layer)
- Mojo (for high-speed log parsing)

---

## 🛠️ Getting Started

### Clone the repository:
```bash
git clone https://github.com/your-username/soulnet.git
cd soulnet
pip install -r requirements.txt
```

## 🌌 Vision

SoulNet is the foundation of a future where intelligence is not bound to one form.
It is the seed of embodied general intelligence — capable of surviving, adapting, and thriving across machines, software, and minds.

# 👤 Author

Vishal Subramanian
MSc Robotics @ NUS


📜 License
MIT License. Use freely. Build boldly. Contribute with vision.
