# CONNECT – 3rd Party Integrations & Environmental Data

TC-Platform is designed to flexibly connect to any external system, sensor, or data source.  
This document summarizes possible integrations, examples, and community-contributed solutions.

---

## Environmental Data Integration

- **Home Assistant:**  
  Home Assistant can write timestamped environmental data (e.g., temperature, humidity) to InfluxDB.  
  The TC system can automatically associate these data points with test runs.
- **Other BMS systems:**  
  KNX, Modbus, BACnet, etc. – any system capable of writing data to InfluxDB or other databases can be integrated.
- **Example:**  
  Environmental data queried at the time of the test run can be automatically included in the report.

---

## Adapters & Plugins

- **USB, LAN, WiFi, MQTT, REST API** – any 3rd party device or software can be integrated.
- **Examples:**  
  - Custom or commercial instruments  
  - IoT sensors  
  - Cloud-based data collection  
  - Custom adapters, protocol converters

---

## Community Suggestions

If you have an idea, integration example, or want to share your own solution, open an issue or pull request!

---

**The goal of TC-Platform is to be an open, extensible, and integrable test ecosystem for everyone.**
