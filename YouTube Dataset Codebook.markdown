# Codebook for YouTube Channels Dataset

## Dataset Description
This dataset contains information about the top YouTube channels as of may 2019. It includes details such as the channel's rank, name, subscriber count, total video views, number of videos, category, and the year the channel was started. The data is useful for analyzing trends in YouTube channel popularity and content categories.

## Variable Descriptions

| Variable Name | Class    | Description                                    | Example Value      |
|---------------|----------|------------------------------------------------|--------------------|
| rank          | integer  | The ranking of the YouTube channel by subscribers | 1                  |
| Youtuber      | character| The name of the YouTube channel                | "T-Series"         |
| subscriber    | numeric  | The number of subscribers to the channel       | 222000000          |
| video view    | numeric  | The total number of views across all videos    | 196000000000       |
| video count   | integer  | The total number of videos uploaded            | 17317              |
| category      | factor   | The primary content category of the channel    | "Music"            |
| started       | date     | The year the YouTube channel was created       | 2006               |
