# Music X Mental Health Dashboard

This project visualizes the relationship between music preferences and mental health issues using Tableau. It explores how different music genres and streaming platforms correlate with mental health conditions such as anxiety, depression, insomnia, and OCD.

## Context

Music therapy (MT) uses music to improve an individual's stress, mood, and overall mental health. MT is recognized as an evidence-based practice, using music to stimulate the production of "happy" hormones such as oxytocin. However, MT employs a wide range of different genres, which vary from one organization to the next.

The MxMH dataset aims to identify correlations between an individual's music taste and their self-reported mental health. These findings could contribute to a more informed application of MT or provide interesting insights about the mind.

## Data Description

### Blocks in the Data

- **Block 0: Background**
  - Respondents answer generic questions focused on their musical background and listening habits.

- **Block 1: Music Genres**
  - Respondents rank how often they listen to 16 music genres, selecting from:
    - Never
    - Rarely
    - Sometimes
    - Very frequently

- **Block 2: Mental Health**
  - Respondents rank their experiences with Anxiety, Depression, Insomnia, and OCD on a scale of 0 to 10:
    - 0 - I do not experience this.
    - 10 - I experience this regularly, constantly, or to an extreme.

Additional data that does not fall in these blocks may provide useful background information. See the column descriptors for more details.

### Data Collection

Data collection was managed by @catherinerasgaitis via a Google Form. Respondents were not restricted by age or location. The form was posted in various Reddit forums, Discord servers, and social media platforms. Posters and "business cards" were also used to advertise the form in libraries, parks, and other public locations. The form was designed to be brief to encourage completion, and more challenging questions (such as BPM) were optional for the same reason.

## Dashboard Overview

![Dashboard Image](./images/music-mental-health-dashboard.png)

The dashboard includes the following visualizations:

- **Summary Metrics**: Displays average scores for Anxiety, Depression, Insomnia, and OCD.
- **Frequency Distribution by Music Effect**: Shows how different music genres affect mental health over time.
- **Average Anxiety by Age**: Visualizes average anxiety levels across different age groups.
- **Hours on Streaming Platforms**: Pie chart showing the distribution of hours spent on different music streaming platforms.
- **Favorite Genre by Age**: Heatmap indicating the favorite music genres of different age groups.

## Files

- `tableau/music_mental_health_dashboard.twbx`: The Tableau workbook file.
- `data/`: Directory for any raw data files used.
- `images/music-mental-health-dashboard.png`: Image of the dashboard.

## Instructions

1. Open the `music_mental_health_dashboard.twbx` file in Tableau.
2. Explore the different visualizations to understand the relationship between music and mental health.

## Dependencies

- Tableau Desktop version 2021.1 or later.

## Acknowledgements

- Data collection by @catherinerasgaitis.
- Survey distribution via Reddit, Discord, and social media platforms.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For any questions or feedback, please contact [Your Name] at [Your Email].

