# News Article websites Analysis 🌐

This project, developed for Ipsos as a class project using their dataset, analyzes news articles across multiple sources to provide SEO recommendations and visualize content relationships. The system combines web scraping, sentiment analysis, and network visualization to deliver insights about content patterns and relationships between news sources.
It was a group project, but the things I worked on individually were:
- slides (design and analysis)
- Network visualization of news sources and their content relationships
- Interactive dashboard for content analysis in python using Dash with:
  - temporal analysis of content trends
  - seo keyword reccomendations
Furthermore my teammates worked on a visualisation using tableau, the data cleaning and the k-means clustering.

## Key Components

### 1. Network Visualization
<img src="https://github.com/laurazecca01/visualising-internet-data-markerting-analytics/blob/main/graph_previews/Screenshot%202025-01-14%20at%2012.00.41.png?raw=true" width="400" alt="Network Visualization Example">


The network visualization component maps relationships between different news sources based on shared content themes and sentiment patterns. Built using NetworkX and Pyvis, it:
- Identifies connections between news sources based on common topics
- Visualizes the strength of relationships through edge weights
- Highlights dominant content themes for each news source
- Uses color coding to distinguish between different types of relationships
- Nodes indicate publishers, with the size reflecting the volume of articles published—larger nodes represent publishers with more article
- Users can filter topics to explore specific areas of interest within the network

Potential Application for Advertisers: For advertisers, this visualization helps identify key publishers for campaigns by showing which sources have significant content output and shared themes, facilitating more effective advertising strategies.

### 2. Interactive Dashboard with SEO Recommendation System
<img src="https://github.com/laurazecca01/visualising-internet-data-markerting-analytics/blob/main/graph_previews/Screenshot%202025-01-14%20at%2012.01.39.png?raw=true" width="400" alt="graph1">


Created using Dash and Plotly, the dashboard provides:
- Real-time content analysis by monitoring content patterns across different news sources
- Sentiment distribution visualization
- Custom filtering options by news source and date
- Keyword frequency monitoring

  <img src="https://github.com/laurazecca01/visualising-internet-data-markerting-analytics/blob/main/graph_previews/Screenshot%202025-01-14%20at%2012.01.18.png?raw=true" width="400" alt="graph2">
  
- Showcases keywords from successful articles and trending topics over time
- Temporal trend analysis


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


