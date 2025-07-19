# Military Spending Comparison (D3.js Visualization)

This project is a simple D3.js-based SVG visualization comparing military spending between the United States, Russia, and Italy.

## What It Shows

- **USA:** ~$997 billion (2024)
- **Russia:** ~$149 billion (2024)
- **Italy:** ~$35.5 billion (2023)

The visualization uses circle sizes to show the proportion of spending, scaled using `d3.scaleSqrt` so the area of the circles is visually proportional.

## Files

- `index.html`: The main HTML page that includes:
  - Inline D3.js script
  - SVG elements generated based on data
  - Labels and spending values
- *(Optional)* `base.css` and `custom.css`: You can include your own styling here.

## How to Run

You can view this visualization locally using a static server.

### Option 1: Using Python

```bash
python3 -m http.server 8080
