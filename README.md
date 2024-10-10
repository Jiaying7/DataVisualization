# Chess Popularity Data Visualization

This project explores the resurgence of chess in the digital age, particularly focusing on how the Netflix series *The Queen's Gambit* and modern chess influencers, like GothamChess, have impacted chess popularity worldwide. Using Google Trends data, this project visualizes the correlation between *The Queen's Gambit* viewership and chess-related online searches.

## Project Overview

The project aims to analyze the influence of modern media on the popularity of chess by tracking search trends from 2020-2023. The data reveals how chess has evolved from a traditional game to a trending online topic due to media representations and content creation on platforms like Twitch and YouTube.

### Key Objectives:
- Analyze the impact of *The Queen's Gambit* on chess popularity.
- Explore how content creators like GothamChess have contributed to further spikes in interest.
- Visualize trends using Tableau to create insightful comparisons between different time periods.

## Data Description

The dataset was gathered from **Google Trends**, specifically tracking weekly searches for "chess" and "The Queen's Gambit" worldwide. After data cleaning and filtering, the dataset spans from 2020 to 2023 to focus on relevant timeframes for the popularity spikes.

- **Attributes**:
  - `Week`: Weekly data points (from 2020-2023).
  - `The Queen's Gambit (Worldwide)`: Number of searches related to *The Queen's Gambit*.
  - `Chess (Worldwide)`: Number of chess-related searches worldwide.

## Data Cleaning Process

1. Removed irrelevant data before 2020 to focus on trends relevant to *The Queen's Gambit*.
2. Addressed the "<1" issue in the dataset by replacing it with "0" to ensure compatibility with Tableau.
3. Verified that there were no blanks in the data columns before importing it to Tableau.

## Visualization

The main visualization uses a **line chart** to display the weekly Google search hits for both "chess" and *The Queen's Gambit*. The graph enables users to observe the clear correlation between the surge in chess searches and the release of the show in late 2020.

### Visualization Highlights:
- **Purple line**: Chess search trends.
- **Green line**: *The Queen's Gambit* search trends.
- The visual highlights the peak in searches following the release of *The Queen's Gambit*, demonstrating a substantial media influence on chess popularity.

## Tools and Libraries

- **Tableau Desktop**: Used for creating the line chart to visualize the trends over time.
- **Google Sheets**: Used for initial data cleaning and preparation before importing the data into Tableau.
- **Microsoft Excel**: Used for further manipulation of the dataset, if needed.

## Conclusion

The data reveals a significant correlation between the release of *The Queen's Gambit* and the increase in chess-related searches worldwide. Even after the show's release, chess remained a trending topic, further boosted by modern chess content creators on platforms like YouTube and Twitch.

## Future Improvements

- **Interactive Features**: Adding filters or interactive elements to allow users to engage more deeply with the data.
- **Annotations**: Highlight key events, such as the release date of *The Queen's Gambit*, to provide more context.
- **Comparative Analysis**: Include data from other cultural phenomena to broaden the context of how media influences public interests.

## References

1. [Google Trends - Chess & The Queen's Gambit](https://trends.google.com/trends/explore?date=today%205-y&q=%2Fg%2F11h8yyk4xy,chess)
2. [New York Times - Chess is Booming](https://www.nytimes.com/2022/06/17/crosswords/chess/chess-is-booming.html)
3. Other sources related to failed data collection and alternative activities.

## License

This project is licensed under the MIT License.
