# 2022-FRC-RapidReact
FRC 2022 Season Java Robot Code

Rapid React game launch happens on 2022, Saturday 8th, 12:30pm.

Java code uses command based programming which breaks up the code into classes that represent subsystems and commands that execute methods in the subsystems.
## Subsystems

Every robot contains multiple subsystems. 
### Drivetrain
The first subsystem that always exists is the drivetrain. The drivetrain represents the structure and motors that move the robot around the field.
#### DrivetrainDefaultCommand
The DefaultCommand for the Drivetrain subsystem is responsible for accepting the joystick values and driving the robot during TeleOp.
#### DrivetrainAutoMoveCommand
The AutoMoveCommand is responsible for commanding the motors on the drivetrain during Autonomous mode. The command should drive a certain distance and rotate the robot a precise degrees. 
### Other Subsystems
🤖
