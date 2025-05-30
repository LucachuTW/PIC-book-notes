# Gateway Device Application (Connected Devices)

## Lab Module 12 - Semester Project - GDA Components

Be sure to implement all the PIOT-GDA-* issues (requirements) listed.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do?

The GDA is now designed to read new data, implemented in the CDA, via MQTT and forward this information to the Ubidots cloud. While this is the intended functionality, there's currently an issue where the data, although successfully received by the GDA, does not appear to reach Ubidots for visualization.

How does your implementation work?

The files involved in the cloud data transmission process have been updated to include the new luminosity data. However, when attempting to send the data collected from the CDA to the GDA, certain unspecified errors are being encountered:

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LucachuTW/PIC-Java-components/tree/labmodule12



### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- 
- 
- 

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- GatewayDeviceAppTest
- CloudClientConnectorTest
- 

EOF.
