\# 📡 IonoSeis-Kazakhstan

> \*\*NASA Space Apps Challenge 2026 Project\*\* | Real-Time Ionospheric VTEC \& Seismic Anomaly Monitoring System for Almaty Region.



\---



\## 🛰️ Overview

\*\*IonoSeis-Kazakhstan\*\* is an open-source monitoring platform that analyzes Total Electron Content (VTEC) in the ionosphere using \*\*NASA CDDIS / JPL GNSS data\*\* and \*\*NOAA Space Weather APIs\*\*. By tracking dynamic rate-of-change vector ($\\Delta Z$) rather than simple absolute thresholds, the system filters out solar noise ($Kp$-index) and detects pre-seismic ionospheric anomalies prior to earthquakes.



\---



\## ✨ Key Features

\- \*\*Real-Time VTEC Stream\*\*: Live physical modeling aligned with real-time NOAA $F10.7$ and $Kp$ indices.

\- \*\*Solar Disturbance Filtering\*\*: Automatic classification of geomagnetic storms ($Kp \\ge 4.0$) to prevent false alarms.

\- \*\*Dynamic Precursor Detection\*\*: Vector algorithm tracking $\\Delta Z = Z\_{current} - Z\_{min}$ to identify trend builds.

\- \*\*Historical Validation\*\*: Tested against the magnitude 7.0 Almaty earthquake (January 2024) using NASA IONEX maps.

\- \*\*Interactive Dashboard\*\*: Built with Streamlit, Matplotlib, and PyDeck for spatial mapping.



\---



\## 🛠️ Tech Stack

\- \*\*Language\*\*: Python 3.10+

\- \*\*Framework\*\*: Streamlit

\- \*\*Data \& Physics\*\*: NumPy, Pandas, Requests

\- \*\*Visualization\*\*: Matplotlib, PyDeck

\- \*\*Data Sources\*\*: NASA CDDIS (GIM/IONEX), NOAA SWPC (Kp, F10.7), USGS Earthquake API



\---



\## 🚀 Quick Start (Local Run)



1\. \*\*Clone the repository:\*\*

&#x20;  ```bash

&#x20;  git clone \[https://github.com/Alua09/IonoSeis-Kazakhstan.git](https://github.com/Alua09/IonoSeis-Kazakhstan.git)

&#x20;  cd IonoSeis-Kazakhstan

