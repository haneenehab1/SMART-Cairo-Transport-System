# Cairo Transport System 🚌

This is an interactive Python project built with Streamlit for visualizing and analyzing Cairo's transportation network using maps and graphs.

## Features

- Dynamic transport network built using `NetworkX`
- Interactive map rendering with `Folium`
- Visual analytics with `Plotly`
- Analysis of wait times, traffic signals, and optimal routes

## Requirements

Install the required Python packages using:

```bash
pip install -r requirements.txt
```

## How to Run

To run the application, use:

```bash
streamlit run app.py
```

## Project Structure

- `app.py` – Main Streamlit application interface
- `cairo_transport.py` – Contains the `CairoTransportSystem` class with network logic

## Notes

Currently, the transportation data is generated as sample data within the code.
You can modify the code later to load real transportation data from external files.
