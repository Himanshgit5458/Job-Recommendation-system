# Job Recommendation System

The Job Recommendation System is a project that takes resumes as input and recommends the best available jobs in the market based on the content written in the resumes. The system involves data collection from job portals using web scraping, extracting and cleaning data from resumes, mapping jobs by finding similarities, and providing a user-friendly interface using HTML and Flask.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Workflow](#workflow)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview

The Job Recommendation System is designed to assist job seekers in finding the most suitable job opportunities by analyzing the content of their resumes and comparing it to job descriptions available in the system's database. The project comprises several key components:

- Data collection through web scraping to populate the job portal database.
- Resume content extraction and cleaning using Python's natural language processing capabilities.
- Mapping jobs to resumes by calculating similarity scores.
- Building a user interface using Flask to display relevant job recommendations.

## Features

- Web scraping: Collects job data from various job portals for creating a comprehensive job database.
- NLP-based data processing: Processes and cleans resume content to extract relevant information.
- Similarity scoring: Measures the similarity between job descriptions and resumes to recommend suitable jobs.
- User-friendly interface: Provides an intuitive web interface for users to upload resumes and view job recommendations.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- Beautiful Soup (for web scraping)
- Spacy (for natural language processing)

### Installation

1. Clone the repository:
