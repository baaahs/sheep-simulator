# sheep-simulator

This is a [Processing](https://processing.org/) project. To run or use this project, download and install Processing on your system.

Once installed, open the [SheepSimulator.pde](SheepSimulator/SheepSimulator.pde) file which should open two tabs in the editor; one for the simulator and one for the camera. This code is effectively Java, so if you're familar with Java you'll feel right at home. Familiar or not, all you have to do to run the Simulator is select the "Play" button. Before you do that, though, install the required libraries...

![Processing Editor](https://github.com/baaahs/sheep-simulator/blob/images/editor.png?raw=true)

To Install libraries in Processing select the "Sketch" top menu, followed by the "Import Library" option, and finally "Add Library".

![Add Library](https://github.com/baaahs/sheep-simulator/blob/images/add_library.png?raw=true)

Next, search for and install the following two libraries:
- "shapes 3d" ![Shapes 3d Library](https://github.com/baaahs/sheep-simulator/blob/images/shapes_3d_library.png?raw=true)
- "g4p" ![G4P](https://github.com/baaahs/sheep-simulator/blob/images/g4p_library.png?raw=true)

Once installed, close the "Add Library" window and select the "Play" button on the SheepSimulator. Processing should produce an additional window with the sheep in its multicolored glory.

The lights server daemon connects to the simulator to render your developed shows here when BAAAHS isn't constructed. If you stop the SheepSimulator, the lights server will bomb and close. If your start the lights server prior to starting the SheepSimulator, it will bomb.

![Sheep Simulator](https://github.com/baaahs/sheep-simulator/blob/images/simulator.png?raw=true)
