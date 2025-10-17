# github-user-created-abc125

## Overview

This project publishes a simple Bootstrap webpage that allows users to input a GitHub username and retrieve the account's creation date. It leverages the GitHub API to fetch user data and displays the creation date in a user-friendly format. The page is designed with a form and a dedicated element to present the information.

## Features

*   Fetches GitHub user data using the GitHub API.
*   Accepts a GitHub username as input via a form with `id="github-user-abc125"`.
*   Optionally accepts a GitHub API token via the `?token=` query parameter for increased rate limits.
*   Displays the GitHub account creation date in YYYY-MM-DD UTC format within an element with `id="github-created-at"`.
*   Utilizes Bootstrap for basic styling and responsiveness.

## How to Use

1.  Open the deployed page in your web browser (e.g., [https://your-github-username.github.io/github-user-created-abc125/](https://your-github-username.github.io/github-user-created-abc125/)). Replace `your-github-username` with your actual GitHub username.
2.  Enter a GitHub username in the input field.
3.  Optionally, append `?token=YOUR_GITHUB_TOKEN` to the URL to use a GitHub API token. Replace `YOUR_GITHUB_TOKEN` with your personal access token.
4.  The account creation date will be displayed below the input field.

## Technology Stack

*   HTML
*   CSS (Bootstrap)
*   JavaScript
*   GitHub API

## Project Structure

```
github-user-created-abc125/
├── index.html
└── style.css
└── script.js
└── README.md
```

## Local Development

1.  Clone the repository: `git clone https://github.com/your-github-username/github-user-created-abc125.git`
2.  Open `index.html` in your web browser.

## License

This project is licensed under the MIT License.