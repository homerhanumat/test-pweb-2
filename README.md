# Testing `personal-web` Theme Adjustments

## Local Development

In `themes/exampleSite` run:

```{sh}
hugo serve --themesDir "../.."
```

## For GitHub Deployment

In root directory run:

```{sh}
hugo --contentDir "themes/personal-web/exampleSite/content" --themesDir "themes"  --config "themes/personal-web/exampleSite/config.toml" -d "docs" --baseURL "https://<github_username>.github.io/<test_repo_name>"
```

