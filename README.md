ORCA_TOP – Floorplanning

As part of my VLSI Physical Design training at StarVLSI, I worked on the Floorplanning stage of the ORCA_TOP design using Synopsys Fusion Compiler.

The objective of this stage was to develop a physically meaningful floorplan by analyzing the design hierarchy, data-flow connectivity, port locations, hard macros, core area, utilization and physical constraints.

🔹 Work Performed
Analyzed the ORCA_TOP design hierarchy and major functional blocks.
Studied the data-flow flylines between different blocks to understand the connectivity and physical data movement.
Placed ports based on the data-flow flylines and connectivity requirements.
Performed hard-macro placement based on the observed data-flow flylines, considering the physical organization of the connected blocks.
Worked on core and die planning.
Analyzed core utilization and available placement area.
Reviewed the placement of hard macros within the core boundary.
Analyzed placement blockages and their effect on the available placement region.
Reviewed the floorplan in Synopsys Fusion Compiler.
Generated and analyzed design, utilization and QoR reports after floorplanning.
Reviewed post-floorplan timing, area and design-rule information to understand the conditions before moving to subsequent physical-design stages.
📊 Floorplan Report Summary
Parameter	Value
Core Utilization	68.53%
Core Area	733,105.816
Chip Area	803,203.096
Hard Macros	40
Blockages	56
Power Domains	2
Voltage Areas	2
Total Nets	56,764

The utilization report shows a 68.53% core utilization, while the design report identifies 40 hard macros and 56 placement blockages.

🔍 QoR Analysis

After completing the floorplan, I analyzed the generated QoR information across different modes, corners and scenarios.

The analysis included:

Setup timing
Hold timing
Critical path slack
Total negative slack
Violating paths
Maximum transition violations
Maximum capacitance violations
Cell and macro area

The purpose of this analysis was to understand the post-floorplan design condition and identify issues that could require optimization in the following physical-design stages.

📸 Proof / Evidence

This folder contains supporting evidence for the floorplanning work:

Initial Floorplan Screenshot
Completed Floorplan Screenshot
Design Hierarchy Screenshot
Utilization Report
Design Report
QoR Report

The screenshots show the floorplan development in Fusion Compiler, while the reports provide quantitative information about utilization, design composition, area and QoR.

🎯 Key Learning

This stage helped me understand that floorplanning is not simply about placing macros inside the core. The placement of ports and macros needs to consider the data-flow and connectivity of the design, along with utilization, physical constraints and downstream implementation requirements.

It also helped me connect the logical hierarchy and data-flow of the design with physical placement decisions.
