# CognitiveAssist

CognitiveAssist is a wearable companion concept designed to provide contextual assistance by combining camera/sensor inputs with activity and contextual reasoning.

## Current prototype

The repository currently contains:

- A web-based CognitiveAssist interface.
- Cytoscape.js support for visualizing contextual/episodic relationships.
- ESP32 camera pin configuration for supported camera boards.

## Architecture

```text
Wearable Sensors / Camera
          |
          v
   Data Acquisition
          |
          v
 Context & Activity Analysis
          |
          v
 Episodic / Context Graph
          |
          v
 Adaptive Assistance Interface
```

## Repository structure

```text
CognitiveAssist/
├── frontend/
│   └── index.html
├── firmware/
│   └── camera_pins.h
├── docs/
│   └── architecture.md
├── README.md
├── .gitignore
└── LICENSE
```

## Technology

- HTML / CSS / JavaScript
- Cytoscape.js
- ESP32 camera hardware
- Sensor-based contextual assistance (prototype direction)

## Status

Prototype / research project. Some planned AI, sensing, and wearable capabilities are not yet represented as production implementations in this repository.

## Future work

- Integrate ESP32 camera capture.
- Add IMU and audio sensing.
- Implement activity/context recognition.
- Build episodic memory graph generation.
- Add adaptive assistance based on detected context.
