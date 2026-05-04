# GRAFCET — Pharmaceutical Bottling & Labeling Line Simulation

A complete, interactive GRAFCET (Grafique Fonctionnel de Commande Étapes/Transitions) simulation for an automated pharmaceutical bottling line featuring **parallel processing** for capping and labeling operations.

## 🎯 Features

- ✅ **Complete GRAFCET State Machine** with master sequence and parallel sub-sequences
- ✅ **Interactive SVG Diagrams** showing all three GRAFCET views
- ✅ **Sensor Input Simulation** - Toggle 8 different sensors (Pb, Pe, h, b, r, d, v, i)
- ✅ **Real-Time Output Indicators** - 7 actuators with live glow effects (T, D, M, A, R, F, O)
- ✅ **Manual & Automatic Modes** - Step-by-step or continuous automatic execution
- ✅ **Adjustable Speed** - Control simulation speed with slider (300ms - 3000ms)
- ✅ **Event Logger** - Timestamped log of all events and state transitions
- ✅ **Color-Coded Legend** - Understand GRAFCET notation instantly
- ✅ **Fully Responsive** - Works on desktop, tablet, and mobile

## 📋 Three GRAFCET Views

1. **Cas Général (Master)** - Overall process control with parallel divergence/convergence
2. **Bouchage (Capping)** - Capping station sequence (T, D, F, M, O)
3. **Étiquetage (Labeling)** - Labeling station sequence (A, R)
4. **Légende** - Complete variable definitions and GRAFCET notation guide

## 🔧 How to Use

1. **Open** `index.html` in any modern browser
2. **Click "▶ Démarrer"** to start the cycle
3. **Use "⏭ Pas à pas"** for manual step-by-step execution
4. **Toggle sensors** on the right panel to simulate bottle detection and limit switches
5. **Watch the event log** to see all transitions and outputs
6. **Use "⚡ Auto"** for continuous automatic operation
7. **Adjust speed** with the slider (1.2s default)
8. **Reset** to return to initial state

## 📚 Input Variables (Sensors)

| Variable | Description |
|----------|-------------|
| **Pb** | Bottle presence at capping station |
| **Pe** | Bottle presence at labeling station |
| **h** | Capper high limit switch |
| **b** | Capper low limit switch |
| **r** | Labeler rear position limit switch |
| **d** | Labeler front position limit switch |
| **v** | Gripper open sensor |
| **i** | Conveyor index sensor (step movement) |

## 📤 Output Variables (Actuators)

| Variable | Description |
|----------|-------------|
| **T** | Conveyor belt motor |
| **D** | Capper descent (down) |
| **M** | Capper ascent (up) |
| **A** | Labeler advance (forward) |
| **R** | Labeler retract (backward) |
| **F** | Gripper close |
| **O** | Gripper open |

## 🎓 GRAFCET Concepts Illustrated

- **Steps** (Étapes): Represented as rectangles with numbers
- **Transitions** (Transitions): Represented as lines with condition boxes
- **Receptivity** (Réceptivité): Conditions that must be true to transition
- **Parallel Divergence (ET)**: Split into concurrent sequences
- **Parallel Convergence (ET)**: Wait for all parallel sequences to complete
- **OR Divergence (OU)**: Choose one of multiple paths
- **OR Convergence (OU)**: Merge alternative paths
- **Actions**: Outputs activated in each step

## 👥 Team

- **Yesser Ben Rhouma**
- **Meriam Warteni**
- **Sarra Fatnassi**
- **Siwar Gouader**

## 🏫 Academic Context

TP - ARC (Travaux Pratiques - Automatisme, Régulation & Capteurs)

## 🌐 Live Demo

Open this repository's GitHub Pages link to see the simulation in action.

## 💻 Technology Stack

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with CSS variables, animations, and gradients
- **SVG** - Vector graphics for GRAFCET diagrams
- **JavaScript (ES6+)** - State machine logic and interactivity
- **Google Fonts** - Share Tech Mono & Exo 2 typefaces

## 📝 License

Open for educational use. Feel free to fork, modify, and distribute.

---

**Made with ❤️ for automation engineering education**
