# Bike Share Data Analysis

This project explores data related to bike share systems for three major cities in the United States—Chicago, New York City, and Washington. The analysis is performed using Python, numpy, and pandas libraries to import the data and compute descriptive statistics.

## Introduction

Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This project aims to analyze the bike share usage patterns using data provided by Motivate, a bike share system provider for many major cities in the United States.

## Statistics Computed

The project computes various descriptive statistics to uncover bike share usage patterns in Chicago, New York City, and Washington. The following information is provided:

### 1. Popular times of travel

- Most common month
- Most common day of the week
- Most common hour of the day

### 2. Popular stations and trips

- Most common start station
- Most common end station
- Most common trip from start to end (i.e., most frequent combination of start station and end station)

### 3. Trip duration

- Total travel time
- Average travel time

### 4. User info

- Counts of each user type
- Counts of each gender (only available for NYC and Chicago)
- Earliest, most recent, and most common year of birth (only available for NYC and Chicago)

## Getting Started

To get started with the project, make sure you have the following prerequisites:

- Python 3 
- numpy 
- pandas
- 7-Zip (https://www.7-zip.org/)
- 
## Instructions

Clone the repository:

```shell
git clone https://github.com/your-username/bike-share-analysis.git
   ```
Extract the CSV data file:

    Locate the downloaded 7z file containing the bike share data.
    Right-click on the 7z file and select "Extract Here" using 7-Zip.

Move the extracted data file:

    Open the extracted folder.
    Move the CSV data file to the same folder as the Python code.
```shell
pip install numpy pandas
```
Extract the 
Run the script:
```shell
python bike_share_analysis.py
```
