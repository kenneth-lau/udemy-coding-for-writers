# Exercise 4: Documenting Constants

Lines of codes with Constants
```json
const productName = "RoboBall";
const versionNumber = 1.6;
const commStop = 0x00;
const commMoveForward = 0x01;
const commMoveBackward = 0x02;
const commTurnLeft = 0x03;
const commTurnRight = 0x04;
const errBadSignal = 0xFF01;
const errBadCommand = 0xFF02;
const errBatteryLow = 0xFF03;
```

## Documentation using a table
Name | Description | Type | Value
--- | --- | --- | ---
commMoveBackward | Command code to send to the robot to move it backward | Number | 0x02
commMoveForward | Command code to send to the robot to move it backward | Number | 0x01
commStop | Command code to send to the robot to make it stop | Number | 0x00
commTurnLeft | Command code to send to the robot to make it turn left | Number |  0x03
commTurnRight | Command code to send to the robot to make it turn right | Number |  0x04
errBadCommand | Error code for a bad command | Number | 0xFF02
errBadSignal | Error code displayed when the signal is weak | Number | 0xFF01
errBatteryLow | Error code for when the battery is low | Number | 0xFF03
productName | Name of the product | String | RoboBall
versionNumber | Version number of the product | Number | 1.6

## Documentation using code
`const commMoveBackward = 0x02;`  
Command code to send to the robot to move it backward.
`const commMoveForward = 0x02;`
Command code to send to the robot to move it forward.
`const commTurnLeft = 0x03;`
Command code to send to the robot to make it turn left.
`const commTurnRight = 0x04;`
Command code to send to the robot to make it turn right.