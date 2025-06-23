# Team Micro Mouse

Hi there, this is organization is a collection of repositories for our school project 'Micro Mouse' for our second semester at the Hogeschool Utrecht.
If you don't know what a micro mouse is, please refer to (this veritasium video)[https://www.youtube.com/watch?v=ZMQbHMgK2rw]. We asked ourselves, how
hard can it be to make our own micro mouse? Apparently, pretty difficult. 

If you would like to read through our code, please make sure to fully read this through first since there is some information on how the project is set up. 
If you wish to contact us, please make sure to do so with an issue either here, or on the repository itself.
Our semester is over now, so we will likely stop updating this organization unless we somehow find the time to do so.

## How does it all work?

We write all our algorithms in C++, this is what's required for our microprocessor. The algorithmes are wrapped with their own interfaces to make them easy
to swap out, but more importantly, easy to use within our (simulator)[https://github.com/Team-MicroMouse/simulatie]. Our simulator has been written in Unity and we have developed this repository (Unity-Micro-Lib)[https://github.com/Team-MicroMouse/Unity-Micro-Lib]
to create a communication layer between C# and C++. In the simulator we have developed some debugging tools so we can more easily test our algorithms.

As for the mouse, we created a (seperate library)[https://github.com/Team-MicroMouse/Arduino-Micro-Lib] for using the algorithms on the arduino. It does differ
in some small ways from the unity micro lib, but its close enough.

## Testing the code

If you want to test the code in the simulator, first follow the instructions here to build the code (unity micro lib)[https://github.com/Team-MicroMouse/Unity-Micro-Lib].
Then, follow the instructions in (the simulator)[https://github.com/Team-MicroMouse/simulatie] for running the code.
