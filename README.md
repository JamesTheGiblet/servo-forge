🤖 ServoForge - Robotics RUL Predictor

ServoForge is a predictive maintenance simulator for Industrial Robotics. It models the Remaining Useful Life (RUL) of robotic actuators based on operating conditions and maintenance strategies.

Designed for the Industry 4.0 context, it demonstrates how "Forge Theory" (Decay Modeling) can prevent costly production line downtime by predicting component failure before it happens.
✨ Key Features

    Stress Modeling: Simulates the non-linear impact of Payload (kg), Temperature (°C), and Speed (m/s) on mechanical wear.

    Intervention Stack: Toggle technologies like Vibration AI Analysis or Auto-Lubrication to see how they flatten the decay curve and extend asset life.

    HMI Aesthetic: Styled to resemble a Siemens/Fanuc factory operator panel with high-contrast data visualization.

    ROI Calculator: Instantly translates "Cycles Gained" into "Capital Expenditure Saved."

🚀 Quick Start

    Open: Load index.html in a browser.

    Stress Test: Increase the Payload and Temperature sliders to see the "Actuator Health" curve steepen and the "Twin" visual turn red.

    Apply Fixes: Toggle Auto-Lubrication on the left panel. Watch the RUL (Remaining Useful Life) extend and the graph flatten out.

    Monitor: Observe the "Predicted Failure" point shift along the X-axis (Cycles).

🧮 The Logic: Mechanical Decay

The tool uses a simplified Arrhenius Equation logic to model component degradation.
Life∝eStress1​

    Stress: A composite score derived from Load, Thermal, and Kinetic energy.

    Threshold: The component is considered "Failed" when Health drops below 20% (the point where precision is lost).

⚠️ Disclaimer

Simulation Only. This tool uses illustrative physics models for demonstration. Real-world predictive maintenance requires historical dataset training (Digital Twins) and specific manufacturer load curves.
📄 License

Open Source. Intended for Industrial IoT (IIoT) dashboard prototyping and pre-sales.
