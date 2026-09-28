# Task 2 - Complete Operation Schema

## Smart Museum Artifact Conservation System

| ID | Operation | Pre-condition | Input | Post-condition |
|---|---|---|---|---|
| OP-01 | Perform Sensor Self-Check | Chamber is powered on | Sensor status | Essential sensors are checked |
| OP-02 | Record Artifact Information | Artifact is placed inside the chamber | Artifact identification information | Artifact information is recorded |
| OP-03 | Load Environmental Limits | Artifact information is recorded | Temperature and humidity limits | Required environmental limits are loaded |
| OP-04 | Monitor Environment | Essential sensors are working | Temperature and humidity readings | Environmental conditions are continuously monitored |
| OP-05 | Correct Temperature | Temperature is outside the permitted range | Current temperature and required range | Temperature correction is started |
| OP-06 | Verify Temperature | Temperature correction has been attempted | New temperature reading | Temperature is verified against the permitted range |
| OP-07 | Correct Humidity | Humidity is outside the permitted range | Current humidity and required range | Humidity correction is started |
| OP-08 | Verify Humidity | Humidity correction has been attempted | New humidity reading | Humidity is verified against the permitted range |
| OP-09 | Reduce Light Exposure | Artifact requires protection | Light exposure level | Light exposure is reduced |
| OP-10 | Generate Operator Alert | Environmental condition cannot be corrected | Problem information | Alert is generated for the museum operator |
| OP-11 | Detect Vibration | Artifact is inside the chamber | Vibration sensor reading | Significant vibration is detected or ruled out |
| OP-12 | Suspend Risky Activities | Significant vibration is detected | Vibration level | Risky activities are temporarily suspended |
