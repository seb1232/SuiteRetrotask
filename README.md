# Agile Project Management Suite

A dynamic Streamlit application designed for Agile project management, combining Sprint Task Planning and Retrospective Analysis in a single, interactive interface with Apple-inspired animations and design.

## Features

### Sprint Task Planner
- Intelligent task distribution across sprints
- Fair distribution of tasks with different priorities
- Optimal capacity utilization across team members
- Remaining capacity is carried forward between sprints
- Integration with Azure DevOps for task updates
- Export results in Excel or CSV formats

### Retrospective Analysis Tool
- Process and analyze feedback from multiple retrospectives
- Consolidate feedback with vote counts
- Visualize results with interactive charts
- Generate insights with AI assistance
- Compare data across multiple retrospective sessions

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/agile-project-management-suite.git
cd agile-project-management-suite

# Install dependencies
pip install -r requirements.txt
```

## Usage

```bash
# Run the Streamlit app
streamlit run app.py
```

## Dependencies

- streamlit
- pandas
- numpy
- matplotlib
- plotly
- msal (for Azure DevOps integration)
- openpyxl (for Excel export)

## Project Structure

```
.
├── app.py                 # Main Streamlit application
├── .streamlit/            # Streamlit configuration
│   └── config.toml        # Streamlit settings
├── assets/                # Static assets
│   ├── animations.js      # JavaScript animations
│   ├── apple_style.css    # CSS styling
│   ├── animations.css     # Animation styles
│   ├── welcome_animation.svg  # SVG animation
│   └── banner.svg         # Banner image
└── requirements.txt       # Project dependencies
```

## Contributors

- Your Name

## License

MIT
