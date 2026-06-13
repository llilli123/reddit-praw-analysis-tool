# Reddit PRAW Analysis Tool

A small non-commercial Python project that uses the official Reddit API through [PRAW](https://praw.readthedocs.io/) to collect limited public Reddit post and comment data for educational analysis.

This project is designed for responsible, API-based access to Reddit data. It does not scrape Reddit HTML pages and does not attempt to bypass Reddit API limits.

## Purpose

The purpose of this project is to analyze public Reddit discussions from a small number of selected subreddits for educational and personal research purposes.

The tool may collect limited public information such as:

- Post title
- Post ID
- Score
- Number of comments
- Created time
- Permalink
- Public comment text when needed

The collected data may be exported locally as CSV or JSON for basic analysis.

## What This Project Does Not Do

This project does not:

- Scrape Reddit HTML pages
- Bypass Reddit rate limits
- Use multiple accounts to avoid limits
- Send automated messages
- Submit posts
- Submit comments
- Manipulate votes
- Collect private data
- Profile users
- Sell or redistribute Reddit data
- Train AI models with Reddit data
- Spam or interfere with Reddit communities

## Technology

- Python
- PRAW
- Reddit OAuth
- python-dotenv
- CSV / JSON export

## Planned Usage

The script will authenticate with Reddit using OAuth credentials from a registered Reddit application.

It will use a descriptive User-Agent and only access a limited number of public posts and comments from specific subreddits.

Example intended subreddits:

- r/redditdev
- r/python
- r/learnpython

## Setup

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/reddit-praw-analysis-tool.git
cd reddit-praw-analysis-tool
