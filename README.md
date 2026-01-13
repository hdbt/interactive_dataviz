# Interactive Data Visualization Course

A comprehensive course on creating interactive data visualizations using R Shiny, Flexdashboards, and popular R visualization frameworks.

## 📚 Course Overview

This repository contains materials for an Interactive Data Visualization course taught at the University level. The course provides hands-on experience with:

- **R Shiny**: Building reactive web applications
- **Flexdashboards**: Creating interactive dashboards
- **Interactive Visualization Frameworks**: plotly, highcharter, leaflet, DT (DataTables)
- **R Markdown**: Generating dynamic reports and presentations

## 🎯 Learning Objectives

By completing this course, you will be able to:

1. Write and deploy Shiny applications
2. Understand Shiny's capabilities and reactive programming
3. Work with popular interactive data visualization frameworks
4. Create interactive dashboards using Flexdashboard
5. Publish and share your interactive visualizations

## 📂 Repository Structure

```
interactive_dataviz/
├── index.Rmd                          # Main course dashboard
├── interactive_viz.Rmd                # Interactive visualization examples
├── datacamp.Rmd                       # Bike share dashboard example
├── exercises.Rmd                      # Course exercises
├── extra.Rmd                          # Additional materials
├── flex.Rmd                           # Flexdashboard examples
├── interactive_viz_slides.Rmd         # Slide deck overview
├── slides/
│   ├── slides1.Rmd                    # Main course presentation
│   └── slides-figure/                 # Course images and assets
└── *.html                             # Generated HTML outputs
```

## 🚀 Getting Started

### Prerequisites

Install R (version 4.0 or higher) and RStudio. Then install the required packages:

```r
# Core packages
install.packages("shiny")
install.packages("flexdashboard")
install.packages("rmarkdown")

# Visualization packages
install.packages("plotly")
install.packages("highcharter")
install.packages("leaflet")
install.packages("DT")

# Data manipulation
install.packages("dplyr")
install.packages("tidyverse")
install.packages("lubridate")

# Themes and styling
install.packages("bslib")
install.packages("shinythemes")
install.packages("shinyWidgets")
install.packages("thematic")

# Additional packages
install.packages("ggplot2")
install.packages("broom")
```

### Running the Course Materials

1. **Clone the repository**:
   ```bash
   git clone https://github.com/hdbt/interactive_dataviz.git
   cd interactive_dataviz
   ```

2. **Open in RStudio**:
   - Open `index.Rmd` to access the main course dashboard
   - Knit the file to HTML to view the interactive course content

3. **Explore individual components**:
   - Open any `.Rmd` file in RStudio
   - Click "Knit" or run code chunks interactively

## 📖 Course Content

### Session I: Introduction to Shiny

#### Topics Covered:
- **Basic Shiny Structure**: UI and Server functions
- **Layouts**: `fluidPage()`, `sidebarLayout()`, `titlePanel()`
- **Inputs**: Text input, numeric input, sliders, dropdowns
- **Outputs**: Text, plots, tables
- **Reactive Programming**: Understanding reactivity
- **Observers**: `observe()`, `observeEvent()`, `updateInput()` functions

#### Key Exercises:
1. **Exercise 0**: Running your first Shiny app (Old Faithful Geyser)
2. **Exercises 1-3**: Building layouts with HTML tags and bootstrap themes
3. **Exercises 4-4.4**: Working with inputs, outputs, and reactive expressions
4. **Exercises 5-7**: Creating interactive plots with ggplot2
5. **Exercise 8**: Adding download functionality
6. **Exercise 9**: Customizing themes with bslib
7. **Exercise 10**: Deploying to shinyapps.io
8. **Exercise 11**: Advanced observers and input updates
9. **Exercise 12**: Using plot outputs as inputs (brushing)

### Session II: Interactive Visualizations

#### Frameworks Covered:

##### 1. **plotly**
- Convert ggplot2 graphics to interactive plots with `ggplotly()`
- Create custom interactive plots with plotly syntax
- Add tooltips, zoom, and pan functionality

##### 2. **highcharter**
- Professional interactive charts
- Multiple series and chart types
- Responsive design

##### 3. **leaflet**
- Interactive maps
- Markers, popups, and layers
- Geospatial visualizations

##### 4. **DT (DataTables)**
- Interactive, searchable data tables
- Filtering and pagination
- Export functionality

### Session III: Flexdashboards and R Markdown

- Creating multi-page dashboards
- Combining multiple visualizations
- Responsive layouts
- Embedding Shiny in dashboards
- Creating presentations with ioslides
- Publishing to RPubs

## 💡 Example Applications

### 1. Bike Share Dashboard (`datacamp.Rmd`)
An interactive dashboard analyzing San Francisco bike share data:
- Interactive map showing trip origins
- Time-based trip analysis
- Filtering by region
- Real-time value boxes

### 2. Diamond Price Explorer
Interactive exploration of diamond prices with:
- Variable selection
- Multiple plot types (histogram, frequency, density)
- ggplot2 integration
- Theme customization

### 3. Real-time Data Updates
Example using `invalidateLater()` for scheduled updates:
- Live regression fitting
- Animated visualizations
- Dynamic data generation

## 🌐 Deployment

### Deploying to shinyapps.io

1. Create an account at [shinyapps.io](https://www.shinyapps.io)
2. Install the rsconnect package:
   ```r
   install.packages("rsconnect")
   ```
3. Configure your account credentials
4. Deploy your app:
   ```r
   rsconnect::deployApp()
   ```

### Publishing R Markdown to RPubs

1. Create an account at [RPubs](https://rpubs.com/)
2. Click "Publish" button after knitting your document
3. Follow the prompts to publish

## 📚 Additional Resources

- [Shiny Official Documentation](https://shiny.rstudio.com/)
- [Mastering Shiny Book](https://mastering-shiny.org/)
- [Flexdashboard Documentation](https://pkgs.rstudio.com/flexdashboard/)
- [plotly for R](https://plotly.com/r/)
- [highcharter Documentation](https://jkunst.com/highcharter/)
- [leaflet for R](https://rstudio.github.io/leaflet/)
- [R Markdown Guide](https://bookdown.org/yihui/rmarkdown/)
- [bslib Package](https://rstudio.github.io/bslib/)

## 🎓 Course Requirements

**For 1 ECTS point:**
- Write your own Shiny app or Flexdashboard
- Present it in Session II

## 🤝 Contributing

This is a course repository. If you find issues or have suggestions for improvements, please open an issue or submit a pull request.

## 📄 License

This course material is provided for educational purposes. Please cite appropriately if you use or adapt these materials.

## 🔗 Download Course Materials

You can download all course materials as a ZIP file from the GitHub repository or use the download link provided in the course dashboard.

---

**Course Date**: April 26, 2022  
**Last Updated**: January 13, 2026
