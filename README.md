# Interactive Simulations and Applets for Theoretical Mechanics

A collection of interactive physics simulations exploring fundamental concepts in theoretical mechanics, developed for educational purposes during Summer 2022. This project has been handed off to future students for continuous development and enhancement.

**Original Development (Summer 2022):**
- **Instructed by:** Assistant Professor Brian Shuve  
- **Implemented by:** Kanalu Monaco & Bryce Tu Chi

**Status:** Ready for continued development by future students and contributors

## 🎯 Overview

This repository contains browser-based interactive simulations that visualize key concepts in theoretical mechanics, including:
- Calculus of variations and action minimization
- Orbital mechanics and celestial dynamics  
- Oscillatory systems and harmonic motion

Each simulation features real-time parameter adjustment, energy plotting, and mathematical visualization to help students understand the underlying physics.

## 🚀 Getting Started

1. **Open the main navigation page:**
   - Open `index.html` in your web browser
   - Or navigate directly to any simulation folder and open its HTML file

2. **Requirements:**
   - Modern web browser (Chrome, Firefox, Safari, Edge)
   - JavaScript enabled
   - No additional installations required

## 📚 Simulation Categories

### 01. Variational Calculus & Action Minimization

Explore the calculus of variations and the principle of least action - fundamental concepts that underlie much of theoretical physics.

#### [Brachistochrone Problem](01-variational-calculus/brachistochrone-problem/)
- **File:** `cycloid.html`
- **Concept:** Find the fastest path between two points under gravity
- **Features:** Interactive control point adjustment, time calculation, cycloid curve overlay
- **Physics:** Demonstrates how the cycloid curve minimizes travel time

#### [1D Trajectory Optimization](01-variational-calculus/trajectory-optimization-1d/)
- **File:** `trajectory.html`
- **Concept:** Optimize vertical projectile motion using parameterized paths
- **Features:** Real-time energy plots, action integral visualization, parameter sweeping
- **Physics:** Shows how nature "chooses" paths that extremize action

#### [2D Trajectory Optimization](01-variational-calculus/trajectory-optimization-2d/)
- **File:** `trajectory2.html`
- **Concept:** Two-dimensional projectile path optimization
- **Features:** Interactive parameter input, trajectory comparison, energy analysis
- **Physics:** Extends action minimization to 2D motion

#### [Cubic Trajectory Optimization](01-variational-calculus/trajectory-optimization-cubic/)
- **File:** `trajectory3.html`
- **Concept:** Advanced path optimization using cubic spline parameterization
- **Features:** Multi-parameter fitting, complex trajectory shapes
- **Physics:** Demonstrates flexibility of variational methods

#### [Multi-Point Trajectory](01-variational-calculus/trajectory-optimization-multipoint/)
- **File:** `trajectory4.html`
- **Concept:** Optimize paths through multiple fixed points
- **Features:** Interactive point positioning, action calculation for constrained motion
- **Physics:** Shows how constraints affect optimal paths

#### [Parabolic Motion Optimization](01-variational-calculus/parabolic-motion-optimization/)
- **File:** `parabola.html`
- **Concept:** Compare parameterized vs. classical projectile motion
- **Features:** Side-by-side trajectory comparison, energy decomposition
- **Physics:** Validates that classical motion extremizes action

#### [Free Drawing Action Analysis](01-variational-calculus/free-drawing-action/)
- **File:** `draw.html`
- **Concept:** Draw arbitrary paths and analyze their action
- **Features:** Mouse drawing interface, real-time energy calculation
- **Physics:** Interactive exploration of action for arbitrary curves

### 02. Orbital Mechanics

Investigate celestial mechanics, Kepler's laws, and the dynamics of orbital systems.

#### [Elliptical Orbits](02-orbital-mechanics/elliptical-orbits/)
- **File:** `orbit.html`
- **Concept:** Classic Keplerian orbital motion
- **Features:** Adjustable orbital parameters, potential energy plots, real-time orbit animation
- **Physics:** Demonstrates conservation laws and Kepler's laws of planetary motion

#### [Parametric Orbits](02-orbital-mechanics/parametric-orbits/)
- **File:** `orbit2.html`
- **Concept:** Alternative parametric representation of orbital dynamics
- **Features:** Parameter-based orbit control, comparative analysis
- **Physics:** Shows different mathematical approaches to orbital mechanics

### 03. Oscillations & Harmonic Motion

Study periodic motion, energy exchange, and the mathematical beauty of oscillatory systems.

#### [Harmonic Oscillator](03-oscillations/harmonic-oscillator/)
- **File:** `spring.html`
- **Concept:** Classic spring-mass system with energy analysis
- **Features:** Adjustable phase, energy vs. time plots, action integral calculation
- **Physics:** Fundamental example of simple harmonic motion

#### [Parametric Spring Motion](03-oscillations/parametric-spring/)
- **File:** `spring2.html`
- **Concept:** Compare different parameterizations of oscillatory motion
- **Features:** Dual spring animation, parameter comparison
- **Physics:** Shows equivalence of different mathematical descriptions

## 🛠️ Technical Implementation

### Technologies Used
- **HTML5 & CSS3:** Structure and styling
- **JavaScript (ES6+):** Simulation logic and interactivity  
- **D3.js v4:** Data visualization and plotting
- **HTML5 Canvas:** Real-time animations
- **SVG:** Scalable vector graphics for curves and plots
- **MathJax:** Mathematical notation rendering

### Code Architecture
- **Modular Design:** Each simulation is self-contained
- **Canvas Animations:** Smooth 60fps physics animations
- **SVG Plotting:** Sharp, scalable energy and parameter plots
- **Interactive Controls:** Real-time parameter adjustment via sliders
- **Responsive Layout:** Adapts to different screen sizes

### Key Features
- **Real-time Parameter Adjustment:** All simulations respond instantly to user input
- **Energy Visualization:** Kinetic and potential energy plots show conservation laws
- **Mathematical Rigor:** Accurate physics calculations and numerical integration
- **Educational Focus:** Clear labeling, legends, and intuitive interfaces

## 🎓 Educational Applications

### Course Integration
These simulations are designed to complement courses in:
- **Theoretical Mechanics (Physics)**
- **Classical Mechanics**
- **Mathematical Physics**
- **Calculus of Variations**
- **Differential Equations**

### Learning Objectives
Students will:
- Visualize abstract mathematical concepts in physics
- Understand the principle of least action
- Explore the connection between energy and motion
- Develop intuition for optimization in physical systems
- See the mathematical beauty underlying natural phenomena

### Usage Tips
- **Start with simple simulations** (1D trajectory, harmonic oscillator)
- **Experiment with parameters** to see immediate effects
- **Compare different approaches** using multiple simulations
- **Focus on energy plots** to understand conservation laws
- **Use as supplementary material** alongside traditional coursework

## 🤝 Contributing & Future Development

**Project Status:** This repository represents the foundation work completed during Summer 2022 and is now open for continuous development by future students and contributors.

### For Future Student Developers
This project serves as an excellent starting point for:
- **Physics/Engineering Students:** Expand simulations with new physics concepts
- **Computer Science Students:** Improve animations, add new visualizations, or enhance UI/UX
- **Mathematics Students:** Implement more sophisticated numerical methods or add new mathematical visualizations
- **Education Students:** Develop assessment tools or guided learning modules

### Development Opportunities
**Immediate Enhancement Ideas:**
- Add more variational calculus problems (geodesics, minimal surfaces)
- Implement 3D orbital mechanics (three-body problems)
- Create coupled oscillator systems
- Add Lagrangian mechanics examples
- Develop quantum mechanical analogies

**Technical Improvements:**
- Modernize to newer D3.js versions
- Add mobile responsiveness
- Implement WebGL for better performance
- Create reusable physics simulation framework
- Add data export capabilities

### Getting Started as a Contributor

1. **Fork the repository**
2. **Choose a simulation category** to extend or create new ones
3. **Follow the existing code patterns** for consistency
4. **Test across different browsers**
5. **Document your physics concepts clearly**
6. **Submit pull requests** with educational focus

### Collaboration Guidelines
- **Maintain educational value** as the primary goal
- **Preserve the interactive, real-time nature** of simulations
- **Keep physics accuracy** as a top priority
- **Follow the established folder structure** for new simulations
- **Include comprehensive comments** for future student developers

**This is a living educational project - your contributions help future students learn physics through interactive exploration!**

## 📖 Background & Theory

### Variational Calculus
The calculus of variations finds functions that extremize integrals. In physics, this leads to:
- **Euler-Lagrange Equations:** Fundamental equations of motion
- **Principle of Least Action:** Nature minimizes the action integral
- **Hamilton's Principle:** Generalization of Newton's laws

### Action Integral
The action S is defined as:
```
S = ∫ L dt = ∫ (T - V) dt
```
where L is the Lagrangian, T is kinetic energy, and V is potential energy.

### Key Physics Concepts
- **Conservation Laws:** Energy, momentum, angular momentum
- **Phase Space:** Position and momentum representations  
- **Harmonic Motion:** Fundamental oscillatory behavior
- **Central Forces:** Gravitational and electromagnetic interactions

## 📝 License & Citation

This educational software was developed during Summer 2022 as foundational work and is now maintained as an open educational resource for continuous student development. If you use these simulations in your research or teaching, please cite:

```
Monaco, K. & Tu Chi, B. (2022). Interactive Simulations and Applets for Theoretical Mechanics. 
Supervised by Prof. Brian Shuve. Summer 2022 Foundation - Continued by Student Contributors.
```

**Project Timeline:**
- **Summer 2022:** Initial development and core simulations
- **2022 Onward:** Open for continuous student development and enhancement

## 🐛 Troubleshooting

### Common Issues
- **Simulations not loading:** Ensure JavaScript is enabled
- **Animations stuttering:** Try closing other browser tabs
- **Math not rendering:** Check internet connection for MathJax CDN
- **Controls not responding:** Refresh the page

### Browser Compatibility
- Chrome 80+
- Firefox 75+  
- Safari 13+
- Edge 80+

---

**This project began in Summer 2022 and continues to grow!** The foundation has been laid - now it's ready for future students to build upon, expand, and enhance. Explore, experiment, discover, and contribute to this educational resource!

## 📞 Contact & Support

**Original Development Team (Summer 2022):**
- **Course Instructor:** Professor Brian Shuve
- **Original Developers:** Kanalu Monaco & Bryce Tu Chi

**For Current Development:**
- **Issues & Feature Requests:** Use GitHub Issues 
- **Pull Requests:** Welcome from student contributors
- **Educational Support:** Physics concepts and simulation ideas always welcome

**Future Students:** Take it away!