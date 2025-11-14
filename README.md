# 🏠 Interactive US Housing Cost Visualization

> An interactive SVG map visualization displaying US housing market data from 2010-2018, featuring dynamic year-based filtering and comprehensive housing cost metrics.

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://shannon-goddard.github.io/Correlation_vs_Causation/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Data Source](https://img.shields.io/badge/Data-US%20Census-orange)](https://data.census.gov)

## 📋 Table of Contents

- [🎯 Project Overview](#-project-overview)
- [✨ Features](#-features)
- [🛠️ Technologies](#️-technologies)
- [📊 Data](#-data)
- [🚀 Live Demo](#-live-demo)
- [💻 Local Development](#-local-development)
- [🔗 Related Projects](#-related-projects)
- [📄 License](#-license)

## 🎯 Project Overview

This interactive visualization presents US housing market data through an engaging SVG map interface. Users can explore housing costs, property values, income levels, and tax information across all 50 states from 2010 to 2018. The project demonstrates effective data visualization techniques using vanilla JavaScript and jQuery.

**Key Highlights:**
- Interactive state-by-state exploration
- Year-based data filtering (2010-2018)
- Comprehensive housing market metrics
- Responsive design with hover tooltips
- Clean, accessible user interface

## ✨ Features

### 🗺️ Interactive Map
- **Hover Effects**: Real-time data display on state hover
- **Dynamic Tooltips**: Contextual information with smooth animations
- **Year Selection**: Dropdown filter for temporal data exploration
- **Responsive Design**: Optimized for desktop and mobile devices

### 📈 Data Visualization
- **Home Values**: Median home prices by state and year
- **Housing Costs**: Monthly housing cost estimates
- **Income Data**: Median household income statistics
- **Tax Information**: Property tax data where available
- **Loan Percentages**: Second mortgage and equity loan rates

### 🎨 User Experience
- Clean, intuitive interface
- Smooth hover animations
- Mobile-friendly responsive design
- Fast loading and performance optimized

## 🛠️ Technologies

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Libraries**: jQuery 2.2.4, D3.js 5.15.0
- **Graphics**: SVG for scalable map visualization
- **Data**: JSON format for efficient data handling
- **Hosting**: GitHub Pages

## 📊 Data

### Data Source
- **Primary**: [US Census Bureau](https://data.census.gov)
- **Coverage**: All 50 US states + DC
- **Time Period**: 2010-2018 (9 years)
- **Metrics**: 6 key housing and economic indicators per state/year

### Data Structure
```javascript
{
  Year: "2018",
  id: "CA",
  State: "California",
  HomeValue: "$566,100",
  Loan: "12.9%",
  Income: "$113,027",
  Cost: "$2,345",
  Taxes: "$4,479"
}
```

## 🚀 Live Demo

**[🌐 View Interactive Map](https://shannon-goddard.github.io/Correlation_vs_Causation/)**

![Map Demo](/mapgif.gif)

### How to Use:
1. **Select Year**: Use the dropdown to choose a year (2010-2018)
2. **Explore States**: Hover over any state to view detailed data
3. **Compare**: Switch between years to see market trends
4. **Analyze**: Use the data to understand regional housing patterns

## 💻 Local Development

### Prerequisites
- Modern web browser
- Local web server (optional, for CORS)

### Setup
```bash
# Clone the repository
git clone https://github.com/shannon-goddard/Correlation_vs_Causation.git

# Navigate to project directory
cd Correlation_vs_Causation

# Open in browser or serve locally
# Option 1: Direct file access
open index.html

# Option 2: Local server (Python)
python -m http.server 8000
# Then visit: http://localhost:8000

# Option 3: Local server (Node.js)
npx serve .
```

### File Structure
```
├── index.html          # Main HTML file
├── main.css           # Styling and responsive design
├── main.js            # Interactive functionality
├── data.js            # Housing market dataset
├── header.png         # Project header image
├── mapgif.gif         # Demo animation
└── README.md          # Project documentation
```

## 🔗 Related Projects

This visualization is part of a larger housing market analysis ecosystem:

### 🏖️ Leaving California Dashboard
- **Live Demo**: [AWS Hosted Dashboard](http://leavingcabucket.s3-website.us-east-2.amazonaws.com/)
- **Repository**: [Leaving California Analysis](https://github.com/JVChermak/Leaving_California.git)
- **Description**: Comprehensive analysis of California housing market trends and migration patterns

## 🎓 Educational Context

**UC Berkeley Data Analytics Bootcamp Project**
- **Course**: Data Visualization and Analytics
- **Focus**: Interactive web-based data visualization
- **Skills Demonstrated**: JavaScript, jQuery, SVG manipulation, data processing
- **Team**: Collaborative bootcamp final project

## 📄 License

### Project License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Third-Party Licenses
- **SVG Map**: Based on [WebsiteBeaver's Interactive US Map](https://websitebeaver.com/how-to-make-an-interactive-and-responsive-svg-map-of-us-states-capitals)
- **License**: [MIT License](https://github.com/WebsiteBeaver/interactive-and-responsive-svg-map-of-us-states-capitals/blob/master/LICENSE)

---

**Built with ❤️ for data visualization and housing market analysis**

*Part of UC Berkeley Data Analytics Bootcamp • Connected to the Leaving California project ecosystem*