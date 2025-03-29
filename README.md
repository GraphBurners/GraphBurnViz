# GraphBurnViz
📌 Overview
The Graph Burning Visualizer Suite is an interactive web-based tool designed to simulate and visualize the process of graph burning—a theoretical model that represents the spread of fire, influence, or information in a network. This tool provides an engaging way to explore network dynamics, making it particularly useful for students, researchers, and professionals working in graph theory, social network analysis, and epidemiology. By offering multiple visualization modes, users can analyze how different graph structures impact the burning process and observe real-time interactions.

🎯 Features
The suite includes multiple graph burning simulation modes to help users explore different network configurations. The K-Paths Burning Visualizer allows users to simulate graph burning on linear paths with adjustable lengths, making it a simple yet effective way to study propagation in sequential networks. The Interactive Graph Burning mode lets users manually select nodes, enabling them to understand how strategic burning points affect the spread of fire across a network.

For those interested in structured environments, the Grid Burning Calculator provides a way to compute and visualize burning numbers for grid-based graphs. This mode is particularly useful for studying controlled environments such as city layouts, circuit networks, or biological systems. Lastly, the Dynamic Path Graph Burning mode demonstrates how the burning number evolves when graph structures are modified, helping users analyze adaptive and evolving networks.

The tool features an intuitive and user-friendly interface that requires no programming knowledge. Its click-to-burn mechanics make interactions simple, while the responsive design ensures smooth performance across different devices, including desktops, tablets, and mobile phones.

🔥 How It Works
At the start of the simulation, all nodes in the graph are in an unburned state. During each round, a new unburned node is selected as the fire source, which then ignites and starts spreading to its adjacent nodes. The fire continues to expand outward, affecting more nodes as time progresses. The process repeats until all nodes are completely burned, and the simulation stops when no further spread is possible. The burning number represents the minimum number of rounds required to burn the entire graph.

By experimenting with different graph structures and configurations, users can analyze how variations in network design influence the speed and efficiency of the burning process. The tool is particularly useful for understanding epidemic spread, information diffusion, network resilience, and cybersecurity threats, among other applications.

🚀 Getting Started
Using the Graph Burning Visualizer Suite is easy. Simply open the Merged.html file in a modern web browser such as Chrome, Firefox, Edge, or Safari. Once the interface loads, users can choose from four available visualization modes: K-Paths Burning, Interactive Graph Burning, Grid Burning, or Dynamic Path Graph Burning. After selecting the desired mode, clicking on the "Launch" button will start the simulation. Users can then configure the settings, interact with the graph, and observe how the burning process unfolds in real time.

The suite is designed to be completely self-contained, meaning that no additional software or installations are required. Everything runs within the browser, making it an accessible and portable tool for quick experiments and demonstrations.

📂 File Structure
The Graph Burning Visualizer Suite is organized into multiple HTML files, each responsible for a different type of visualization.
/GraphBurningVisualizer/
│── Merged.html               # Main dashboard
│── kpaths.html               # K-Paths Burning Visualizer
│── improved-graph-burning-visualizer.html # Interactive Graph Burning
│── gridburnerv.html          # Grid Burning Calculator
│── fixed-graph-burning-visualizer.html  # Dynamic Path Burning
│── assets/                   # CSS, JS, and other assets
Users can navigate between these files to access different burning models, each offering unique insights into the graph burning process.

👥 Credits
The Graph Burning Visualizer Suite was developed as part of a research project focused on Graph Burning Theory and its applications in network science and computational modeling. During our research, we faced significant difficulty in manually constructing graphs and simulating the burning process each time. Writing out the entire graph and tracking its burning sequence was both time-consuming and error-prone. To overcome this challenge, we sought to automate the process by developing an interactive tool that could dynamically generate graphs and simulate burning with minimal user effort.

This visualizer serves as a valuable educational and analytical tool, helping researchers, students, and professionals understand the behavior of spreading processes in various types of networks more efficiently.
