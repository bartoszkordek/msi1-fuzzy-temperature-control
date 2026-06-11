# Proactive Intelligent HVAC Controller using Fuzzy Logic

A production-grade, knowledge-based expert system designed in Python to optimize human thermal comfort and energy efficiency in HVAC units.

## 🛠️ Tech Stack & Methods
- **Language:** Python 3.13
- **Libraries:** scikit-fuzzy, NumPy, Matplotlib
- **Inference Engine:** Mamdani Fuzzy Inference Method
- **Defuzzification:** Center of Gravity (Centroid) Method

## 🧠 Core Architecture
The system dynamically maps **4 crisp input variables** into an optimized **100-point power scale output** utilizing a conflict-free matrix of **19 linguistic rules**:
1. **Temperature Error (°C):** Internal deviation from setpoint (5 membership functions).
2. **Temperature Trend (°C/h):** Rate of indoor climate change (3 membership functions).
3. **Relative Air Humidity (%):** Human thermal perception modifier (3 membership functions).
4. **Outdoor Temperature (°C):** Feed-forward environmental loss anticipation (4 membership functions).

## 📊 Analytical Insights
The repository includes advanced 3D Control Surface generation scripts mapping non-linear decisions like "humidity penalties" and proactive multi-variable weather boundaries.