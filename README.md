Setup Checklist Before Running
Generate a GitHub PAT:
Go to https://github.com/settings/tokens > Generate token (classic or fine-grained)

Required scopes: repo, workflow, public_repo

Copy the token

Add the PAT to your repo secrets:

Go to your repo > Settings > Secrets and Variables > Actions > New repository secret

Name it: `TWRP_PUSH`
tokens: like `ghp_cytIgN4AE1yQTKK3A9XcdRE5WU0wty10U6w1` use your own token
these not mine token haha these example.

Paste the token
