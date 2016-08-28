# ReLX
Lighting CAD with truss calculations, power and dmx wire routing, and simulation.<br \>

Language: C#<br />
OS: Linux, Windows, ++<br />
Current status: Collecting Ideas<br />

##Three stages of operation.##
- Rigging
    - Truss centric
    - Configure trusses and hanging points with weight allowances.
    - Configure stage elements with weight allowances.
    - Design and import room structure (3d scanning?)
    - Hang lamps on trusses or position on surfaces.
        - Give warnings about overloading.
- Routing
    - Configure tree structures of power distribution.
        - Calculation of required wattage and wire gauges(in square mm.)
        - Get warnings for electrical overloading.
    - Configure DMX distribution
        - Ethernet interfaces, and dmx splitters.
        - Drag and drop lamp adress patching
        - Overlapping patches (Allowed, but with warning)
        - Fault finding
            - Cable lengths
            - Number of units
            - Singnal bounce simulation
            - Problematic splits
- Presentation
    - 2d drawings for riggers and lx operators
    - patch, color and gobo lists
    - 3d rendered pictures
    - 3d simulation with mixer input

##Rules##
- Every function and class should be commented fully before submitting to Git.
- There is a quite strict code standard in place. Familiarize yourself with it.
