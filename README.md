# 🚦 TrafficSimX

**TrafficSimX** is an advanced traffic simulation and visualization tool built entirely in R. It combines real-time heatmap visualizations, route optimization, and vehicle simulation using a modern R dashboard powered by Shiny.

### 🔧 Features

- **Live Traffic Heatmaps** – Simulate congestion with dynamic map visuals using `leaflet` and `leaflet.extras`.
- **Route Optimization** – Boosted by C++ code via `Rcpp`, for high-speed calculations.
- **Simulation Controls** – Adjust vehicle speed and traffic density to observe changes instantly.
- **Vehicle & Infrastructure Analytics** – Detailed tables and debug info for all simulation entities.
- **Fully Interactive UI** – Built with `shinydashboard` for seamless user experience.
- **Modular R Package** – Structured for scalability, version control, and easy deployment.

### 🛠 Technologies Used

- R, Shiny, Leaflet, `Rcpp`, `R6`, S3/S4 OOP, `data.table`, `jsonlite`
- C++ (via Rcpp) for route optimization
- Full R package ecosystem: `devtools`, `roxygen2`, `LinkingTo`

### 🚀 How to Launch the App

```r
library(TrafficSimX)
run_traffic_simulation_app()
```

### 📁 Package Structure

- `R/`: R scripts and simulation logic (OOP, UI)
- `src/`: C++ source code (`route_optimizer.cpp`)
- `inst/`: Assets and support files
- `NAMESPACE` & `DESCRIPTION`: Package metadata and exports

### 📌 Author

Mirzakalonboy Khamidov  
Version: **0.3.0**
