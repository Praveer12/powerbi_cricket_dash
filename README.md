## Live IPL Scores Power BI Dashboard
![View](https://github.com/Praveer12/powerbi_cricket_dash/blob/master/Images/ipl_show_page.png?raw=true)

### Project Overview

This Power BI Dashboard is designed to display live IPL scores in real-time, leveraging the Cricbuzz API available through RapidAPI. This advanced project integrates multiple DAX queries and functions to provide a dynamic and interactive user experience, showcasing various aspects of ongoing cricket matches.

### Key Features

- **Live Score Updates**: Fetches and displays real-time scores, ball-by-ball commentary, and other match details using the Cricbuzz API.
- **Detailed Team and Player Statistics**: Presents comprehensive statistics for both batting and bowling teams, including player performance metrics.
- **Interactive Visualizations**: Utilizes Power BI’s visualization capabilities to create interactive charts and graphs, making it easy to analyze match data.
- **Dynamic Filtering**: Allows users to filter data based on specific teams, players, or match details, providing customized views of the data.
- **Advanced Data Transformations**: Implements complex data transformations using DAX and Power Query to ensure accurate and meaningful data representation.
- **Team Logos and Images**: Integrates team logos and player images to enhance the visual appeal of the dashboard.

### Technical Details

- **API Integration**: The dashboard integrates with the Cricbuzz API via RapidAPI to fetch live match data. The API requests are handled using Power Query’s `Web.Contents` function, which retrieves JSON data from the API endpoints.
- **Data Transformation**: The raw JSON data is transformed using Power Query to expand nested records and columns, making the data suitable for visualization. This involves several steps, such as converting lists to tables, expanding records, and renaming columns.
- **DAX Queries**: Advanced DAX (Data Analysis Expressions) queries are used to create calculated columns and measures, enabling complex calculations and data aggregations. These DAX functions facilitate the creation of dynamic and interactive visualizations.
- **Error Handling**: Implements robust error handling to manage API errors and ensure the dashboard remains functional even when data retrieval issues occur.

### How It Works

1. **API Request**: The dashboard sends an HTTP GET request to the Cricbuzz API endpoint using the provided API key.
2. **Data Retrieval**: The API returns JSON data containing live match information, including scores, player statistics, and team details.
3. **Data Transformation**: Power Query processes the JSON data, expanding and transforming it into a structured format suitable for Power BI.
4. **Visualization**: The transformed data is visualized using various Power BI charts and graphs, allowing users to interact with and analyze the live match data.
5. **Dynamic Updates**: The dashboard updates in real-time as new data becomes available, ensuring users always have access to the latest match information.

### Conclusion

This Power BI Dashboard project is a comprehensive solution for cricket enthusiasts and analysts who want to stay updated with live IPL scores and in-depth match statistics. By integrating with the Cricbuzz API and leveraging the powerful capabilities of Power BI, this project delivers an advanced, interactive, and visually appealing dashboard that enhances the user experience.
