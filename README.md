# 🚀 Interactive Physics Visualizer - Projectile Motion

A comprehensive physics simulation tool with advanced analytical features for visualizing, comparing, and analyzing projectile motion. Features include comparative trajectory analysis, reachability envelope visualization, and preset demonstration scenarios.

## 🎥 Demo

▶ Click to view the demo video:  
[demo/simverse_projectile_motion.mp4](demo/simverse_projectile_motion.mp4)



This demo showcases projectile motion, collision prediction, comparative trajectories, and reachability envelope visualization.


## ✨ Core Features

### Interactive Simulation
- **Real-time Physics**: Accurate projectile motion calculations using standard physics formulas
- **Dynamic Camera**: Smooth camera tracking with manual pan/zoom controls
- **Object Placement**: Interactive target objects with collision detection
- **Live Data Display**: Real-time position, velocity, and trajectory information
- **Multiple Gravity Settings**: Earth, Moon, Mars gravity presets

### Comparative Trajectory Mode
- **Dual Trajectory Analysis**: Compare two projectile configurations side-by-side
- **Color-Coded Visualization**: Blue (Trajectory A) vs Red (Trajectory B)
- **Independent Controls**: Separate velocity and angle settings for each trajectory
- **Comparative Metrics**: Side-by-side impact data and collision analysis
- **Shared Environment**: Same gravity and object placement for fair comparison

### Reachability Envelope Visualization
- **Theoretical Limits**: Visual representation of all reachable points for a given max speed
- **Dynamic Envelope**: Real-time updates based on gravity and maximum launch speed
- **Semi-transparent Overlay**: Never obstructs trajectory visibility
- **Educational Insight**: Shows optimal vs actual trajectory performance
> Reachability envelope assumes launch and landing at the same vertical height.


###  Preset Scenario System
- **🎯 Basic Target Hit**: Standard target practice scenario
- **🏔️ Elevated Platform**: Projectile motion to elevated targets
- **🚧 Obstacle in Path**: Navigate around obstacles to reach targets
- **🚀 Long-Range Shot**: Extended distance trajectory challenges
- **Auto-Configuration**: Instantly sets up complete scenarios with objects and parameters

###  Advanced Calculator
- **Reverse Calculator**: Enter any 1-2 values to calculate remaining parameters
- **Flexible Inputs**: Calculate from velocity, angle, range, height, or flight time
- **Smart Solutions**: Provides optimal trajectory solutions with flight time emphasis
- **One-Click Apply**: Instantly apply calculated values to the simulator

##  How to Use

### Basic Simulation
1. **Adjust Parameters**: Use sliders for launch angle (5°-85°) and velocity (10-150 m/s)
2. **Place Objects**: Click "Add Rectangle Target" then click on canvas to place targets
3. **Launch**: Click "🚀 Launch" to start simulation with automatic camera following
4. **Manual Control**: Drag to pan view, mouse wheel to zoom, pause/resume as needed

### Comparative Analysis
1. **Enable Compare Mode**: Check "🔄 Compare Mode" in Analysis Modes
2. **Configure Trajectories**: Set different parameters for blue (A) and red (B) trajectories
3. **Launch Both**: Single launch button fires both projectiles simultaneously
4. **Analyze Results**: Compare flight times, ranges, and collision outcomes

### Reachability Analysis
1. **Enable Envelope**: Check "📊 Reachability Envelope" 
2. **Set Max Speed**: Adjust slider to define theoretical launch speed limit
3. **Visualize Limits**: Green shaded area shows all theoretically reachable points
4. **Compare Performance**: See how actual trajectories relate to theoretical maximum

### Preset Scenarios
1. **Select Scenario**: Choose from dropdown menu (Basic Target, Elevated Platform, etc.)
2. **Auto-Setup**: Scenario automatically configures parameters and places objects
3. **Customize**: Modify parameters after loading if desired
4. **Demonstrate**: Perfect for educational presentations and physics demonstrations

## 📊 Physics & Mathematics

### Core Equations
- **Range**: `R = (v² × sin(2θ)) / g`
- **Maximum Height**: `h = (v² × sin²(θ)) / (2g)`
- **Flight Time**: `t = (2v × sin(θ)) / g`
- **Reachability Envelope**: `y = (v²/(4g)) - (gx²)/(4v²)`

### Advanced Features
- **Error Validation**: Compares theoretical vs simulated results
- **Collision Detection**: Real-time object intersection calculations
- **Camera Mathematics**: Smooth easing and viewport transformations
- **Envelope Computation**: Efficient 100-point curve generation

##  Repository Structure
> Note: The simulator is implemented as a single self-contained HTML file to simplify deployment, ensure portability, and eliminate setup friction during demos. All physics, rendering, and UI logic are modularized internally.


```
📁 projectile-motion-simulator/
├──  interactive_physics_visualizer.html     # Advanced version with all features
├──  demo/
|     └──simverse_projectile_motion          # Demo Video
└──  README.md                               # This documentation

```

##  Quick Start Examples

### Educational Demonstrations
1. **Angle Comparison**: Enable Compare Mode, set 30° vs 60° at same velocity
2. **Gravity Effects**: Switch between Earth/Moon/Mars to see trajectory differences  
3. **Optimal Range**: Use envelope to show 45° gives maximum range
4. **Obstacle Navigation**: Load "Obstacle in Path" scenario for trajectory planning

### Physics Analysis
1. **Theoretical Limits**: Enable envelope, adjust max speed to see reachable area
2. **Trajectory Optimization**: Use reverse calculator to hit specific targets
3. **Collision Analysis**: Place objects and compare which trajectory hits first
4. **Real-world Applications**: Model actual projectile scenarios with custom parameters

##  Educational Applications

### Physics Concepts Demonstrated
- **Projectile Motion Fundamentals**: Parabolic trajectories and physics equations
- **Angle Optimization**: Understanding why 45° gives maximum range
- **Gravity Effects**: Comparing motion on different celestial bodies
- **Theoretical vs Practical**: Envelope shows theoretical limits vs actual performance
- **Trajectory Comparison**: Side-by-side analysis of different launch parameters

### Classroom Use
- **Interactive Demonstrations**: Preset scenarios for instant professional demos
- **Student Exploration**: Hands-on parameter adjustment and result observation
- **Problem Solving**: Reverse calculator for finding launch parameters
- **Advanced Analysis**: Comparative mode for hypothesis testing
- **Visual Learning**: Color-coded trajectories and real-time data display

Perfect for physics education, engineering courses, and anyone interested in understanding projectile motion mechanics through interactive visualization and analysis!