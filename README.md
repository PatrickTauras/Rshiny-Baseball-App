# R Shiny Baseball App

## Overview

This project is an R Shiny application that allows users to explore baseball player statistics from 2010 to 2022. Users can select either pitchers or batters and view various statistics through dynamic visualizations and interactive tables.

## Features

- **Player Type Selection**: Choose between pitcher and batter.
- **Dynamic Sliders**: Adjust filters for various statistics like strikeouts, ERA, WHIP, hits, home runs, etc.
- **Interactive Table**: View and filter player data based on selected criteria.
- **Visualizations**: Display player statistics over the selected years using plots.

## Detailed Explanation

### **Pitcher Side**
- **Year Range**: Select the range of years to focus on pitcher statistics within a specific timeframe.
- **Strikeouts**: Filter pitchers by the number of strikeouts achieved during the selected years.
- **ERA (Earned Run Average)**: Filter pitchers by their ERA, indicating earned runs allowed per nine innings pitched.
- **WHIP (Walks plus Hits per Inning Pitched)**: Filter pitchers by WHIP, measuring the number of baserunners allowed per inning.
- **Innings Pitched**: Filter based on the total number of innings pitched during the selected seasons.
- **Games Started**: Filter by the number of games a pitcher started, focusing on starting pitchers.
- **Hits Allowed**: Filter by the number of hits a pitcher allowed during the selected years.

### **Batter Side**
- **Year Range**: Select the range of years to filter batter data.
- **Hits**: Filter batters based on the number of hits achieved.
- **Home Runs**: Filter batters by the number of home runs hit, indicating power.
- **RBIs (Runs Batted In)**: Filter batters by RBIs, showing how many runs they drove in.
- **Runs**: Filter batters by the total number of runs they scored.
- **Stolen Bases**: Filter by the number of bases a batter stole, indicating speed.

## Selecting Individual Players and Comparing Performance

- **Selecting Individual Players**: Use the search bar at the top right of the data table to type in a player's name. This will filter the table to show only the records of the selected player. You can select multiple records (e.g., different years) to compare the performance of the same player over time.

- **Graphical Comparison**: After selecting the records of interest, the plots below the table will automatically update to reflect the selected data. You can visually compare how a player's statistics (such as hits, home runs, ERA, etc.) have changed over the years, or compare multiple players by selecting their records.

## Instructions

1. **Run the App**: The app can be run directly in RStudio using the `shinyApp(ui, server)` function.
2. **Navigate**: Use the radio buttons and sliders to filter and explore player data.
3. **Explore**: View detailed plots for selected player statistics.

