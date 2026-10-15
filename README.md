# Hi, I'm Tejas Dalvi 👋

### M.Sc. Artificial Intelligence @ Radboud University | Brain-Inspired AI | Neuromorphic Computing | Agentic AI

I'm a Master's student in **Artificial Intelligence: Intelligent Technology at Radboud University, Netherlands**, interested in building intelligent systems inspired by the brain. My work and research interests span **Spiking Neural Networks (SNNs), neuromorphic computing, brain-inspired learning, and agentic AI**.

I'm particularly interested in how biologically inspired neural architectures can support autonomous decision-making, adaptive behaviour, and efficient computation.

- 🎓 **Currently:** M.Sc. Artificial Intelligence at Radboud University
- 🧠 **Research focus:** Brain-inspired and neuromorphic AI
- 🔬 **Current research:** Spiking Neural Networks for autonomous and adaptive intelligence
- 🤖 **Other interests:** Agentic systems, human–robot interaction, neurotechnology, and intelligent robotics
- 🎯 **Long-term goal:** Contribute to research in brain-inspired AI and pursue opportunities in academic research.

---

## 🔬 Current Research

### Brain-Inspired Agentic AI: Spiking Neural Networks for Autonomous and Adaptive Intelligence [In Progress]

My Master's thesis explores the design of an agentic architecture built around Spiking Neural Networks, investigating how brain-inspired computation and learning mechanisms can support autonomous decision-making.

The current prototype uses **CartPole as an experimental environment** and is organised around three cooperating components:

- **World Model** — predicts the next environment state.
- **Action Evaluator** — estimates the potential value of candidate actions.
- **Planner** — uses predicted states and action evaluations to select an action.

The research direction is to investigate SNN-based implementations and reward-modulated, biologically inspired learning mechanisms such as **Reward-Modulated Spike-Timing-Dependent Plasticity (R-STDP)**.

**Current status:** Research prototype in development. The goal is to evaluate task performance, adaptation, robustness, and computational efficiency as the system evolves.

**Research interests:** Agentic AI · Spiking Neural Networks · Biologically Inspired Learning · Neuromorphic Computing · Autonomous Decision-Making

---

## 🧠 Selected Research & Projects

### 1. Toward a Universal Spike Encoding Framework: Comparative Evaluation of Threshold Mechanisms

**Area:** Neuromorphic Computing · Spike Encoding · Machine Learning

A comparative investigation of spike-encoding threshold mechanisms, exploring how encoding strategies affect neural network performance across different data modalities.

The project considers three approaches:

- **Fixed threshold encoding** - uses a constant firing threshold.
- **STAL** - an adaptive threshold mechanism intended to regulate neuronal activity.
- **LT-SNN** - a learnable-threshold spiking neural network approach.

The evaluation covers image classification using MNIST and audio classification using Google Speech Commands. An earlier phase also investigated STAL on MNIST and CREMA-D emotional speech.

The reported results suggest that the benefits of adaptive thresholding may depend on the data modality and task, motivating further investigation into when adaptive spike encoding is most useful.

**Key themes:** Spike encoding · Threshold adaptation · SNNs · Image and audio classification · Experimental evaluation

---

### 2. The Two-Learner Problem: Co-Adaptation Between Neural Plasticity and Adaptive Decoding in Closed-Loop Interfaces

**Area:** Neurotechnology · Brain–Computer Interfaces · Adaptive Systems

A review of the **two-learner problem** in closed-loop neural interfaces, where both the biological user and the machine decoder can adapt over time.

The review brings together perspectives on:

- Biological neural plasticity and user adaptation.
- Adaptive decoding algorithms.
- Control theory and game-theoretic perspectives.
- Shared autonomy and closed-loop interaction.
- Neuromorphic approaches to adaptive interfaces.

The central question is how to design systems that account for the coupled adaptation of the human user and the machine, rather than treating the decoder as the only learning component.

**Key themes:** Neural plasticity · Adaptive decoding · Brain–computer interfaces · Co-adaptation · Human–machine interaction

---

### 3. Evaluating the Performance of Spiking Neural Network Architectures on State-of-the-Art FPGA Hardware

**Area:** Neuromorphic Computing · FPGA Acceleration · Hardware–Software Co-Design

A group project exploring the evaluation of spiking neural network architectures on FPGA hardware.

The proposed research direction considers event-driven computation, Izhikevich neuron models, and sparse recurrent connectivity, with an emphasis on evaluating performance across hardware and software platforms.

Relevant evaluation dimensions include:

- Processing latency and spike throughput.
- Energy per spike and communication overhead.
- Scalability of event-driven neural architectures.
- Comparison with established neural simulation and neuromorphic platforms.

The project focuses on the challenges of implementing and evaluating SNN workloads on reconfigurable hardware.

**Key themes:** FPGA · Event-driven computation · SNN hardware acceleration · Neuromorphic engineering

---

### 4. How Expressive Should a Rehabilitation Robot Be?

**Area:** Human–Robot Interaction · Socially Assistive Robotics

A group project investigating how different expressive behaviours in a socially assistive robot influence people's perceptions of rehabilitation exercises.

Using a NAO humanoid robot, the project compared two interaction styles:

- **Simple mode:** neutral speech, minimal gestures, and functional guidance.
- **Advanced mode:** expressive speech, gestures, LED feedback, and motivational cues.

Both modes guided exercises such as arm raises and squats. Observations suggested that the simple mode was perceived as clear and efficient, while the advanced mode was perceived as more natural and emotionally motivating.

The project highlights the importance of designing robot behaviour around the needs and experiences of people interacting with assistive technology.

**Key themes:** Human–robot interaction · Socially assistive robots · Robot expressiveness · Rehabilitation technology

[Project overview on LinkedIn](https://lnkd.in/p/eDmjg88T)

---

### 5. BomenBabbel — Conversational Interaction for Urban Tree Awareness

**Area:** Conversational AI · Environmental Awareness · Human-Centred AI

A group project developed with Cobra, building on the BomenSpotter concept. BomenBabbel explores how a conversational interface can make individual trees more visible and encourage people to notice, understand, and care about their surroundings.

The concept combines conversational interaction with an environmental-awareness goal, illustrating how AI interfaces can support engagement with the physical world.

**Key themes:** Conversational interfaces · Human-centred AI · Environmental awareness

---

### 6. Crazyflie Drone Surprisal — Autonomous Multi-Drone Robotics [In Progress]

**Area:** Robotics · Autonomous Systems · Simulation and Real-World Experimentation

A separate robotics project exploring surprise-based approaches to drone behaviour in simulation and with Crazyflie hardware.

The broader experimental setup investigates a three-drone leader–follower configuration, with the aim of studying coordination and navigation in multi-agent systems.

The project involves simulation workflows using CrazySim/Gazebo and hardware-oriented development with Crazyflie drones and Lighthouse-based positioning.

**Key themes:** Autonomous robotics · Multi-agent coordination · Drone navigation · Simulation-to-hardware experimentation

---

## 🛠️ Technical Interests & Tools

**AI and Machine Learning**
- Python
- PyTorch
- Deep learning and model evaluation
- Reinforcement learning fundamentals

**Neuromorphic Computing**
- Spiking Neural Networks
- snnTorch
- Spike encoding and neuronal threshold mechanisms
- Surrogate-gradient learning
- Biologically inspired plasticity, including R-STDP

**Agentic AI**
- Modular agent architectures
- World models and state prediction
- Action evaluation and planning
- Autonomous and adaptive decision-making

**Robotics and Experimentation**
- Crazyflie development
- CrazySim and Gazebo
- Experimental design, benchmarking, and evaluation

---

## 🌱 What I'm Exploring

I'm particularly interested in the following research questions:

- How can spiking neural networks support multi-component agentic architectures?
- Can biologically inspired plasticity enable adaptive behaviour without relying entirely on conventional gradient-based training?
- When do adaptive spike-encoding mechanisms improve performance across different data modalities?
- How can neuromorphic systems balance task performance, computational efficiency, and robustness?
- How should intelligent systems adapt when both the agent and its environment change over time?

---

## 🤝 Connect With Me

I'm interested in connecting with researchers and students working on brain-inspired AI, neuromorphic computing, spiking neural networks, agentic systems, neurotechnology, and intelligent robotics.

- **LinkedIn:** [linkedin.com/in/tejasdalvi358](https://www.linkedin.com/in/tejasdalvi358/)
- **Medium:** [@tejasdalvi927](https://medium.com/@tejasdalvi927)

---

*Building toward intelligent systems that combine the adaptability of biological learning with the capabilities of modern AI.*
