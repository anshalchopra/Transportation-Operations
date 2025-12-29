# Generating Synthetic Logistics Dataset

## Dataset Overview
This synthetic logistics operations dataset simulates end-to-end trucking workflows enriched with onboard IoT telematics and environmental context.

Each truck is equipped with a simulated IoT telematics unit that continuously captures in-vehicle and cargo-bay environmental conditions, including temperature and humidity, alongside standard GPS telemetry. The same device also retrieves external weather conditions (ambient temperature, humidity, rainfall, wind, and visibility) via internet-based weather services based on the truck’s current geolocation.

Trucks transmit geolocation updates at fixed intervals, interleaved with operational events such as dispatch, loading start/end, in-transit, stalled, refueling, and delivered. These event logs represent the operational state of the truck and shipment throughout the journey.

Each shipment includes detailed payload characteristics—weight, product category, and volume occupied—along with loading and unloading times. Trucks have defined capacity constraints and cost structures, enabling realistic modeling of utilization, delays, and cost drivers.

Cost data is modeled using industry-aligned logistics economics, incorporating fixed vehicle costs, distance-based operating costs, fuel consumption influenced by driving conditions, and driver labor costs.

By combining GPS trajectories, operational events, onboard sensor readings, external weather context, and cost structures, the dataset is designed to support operations analytics use cases. such as ETA prediction, service-level risk monitoring (especially for perishable goods), bottleneck identification, cost optimization, and root-cause analysis of delays.

## Key Analytical Use Cases
1. Route Optimisation
2. ETA Prediction
3. Cost Optimisation
4. Risk Monitoring
5. Demand Forecasting



