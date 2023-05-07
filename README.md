This project provides a basic demonstration of how to create and transmit MAVLink messages for a custom drone from Simulink to any MAVLink-based ground stations or nodes. The code uses Simulink's MAVLink blockset to generate the messages and transmit them via UDP on port 14550 on the localhost. This means that QGroundControl or any other MAVLink-based ground station connected to the same PC should be able to receive the messages automatically.

You can easily modify the data in the Simulink model to generate your own custom MAVLink messages. The project is available on GitHub and includes detailed instructions on how to use it.

YouTube Demo and other updates will be available on the GitHub repository:

https://github.com/alireza787b/simulink_mavlink_generator


[![View Simulink Mavlink Communication Demo on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/129094-simulink-mavlink-communication-demo)
