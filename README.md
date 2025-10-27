# Kerr-Black-Hole-Visualization
Bleedging Edge Black Hole Simulator
kerr-black-hole-viz/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CHANGELOG.md
├── .gitignore
├── package.json
├── package-lock.json
│
├── src/
│   ├── components/
│   │   ├── KerrBlackHoleSimulation.jsx
│   │   ├── PhysicsPanel.jsx
│   │   ├── ControlsPanel.jsx
│   │   ├── CameraPanel.jsx
│   │   └── InfoOverlay.jsx
│   │
│   ├── utils/
│   │   ├── blackHolePhysics.js
│   │   ├── particleSystem.js
│   │   ├── photonTracer.js
│   │   └── diskRenderer.js
│   │
│   ├── constants/
│   │   └── physicsConstants.js
│   │
│   ├── hooks/
│   │   ├── useBlackHoleSimulation.js
│   │   └── useDraggablePanel.js
│   │
│   ├── App.jsx
│   └── index.js
│
├── public/
│   ├── index.html
│   ├── favicon.ico
│   └── assets/
│       └── screenshots/
│
├── docs/
│   ├── PHYSICS.md
│   ├── API.md
│   ├── DEVELOPMENT.md
│   └── EXAMPLES.md
│
├── tests/
│   ├── physics.test.js
│   ├── components.test.js
│   └── integration.test.js
│
└── examples/
    ├── basic-usage.jsx
    ├── custom-parameters.jsx
    └── educational-demo.jsx
