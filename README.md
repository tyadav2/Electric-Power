# Electric-Power

This R code sets up a Shiny web application for visualizing and analyzing energy generation data from the United States for the years 1990 to 2019. Here's a breakdown of what the code does:

1. **Data Preparation**:
   - Reads in a CSV file named "annual_generation_state.csv" containing energy generation data.
   - Cleans up the data, filtering out irrelevant entries and converting data types as needed.

2. **User Interface (UI)**:
   - Sets up a navbarPage layout with different tabs for different types of visualizations and data.
   - Includes tabs for stacked bar charts, line charts, table data, state comparison, map comparison, and an "About" tab.

3. **Server**:
   - Defines various reactive functions that generate plots and tables based on user inputs.
   - For example, when users select specific energy sources or years, the corresponding plots and tables are updated accordingly.
   - Renders plots using ggplot2 and maps using usmap package.
   - Sets up interactivity for selecting energy sources, years, and states for comparison.

4. **Visualization**:
   - Includes stacked bar charts, line charts, tables, and maps to visualize energy generation data.
   - Allows users to compare energy generation between different states, energy sources, and years.

5. **About Tab**:
   - Provides information about the data source and the developer of the application.

6. **ShinyApp**:
   - Combines the UI and server components to create the Shiny web application.

Overall, this code creates an interactive dashboard that allows users to explore and analyze energy generation data for different states in the United States over a span of several years.
