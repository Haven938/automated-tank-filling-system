# automated-tank-filling-system

A simulation of an automated tank filling process built in **CODESYS** using **ladder logic** and a custom **HMI interface**.

## Project Overview

This system simulates pressure-based filling of a virtual tank, allowing the user to set a pressure setpoint, start/stop the process, and view real-time visual feedback.

### Features

- Start/Stop button logic
- Setpoint control via dial
- Pressure increases using timers and logic
- Tank full lamp indicator
- Reset logic resets pressure and setpoint
- Three-screen HMI (Home + Control + Help)

### Controls

| Button        | Function                           |
|---------------|------------------------------------|
| Start         | Starts the fill process            |
| Stop          | Stops and resets the system        |
| Reset         | Clears pressure, setpoint, and lamp|
| Setpoint Dial | Sets the desired tank pressure     |

## Technologies Used

- CODESYS (Ladder Logic + Visualization)
- Function blocks: TON, ADD, MOVE, GE, SET/RESET
- Simulated HMI interface

  ## Author

    **HAVEN FENLEY**
