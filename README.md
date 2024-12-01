# HSE Test App

![HSE Test App Banner](https://github.com/hse5555/hse_test/raw/main/banner.png)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

**HSE Test App** is a demonstration application designed to showcase how to interact with X's (formerly Twitter) API using Python. The app collects real-time tweets based on specific topics, analyzes the data to extract common interests, and provides targeted recommendations. This project serves as a foundation for developing more sophisticated data-driven applications that leverage social media data to understand customer interests and enhance marketing strategies.

## Features

- **Real-Time Data Collection:** Utilizes X's API to gather tweets related to predefined topics.
- **Data Cleaning & Processing:** Cleans and preprocesses tweet data for accurate analysis.
- **Text Analysis:** Extracts common words and identifies trending topics using `pandas` and `scikit-learn`.
- **Recommendation Engine:** Provides simple text similarity-based recommendations.
- **Interactive Web Interface:** Hosts a basic website using GitHub Pages to display privacy policy and terms of service.
- **Security Compliance:** Ensures data protection and privacy compliance by implementing HTTPS and OAuth 2.0.

## Demo

Visit the [HSE Test App Website](https://hse5555.github.io/hse_test/) to view the application in action.

![Demo Screenshot](https://github.com/hse5555/hse_test/raw/main/demo_screenshot.png)

## Installation

### Prerequisites

- **Python 3.7+**
- **Git**
- **GitHub Account** (for GitHub Pages)
- **X Developer Account** (formerly Twitter Developer Account) to obtain API keys

### Clone the Repository

```bash
git clone https://github.com/hse5555/hse_test.git
cd hse_test
