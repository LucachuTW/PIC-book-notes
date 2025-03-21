# Constrained Device Application (Connected Devices)

## Lab Module 04

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

In this module, actuator support has been integrated into the CDA. I implemented classes such as LedActivatorTask, HvacActuatorSimTask, HumidifierActuatorSimTask, and GenericActuatorSimTask to emulate devices that execute commands like switching on/off or adjusting levels (for example, temperature or humidity).

These actuator classes are coordinated through ActuatorAdapterManager, which connects them with the DeviceDataManager. Additionally, I introduced a new actuator data type for testing purposes. This simulated setup reflects how the CDA will manage real hardware in future applications.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LucachuTW/PIC-Python-components/tree/labmodule04


### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ConfigUtilTest  
- DataUtilTest  
- DeviceDataManagerTest  
- ActuatorAdapterManagerTest  
- GenericActuatorSimTaskTest  
- HvacActuatorSimTaskTest  
- HumidifierActuatorSimTaskTest  
- LedActivatorTaskTest  

### Integration Tests Executed

- ConstrainedDeviceAppTest

EOF.
