# [Sensor Device Driver Design Guide](index.md)
# [What's New In Sensors](what-s-new-in-sensors.md)
# [Universal Sensor Driver Model for Windows 10](converged-sensor-driver-model-for-windows-10.md)
## [Design Guide](design-guide.md)
### [Overview of Universal Sensor Driver Model](overview-of-converged-sensor-driver-model.md)
### [Windows Sensor Driver Features](windows-sensor-driver-features.md)
#### [Sensor Data Batching for Power Savings](sensor-batching-for-power-saving-.md)
#### [Sensors ACPI Entries](sensors-acpi-entries.md)
## [Programming Guide](programming-guide-v2.md)
### [How to Build a Universal Sensor Driver](how-to-build-a-universal-sensor-driver.md)
#### [Set up your Development Environment](set-up-your-development-environment.md)
#### [Prepare your Sensor Test Board](prepare-your-sensor-test-board.md)
#### [Connect your Sensor to the Sharks Cove Board](connect-your-sensor-to-the-sharks-cove-board.md)
#### [Write and Deploy your Universal Sensor Driver](write-and-deploy-your-universal-sensor-driver.md)
##### [Make the Driver Loadable](make-the-driver-loadable.md)
##### [Connect to Hardware](connect-to-hardware.md)
##### [Read Data from Hardware](read-data-from-hardware.md)
##### [Review the INX File](review-and-revise-the-inf-file.md)
###### [Creating a Mobile Package](creating-a-mobile-package.md)
##### [Build the Sensor Driver](build-the-sensor-driver.md)
##### [Install the Sensor Driver](install-the-sensor-driver.md)
#### [Test your Universal Sensor Driver](test-your-universal-sensor-driver.md)
#### [Collecting and Decoding WPP Logs](collecting-and-decoding-wpp-logs.md)
### [Fusion Sensor Implementation Details](fusion-sensor-implementation-details.md)
# [Sensor Driver Model for Windows 8.1](sensor-driver-model-for-windows-8-1.md)
## [New Sensor Features and Improvements for Windows 8.1](new-sensor-features-and-improvements-for-windows-8-1.md)
## [Design Guide](sensor-driver-design-guide.md)
### [Getting Started](getting-started.md)
#### [Introduction to the Sensor and Location Platform in Windows](introduction-to-the-sensor-and-location-platform-in-windows.md)
#### [For More Information](for-more-information.md)
### [Sensor Driver Overview](sensor-driver-overview.md)
#### [Architecture Overview](architecture-overview-for-sensor-drivers.md)
#### [About the Sensor Class Extension](about-the-sensor-class-extension.md)
#### [About the Interfaces](about-the-interfaces.md)
##### [About ISensorClassExtension](about-isensorclassextension.md)
##### [About ISensorDriver](about-isensordriver.md)
##### [About the Parameter Types](about-the-parameter-types.md)
#### [About Sensor Driver Events](about-sensor-driver-events.md)
#### [About Sensor Constants](about-sensor-constants.md)
##### [Event Constants](event-constants.md)
##### [Sensor Properties](sensor-properties.md)
##### [Sensor Icon Constants](sensor-icon-constants.md)
##### [Sensor Categories, Types, and Data Fields](sensor-categories--types--and-data-fields.md)
###### [SENSOR_CATEGORY_ALL](sensor-category-all.md)
###### [SENSOR_CATEGORY_BIOMETRIC](sensor-category-biometric.md)
###### [SENSOR_CATEGORY_ELECTRICAL](sensor-category-electrical.md)
###### [SENSOR_CATEGORY_ENVIRONMENTAL](sensor-category-environmental.md)
###### [SENSOR_CATEGORY_LIGHT](sensor-category-light.md)
###### [SENSOR_CATEGORY_LOCATION](sensor-category-loc.md)
###### [SENSOR_CATEGORY_MECHANICAL](sensor-category-mechanical.md)
###### [SENSOR_CATEGORY_MOTION](sensor-category-motion.md)
###### [SENSOR_CATEGORY_ORIENTATION](sensor-category-orientation.md)
###### [SENSOR_CATEGORY_SCANNER](sensor-category-scanner.md)
#### [About Sensor Properties](sensor-properties2.md)
##### [Common Sensor Properties](common-sensor-properties.md)
##### [Enumeration Properties](enumeration-properties.md)
##### [Other Sensor Properties](other-sensor-properties.md)
###### [Proximity Sensor Property](proximity-sensor-property.md)
###### [Light Sensor Property](light-sensor-property.md)
###### [Orientation Sensor Property](orientation-sensor-property.md)
###### [Activity Sensor Properties](activity-sensor-properties.md)
###### [Pedometer Sensor Property](pedometer-sensor-property.md)
##### [Data Field Properties](data-field-properties.md)
###### [Required Data Field Properties](required-data-field-properties.md)
#### [About Sensor Data Fields](sensor-data-fields.md)
##### [Common Data Fields](common-data-fields.md)
##### [Accelerometer Data Fields](accelerometer-data-fields.md)
##### [Linear Accelerometer Data Fields](-linear-accelerometer-data-fields.md)
##### [Magnetometer Data Fields](magnetometer-data-fields.md)
##### [Geomagnetic Orientation](geomagnetic-orientation.md)
##### [Gravity Vector Data Fields](gravity-vector-data-fields.md)
##### [Gyroscope Data Fields](gyroscope-data-fields.md)
##### [Light Sensor Data Fields](light-sensor-data-fields.md)
##### [Device Orientation Sensor Data Fields](device-orientation-sensor-data-fields.md)
##### [Proximity Sensor Data Fields](proximity-sensor-data-fields.md)
##### [Environmental Sensor Data Fields](environmental-sensor-data-fields.md)
##### [Simple Device Orientation Sensor Data Fields](simple-device-orientation-sensor-data-fields.md)
##### [Activity Detection Sensor Data Fields](activity-detection-sensor-data-fields.md)
##### [Pedometer Data Fields](pedometer-data-fields.md)
##### [Relative Orientation Sensor Data Fields](relative-orientation-data-fields.md)
##### [Custom Sensor Data Fields](custom-sensor-data-fields.md)
#### [Default Thresholds and Intervals](default-thresholds-and-intervals.md)
##### [Accelerometer Thresholds and Interval](accelerometer-thresholds-and-interval.md)
##### [Magnetometer Thresholds and Interval](magnetometer-thresholds-and-interval.md)
##### [Gyroscope Thresholds and Interval](gyroscope-thresholds-and-interval.md)
##### [Light Sensor Thresholds and Interval](light-sensor-thresholds-and-interval.md)
#### [Marshalling Helper Functions](marshalling-helper-functions.md)
##### [Time Stamp Helper](timestamp-helper.md)
##### [PropVariant Helpers](propvariant-helpers.md)
##### [Collection List Helpers](collection-list-helpers.md)
##### [Collection List Serialization Helpers](collection-list-serialization-helpers.md)
##### [Collection List Legacy Helpers](collection-list-legacy-helpers.md)
## [Programming Guide](programming-guide.md)
### [Sensor Driver Development Basics](sensor-driver-development-basics.md)
#### [Writing a Sensor Device Driver](writing-a-sensor-device-driver.md)
##### [Considerations for Writing a Sensor Driver](considerations-for-writing-a-sensor-driver.md)
##### [Creating a Sensor Driver](creating-the-driver.md)
##### [Creating a Persistent Unique Identifier for a Sensor](creating-a-persistent-unique-identifier.md)
##### [Raising Sensor Events](raising-events.md)
##### [Filtering Data](filtering-data.md)
##### [Using Vector Types with Sensors](using-vector-types.md)
##### [Defining Custom Values for Sensor Constants](defining-custom-values-for-constants.md)
##### [Specifying a Sensor Icon](specifying-an-icon.md)
##### [Sensor Driver Best Practices](sensor-driver-best-practices.md)
#### [Supporting Ambient Light Sensors](supporting-ambient-light-sensors.md)
### [Sensor Driver Logic](driver-logic--pseudo-code-.md)
#### [Driver Initialization Methods](driver-initialization-methods.md)
#### [Driver Interface Methods](driver-interface-methods.md)
#### [Driver Update Methods](internal-helper-methods.md)
#### [Device Update Methods](device-update-methods.md)
#### [Internal Driver Methods](internal-driver-methods.md)
#### [Device Methods](device-methods.md)
### [Testing Sensor Functionality with the Sensor Diagnostic Tool](the-sensor-diagnostic-tool.md)
#### [Testing Sensor Functionality](testing-sensor-functionality.md)
##### [Testing Sensor Events](testing-sensor-events.md)
##### [Testing Sensor Data Retrieval](testing-sensor-properties.md)
##### [Testing Sensor Property Support](testing-and-logging-sensor-data.md)
#### [Testing Location Functionality](testing-location-functionality.md)
#### [Known Issues](known-issues.md)
### [SpbAccelerometer Driver Sample](spbaccelerometer-driver-sample.md)
#### [Supporting Multiple Sensors](supporting-multiple-sensors.md)
#### [The Driver I/O Model](the-driver-i-o-model.md)
#### [Defining the Accelerometer Object](defining-the-accelerometer-object.md)
#### [Using the Sensor Class Extension](using-the-sensor-class-extension.md)
#### [Supporting the Accelerometer Properties](supporting-the-accelerometer-properties.md)
#### [The Driver Sample File List](the-driver-sample-file-list.md)
## [SpbAccelerometer Driver Cookbook](spbaccelerometer-driver-cookbook.md)
### [Install the Sample Device and Driver on your Sharks Cove Board](installing-the-sample-device-and-driver-on-your-sharks-cove-board.md)
### [SpbAccelerometer Driver Overview](spbaccelerometer-driver-overview.md)
### [Sample Driver I/O Model](the-sample-driver-i-o-model.md)
### [I2C Transport](the-i2c-transport.md)
### [Accelerometer Object](the-accelerometer-object.md)
### [Access the Sensor Class Extension](accessing-the-sensor-class-extension.md)
### [Support for Device Properties](supporting-the-device--properties.md)
### [Driver Initialization](driver-initialization.md)
### [Modify the Sample to Support Another Sensor](modifying-the-sample-to-support-another-sensor.md)
### [Use the Sensors Diagnostic Tool to Test your Driver and Device](using-the-sensors-diagnostic-tool-to-test-your-driver-and-device.md)

