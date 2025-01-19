# 30 Days DevOps Challenge - Weather Dashboard

Day 1: Building a weather data collection system using AWS S3 and OpenWeather API

# Weather Data Collection System - DevOps Day 1 Challenge

## Project Overview
This project is a Weather Data Collection System that demonstrates core DevOps principles by combining:
- External API Integration (OpenWeather API)
- Cloud Storage (AWS S3)
- Infrastructure as Code
- Version Control (Git)
- Python Development
- Error Handling
- Environment Management

## Features
- Fetches real-time weather data for multiple cities
- Displays temperature (°F), humidity, and weather conditions
- Automatically stores weather data in AWS S3
- Supports multiple cities tracking
- Timestamps all data for historical tracking

## Technical Architecture
- **Language:** Python 3.x
- **Cloud Provider:** AWS (S3)
- **External API:** OpenWeather API
- **Dependencies:** 
  - boto3 (AWS SDK)
  - python-dotenv
  - requests

```markdown
## Project Structure
weather-dashboard/
  src/
    __init__.py
    weather_dashboard.py
  tests/
  data/
  .env
  .gitignore
  requirements.txt

## Issues Encountered
1. I mistook the OpenWeatherAPI for my AWS Access Key. This resulted in an empty bucket on AWS S3
Solution Steps:
* Understand that OpenWeatherAPI is different from AWS Access key.
* Upon creating an account on OpenWeatherAPI, you can generate an API Key
* Wait for at least an hour (Free account) before you can use it

2. While uploading this work to github, I kept on missing "git add {any changes made}"
3. I also had authentication issues for my github.
Solution Steps:
* In place of password, use your personal access token which you can generate in github under the developer settings

What I Learned

AWS S3 bucket creation and management
Environment variable management for secure API keys
Python best practices for API integration
Cloud resource management
