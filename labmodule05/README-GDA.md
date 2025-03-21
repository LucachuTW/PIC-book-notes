# Gateway Device Application (Connected Devices)

## Lab Module 05

Be sure to implement all the PIOT-GDA-* issues (requirements) listed.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

In this module, MQTT support was added to the GDA. The implementation of the MqttClientConnector is integrated with the DeviceDataManager, ensuring that the GDA properly manages messages from remote devices via an MQTT broker.

This configuration allows the GDA to handle sensor data input and actuator commands sent through the cloud. Both publishing and subscribing functionalities were tested to confirm that the message handling operates as expected.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LucachuTW/PIC-Java-components/tree/labmodule05


### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ConfigUtilTest  
- DataUtilTest  
- MqttClientConnectorTest  
- DeviceDataManagerTest  

### Integration Tests Executed

- GatewayDeviceAppTest

EOF.
