# Smart Home Project 🏠

A graduation project that simulates an IoT-based Smart Home system using sensors, a central controller, automation rules, and visualization via a web dashboard.

## 📌 Project Components
- **Sensors**: Temperature, Motion (PIR), Gas, Soil Moisture, Water Level, Fire/Smoke
- **Controller**: Python-based logic using MQTT protocol for device communication
- **Automation Roles**: Automated rules triggered by sensor data (e.g., turn on AC when temp > 28°C)
- **Actuators**: Devices that respond to controller commands (lights, fans, valves, etc.)
- **Visualization**: Real-time monitoring through FastAPI or Node-RED dashboards

## 🔧 Tools & Technologies
- Python
- EMQX MQTT Broker
- GNS3 for network simulation
- FastAPI (web interface)
- Node-RED (optional dashboard)
- Docker (for deployment)

## 📁 Repository Structure
- `data.rar` → Contains source code and configurations
- `docs/` → (Optional) Final report, diagrams, etc.
- `code/` → (Optional) Python scripts and automation logic

## 🧠 Project Workflow
1. Sensors collect environmental data
2. Data sent to controller via MQTT
3. Controller evaluates automation conditions and triggers actions
4. Actions are executed through actuators
5. Results and actions are displayed on the dashboard

## 💡 Authors & Contributors
- Hagar Shams
- Mahmoud Ahmed

---

For any questions or collaboration ideas, feel free to open an issue or fork the repo 💬
