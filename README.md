# News Article websites Analysis 🌐

This project, developed in collaboration with Ipsos, analyzes news articles across multiple sources to provide SEO recommendations and visualize content relationships. The system combines web scraping, sentiment analysis, and network visualization to deliver insights about content patterns and relationships between news sources.
It was a group project, but the things I worked on individually were:
- slides (design and analysis)
- Network visualization of news sources and their content relationships
- Interactive dashboard for content analysis in python using Dash with:
  - temporal analysis of content trends
  - seo keyword reccomendations
Furthermore my teammates worked on a visualisation using tableau, the data cleaning and the k-means clustering.

## Key Components

### 1. Network Visualization
![Network Visualization Example](path_to_network_visualization.png)

The network visualization component maps relationships between different news sources based on shared content themes and sentiment patterns. Built using NetworkX and Pyvis, it:
- Identifies connections between news sources based on common topics
- Visualizes the strength of relationships through edge weights
- Highlights dominant content themes for each news source
- Uses color coding to distinguish between different types of relationships

### 2. Interactive Dashboard
![Dashboard Screenshot](path_to_dashboard.png)

Created using Dash and Plotly, the dashboard provides:
- Real-time content analysis
- Sentiment distribution visualization
- Temporal trend analysis
- Keyword frequency monitoring
- Custom filtering options by news source and date

### 3. SEO Recommendation System
Built using Beautiful Soup for web scraping and NLTK for text analysis, the system:
- Extracts relevant keywords from successful articles
- Analyzes trending topics over time
- Provides keyword recommendations based on historical performance
- Monitors content patterns across different news sources

## Technologies Used
- **Web Scraping**: Beautiful Soup, Newspaper3k
- **Data Analysis**: Pandas, NLTK, VADER
- **Visualization**: NetworkX, Pyvis, Plotly, Dash
- **Image Processing**: PIL, WordCloud
- **Other**: NumPy, Matplotlib


## Project Structure
```
project/
│
├── Keywords dashboard/
│   ├── assets (css styling)
│   └── Dashboard.ipynb
│
├── Network visualisation/
│   ├── sentiment+network code.ipynb
│   ├── network.html (visualisation)
│
├── Area chart.twbx (Tableau visualisation)
│
└── Presentation pdf
```


