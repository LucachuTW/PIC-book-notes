# Constrained Device Application (Connected Devices)

## Lab Module 03

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

In this module, support for sensor data has been enhanced by introducing new classes: I2cSensorAdapter, MockI2cSensorAdapter, EnvironmentalSensorAdapterTask, and SensorAdapterManager. These additions enable the CDA to emulate the collection of temperature, humidity, and pressure readings, which are then forwarded to the DeviceDataManager.

This implementation leverages simulated data and schedules sensor readings to mimic real-world behavior. The integration of these components is verified through thorough testing of both scripts and tests, ensuring a reliable data flow and paving the way for future hardware integration.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LucachuTW/PIC-Python-components/tree/labmodule03

### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ConfigUtilTest  
- DataUtilTest  
- DeviceDataManagerTest  
- SensorAdapterManagerTest  
- EnvironmentalSensorAdapterTaskTest  
- MockI2cSensorAdapterTest  

### Integration Tests Executed

- ConstrainedDeviceAppTest

EOF.
