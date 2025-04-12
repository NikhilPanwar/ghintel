# GHIntel

[ghintel.secrets.ninja](https://ghintel.secrets.ninja) is a web-based tool that scans GitHub commit histories to identify employee emails and usernames associated with a specific user or organization.

## Features

- 🔍 Scans all public repositories of a user/org
- 📄 Parses the commits per repository
- 📧 Extracts author emails and usernames
- 🚫 Option to exclude forked repositories
- 🔑 Supports GitHub API token for higher rate limits
- 📁 Export results as CSV

## Usage

1. Go to [ghintel.secrets.ninja](https://ghintel.secrets.ninja)
2. Enter a GitHub username or organization
3. (Optional) Add a GitHub token to bypass API rate limits
4. Click `Find`
5. View or download results

## Notes

- Only public data is accessed
- Data is collected from Git commit metadata in your browser on frontend
- Use responsibly
