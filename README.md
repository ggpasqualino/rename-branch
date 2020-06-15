# rename-branch
A little script to help you rename your repos' branch name from `master` to `main` and set it as the default branch in github.

# Dependencies
- curl
- jq

# Usage

[Create a Github Personal Access Token](https://github.com/settings/tokens/new)

Then execute the following in your terminal
```bash
export GH_USERNAME=your-username
export GH_TOKEN=the-token-above
./rename.sh
```

# Pagination
If you have more than 30 repos you will need to adjust the pagination accordingly.
