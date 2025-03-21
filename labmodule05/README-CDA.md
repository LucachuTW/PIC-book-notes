# Constrained Device Application (Connected Devices)

## Lab Module 05

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

In this module, I enhanced the CDA by integrating MQTT functionality. I implemented the `MqttClientConnector` class and linked it with the `DeviceDataManager`, allowing the app to both publish and subscribe to messages from an MQTT broker.

Additionally, I modified the configuration to incorporate MQTT settings and confirmed that the CDA can transmit actuator commands and handle responses over the network. This enhancement supports remote control and monitoring, marking a significant advancement toward a fully connected IoT solution.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LucachuTW/PIC-Python-components/tree/labmodule05


### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ConfigUtilTest  
- DataUtilTest  
- DeviceDataManagerTest  
- MqttClientConnectorTest  

### Integration Tests Executed

- ConstrainedDeviceAppTest

EOF.
