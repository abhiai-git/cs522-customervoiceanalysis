# CS-522 Customer Voice Analysis - Master's Project IIT Chicago

This repository contains a project developed for the CS-522 Customer Voice Analysis course during my Master's studies at IIT Chicago. The project focuses on collecting, processing, and analyzing customer feedback, potentially from social media sources like Twitter.

## Overview

This is a group project aimed at understanding customer sentiment and feedback through various analytical techniques. The repository is structured to accommodate contributions from multiple team members, with each member's work organized in dedicated subdirectories. A key component of this project involves programmatic data collection from Twitter.

## Project Structure

The repository is organized by team member contributions and shared resources:

- `abhishek/`: Contains contributions from Abhishek, including:
    - `crao/`: Further sub-project or module.
    - `GetOldTweets-python-master/`: A utility to programmatically retrieve old tweets, bypassing Twitter API limitations. This tool is crucial for gathering historical customer voice data.
        - `Exporter.py`: Script to export tweets to a CSV file.
        - `Main.py`: Main script for using the tweet retrieval functionality.
        - `got/`: Core library for tweet retrieval.
        - `requeriments.txt`: Dependencies for the tweet retrieval tool.
- `amruta/`: Contributions from Amruta.
- `maneesha/`: Contributions from Maneesha.
- `rohan/`: Contributions from Rohan.
- `samruddhi/`: Contributions from Samruddhi.
- `README.md`: This main README file.

## Key Functionality (from `GetOldTweets-python-master`)

The `GetOldTweets-python-master` component allows for:
- Retrieving tweets older than the Twitter API's one-week limit.
- Searching tweets by username, query text, and date ranges.
- Exporting collected tweets to a CSV file.

## Technologies and Libraries (Inferred)

- **Python**: Primary programming language.
- **Jupyter Notebook**: Likely used for data exploration, analysis, and presentation (inferred from other projects).
- **Twitter Data Collection**: Custom scripts or libraries (like `GetOldTweets-python-master`) for gathering social media data.
- **Natural Language Processing (NLP)**: Expected for analyzing customer voice (e.g., sentiment analysis, topic modeling).
- **Data Analysis Libraries**: Potentially `pandas`, `numpy`, `scipy` for data manipulation and statistical analysis.
- **Machine Learning**: Could involve classification or clustering techniques for customer feedback.

## Setup and Usage

To set up and run this project:

1. **Clone the repository**:
   ```bash
   git clone [repository_url]
   cd cs522-customervoiceanalysis
   ```

2. **Install dependencies**:
   Navigate to relevant subdirectories (e.g., `abhishek/GetOldTweets-python-master/`) and install their specific requirements. For `GetOldTweets-python-master`, refer to its `requeriments.txt` (note: it's `requeriments.txt` not `requirements.txt`).
   ```bash
   pip install -r abhishek/GetOldTweets-python-master/requeriments.txt
   ```
   Additional dependencies for other parts of the project may need to be installed as per their respective subdirectories.

3. **Explore Individual Components**:
   Refer to the `README.md` files or code within each team member's directory for specific instructions on how to run and utilize their contributions. For example, to use the tweet exporter:
   ```bash
   cd abhishek/GetOldTweets-python-master/
   python Exporter.py --username "barackobama" --maxtweets 10
   ```

## Team Members

- Abhishek Bhardwaj
- Archi Dsouza (inferred from other projects)
- Piyush Nath (inferred from other projects)
- Amruta (inferred from directory name)
- Maneesha (inferred from directory name)
- Rohan (inferred from directory name)
- Samruddhi (inferred from directory name)
