# Edmonton Neighborhood Explorer

**Live Application**: *[Will be updated after deployment]*  
**Developed by**: [RG-FIDES](https://github.com/RG-FIDES)  
**Client**: Square One Coffee

---

## About This Application

The Edmonton Neighborhood Explorer is an interactive mapping tool that allows users to explore Edmonton's neighborhoods through demographic data and geographic visualization. This application provides insights into population distribution, density patterns, and neighborhood characteristics across the city.

## How to Use

### Interactive Map Features

1. **Neighborhood Selection**
   - Click on any neighborhood on the map to view detailed information
   - Selected neighborhoods are highlighted in yellow
   - A popup displays the neighborhood name and current metric value

2. **Metric Visualization**
   - Use the "Select Metric" dropdown to choose which data to visualize
   - Available metrics are displayed as color-coded choropleth maps
   - Legend shows the range of values and color scale

3. **Map Controls**
   - **Zoom**: Use +/- buttons or mouse scroll wheel
   - **Pan**: Click and drag to move around the map
   - **Reset**: Double-click to return to default view

### Available Metrics

#### Total Population
- **Description**: The total number of residents in each neighborhood
- **Data Source**: 2019 Census Data (Statistics Canada)
- **Color Scale**: Yellow to Red (lighter = fewer residents, darker = more residents)
- **Use Case**: Identify which neighborhoods have the largest populations

#### Population Density (per km²)
- **Description**: Number of residents per square kilometer
- **Calculation**: Total Population ÷ Neighborhood Area
- **Color Scale**: Yellow-Green to Blue (lighter = lower density, darker = higher density)
- **Use Case**: Understand how densely or sparsely populated different areas are

#### None (Gray)
- **Description**: Display neighborhood boundaries without metric overlay
- **Use Case**: Focus on geographic shapes and locations without data visualization

### Data Information

**Snapshot Date**: December 19, 2025  
**Geographic Scope**: City of Edmonton, Alberta, Canada  
**Coordinate System**: WGS84 (EPSG:4326)

## Data Sources

This application uses publicly available data from:
- **City of Edmonton Open Data Portal**: Neighborhood boundaries and geographic information
- **Statistics Canada 2019 Census**: Population and demographic data

All data has been processed and integrated through the Ellis pipeline developed by RG-FIDES.

## Technical Specifications

### Built With
- **R Shiny**: Interactive web application framework
- **Leaflet**: Interactive mapping library
- **Simple Features (sf)**: Spatial data processing
- **RSQLite**: Embedded database

### Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge

### Performance
- Optimized for desktop and tablet viewing
- Mobile responsive design
- Data preloaded for fast interaction

## Contact

For questions about this application or Square One Coffee partnership inquiries:
- **Email**: contact@rg-fides.com
- **GitHub**: [RG-FIDES Organization](https://github.com/RG-FIDES)
- **Square One Coffee**: [squareonecoffee.com](https://squareonecoffee.com)

## License

MIT License - Free to use with attribution

---

*This application is part of the Square One Coffee research partnership focused on data-driven business intelligence and community insights. The project demonstrates reproducible analytical pipeline (RAP) principles and open data integration for business decision support.*
