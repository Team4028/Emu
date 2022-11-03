# Emu Team

<br/>

## Goal
The goal for Emu Team is to learn the basics of configuring and smoke-testing a robot. You will use Leeroy for this activity.

<br/>

### Task 1: Configure Robot
Familiarize yourself with the electrical layout of Leeroy and then be sure to flash the latest firmware to the RoboRIO and all motor controllers. Then, assign CAN IDs to all the CAN devices and be sure to document this list as you go.

<br/>

### Task 2: Smoke Test
You will write some basic code to spin each motor to perform a basic smoke test. This will require an Intake and Drivetrain subsystem. NOTE: The motor which pivots the arm is inoperable, and should not be turned on. Spin the intake wheel and drive the robot forward and backward, being sure that nothing is binding, grinding, or otherwise behaving in an unexpected manner. Feel free to look at the old Leeroy code in the Resources section for help.

<br/><br/>

#### **Tips**
- You will need to be sure to include the vendor dependencies (REV, CTRE, etc).
- When spinning a motor for the first time, _never_ go above 10% speed.


<br/>

#### **Helpful Resources**
- [Old Leeroy Code](https://github.com/Team4028/2016-Leroy-New/tree/master/src/org/usfirst/frc/team4028/robot)
- [WPILib CAN Documentation](https://docs.wpilib.org/en/stable/docs/software/can-devices/third-party-devices.html#third-party-can-devices)