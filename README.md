# stockholm-github-users
- The data was scraped using the GitHub API to gather users in Stockholm with over 100 followers and details on their repositories.
- A surprising insight from the analysis is that longer bios have a positive correlation with followers, though the effect size is small.
- Developers could consider optimizing their GitHub bios with concise, impactful details to potentially increase follower engagement.

## Project Overview

This project analyzes GitHub users located in Stockholm who have more than 100 followers. Using the GitHub API, data was collected on user profiles and repository information, focusing on attributes such as bio length, follower count, and repository statistics.

### Files in This Repository
- `users.csv`: Contains details on each GitHub user from Stockholm with more than 100 followers, including username, bio, company, location, and follower count.
- `repositories.csv`: Lists the public repositories of these users, containing information like repository name, star count, programming language, and license type.
- `README.md`: Explains the project process, key findings, and recommendations.

### Data Collection Process
1. Used the GitHub API to identify users in Stockholm with over 100 followers.
2. Retrieved profile details for each user and compiled the data into `users.csv`.
3. Collected data on each user’s repositories (up to 500 per user) and saved it in `repositories.csv`.

### Key Findings
- **Bio Length and Follower Count**: A linear regression analysis suggests a small positive correlation between bio length (in words) and follower count. Developers with longer bios tend to have slightly more followers on average.
- **Top-Performing Repositories**: Certain repositories had significantly more stars, often aligning with popular languages like JavaScript and Python.

### Recommendations for Developers
Based on the analysis, developers may benefit from maintaining a well-crafted, informative bio that includes professional highlights and interests, as this could subtly boost follower count and engagement.
