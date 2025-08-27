# Maritime Intelligence Monitoring System (Demo Project)

This is a **demonstration project** showcasing Business Intelligence (BI) skills using **Prometheus** and **Grafana**. It simulates maritime data to create dashboards, alerts, and visualizations. **This project is for demonstration purposes only** and is **not intended for real-world maritime monitoring**.

## Features

* **Simulated Maritime Data**: Generates maritime metrics for demonstration.
* **Prometheus Integration**: Collects and stores time-series data.
* **Grafana Dashboards**: Visualize data trends, patterns, and anomalies.
* **Alerting Demo**: Showcases how alerts can be configured based on metrics.
* **Dockerized**: Easy to run in any environment.

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/FoshuaJong/Maritime-Intelligence-Monitoring-System-using-Prometheus-and-Grafana
cd Maritime-Intelligence-Monitoring-System-using-Prometheus-and-Grafana
```

2. **Set up Docker containers**

```bash
docker-compose -f .\docker\docker-compose.yml build
docker-compose -f .\docker\docker-compose.yml up -d
```

3. **Configure Prometheus**
   Adjust `monitoring/` configuration if needed to simulate different metrics.

4. **Launch Grafana**
   Open `http://localhost:3000`, connect Prometheus as a data source, and explore the demo dashboards.


## Using the premade Grafana Dashboards
1. Run the Docker Setup
2. Go into Grafana `http://localhost:3000` -> Dashboards -> Import
3. Upload the `.json` files in `grafana-dashboards/`

## Grafana Dashboard screenshots
![Shipping Companies / Fleet Operators](https://github.com/FoshuaJong/Maritime-Intelligence-Monitoring-System-using-Prometheus-and-Grafana/tree/main/grafana-dashboards/images/dashboard_screenshot.png)
![Port Authorities / Terminal Operators](https://github.com/FoshuaJong/Maritime-Intelligence-Monitoring-System-using-Prometheus-and-Grafana/tree/main/grafana-dashboards/images/dashboard_screenshot_1.png)

## Notes

* **Demo Only**: All data is simulated for demonstration purposes.
* **Not for Operational Use**: This system is **not connected to real maritime systems**.

## Requirements

* Docker & Docker Compose
* Python 3.x

## License

MIT License
