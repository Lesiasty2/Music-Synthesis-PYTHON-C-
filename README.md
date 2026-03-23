# Music-Synthesis-PYTHON-C-

Version SEMANTICS
MAJOR.MINOR.PATCH
Version 0.0.0

Project plans:
1. Python - create simple oscilator/filter,
test behavior, visualize aka sandboxing the synthesizer

NumPy,MatPlotLib,Sounddevice, 
pytest ## POSIBLE TEST MAKING

2. C++ - used for creating DSP playground script
based of the prototypes designed in Python
(JUCE/ImGui) - GUIs for visual representation

3. JSON - managing presets and unification of
data

JUCE,ImGui, nlohmann/json

Possible tree visualisation

'''bash 
synth-project/
├── dsp/            # C++ DSP code
├── gui/            # UI (JUCE / ImGui)
├── presets/        # JSON presets
├── python/         # experiments / prototypes
├── tests/          # optional
├── CMakeLists.txt
└── README.md
'''