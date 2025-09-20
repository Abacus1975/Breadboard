# Breadboard Simulator

An interactive in-browser breadboard that helps prototype simple circuits without real hardware.

## Features
- Place batteries, resistors, LEDs, switches, capacitors, transistors, a flasher IC, wires, and probes directly onto the virtual board.
- Adjust the supply voltage and enable a live voltage heatmap to visualise power rails and node potentials.
- Built-in hints and a tutorial panel covering placement, editing, and deletion workflows.
- Save your design to a downloadable .json file and reload it later to continue iterating.
- Responsive layout optimised for desktop browsers using only HTML, CSS, and vanilla JavaScript.

## Getting Started
1. Open Breadboard.html in a modern desktop browser (Chrome, Edge, Firefox, or Safari).
2. Use the component toolbar to select a tool, then click the breadboard to place parts or draw wires.
3. Adjust the battery slider, toggle the voltage heatmap, and experiment with switches and the flasher IC.
4. Click **Save Circuit** to download your layout, or **Load Circuit** to bring a saved design back onto the board.

## Project Structure
- Breadboard.html – single-page application containing the complete simulator UI and logic.

## Notes
- No build tooling or dependencies are required; static hosting is sufficient if you want to share the simulator online.
- A license has not been specified. Add one if you plan to publish or share the project broadly.
