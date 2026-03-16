# Water Use Game

An interactive web application to learn about water footprints and AI environmental impact through an engaging guessing game and data visualization.

## Features

- **Guessing Game**: Compare water usage of everyday items with ChatGPT queries
- **Multiple Visualizations**: Choose between bar charts and scale views for results
- **Estimate Comparison**: View and compare different ChatGPT water usage estimates
- **Educational Content**: Information about water footprints and environmental impact

## Structure

- `index.html`: Main application with tabbed interface
- `data.json`: Contains all water usage data and estimates (easily updatable)
- `README.md`: This file

## Data Management

All water usage data is stored in `data.json` for easy maintenance and updates. The file contains:
- Items with their water footprints
- ChatGPT water usage estimates from various sources

To update data, simply edit `data.json` - no code changes required.

## Running Locally

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`
