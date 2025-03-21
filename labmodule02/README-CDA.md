# Constrained Device Application (Connected Devices)

## Lab Module 02

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

In this module, I developed the component called SystemPerformanceManager to gather and manage system metrics such as CPU load and memory consumption. I constructed two utility classes, SystemCpuUtilTask and SystemMemUtilTask, both extending from a shared BaseSystemUtilTask superclass. The manager schedules these tasks to execute at regular intervals.

Following that, I integrated the SystemPerformanceManager into the main CDA application. Additionally, I implemented tests for each new class to ensure they function as intended. The CDA now continuously gathers and logs system performance metrics, a feature that will enhance monitoring and support potential future cloud integration.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/LucachuTW/PIC-Python-components/tree/labmodule02

### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ConfigUtilTest  
- DataUtilTest  
- NameServerManagerTest  
- SystemPerformanceManagerTest  
- SystemCpuUtilTaskTest  
- SystemMemUtilTaskTest 

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- ConstrainedDeviceAppTest

EOF.
