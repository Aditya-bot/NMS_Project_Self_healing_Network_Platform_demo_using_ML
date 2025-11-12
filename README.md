# Autonomous Network Healing Platform (Colab Demo)

This repository contains a Google Colab notebook that simulates an **Autonomous Network Healing Platform**.

### What it does
- Builds a virtual self-healing network with simulated web servers & load balancer  
- Runs attack → detect → remediate loop using simple ML (Isolation Forest)  
- Displays a professional **Gradio interface** to control and visualize healing  
- Generates metrics, timelines, and an SVG network architecture diagram  

### Run in Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<YOUR_USERNAME>/<YOUR_REPO>/blob/main/<YOUR_NOTEBOOK>.ipynb)

### Outputs
- `self-heal-architecture.svg` — network topology diagram  
- `metrics_log.csv` — time-series metrics  
- `timeline.csv` — attack / healing events  
- `monitor_actions.csv` — remediation actions  

### Tech Stack
`Flask · Prometheus · IsolationForest · Gradio · Python · Colab`

---
